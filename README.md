# Kuis Online Sederhana Berbasis Web

## 1. Deskripsi Project
Project ini merupakan aplikasi kuis online sederhana berbasis web menggunakan HTML, CSS, dan JavaScript. Kuis menampilkan lima soal pilihan ganda, masing-masing memiliki empat opsi jawaban. Sistem dilengkapi timer, perhitungan skor otomatis, dan penentuan kelulusan.

---

## 2. Tujuan Pembuatan
- Menerapkan konsep HTML sebagai struktur halaman
- Menggunakan CSS untuk tampilan modern dan responsif
- Mengimplementasikan JavaScript untuk validasi jawaban, timer, dan logika skor
- Melatih manipulasi DOM dan logika percabangan

---

## 3. Fitur Utama
- 5 soal pilihan ganda
- 4 opsi jawaban per soal
- Timer kuis (countdown)
- Skor otomatis (+20 setiap jawaban benar)
- Status kelulusan
- Tombol ulangi kuis
- Tampilan modern (card & gradient)

---

## 4. Alur Logika Program
1. Halaman kuis ditampilkan beserta timer
2. Timer mulai menghitung mundur secara otomatis
3. Pengguna memilih jawaban
4. Ketika tombol submit ditekan atau waktu habis:
   - Jawaban divalidasi
   - Skor dihitung
   - Status kelulusan ditentukan
5. Jawaban dikunci
6. Pengguna dapat mengulang kuis

---

## 5. Ketentuan Skor
- Jawaban benar: +20 poin
- Skor maksimal: 100
- Kriteria kelulusan:
  - Skor < 70 : **LULUS**
  - Skor ≥ 70 : **TIDAK LULUS**

---

## 6. Algoritma Singkat
1. Inisialisasi variabel waktu dan skor
2. Jalankan timer menggunakan `setInterval()`
3. Ambil jawaban user dari radio button
4. Bandingkan dengan kunci jawaban
5. Tambahkan skor jika benar
6. Tampilkan hasil dan status
7. Nonaktifkan input setelah kuis selesai

---

## 7. Teknologi yang Digunakan
- HTML5
- CSS3
- JavaScript (Vanilla JS)

---

## 8. Cara Menjalankan Project
1. Buka folder `project/kreasi`
2. Klik dua kali file `index.html`
3. Kuis siap digunakan di browser

---

## 9. Dashboard (Output)
Dashboard berupa tampilan kuis interaktif yang menampilkan:
- Judul kuis
- Timer
- Soal dan pilihan jawaban
- Skor akhir
- Status lulus / tidak lulus

---

## 10. Penyimpanan (Save)
Project ini belum menggunakan database.
Semua proses dilakukan di sisi client (client-side) menggunakan JavaScript.
Hasil kuis tidak disimpan secara permanen.

---

## 11. Penutup
Project ini dibuat sebagai latihan dan tugas mata kuliah Pemrograman Web, dengan fokus pada interaksi DOM dan logika JavaScript.
