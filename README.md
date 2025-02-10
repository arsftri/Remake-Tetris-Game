# Remake-Tetris-Game

Remake Tetris Game adalah implementasi permainan Tetris menggunakan bahasa pemrograman Python dengan pustaka Pygame. Permainan ini memiliki fitur seperti pergerakan blok, rotasi, pencatatan skor, serta rekor tertinggi yang tersimpan dalam file.

## Persyaratan
Sebelum menjalankan game ini, pastikan Anda telah menginstal Python dan pustaka Pygame.

### Instalasi Pygame
```sh
pip install pygame
```

## Cara Menjalankan
Jalankan program dengan perintah berikut di terminal atau command prompt:
```sh
python tetris.py
```

## Fitur
- **Gerakan Blok**: Blok dapat digerakkan ke kiri, kanan, dan bawah.
- **Rotasi Blok**: Blok dapat diputar dengan tombol "Up Arrow".
- **Pencatatan Skor**: Skor akan bertambah berdasarkan jumlah garis yang dihapus.
- **Rekor Tertinggi**: Skor tertinggi akan disimpan dalam file `record`.
- **Musik Latar**: Musik tema Tetris akan diputar selama permainan.

## Kontrol Permainan
- **Panah Kiri (←)**: Memindahkan blok ke kiri.
- **Panah Kanan (→)**: Memindahkan blok ke kanan.
- **Panah Bawah (↓)**: Mempercepat jatuhnya blok.
- **Panah Atas (↑)**: Memutar blok.
- **ESC / Tutup Jendela**: Keluar dari permainan.

## Struktur Kode
- **Inisialisasi**: Mengatur ukuran layar, warna, font, dan memuat musik.
- **Grid dan Field**: Menyimpan informasi posisi dan warna blok.
- **Fungsi Utama**:
  - `check_borders()`: Memeriksa apakah blok melebihi batas permainan.
  - `get_record()`: Membaca rekor tertinggi dari file `record`.
  - `set_record()`: Memperbarui rekor jika skor baru lebih tinggi.
- **Gameplay**:
  - Pergerakan blok dan rotasi.
  - Memeriksa garis yang penuh dan memperbarui skor.
  - Menampilkan elemen visual (grid, blok, teks).

## Dependensi
- Python 3.x
- Pygame

## Catatan
Pastikan file berikut tersedia sebelum menjalankan game:
- `tetris_theme.mp3` (musik latar)
- `img/bg.jpg` (background utama)
- `img/bg2.jpg` (background game area)
- `font/font.ttf` (font untuk teks)

## Lisensi
Proyek ini dibuat untuk tujuan pembelajaran dan bersifat open-source.


