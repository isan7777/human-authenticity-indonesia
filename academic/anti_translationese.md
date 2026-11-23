# Anti-Translationese: Kamus De-kalkifikasi Bahasa Ilmiah Indonesia
*Berdasarkan Analisis Leksikal 114 Naskah Skripsi & Jurnal Ilmiah (1.337.090 Kata)*

Dokumen ini adalah rujukan leksikal untuk membersihkan naskah akademik dari serapan kaku konstruksi bahasa Inggris (*calque translation*) dan pola penerjemahan mesin yang menjadi indikator utama deteksi AI (Turnitin AI, GPTZero, dsb.).

---

## 1. Tabel De-kalkifikasi Frasa & Konjungsi Ilmiah

| Frasa Translationese AI (Canggung) | Pola Asal Bahasa Inggris | Alternatif Bahasa Ilmiah Alami (Korpus Riil) |
| :--- | :--- | :--- |
| *"Di sisi lain..."* (dipakai berulang) | *On the other hand...* | **Namun**, **Akan tetapi**, **Sementara itu**, **Sebaliknya** |
| *"Bermain peran penting dalam..."* | *Plays an important/key role in...* | **Memegang peranan vital/strategis dalam...**, **Berperan sentral dalam...** |
| *"Secara fundamental dibutuhkan..."* | *Is fundamentally needed...* | **Menjadi landasan mutlak bagi...**, **Sangat mendasar bagi...** |
| *"Penting untuk dicatat bahwa..."* | *It is important to note that...* | **Perlu digarisbawahi bahwa...**, **Patut dicermati bahwa...** |
| *"Berdasarkan pada kenyataan bahwa..."* | *Based on the fact that...* | **Bertolak dari kenyataan bahwa...**, **Mengingat bahwa...** |
| *"Membawa wawasan baru..."* | *Bring new insights...* | **Membuka perspektif baru...**, **Memperkaya khazanah kajian...** |
| *"Membuat perbedaan yang signifikan..."* | *Make a significant difference...* | **Memberikan dampak terukur...**, **Berdampak nyata terhadap...** |
| *"Di akhir hari..."* | *At the end of the day...* | **Pada akhirnya...**, **Bagaimanapun juga...** |
| *"Menghadapi tantangan tak terduga..."* | *Unprecedented challenges...* | **Menghadapi hambatan baru...**, **Menghadapi anomali lapangan...** |
| *"Menjadi bukti bagi..."* | *Is a testament to...* | **Membuktikan bahwa...**, **Menegaskan kembali bahwa...** |
| *"Dalam rangka untuk..."* (mubazir) | *In order to...* | **Guna...**, **Untuk...**, **Dalam rangka...** (pilih salah satu) |
| *"Sebagai hasil dari..."* | *As a result of...* | **Sebagai konsekuensi dari...**, **Akibat...** |
| *"Sesuai dengan apa yang dikatakan X..."* | *In accordance with what X said...* | **Sebagaimana dikemukakan oleh X (Tahun)...** |
| *"Hal ini adalah karena..."* | *This is because...* | **Hal tersebut dilandasi oleh...**, **Kondisi ini disebabkan oleh...** |

---

## 2. Reduksi Frasa "Di Sisi Lain" yang Berlebihan

Detektor AI mendeteksi kemunculan frasa *"di sisi lain"* sebagai sinyal kuat teks sintetis karena model bahasa besar cenderung menggunakan frasa ini sebagai penyeimbang mekanis di hampir setiap paragraf. 

**Bukti Korpus Riil**:
Dalam korpus 1,33 juta kata skripsi dan jurnal Indonesia, frasa *"di sisi lain"* hanya ditemukan sebanyak **29 kali**. Sebaliknya, penulis manusia menggunakan:
- *Namun,* (927 kali)
- *Akan tetapi,* (367 kali)
- *Sebaliknya,* (174 kali)
- *Sementara itu,* (52 kali)
- *Adapun...* (287 kali)

**Panduan Koreksi**:
Ganti penggunaan *"di sisi lain"* dengan konjungsi antarkalimat yang spesifik sesuai hubungan logisnya:
- Gunakan **Namun** atau **Akan tetapi** jika menunjukkan pertentangan langsung antara premis dan fakta.
- Gunakan **Sementara itu** jika menunjukkan dua peristiwa atau kondisi yang berlangsung beriringan di ruang/subjek berbeda.
- Gunakan **Sebaliknya** jika menunjukkan perbandingan kondisi yang bertolak belakang secara simetris.

---

## 3. Aturan Tanda Kurung Istilah Asing & Kebersihan Word

AI sering kali menyisipkan padanan bahasa Inggris di dalam kurung miring pada setiap kalimat:
- *Buruk (Khas AI)*: *"Pelajar mengalami penurunan fokus (*attention span*) akibat ketergantungan gawai (*gadget*)."*
- *Baku Alami*: *"Pelajar mengalami penurunan rentang konsentrasi akibat ketergantungan pada gawai pintar."*

### Pedoman Penggunaan Istilah Asing:
1. **Prioritaskan Istilah Baku KBBI**:
   Jika istilah keilmuan sudah diserap dan memiliki padanan resmi (misalnya: *analisis, sampel, variabel, hipotesis, populasi, efisiensi, validitas, reliabilitas, gawai, luring, daring*), gunakan istilah Indonesia murni tanpa mencantumkan kata bahasa Inggrisnya lagi.
2. **Kaidah Dwibahasa Resmi**:
   Bila istilah asing baru atau konsep spesifik yang belum memiliki padanan baku harus diperkenalkan untuk pertama kali, tuliskan padanan Indonesianya terlebih dahulu, diikuti istilah aslinya dalam kurung tanpa format rusak:
   - *Pola Benar*: *efek pengganda (multiplier effect)*, *penelitian tindakan (action research)*, *kutub pertumbuhan (growth pole)*.
   - *Pola Rusak (Dilarang)*: `*multiplier effect*`, `(*multiplier effect*)`.

---

## 4. Hubungan dengan Modul Lain

- Untuk kaidah formal penyusunan Bab 1 dan 2, lihat [formal_research_guide.md](formal_research_guide.md).
- Untuk studi kasus perbandingan sebelum dan sesudah rekonstruksi, baca [academic_examples.md](academic_examples.md).
- Untuk pengecekan naskah akhir, gunakan [academic_checklist.md](academic_checklist.md).
