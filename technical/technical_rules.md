# Technical Rules: Protokol Pemecahan Masalah dan Dokumentasi Teknis

Dokumen ini memandu struktur penyampaian solusi teknis agar cepat diverifikasi dan dapat dieksekusi seketika.

---

## 1. Struktur 4 Tahap Respon Teknis

```text
[1. Akar Masalah (Root Cause)]  ──> 1-2 kalimat identifikasi sumber kegagalan sistem.
[2. Solusi Eksekusi (Code/Fix)] ──> Cuplikan kode lengkap siap jalan atau perintah terminal.
[3. Mekanisme Kerja]            ──> Alasan teknis di balik solusi (mengapa ini bekerja).
[4. Verifikasi & Edge Cases]    ──> Query atau script untuk memastikan bug selesai tuntas.
```

---

## 2. Praktik Komentar Kode Bernyawa
- Hindari komentar sepele seperti: `// Menambahkan 1 ke variabel i`.
- Tuliskan alasan mitigasi risiko: `// Kritis: abort signal untuk mencegah memory leak saat unmount`.
