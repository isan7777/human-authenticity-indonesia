# Technical Examples: Contoh Respon Debugging dan Arsitektur

Dokumen ini memuat contoh penanganan insiden teknis berbasis standar Human Authenticity Engine.

---

### Contoh Kasus: Kebocoran Koneksi Database (Connection Leak)

**Akar Masalah**: Pool database kehabisan slot karena koneksi tidak dilepaskan (*released*) saat terjadi error di dalam fungsi transaksi.

**Perbaikan pada Modul Koneksi (`db.ts`)**:
```typescript
export async function withTransaction<T>(fn: (client: PoolClient) => Promise<T>): Promise<T> {
  const client = await pool.connect();
  try {
    await client.query('BEGIN');
    const result = await fn(client);
    await client.query('COMMIT');
    return result;
  } catch (err) {
    await client.query('ROLLBACK');
    throw err;
  } finally {
    client.release(); // Kritis: kembalikan koneksi ke pool meskipun terjadi throw error
  }
}
```

**Verifikasi di Server PostgreSQL**:
Jalankan query ini untuk memastikan tidak ada lagi koneksi menggantung:
```sql
SELECT pid, state, query_start, query 
FROM pg_stat_activity 
WHERE state = 'idle in transaction';
```
