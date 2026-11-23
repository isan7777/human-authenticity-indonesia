# Vocabulary Selection: Kurasi Kosakata dan Protokol Anti-Translationese

Dokumen ini memandu pemilihan kata yang berkarakter, berdaya pikat, dan secara sistematis memberantas penyakit terjemahan harfiah (*translationese*) yang sering menjangkiti keluaran model bahasa besar di Indonesia.

---

## 1. Protokol Anti-Translationese (De-kalkifikasi Bahasa)

Model bahasa sering kali 'berpikir' dalam konstruksi bahasa Inggris lalu menerjemahkannya secara kaku ke dalam bahasa Indonesia (*calque translation*). Pola ini menghasilkan kalimat yang canggung dan tidak wajar bagi penutur asli:

| Pola Translationese AI | Mengapa Canggung | Alternatif Bahasa Indonesia Alami |
| :--- | :--- | :--- |
| *"Di akhir hari..."* (At the end of the day) | Terjemahan harfiah idiom bahasa Inggris. | *"Pada akhirnya..."*, *"Bagaimanapun juga..."* |
| *"Terakselerasi oleh normalisasi X..."* | Runtunan kata serapan Latinate yang kaku. | *"Makin meluas akibat kebiasaan X yang dianggap wajar..."* |
| *"Secara fundamental dibutuhkan..."* | Frasa abstrak bergaya terjemahan mesin. | *"Sangat mendasar bagi..."*, *"Menjadi modal utama bagi..."* |
| *"Menjawab rasa penasaran Anda..."* | Formula sopan santun chatbot barat. | *"Menjelaskan duduk perkaranya..."* |
| *"Membuat perbedaan yang nyata..."* (Make a real difference) | Klise serapan dari bahasa Inggris korporat. | *"Memberikan dampak terukur..."*, *"Berdampak nyata..."* |
| *"Mengambil langkah mundur..."* (Take a step back) | Kiasan fisik yang canggung dalam teks konseptual. | *"Melihat gambaran besarnya..."*, *"Meninjau kembali..."* |
| *"Penumpukan istilah asing dalam kurung"* e.g. `gawai (*gadget*)` | Mengotori teks dan merusak format dokumen. | Pilih salah satu: gunakan istilah Indonesia secara konsisten atau istilah asing tanpa kurung miring berulang. |

---

## 2. Daftar Kata dan Frasa Klise Terlarang (AI Buzzword Blacklist)

Frasa-frasa berikut dilarang digunakan karena telah kehilangan makna akibat inflasi penggunaan oleh mesin:

```text
Daftar Frasa Terlarang:
❌ "Dalam era digital saat ini..." / "Di zaman modern yang serba cepat..."
❌ "Menyelami lebih dalam..." (Delve into)
❌ "Merupakan aspek krusial..." / "Sangat penting untuk diingat bahwa..."
❌ "Lanskap yang dinamis dan terus berkembang..."
❌ "Menghadirkan permadani kekayaan..." (Rich tapestry)
❌ "Bagaikan pedang bermata dua..."
❌ "Tidak dapat dipungkiri bahwa..."
❌ "Merevolusi cara kita hidup dan bekerja..."
```

---

## 3. Heuristik Konstruktif Pemilihan Kata (Positive Lexical Selection)

1. **Prioritaskan Kata Kerja Aktif Bertenaga**:
   Gantilah penumpukan kata benda abstrak (nominalisasi) dengan aksi langsung:
   - *Lemah (Nominalisasi)*: "Pihak manajemen melakukan implementasi terhadap kebijakan pengurangan jam kerja."
   - *Kuat (Aktif)*: "Manajemen memangkas jam kerja."
2. **Presisi Sensorik dan Konkret**:
   Bawa pembaca ke realitas fisik yang dapat dibayangkan:
   - *Abstrak*: "Kondisi lalu lintas sangat padat dan bising."
   - *Konkret*: "Deru knalpot truk bercampur klakson mikrolet mengunci perempatan sejak pukul lima sore."
3. **Pangkas Adverbia Pelembut yang Lemah**:
   Hindari pemakaian berulang kata *sangat*, *amat*, *sungguh*, dan *luar biasa*. Biarkan kata kerja atau kata benda utama yang memikul bobot emosi kalimat.

---

## 4. Hubungan dengan Modul Lain

- Untuk integrasi variasi kalimat, baca [Sentence Variation](sentence_variation.md).
- Untuk perbaikan alur antar-paragraf, baca [Paragraph Flow](paragraph_flow.md).
- Untuk memeriksa respon generik yang harus dibuang, baca [Generic Responses](../patterns/generic_responses.md).
