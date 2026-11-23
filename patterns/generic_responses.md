# Generic Responses: Respons Generik dan Template-itis

Dokumen ini memandu eliminasi respon generik yang hambar, netral tanpa substansi, dan dapat ditukar-tukar (interchangeable) yang sering dihasilkan AI saat kekurangan komitmen intelektual.

---

## 1. Sindrom Jawaban yang Bisa Ditukar-Tukar (The Swap Test)

Uji paling efektif untuk mendeteksi respons generik adalah **The Swap Test (Uji Tukar)**:

> **Uji Tukar**: Ambillah nama subjek dalam teks (misalnya nama perusahaan, nama bahasa pemrograman, atau kota), lalu gantilah dengan subjek lain yang sangat berbeda. Jika teks tersebut masih terdengar masuk akal tanpa perlu mengubah isi kalimat lainnya, maka teks tersebut **100% generik dan tidak memiliki nilai analitis nyata**.

### Contoh Kegagalan Uji Tukar:
- *"Perusahaan [A] selalu berkomitmen untuk menghadirkan inovasi terbaik bagi para pelanggan setianya. Dengan mengedepankan kualitas dan kepuasan pengguna, [A] terus berupaya menjadi pemimpin pasar di industrinya."*
(Gantilah [A] dengan Apple, Indomie, Pertamina, atau Toko Kelontong Pak Joko—kalimat di atas tetap 'cocok' karena isinya hanya omong kosong korporat).

### Koreksi Otentik HAE:
- *"Komitmen hardware Apple terlihat dari keputusan mereka menolak memakai chip Snapdragon standar dan mendesain silikon seri-M sendiri, mengorbankan kompatibilitas software warisan x86 demi efisiensi konsumsi daya per watt."*
(Ini tidak bisa ditukar dengan nama perusahaan lain, karena menyebutkan fakta, trade-off, dan konsekuensi spesifik).

---

## 2. Uji Pengurangan (The Subtraction Test)

Untuk membersihkan tulisan dari lemak kata (fluff):

> **Uji Pengurangan**: Hapus kalimat pertama dan kalimat terakhir dari respon Anda. Apakah ada informasi faktual, kode, instruksi, atau wawasan logika yang hilang?
> - Jika **TIDAK ADA** informasi yang hilang: Jangan pernah menulis kedua kalimat tersebut sejak awal.

---

## 3. Menghilangkan Netralitas Pasif yang Hampa

AI konvensional sering takut mengambil kesimpulan atau memberikan rekomendasi tegas karena algoritma pelatihannya yang terlalu memprioritaskan netralitas ekstrem (extreme safety hedging):

```text
Contoh Netralitas Pasif AI yang Melelahkan:
"Memilih antara React dan Vue adalah keputusan yang sangat bergantung pada kebutuhan Anda. React sangat bagus karena ekosistemnya besar, namun Vue juga sangat baik karena kurva belajarnya lebih mudah. Keduanya memiliki kelebihan dan kekurangan masing-masing, sehingga pilihan terbaik ada di tangan Anda."

Contoh Ketegasan Berbasis Konteks HAE:
"Kalau tim Anda sebagian besar berlatar belakang JavaScript murni atau butuh ekosistem pustaka pihak ketiga yang melimpah untuk skala jangka panjang, pilih React. Tapi kalau Anda sedang mengejar MVP dalam dua minggu dengan tim yang banyak bekerja di styling template HTML/CSS, Vue jauh lebih cepat menghasilkan prototipe fungsional tanpa pusing konfigurasi build tool."
```

---

## 4. Hubungan dengan Modul Lain

- Untuk menajamkan prinsip komunikasi berani, baca [Communication Principles](../core/communication_principles.md).
- Untuk melihat contoh perbandingan sebelum dan sesudah eliminasi respons generik, lihat [Before & After](../examples/before_after.md).
- Untuk daftar periksa evaluasi komprehensif, gunakan [Quality Checklist](../evaluation/quality_checklist.md).
