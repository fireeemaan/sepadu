<div align="center">
  <img src="https://i.ibb.co/whGFD37s/logo-remove.png" alt="Logo SEPADU" style="border-radius: 50%;">
  <h1 align="center">🚀 SEPADU 🚀</h1>
  <p align="center">
    <strong>Sistem Elektronik Pelayanan Terpadu</strong>
    <br />
    Solusi digital modern untuk menyederhanakan proses pengajuan, pelatihan, dan verifikasi.
  </p>
  <p align="center">
    <a href="#"><strong>Lihat Demo »</strong></a>
    ·
    <a href="#">Laporkan Bug</a>
    ·
    <a href="#">Minta Fitur Baru</a>
  </p>
</div>

<!-- SHIELDS -->
<div align="center">
  <img src="https://img.shields.io/badge/Framework-Laravel-FF2D20?style=for-the-badge&logo=laravel" alt="Laravel">
  <img src="https://img.shields.io/badge/PHP-8.3%2B-777BB4?style=for-the-badge&logo=php" alt="PHP">
  <img src="https://img.shields.io/badge/Styling-TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss" alt="Tailwind CSS">
  <img src="https://img.shields.io/github/stars/fireeemaan/sepadu?style=for-the-badge&logo=github&label=Stars">
  <img src="https://img.shields.io/badge/Lisensi-MIT-yellow.svg?style=for-the-badge" alt="Lisensi">
</div>
<br>

> **Misi Proyek:** Menciptakan sebuah platform terintegrasi yang efisien, transparan, dan mudah digunakan bagi admin dan peserta dalam mengelola kegiatan pelatihan dan layanan terpadu.

<details>
  <summary>📖 Klik untuk Melihat Daftar Isi</summary>
  <ol>
    <li><a href="#✨-tentang-proyek">✨ Tentang Proyek</a></li>
    <li><a href="#-teknologi-yang-digunakan">🛠️ Teknologi yang Digunakan</a></li>
    <li><a href="#-memulai">🚀 Memulai</a></li>
    <li><a href="#-fitur-unggulan">🎉 Fitur Unggulan</a></li>
    <li><a href="#-struktur-database">🗄️ Struktur Database</a></li>
    <li><a href="#-berkontribusi">💖 Berkontribusi</a></li>
    <li><a href="#-lisensi">📄 Lisensi</a></li>
    <li><a href="#-kontak">📬 Kontak</a></li>
  </ol>
</details>
<hr>

## ✨ Tentang Proyek

![Gambar Cuplikan Layar Proyek](https://i.ibb.co/zWzXdjkr/127-0-0-1-8000.png)

**SEPADU** (Sistem Elektronik Pelayanan Terpadu) lahir dari kebutuhan untuk mengatasi kerumitan administrasi dalam proses pelayanan. Lupakan tumpukan kertas dan alur kerja yang membingungkan! SEPADU mentransformasi semuanya ke dalam satu aplikasi web yang intuitif dan powerfull.

Sistem ini memfasilitasi seluruh alur kerja, mulai dari:
* **Peserta:** Mendaftar pelatihan, mengajukan permohonan, hingga memantau riwayat dengan mudah.
* **Admin:** Mengelola data master, memverifikasi pengajuan secara digital, dan menjadwalkan pelatihan tanpa pusing.

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun di atas fondasi teknologi web modern yang andal dan skalabel.

| Kategori | Teknologi |
| :--- | :--- |
| **Backend** | ![Laravel](https://img.shields.io/badge/Laravel-v10-FF2D20?logo=laravel) ![PHP](https://img.shields.io/badge/PHP-v8.1-777BB4?logo=php) |
| **Frontend** | ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v3-06B6D4?logo=tailwindcss) ![Alpine.js](https://img.shields.io/badge/Alpine.js-v3-0D9488?logo=alpine.js) |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?logo=mysql) |
| **Tools** | ![Vite](https://img.shields.io/badge/Vite-v4-646CFF?logo=vite) ![NPM](https://img.shields.io/badge/NPM-v9-CB3837?logo=npm) ![Composer](https://img.shields.io/badge/Composer-v2-885610?logo=composer) |

## 🚀 Memulai

Siap untuk menjalankan SEPADU di lingkungan lokal Anda? Ikuti panduan di bawah ini.

### Prasyarat

Pastikan semua dependensi ini sudah terpasang:
* PHP (versi 8.3 atau lebih tinggi)
* [Composer](https://getcomposer.org/)
* [Node.js](https://nodejs.org/) & NPM
* Database (MySQL)

### Instalasi

1.  **Clone repositori ini**
    ```sh
    git clone [https://github.com/fireeemaan/sepadu.git](https://github.com/fireeemaan/sepadu.git)
    cd sepadu
    ```
2.  **Pasang Dependensi (Backend & Frontend)**
    ```sh
    composer install
    npm install
    ```
3.  **Konfigurasi Lingkungan**
    Salin `.env.example` ke `.env` dan sesuaikan koneksi database Anda.
    ```sh
    cp .env.example .env
    php artisan key:generate
    ```
4.  **Setup Database**
    Jalankan migrasi untuk membuat tabel dan seeder untuk mengisi data awal.
    ```sh
    php artisan migrate --seed
    ```
5.  **Buat Tautan Penyimpanan**
    ```sh
    php artisan storage:link
    ```
6.  **Jalankan Aplikasi!**
    * Buka 2 terminal.
    * Terminal 1 (Vite):
        ```sh
        npm run dev
        ```
    * Terminal 2 (Laravel Server):
        ```sh
        php artisan serve
        ```
    🎉 Selamat! Aplikasi Anda sekarang berjalan di `http://127.0.0.1:8000`.

## 🎉 Fitur Unggulan

-   🔑 **Otentikasi & Hak Akses Ganda**: Sistem login yang aman dengan pemisahan peran antara Admin dan Pengguna.
-   📊 **Dashboard Interaktif**: Visualisasi data penting untuk pengambilan keputusan yang lebih cepat.
-   📂 **Alur Pengajuan Digital**: Proses pengajuan yang terstruktur dari A sampai Z, mudah dilacak dan diverifikasi.
-   🎓 **Manajemen Pelatihan & Pendaftaran**: Pengguna dapat dengan mudah menemukan dan mendaftar pelatihan yang relevan.
-   📅 **Penjadwalan Cerdas**: Admin dapat mengatur jadwal dengan mudah dan menghindari konflik.
-   ✅ **Verifikasi Satu Klik**: Modul khusus bagi admin untuk menyetujui atau menolak pengajuan dengan efisien.
-   👤 **Profil Pengguna**: Pengguna dapat mengelola data pribadi mereka secara mandiri.
-   📜 **Audit Trail & Riwayat**: Lacak semua aktivitas penting untuk transparansi dan akuntabilitas.
-   ❓ **Pusat Bantuan (FAQ)**: Kurangi pertanyaan berulang dengan halaman FAQ yang mudah dikelola.

## 🗄️ Struktur Database

Berikut adalah gambaran singkat dari arsitektur tabel utama:
* `admins` & `users`: Mengelola akses untuk masing-masing peran.
* `komoditas`: Tabel master untuk jenis komoditas.
* `pengajuan`: Jantung dari sistem, mencatat semua pengajuan yang masuk.
* `jadwal`: Mengatur semua event dan pelatihan.
* `pendaftaran` & `pesertas`: Menghubungkan pengguna dengan jadwal yang mereka ikuti.
* `faqs`: Basis pengetahuan untuk pengguna.
