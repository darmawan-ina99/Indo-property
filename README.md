# Indo Property

Katalog properti satu halaman: hunian dan properti mewah di Bali, Jakarta, dan Tangerang.

## Fitur
- Katalog listing dengan filter kota, tipe, dan status
- Detail properti dengan galeri foto
- Tombol konsultasi via WhatsApp
- Panel admin untuk tambah, edit, dan hapus listing

## Catatan teknis
- Satu file: `index.html` (tanpa build step)
- Data listing tersimpan di `localStorage` browser, jadi perubahan lewat admin hanya terlihat di perangkat yang sama. Untuk data bersama semua pengunjung, dibutuhkan backend.
- Login admin membandingkan hash SHA-256 di browser. Ini menyamarkan password dari pembaca kode, tetapi bukan pengamanan sungguhan karena semua logikanya berjalan di sisi klien.

## Deploy
GitHub Pages: push ke branch `main`.
