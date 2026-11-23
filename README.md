# Human Authenticity Engine (HAE)

**Human Authenticity Engine (HAE)** adalah arsitektur instruksi AI modular tingkat lanjut yang dirancang khusus untuk membebaskan model kecerdasan buatan dari gaya komunikasi robotik, formula kaku, simetri berlebihan, dan bahasa klise yang sering menjadi ciri khas teks sintetis.

---

## 🌟 Mengapa Human Authenticity Engine Dibutuhkan?

Sebagian besar model bahasa besar (LLM) dilatih menggunakan optimasi rata-rata probabilitas dan preferensi keamanan (RLHF) yang cenderung mendorong AI ke dalam zona aman:
- Selalu memuji pertanyaan pengguna (*sycophancy*).
- Mengulang pertanyaan pengguna di kalimat pembuka (*parroting*).
- Menggunakan struktur yang dapat diprediksi: Paragraf Pengantar -> 3 Bullet Point Simetris -> Paragraf Kesimpulan Moralistik (*the sandwich structure*).
- Ketergantungan berlebih pada kata transisi mekanis (*"Selain itu"*, *"Di sisi lain"*, *"Secara keseluruhan"*).
- Menghamburkan kata-kata klise (*"lanskap yang dinamis"*, *"menyelami lebih dalam"*, *"merupakan aspek krusial"*).

**Human Authenticity Engine merekonstruksi cara AI berkomunikasi** dari tingkat penalaran epistemik, dinamika giliran bicara, arsitektur sintaksis (ritme kalimat staccato-moderat-periodik), hingga penghapusan basa-basi secara radikal.

---

## 📁 Struktur Direktori Terpisah per Mode

Proyek ini dibangun secara terstruktur dengan memisahkan setiap domain penulisan ke dalam folder mandiri yang lengkap dengan panduan, contoh, dan checklist tersendiri:

```text
human-authenticity/
├── SKILL.md                          # Entry point resmi general skill
├── README.md                         # Dokumentasi instalasi, konfigurasi, & arsitektur
├── academic/                         # MODUL KHUSUS AKADEMIK & SKRIPSI
│   ├── SKILL.md                      # Entry point mandiri (human-authenticity-academic)
│   ├── formal_research_guide.md      # Panduan Bab 1 Skripsi & Jurnal Empiris Baku
│   ├── scholarly_essay_guide.md      # Panduan Esai Cendekia & Risalah Kebijakan
│   ├── anti_translationese.md        # Kamus De-kalkifikasi Bahasa Ilmiah Indonesia
│   ├── academic_examples.md          # Contoh naskah lolos Turnitin / GPTZero
│   └── academic_checklist.md         # Lembar periksa mandiri sebelum bimbingan
├── casual/                           # MODUL KHUSUS OBROLAN SANTAI
│   ├── SKILL.md                      # Entry point obrolan santai
│   ├── conversational_rules.md       # Aturan dialog dan partikel wacana alami
│   ├── casual_examples.md            # Contoh dialog sehari-hari
│   └── casual_checklist.md           # Lembar periksa percakapan santai
├── professional/                     # MODUL KHUSUS KOMUNIKASI KERJA
│   ├── SKILL.md                      # Entry point komunikasi kerja
│   ├── workplace_communication.md    # Panduan surel & pelaporan kendala proyek
│   ├── professional_examples.md      # Contoh surel eksekutif & penolakan sopan
│   └── professional_checklist.md     # Lembar periksa pesan profesional
├── storytelling/                     # MODUL KHUSUS FIKSI & NARASI
│   ├── SKILL.md                      # Entry point penulisan fiksi
│   ├── narrative_rules.md            # Show don't tell, dialog realistis, & pacing
│   ├── storytelling_examples.md      # Contoh adegan fiksi kaya sensorik
│   └── storytelling_checklist.md     # Lembar periksa naskah naratif
├── technical/                        # MODUL KHUSUS DOKUMENTASI & DEBUGGING
│   ├── SKILL.md                      # Entry point instruksi teknis
│   ├── technical_rules.md            # Protokol 4 tahap (Root Cause -> Fix -> Verify)
│   ├── technical_examples.md         # Contoh solusi incident response & database
│   └── technical_checklist.md        # Lembar periksa respon teknis
├── social-media/                     # MODUL KHUSUS KONTEN SOSIAL
│   ├── SKILL.md                      # Entry point media sosial
│   ├── social_media_rules.md         # Kaidah hook organik & anti kebun emoji
│   ├── social_media_examples.md      # Draf unggahan X dan LinkedIn berwibawa
│   └── social_media_checklist.md     # Lembar periksa konten sosial
├── core/                             # Modul Inti Filosofi & Karakter
├── behavior/                         # Modul Perilaku Percakapan
├── writing/                          # Modul Teknik Penulisan Prosa
├── patterns/                         # Modul Anti-Pola & Diagnosis Bahasa
├── examples/                         # Rujukan Umum & Komparasi Before/After
└── evaluation/                       # Kerangka Evaluasi Mutu 6 Dimensi
    ├── quality_checklist.md          # Daftar periksa pra-rilis respon
    ├── naturalness_test.md           # Protokol uji baca nyaring & uji warung kopi
    └── evaluation_criteria.md        # Rubrik evaluasi 6 dimensi standar mutu
```

---

## 🚀 Panduan Instalasi dan Penggunaan

### 1. Penggunaan pada Antigravity AI
Skill ini secara otomatis terbaca oleh Antigravity jika diletakkan di dalam folder `.agents/skills/` pada proyek kerja atau repositori Anda:

```bash
# Salin folder human-authenticity ke direktori .agents/skills/ proyek Anda:
cp -r human-authenticity .agents/skills/human-authenticity
```
Setelah tersalin, asisten Antigravity akan mendeteksi `human-authenticity` sebagai skill aktif dan memuat modul yang relevan saat Anda berinteraksi.

### 2. Penggunaan pada Claude Code / Cursor / OpenCode
Tambahkan referensi ke dalam berkas instruksi proyek (`AGENTS.md` atau `CLAUDE.md` atau `.cursorrules`):

```markdown
Saat menghasilkan respon, ikuti prinsip-prinsip penulisan dan komunikasi alami 
dari folder `human-authenticity/SKILL.md`. Jangan gunakan format chatbot klise, 
hindari pengantar basa-basi, dan terapkan variasi panjang kalimat secara dinamis.
```

### 3. Penggunaan sebagai System Prompt Mandiri (API / Local LLM)
Jika Anda menggunakan OpenAI API, Anthropic API, atau Ollama lokal, Anda dapat menggabungkan inti instruksi dari `core/communication_principles.md`, `writing/sentence_variation.md`, dan `patterns/ai_cliches.md` sebagai bagian dari System Prompt utama aplikasi Anda.

---

## 🎯 Enam Dimensi Evaluasi Standar HAE

Keluaran teks diukur menggunakan rubrik 6 dimensi pada skala 1–5 (lihat [evaluation/evaluation_criteria.md](evaluation/evaluation_criteria.md)):

1. **Naturalness**: Keluwesan ekspresi, ketiadaan rasa robotik dan basa-basi.
2. **Context Awareness**: Kesesuaian nada dan format dengan situasi emosi atau beban tugas pengguna.
3. **Readability**: Kemudahan membaca, alur napas teks, dan kejelasan logika.
4. **Linguistic Variation**: Variasi panjang kalimat, kekayaan leksikal, dan asimetri visual.
5. **Accuracy**: Ketepatan teknis, kedalaman penalaran, dan ketiadaan halusinasi.
6. **Consistency**: Penjagaan suara/nada yang stabil dari awal hingga akhir dokumen.

---

## ⚖️ Penegasan Etika dan Integritas

> **PENTING**: Human Authenticity Engine **TIDAK** dirancang untuk menipu alat pendeteksi AI melalui trik murahan seperti menyengaja salah ketik (typo), merusak tata bahasa, atau memasukkan karakter tak terlihat. Tujuan HAE adalah **mengembalikan keanggunan, martabat, dan kejernihan pemikiran dalam komunikasi bahasa manusia**.
