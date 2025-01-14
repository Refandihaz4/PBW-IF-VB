Sistem Penjualan Barang Berbasis Web

Proyek ini adalah sebuah sistem penjualan barang berbasis web yang memungkinkan pengguna untuk mengelola data barang, transaksi, laporan, dan pengaturan lainnya. Sistem ini dirancang untuk membantu toko dalam memantau stok barang, mencatat penjualan, dan menghasilkan laporan dengan mudah.

Cara Instalasi

Persiapan Lingkungan

Pastikan Anda telah menginstal XAMPP atau server lokal lainnya yang mendukung PHP dan MySQL.

Unduh proyek ini dan ekstrak ke folder htdocs (jika menggunakan XAMPP).

Import Database

Buka phpMyAdmin melalui browser (biasanya di http://localhost/phpmyadmin).

Buat database baru dengan nama sistem_penjualan.

Import file database yang disertakan dalam proyek ini (sistem_penjualan.sql).

Konfigurasi File Koneksi

Buka file config/koneksi.php.

Sesuaikan nama database, username, dan password sesuai dengan konfigurasi server Anda.

$host = "localhost";
$user = "root";
$pass = "";
$db   = "sistem_penjualan";

Menjalankan Proyek

Jalankan XAMPP dan aktifkan Apache serta MySQL.

Buka browser Anda dan akses proyek ini melalui URL: http://localhost/nama_folder_proyek.

Cara Menjalankan

Login ke sistem menggunakan akun yang tersedia di database (default username dan password dapat ditemukan di file SQL).

Navigasikan menu untuk:

Mengelola data barang dan kategori di menu Master.

Melihat dan mencatat transaksi di menu Transaksi.

Menghasilkan laporan di menu Laporan.

Melakukan pengaturan toko di menu Setting.

Kelompok 5:
Ketua: Hikmawati
Muhammad Faris
Devi Cahyati
Obi Bagas