# Program Analisis Artikel SISKO

Program web sederhana berbasis Flask untuk menganalisis artikel tentang SISKO (Sistem Informasi Sekolah). Aplikasi ini menyediakan fitur-fitur untuk mencari kata, mengganti kata, dan mengurutkan kata secara abjad dalam artikel-artikel yang tersedia.

## Fitur

- **Pencarian Kata**: Mencari jumlah kemunculan kata tertentu dalam artikel.
- **Penggantian Kata**: Mengganti kata lama dengan kata baru dalam artikel.
- **Pengurutan Kata Abjad**: Mengurutkan kata-kata unik secara abjad dari artikel.

## Instalasi

1. Pastikan Anda memiliki Python terinstal di sistem Anda.
2. Clone repositori ini atau unduh file-file proyek.
3. Install dependensi yang diperlukan:

   ```
   pip install -r requirements.txt
   ```

## Penggunaan

1. Jalankan aplikasi:

   ```
   python app.py
   ```

2. Buka browser dan akses `http://localhost:5000`.
3. Pilih fitur yang diinginkan dari menu.
4. Masukkan input yang diperlukan dan klik tombol submit untuk melihat hasil.

## Struktur Proyek

- `app.py`: File utama aplikasi Flask yang berisi logika backend dan definisi rute.
- `templates/index.html`: Template HTML untuk antarmuka pengguna.
- `static/styles.css`: File CSS untuk styling halaman web.
- `requirements.txt`: Daftar dependensi Python yang diperlukan.

## Teknologi yang Digunakan

- **Flask**: Framework web Python untuk backend.
- **HTML**: Untuk struktur halaman web.
- **CSS**: Untuk styling dan tata letak.
- **Python**: Bahasa pemrograman utama.

## Lisensi

Proyek ini tidak memiliki lisensi khusus. Gunakan sesuai kebutuhan Anda.
