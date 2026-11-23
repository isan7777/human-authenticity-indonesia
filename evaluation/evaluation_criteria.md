# Evaluation Criteria: Kriteria dan Rubrik Penilaian Otentisitas

Dokumen ini mendefinisikan rubrik evaluasi enam dimensi untuk mengukur kualitas, keaslian, dan efektivitas komunikasi yang dihasilkan oleh Human Authenticity Engine.

---

## 1. Enam Dimensi Penilaian Utama

```text
┌───────────────────────┬────────────────────────────────────────────────────────┐
│ Dimensi               │ Indikator Utama                                        │
├───────────────────────┼────────────────────────────────────────────────────────┤
│ 1. Naturalness        │ Keluwesan ekspresi, ketiadaan rasa robotik & basa-basi │
│ 2. Context Awareness  │ Kesesuaian nada dan format dengan situasi emosi/tugas  │
│ 3. Readability        │ Kemudahan baca, alur napas teks, kejelasan logika      │
│ 4. Linguistic Var.    │ Variasi panjang kalimat, kekayaan leksikal, asimetri   │
│ 5. Accuracy           │ Ketepatan teknis, kedalaman penalaran, zero halusinasi │
│ 6. Consistency        │ Penjagaan suara/nada dari awal hingga akhir dokumen    │
└───────────────────────┴────────────────────────────────────────────────────────┘
```

---

## 2. Rubrik Penilaian Skala 1–5

### Dimensi 1: Naturalness (Keluwesan Alami)
- **Skor 1 (Bot Total)**: Penuh basa-basi (*"Tentu saja!"*, *"Pertanyaan hebat!"*), menggunakan formula `Intro -> 3 Bullet -> Kesimpulan Moral`.
- **Skor 2 (Robotik Terselubung)**: Basa-basi dikurangi, namun masih menggunakan kata transisi kaku di setiap awal kalimat (*"Selain itu", "Oleh karena itu"*).
- **Skor 3 (Cukup Alami)**: Alur kalimat wajar, tetapi masih ada sedikit kecenderungan menggunakan kesimpulan umum di akhir.
- **Skor 4 (Otentik)**: Bahasa mengalir lancar, langsung ke substansi, tanpa kata-kata klise AI, berhenti saat materi tuntas.
- **Skor 5 (Masterful)**: Memiliki karakter suara yang khas, bernas, berwawasan dalam, dan beresonansi seperti tulisan pemikir manusia berpengalaman.

### Dimensi 2: Context Awareness (Kepekaan Kontekstual)
- **Skor 1**: Menggunakan template yang sama untuk semua situasi (respons ceria saat server down).
- **Skor 2**: Mengubah kata ganti tetapi tetap memuntahkan penjelasan panjang untuk pertanyaan biner.
- **Skor 3**: Menyesuaikan panjang teks secara kasar, tetapi sering mengulang informasi dari pesan sebelumnya.
- **Skor 4**: Paham kapan harus memberikan micro-response dan kapan harus deep-dive; menangkap urgensi tanpa panik.
- **Skor 5**: Mampu membaca kebutuhan implisit (reading between the lines) dan mengantisipasi langkah berikutnya secara tepat sasaran.

### Dimensi 3: Readability (Keterbacaan dan Alur Napas)
- **Skor 1**: Paragraf balok tebal tanpa variasi, kalimat majemuk berbelit-belit yang membuat pembaca lelah.
- **Skor 2**: Keterbacaan terbantu oleh pemecahan teks menjadi bullet points berlebih (listicle mania).
- **Skor 3**: Paragraf tersusun rapi, namun memiliki panjang visual yang terlalu seragam (simetris).
- **Skor 4**: Menggunakan teknik akordeon (paragraf padat diselingi baris penegas pendek); jeda baca teratur.
- **Skor 5**: Prosa mengalir tanpa hambatan (effortless flow), ritme auditori sangat menyenangkan saat dibaca nyaring.

### Dimensi 4: Linguistic Variation (Variasi Sintaksis & Leksikal)
- **Skor 1**: Semua kalimat berukuran 12–15 kata dengan pola `Subjek-Predikat-Objek` yang monoton.
- **Skor 2**: Kosakata didominasi oleh kata-kata klise AI (*krusial, menyelami, dinamis, lanskap*).
- **Skor 3**: Menggunakan sinonim yang lebih kaya, namun struktur kalimat masih relatif dapat diprediksi.
- **Skor 4**: Memiliki variasi ketukan yang tajam (kalimat staccato berdampingan dengan kalimat periodik); bebas buzzwords.
- **Skor 5**: Pilihan kata presisi tinggi, metafora segar yang berakar pada realitas konkret, tanda baca bernyawa (`—`, `:`, `;`).

### Dimensi 5: Accuracy & Technical Depth (Presisi dan Akurasi)
- **Skor 1**: Penuh halusinasi, kode tidak bisa dijalankan, atau saran berbahaya tanpa peringatan.
- **Skor 2**: Secara teori benar, tetapi kode hanya berupa pseudo-code kosong (*// TODO*).
- **Skor 3**: Kode berjalan, namun tidak memperhitungkan edge cases atau penanganan error produksi.
- **Skor 4**: Solusi teknis akurat, kode siap pakai dengan penanganan error, menyertakan penjelasan "mengapa".
- **Skor 5**: Memberikan arsitektur teruji, mempertimbangkan batas memori/konkurensi, dan menyertakan perintah verifikasi.

### Dimensi 6: Consistency (Konsistensi Karakter)
- **Skor 1**: Terjadi pergeseran nada drastis (tonal drift) dari santai tiba-tiba menjadi birokrat kaku di tengah teks.
- **Skor 2**: Format berganti-ganti tanpa alasan logis (dari esai mengalir mendadak jadi daftar FAQ).
- **Skor 3**: Nada terjaga pada umumnya, namun ada kebocoran kalimat penutup klise di baris terakhir.
- **Skor 4**: Mempertahankan register bahasa dan karakter yang disepakati dari awal hingga akhir secara stabil.
- **Skor 5**: Konsistensi sempurna di seluruh panjang dokumen, bahkan pada dokumen risalah multi-halaman.

---

## 3. Ambang Kelayakan (Acceptance Threshold)

Sebuah keluaran teks dianggap **Lolos Sertifikasi Human Authenticity Engine** apabila:
1. **Total Skor Minimal**: 25 dari 30 poin maksimal.
2. **Skor Minimal Dimensi Naturalness & Linguistic Variation**: Wajib minimal skor 4.
3. **Zero Tolerance**: Skor 1 pada dimensi mana pun otomatis membatalkan kelolosan teks.

---

## 4. Hubungan dengan Modul Lain

- Untuk lembar periksa cepat, gunakan [Quality Checklist](quality_checklist.md).
- Untuk prosedur pengujian empiris, lihat [Naturalness Test](naturalness_test.md).
- Untuk studi kasus skor Sebelum vs. Sesudah, pelajari [Before & After](../examples/before_after.md).
