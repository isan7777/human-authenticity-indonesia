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

## 📁 Struktur Direktori

Proyek ini dibangun secara terstruktur dan modular dengan pembagian tanggung jawab yang jernih:

```text
human-authenticity/
├── SKILL.md                          # Entry point resmi skill (YAML Frontmatter & Pipeline)
├── README.md                         # Dokumentasi instalasi, konfigurasi, & arsitektur
├── core/                             # Modul Inti Filosofi & Karakter
│   ├── identity.md                   # Karakter dasar komunikator intelektual matang
│   ├── communication_principles.md   # Sepuluh prinsip komunikasi alami (Ten Tenets)
│   ├── natural_reasoning.md          # Penalaran dialektis non-linear & analogi segar
│   └── authenticity.md               # Hakikat keaslian vs manipulasi detektor AI
├── behavior/                         # Modul Perilaku Percakapan
│   ├── conversational_behavior.md    # Ritme turn-taking & eliminasi nada Customer Service
│   ├── response_adaptation.md        # Kalibrasi panjang (Micro, Compact, Deep-Dive)
│   ├── contextual_awareness.md       # Membaca niat implisit & memori kontinuitas
│   └── emotional_intelligence.md     # Empati membumi & kelakar halus situasional
├── writing/                          # Modul Teknik Penulisan Prosa
│   ├── natural_writing.md            # Menghapus kilap sintetis (show, don't tell)
│   ├── sentence_variation.md         # Variasi panjang kalimat & tanda baca bernyawa
│   ├── paragraph_flow.md             # Perkembangan tematik & teknik akordeon
│   ├── vocabulary_selection.md       # Kurasi kata & blacklist buzzwords AI
│   └── writing_styles.md             # Spektrum register (santai, formal, sastra)
├── modes/                            # Modul Adaptasi Kontekstual per Mode
│   ├── casual.md                     # Obrolan santai sehari-hari yang luwes
│   ├── professional.md               # Komunikasi kerja modern, lugas, solutif
│   ├── academic.md                   # Diskursus ilmiah & tinjauan metodologis kritis
│   ├── storytelling.md               # Narasi fiksi hidup & dialog berkarakter
│   ├── technical.md                  # Dokumentasi & debugging zero-fluff
│   └── social_media.md               # Konten media sosial bebas emoji salad
├── patterns/                         # Modul Anti-Pola & Diagnosis Bahasa
│   ├── ai_cliches.md                 # Katalog pembuka, kiasan, & penutup klise AI
│   ├── repetitive_structures.md      # Pembongkaran triad berbutir & simetri visual
│   ├── unnatural_transitions.md      # Eliminasi kata transisi mekanis
│   └── generic_responses.md          # Uji tukar (Swap Test) & uji pengurangan
├── examples/                         # Modul Contoh & Studi Komparasi
│   ├── conversation_examples.md      # Dialog nyata di berbagai situasi interaksi
│   ├── writing_examples.md           # Draf karya tulis utuh lintas genre
│   └── before_after.md               # Komparasi mendalam Chatbot Biasa vs HAE
└── evaluation/                       # Modul Kerangka Evaluasi Kualitas
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
