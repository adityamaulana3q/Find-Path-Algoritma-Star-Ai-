# Maze Solver - A* Algorithm

Aplikasi visualisasi algoritma pencarian jalur menggunakan **A\*** (A-star) yang dibangun menggunakan **Python** dan **Pygame**. Pengguna dapat membuat labirin (maze) secara manual, menentukan titik awal dan tujuan, lalu melihat bagaimana algoritma A* mencari jalur tercepat.

## 🎯 Fitur

- Antarmuka grafis interaktif berbasis grid
- Pengaturan titik awal (start) dan akhir (end)
- Penempatan rintangan (barrier) dengan klik kiri
- Jalur solusi divisualisasikan secara real-time
- Reset peta dengan tombol
- Menggunakan algoritma A* dengan **heuristic Manhattan Distance**

## 🧠 Algoritma

Algoritma A* adalah algoritma pathfinding yang mencari jalur terpendek dengan kombinasi **biaya sebenarnya (g)** dan **heuristik estimasi (h)**. Program ini menggunakan *Manhattan Distance* sebagai heuristiknya.

## 🎮 Cara Menggunakan

1. **Jalankan program**:  
   Pastikan Anda memiliki Python dan Pygame.
   
2. **Gunakan Mouse:**
- **Klik kiri** untuk:
  - Klik pertama: pilih titik mulai
  - Klik kedua: pilih titik tujuan
  - Klik selanjutnya: tempatkan rintangan (tembok)
- **Klik kanan** untuk menghapus sel

3. **Keyboard:**
- Tekan `SPACE` untuk memulai pencarian jalur
- Tekan `C` untuk mereset seluruh grid

## 🖼️ Tampilan

- 🟧 Start Node
- 🟪 End Node
- ⬛ Barrier (rintangan)
- 🟩 Open Node (dalam proses pencarian)
- 🟥 Closed Node (sudah dievaluasi)
- 🟦 Path (jalur yang ditemukan)

## 🛠️ Struktur Kode

- `Spot`: Kelas untuk merepresentasikan satu sel/grid
- `algorithm`: Fungsi utama algoritma A*
- `main`: Fungsi utama yang menangani interaksi pengguna
- `draw`, `make_grid`, dll: Fungsi bantu untuk visualisasi

## 📦 Requirements

- Python 3.x
- Pygame (`pip install pygame`)

## 💡 Catatan

- Grid berukuran 30x30 (dapat diubah dengan memodifikasi variabel `ROWS`)
- Grid bersifat statis, tidak mendukung diagonal
- Cocok untuk belajar algoritma pencarian jalur secara visual



