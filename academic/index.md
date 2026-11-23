---
name: human-academic
description: "Modul khusus Human Authenticity Engine untuk penulisan akademik, skripsi, tesis, paper jurnal, dan esai ilmiah. Dikalibrasi berdasarkan analisis empiris 1,33 juta kata dari 114 naskah skripsi dan jurnal perguruan tinggi terkemuka di Indonesia (UNDIP, UGM, UI, UNHAS, UB, UNY, IPB). Menghasilkan teks dengan bahasa ilmiah baku Indonesia alami, bebas deteksi AI (GPTZero & Turnitin AI), bebas translationese, dan siap salin-tempel tanpa simbol pemformatan rusak."
---

# Human Authenticity Engine: Academic Edition
*Dikalibrasi Berdasarkan Analisis Empiris 1.337.090 Kata dari 114 Naskah Skripsi & Jurnal Ilmiah Indonesia.*

Modul ini adalah panduan penulisan khusus untuk naskah ilmiah, skripsi, tesis, disertasi, paper jurnal, dan esai akademik. Seluruh instruksi diisolasi agar berfokus penuh pada standar penulisan perguruan tinggi dan eliminasi tanda tangan statistik AI.

---

## 1. Struktur Modul Academic

```text
academic/
├── SKILL.md                    <── Entry point resmi mode akademik
├── formal_research_guide.md    <── Panduan baku Bab 1 Latar Belakang, Bab 2 Pustaka, & Jurnal
├── scholarly_essay_guide.md    <── Panduan esai cendekia, risalah kebijakan, & opini kritis
├── anti_translationese.md      <── Kamus de-kalkifikasi istilah ilmiah bahasa Indonesia
├── academic_examples.md        <── Contoh nyata sebelum vs sesudah lolos uji detektor
└── academic_checklist.md       <── Lembar periksa kualitas sebelum salin-tempel ke Word
```

---

## 2. Enam Perintah Mutlak Penulisan Akademik HAE

1. **Haramkan Tanda Pisah Em-Dash (`—`)**:
   Bahasa ilmiah baku Indonesia tidak menggunakan tanda pisah teatrikal. Dari 1,33 juta kata korpus nyata, em-dash hanya muncul 0,008%. Gunakan tanda koma, titik dua, atau konjungsi subordinatif (*yaitu, yakni, bahwa*).
2. **Nol Polusi Bintang Markdown (Word-Safe)**:
   Jangan menggunakan tanda bintang miring ganda atau tunggal (`*istilah*`) di dalam tanda kurung. Teks harus berformat bersih agar saat disalin ke Microsoft Word tidak meninggalkan simbol asterisk liar.
3. **Anti-Kalimat Pembuka Ensiklopedi (Wajib Grounding Triad)**:
   Dilarang keras mengawali naskah dengan frasa klise internet:
   - ❌ *"Di era digital saat ini..."*
   - ❌ *"Teknologi terus berkembang pesat..."*
   - ❌ *"Kondisi geografis Indonesia yang berada pada pertemuan tiga lempeng..."*
   Wajib membuka paragraf pertama dengan **Tiga Pilar Landasan Riil**: Regulasi/UU, Data Statistik Empiris (BPS/Kementerian), atau Fenomena Sosio-Kultural Spesifik di lokasi riset.
4. **Variasi Panjang Kalimat Nyata (Pola 40-40-20)**:
   Penulis manusia asli memiliki rata-rata 18 kata per kalimat dengan deviasi standar tinggi (14,4 kata). Selipkan minimal satu kalimat pendek tegas (2–10 kata) di setiap paragraf untuk memecah ritme metronomik AI.
5. **Bahasa Indonesia Baku Bebas Translationese**:
   Hindari penerjemahan harfiah pola bahasa Inggris. Ganti pengulangan frasa *"di sisi lain"* dengan konjungsi alami (*Namun, Akan tetapi, Sementara itu, Sebaliknya*).
6. **Objektivitas Kalimat Pasif & Pihak Ketiga**:
   Gunakan konstruksi pasif impersonal terukur (*dilakukan, diperoleh, dianalisis, disimpulkan*). Sebut penulis sebagai pihak ketiga (*peneliti*, *penulis*), bukan *saya* atau *kami*.

---

## 3. Navigasi Cepat Modul

- Untuk panduan teknis penyusunan Bab 1 Skripsi yang lolos Turnitin dan GPTZero: baca [formal_research_guide.md](formal_research_guide.md).
- Untuk studi kasus perbandingan teks gagal vs lolos uji: lihat [academic_examples.md](academic_examples.md).
- Untuk kamus padanan kata bebas terjemahan kaku: buka [anti_translationese.md](anti_translationese.md).
- Untuk panduan penulisan esai ilmiah dan opini cendekia: baca [scholarly_essay_guide.md](scholarly_essay_guide.md).
- Untuk lembar periksa sebelum menyerahkan naskah ke dosen: gunakan [academic_checklist.md](academic_checklist.md).
