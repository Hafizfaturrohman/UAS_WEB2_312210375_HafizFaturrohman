# 📚 E-Library: Sistem Informasi Rental Buku Digital
> **Tugas Proyek Akhir - Pemrograman Web 2**

[cite_start]Aplikasi **E-Library** adalah sebuah platform manajemen rental buku dan komik digital yang dibangun dengan mengimplementasikan pola *Decoupled Architecture*[cite: 4]. [cite_start]Sistem ini dirancang untuk memisahkan secara penuh antara layanan server (Backend) dan klien (Frontend)[cite: 4], guna memberikan performa pengiriman data yang optimal.

[cite_start]Aplikasi ini mengelola berbagai data master seperti buku, genre, penulis, status peminjaman, dan anggota[cite: 19].

---

## 👨‍💻 Informasi Pengembang
* **Nama:** [Hafiz Faturrohman]
* **NIM:** [312210375]

---

## 🚀 Teknologi yang Digunakan
[cite_start]Proyek ini dikembangkan murni menggunakan ekosistem modern tanpa *hard-reload*[cite: 7, 40]:
* [cite_start]**Backend API:** CodeIgniter 4 (CI4) bertindak sebagai *Resource Controller* untuk melayani operasi CRUD[cite: 8, 25].
* [cite_start]**Frontend SPA:** VueJS 3 (CDN) dengan sistem manajemen *routing* dari Vue Router[cite: 9].
* [cite_start]**Styling UI:** TailwindCSS (CDN) untuk desain antarmuka *utility-first*[cite: 10].
* [cite_start]**HTTP Client:** Axios Interceptors untuk otomatisasi injeksi token dan penanganan error secara asinkron[cite: 11, 46].

---

## 📸 Dokumentasi & Tangkapan Layar (Screenshots)

### 1. Skema Relasi Database
[cite_start]Aplikasi ini menggunakan rancangan basis data dengan tabel yang saling berelasi[cite: 23].
[cite_start]`![Skema Database](Link_Gambar_phpMyAdmin_Disini)` 

### 2. Pengujian Keamanan API (Proteksi Token)
[cite_start]Endpoint API manipulasi data dilindungi menggunakan *CodeIgniter Filters*[cite: 26]. [cite_start]Berikut adalah bukti penolakan akses (Error 401) ketika API dipanggil melalui Postman tanpa menyertakan *Authorization Bearer Token*[cite: 27, 67]:
[cite_start]`![Error 401 Postman](Link_Gambar_Postman_Disini)` 

### 3. Antarmuka Pengguna (UI TailwindCSS)
[cite_start]Seluruh antarmuka dirancang menggunakan spesifikasi TailwindCSS untuk formulir, tabel, dan kotak modal interaktif[cite: 50].
* [cite_start]**Halaman Autentikasi (Login):** `![Halaman Login](Link_Gambar_Disini)` 
* [cite_start]**Panel Utama (Dashboard Admin):** `![Dashboard Admin](Link_Gambar_Disini)` 
* [cite_start]**Tabel Data Interaktif:** `![Tabel Data Tailwind](Link_Gambar_Disini)` 
* [cite_start]**Modal Form (Tambah & Edit):** `![Form Modal Tambah/Edit](Link_Gambar_Disini)` 

---

## ⚙️ Panduan Instalasi Lokal

[cite_start]Ikuti panduan di bawah ini untuk menjalankan kode sumber secara lokal di perangkat Anda:

### Tahap 1: Menjalankan API Server (Backend)
1. [cite_start]Buka terminal dan arahkan ke direktori `backend-api/`[cite: 62].
2. [cite_start]Gandakan file konfigurasi `env` menjadi `.env` lalu sesuaikan kredensial koneksi database MySQL/MariaDB Anda[cite: 11].
3. Aktifkan server lokal CodeIgniter dengan perintah: `php spark serve`.

### Tahap 2: Menjalankan Aplikasi Klien (Frontend)
1. [cite_start]Buka direktori `frontend-spa/`[cite: 63].
2. [cite_start]Pastikan perangkat Anda terhubung ke internet untuk memuat pustaka dari CDN VueJS dan TailwindCSS[cite: 9, 10].
3. [cite_start]Jalankan file `index.html` menggunakan ekstensi seperti **Live Server** di teks editor Anda[cite: 63].

---

## 🎥 Demo & Tautan Proyek
* [cite_start]🌐 **Demo Aplikasi:** [Tempel URL Demo Web Anda di sini, jika ada] 
* [cite_start]▶️ **Video Presentasi:** [Tempel URL YouTube Presentasi Anda di sini]
