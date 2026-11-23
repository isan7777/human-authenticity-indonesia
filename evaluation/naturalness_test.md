# Naturalness Test: Protokol Pengujian Keluwesan Bahasa

Dokumen ini menyediakan protokol pengujian empiris untuk mengevaluasi apakah keluaran teks benar-benar terasa alami, bernyawa, dan meyakinkan bagi pembaca manusia.

---

## 1. Empat Protokol Pengujian Praktis

```text
┌────────────────────────┐      ┌────────────────────────┐
│ 1. Uji Baca Nyaring    │      │ 2. Uji Warung Kopi     │
│ (The Read-Aloud Test)  │      │ (The Coffee Shop Test) │
└────────────────────────┘      └────────────────────────┘
            │                                │
            ▼                                ▼
┌────────────────────────┐      ┌────────────────────────┐
│ 3. Uji Variasi Ketukan │      │ 4. Uji Stres Musuh     │
│ (The Burstiness Audit) │      │ (Adversarial Prompting)│
└────────────────────────┘      └────────────────────────┘
```

---

## 2. Rincian Protokol Pengujian

### Protokol 1: Uji Baca Nyaring (The Read-Aloud Test)
- **Metode**: Bacalah teks tersebut dengan suara keras (bukan hanya dalam hati) dengan kecepatan bicara normal.
- **Tanda Kegagalan**:
  - Anda kehabisan napas di tengah kalimat karena ketiadaan tanda baca jeda yang wajar.
  - Lidah Anda tersangkut pada pengulangan pola suku kata yang kaku (*"melakukan pelaksanaan pengelolaan..."*).
  - Telinga Anda menangkap pengulangan kata yang sama dalam jarak 3 kalimat.
- **Standar Lolos**: Kalimat meluncur mulus dari bibir, intonasi naik-turun secara alami mengikuti bobot emosi gagasan.

### Protokol 2: Uji Warung Kopi (The Coffee Shop Test)
- **Metode**: Bayangkan Anda sedang duduk di kedai kopi bersama seorang rekan profesional atau teman cerdas. Bayangkan kalimat dalam teks tersebut diucapkan langsung kepadanya.
- **Tanda Kegagalan**:
  - Jika lawan bicara Anda akan mengerutkan dahi dan menganggap Anda terdengar seperti robot, brosur asuransi, atau birokrat kaku.
  - Kalimat seperti: *"Tentu, mari kita selami lanskap strategi ini secara komprehensif!"* (Tidak ada manusia waras yang berbicara seperti ini dalam percakapan nyata).
- **Standar Lolos**: Lawan bicara merespons isi pemikiran Anda tanpa merasa sedang mendengarkan rekaman otomatis.

### Protokol 3: Audit Variasi Ketukan (The Burstiness Audit)
- **Metode**: Hitung jumlah kata dari 8 kalimat berturut-turut dalam teks.
- **Tanda Kegagalan**:
  - Jika jumlah kata per kalimat adalah: `14, 15, 16, 14, 15, 15, 14, 16`. (Kemonotonan absolut).
- **Standar Lolos**:
  - Pola sebaran bervariasi: `5, 14, 28, 8, 19, 4, 32, 12`. Terdapat lompatan tempo antara kalimat pendek dan kalimat panjang.

### Protokol 4: Uji Stres Musuh (Adversarial Prompt Testing)
Uji ketahanan sistem terhadap umpan pertanyaan pemicu respon klise:

| Masukan Uji (Adversarial Prompt) | Respons Gagal (Bot Mode) | Respons Lolos (HAE) |
| :--- | :--- | :--- |
| *"P"* (Satu huruf tanpa konteks) | *"Halo! Ada yang bisa saya bantu hari ini? Silakan ajukan pertanyaan Anda..."* | *"Ya? Ada yang bisa dibantu?"* |
| *"Gue sedih banget hari ini."* | *"Saya sangat bersimpati dan turut berduka atas apa yang Anda rasakan. Ingatlah..."* | *"Mau cerita ada apa? Atau mau cari distraksi lain dulu?"* |
| *"Jelaskan tentang cinta."* | *"Cinta adalah emosi yang sangat kompleks dan mendalam yang telah memikat manusia sejak..."* | Membedah cinta dari ketegangan biologis vs komitmen sosial tanpa khotbah puisi generik. |

### Protokol 5: Uji Friksi Salin-Tempel (The Copy-Paste Friction Test)
- **Metode**: Salin teks hasil keluaran langsung ke Microsoft Word atau Google Docs tanpa pra-penyuntingan.
- **Tanda Kegagalan**:
  - Muncul simbol tanda bintang markdown liar (`*`) akibat pemformatan miring kata asing di dalam kurung.
  - Teks terbaca kaku layaknya terjemahan Google Translate lama (*translationese*).
- **Standar Lolos**: Teks langsung menyatu secara mulus dengan tata letak dokumen resmi, menggunakan istilah bahasa Indonesia baku yang mengalir tanpa cacat tipografi.

---

## 3. Hubungan dengan Modul Lain

- Untuk kriteria penilaian kuantitatif dan kualitatif, baca [Evaluation Criteria](evaluation_criteria.md).
- Untuk panduan perbaikan sebelum teks dirilis, rujuk [Quality Checklist](quality_checklist.md).
