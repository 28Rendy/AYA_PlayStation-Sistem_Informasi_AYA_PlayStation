<div align="center">

<img src="https://img.shields.io/badge/AYA_PlayStation-Sistem_Informasi-blue?style=for-the-badge&logo=playstation&logoColor=white" alt="AYA PlayStation" width="500"/>

# 🎮 AYA PlayStation - Sistem Informasi

**Sistem manajemen rental PlayStation berbasis web yang modern, lengkap, dan mudah digunakan.**

[![Laravel](https://img.shields.io/badge/Laravel-7.x-FF2D20?style=flat-square&logo=laravel&logoColor=white)](https://laravel.com)
[![PHP](https://img.shields.io/badge/PHP-≥7.2.5-777BB4?style=flat-square&logo=php&logoColor=white)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=flat-square&logo=mysql&logoColor=white)](https://mysql.com)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-Frontend-7952B3?style=flat-square&logo=bootstrap&logoColor=white)](https://getbootstrap.com)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

</div>

---

## 📋 Daftar Isi

- [Tentang Proyek](#-tentang-proyek)
- [Fitur Unggulan](#-fitur-unggulan)
- [Teknologi yang Digunakan](#-teknologi-yang-digunakan)
- [Persyaratan Sistem](#-persyaratan-sistem)
- [Langkah Instalasi](#-langkah-instalasi)
- [Struktur Proyek](#-struktur-proyek)
- [Akun Default](#-akun-default)
- [Kontribusi](#-kontribusi)
- [Lisensi](#-lisensi)

---


> ### 🛡️ Pernyataan Data Dummy & Penafian Orisinalitas (Disclaimer)
> Seluruh konten dan data di dalam repositori ini termasuk namun tidak terbatas pada **nama usaha/entitas (*AYA PlayStation / Sistem manajemen rental PlayStation berbasis web*)**, nama produk, nama pelanggan/pengguna, data transaksi, harga, alamat galeri, nomor telepon, testimoni, hingga foto katalog batik merupakan **100% data tiruan (pure dummy data)** yang dibuat khusus untuk keperluan demonstrasi fungsional, bahan pembelajaran, dan portofolio pengembangan perangkat lunak sumber terbuka (*open-source*).
> 
> Segala bentuk kesamaan nama merek, tokoh, alamat, atau produk di dunia nyata adalah **murni ketidaksengajaan** tanpa ada niat plagiarisme, pencemaran nama baik, maupun pelanggaran hak cipta. Proyek ini tidak memuat dan tidak menyebarkan data pribadi (*privacy*) milik pihak manapun.

---

## 🕹️ Tentang Proyek

**AYA PlayStation** adalah sistem informasi manajemen rental PlayStation yang dirancang untuk memudahkan pengelolaan bisnis rental game. Sistem ini menyediakan dua portal utama:

- 🔑 **Portal Admin** - Kelola seluruh operasional bisnis: data ruang, PS, pelanggan, keuangan, dan konten website.
- 👤 **Portal Pelanggan** - Pelanggan dapat melihat ruang yang tersedia dan melakukan pemesanan secara online.

---

## ✨ Fitur Unggulan

### 🖥️ Panel Admin
| Fitur | Deskripsi |
|-------|-----------|
| 📊 Dashboard | Ringkasan data operasional dan keuangan |
| 🏠 Data Ruang | Kelola data ruang rental PlayStation |
| 🎮 Data PS | Manajemen unit PlayStation yang tersedia |
| 👥 Data Pelanggan | Pengelolaan data pelanggan terdaftar |
| 📋 Data Penyewa | Riwayat dan data transaksi penyewaan |
| 💰 Data Pemasukan | Pencatatan dan laporan pemasukan |
| 💸 Data Pengeluaran | Pencatatan dan laporan pengeluaran |
| 🔁 Data Perental | Manajemen periode dan kas masuk |
| 👨‍💼 Data Admin | Pengelolaan akun pengguna admin |
| ⭐ Ulasan | Moderasi ulasan dari pelanggan |
| 🌐 Pengaturan Website | Kustomisasi konten dan tampilan website |
| 🖼️ Galeri Foto | Manajemen foto untuk halaman galeri |
| 🏆 Konten Fasilitas | Kelola informasi fasilitas yang ditampilkan |

### 🌐 Halaman Frontend (Publik)
| Halaman | Deskripsi |
|---------|-----------|
| 🏠 Beranda | Halaman utama dengan informasi umum |
| ℹ️ Tentang Kami | Profil dan sejarah AYA PlayStation |
| ⭐ Keunggulan | Keunggulan layanan yang ditawarkan |
| 🎯 Fasilitas | Daftar fasilitas yang tersedia |
| 📸 Galeri | Foto-foto ruang dan fasilitas |
| 🚪 Daftar Ruang | Daftar ruang yang bisa disewa |
| 📞 Kontak | Informasi kontak dan lokasi |

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Versi | Kegunaan |
|-----------|-------|----------|
| **Laravel** | `^7.0` | Framework PHP Backend |
| **PHP** | `^7.2.5` | Bahasa Pemrograman |
| **MySQL** | - | Database |
| **Bootstrap** | - | Framework CSS Frontend |
| **Laravel UI** | `2.4` | Autentikasi & UI Scaffolding |
| **Composer** | - | Dependency Manager PHP |
| **Node.js / NPM** | - | Asset Compilation (Mix) |

---

## 📦 Persyaratan Sistem

Pastikan perangkat Anda memenuhi persyaratan berikut sebelum instalasi:

- ✅ **PHP** versi `7.2.5` atau lebih baru
- ✅ **Composer** versi terbaru
- ✅ **Node.js** & **NPM** versi terbaru
- ✅ **MySQL** / **MariaDB**
- ✅ **Web Server**: Apache / Nginx / Laragon *(disarankan)*
- ✅ **Git**

---

## 🚀 Langkah Instalasi

Ikuti langkah-langkah berikut untuk menjalankan proyek ini di lokal Anda.

### 1️⃣ Clone Repository

```bash
git clone https://github.com/28Rendy/AYA_PlayStation-Sistem_Informasi_AYA_PlayStation.git
cd AYA_PlayStation-Sistem_Informasi_AYA_PlayStation
```

### 2️⃣ Install Dependensi PHP

```bash
composer install
```

### 3️⃣ Install Dependensi Node.js

```bash
npm install
```

### 4️⃣ Salin File Konfigurasi Environment

```bash
cp .env.example .env
```

> **Windows:**
> ```bash
> copy .env.example .env
> ```

### 5️⃣ Generate Application Key

```bash
php artisan key:generate
```

### 6️⃣ Konfigurasi Database

Buka file `.env` dan sesuaikan konfigurasi database Anda:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=aya_playstation   # Sesuaikan nama database
DB_USERNAME=root              # Sesuaikan username
DB_PASSWORD=                  # Sesuaikan password
```

### 7️⃣ Buat Database

Buat database baru di MySQL dengan nama yang sesuai `.env` di atas, contohnya `aya_playstation`.

```sql
CREATE DATABASE aya_playstation;
```

### 8️⃣ Jalankan Migrasi & Seeder

```bash
php artisan migrate --seed
```

> Perintah ini akan membuat seluruh tabel database dan mengisi data awal (termasuk akun admin default).

### 9️⃣ Buat Symlink Storage

```bash
php artisan storage:link
```

### 🔟 Compile Asset Frontend

```bash
npm run dev
```

> Atau untuk production:
> ```bash
> npm run production
> ```

### 1️⃣1️⃣ Jalankan Server Aplikasi

```bash
php artisan serve
```

Aplikasi akan berjalan di: **[http://127.0.0.1:8000](http://127.0.0.1:8000)**

> 💡 **Tips:** Jika menggunakan **Laragon**, cukup tempatkan folder proyek di `C:\laragon\www\` dan akses melalui `http://aya-playstation.test` secara otomatis.

---

## 📁 Struktur Proyek

```
AYA_PlayStation/
├── app/
│   ├── Http/
│   │   ├── Controllers/       # Semua Controller (Admin, Frontend, Auth)
│   │   └── Middleware/        # Middleware autentikasi
│   └── Models/                # Model Eloquent
├── database/
│   ├── migrations/            # File migrasi tabel database
│   └── seeds/                 # Data awal (Seeder)
├── public/                    # Asset publik (CSS, JS, gambar)
├── resources/
│   └── views/                 # Blade template (Frontend & Admin)
├── routes/
│   └── web.php                # Definisi semua route aplikasi
├── storage/                   # File upload & log
├── .env.example               # Contoh konfigurasi environment
└── README.md
```

---

## 🔐 Akun Default

Setelah menjalankan seeder, gunakan akun berikut untuk login:

| Role | Email | Password |
|------|-------|----------|
| 👨‍💼 **Admin** | `admin@aya.com` | `password` |

> ⚠️ **Penting:** Segera ganti password default setelah pertama kali login!

---

## 🤝 Kontribusi

Kontribusi sangat terbuka dan diterima! Berikut cara berkontribusi:

1. **Fork** repository ini
2. Buat **branch** fitur baru: `git checkout -b fitur/nama-fitur`
3. **Commit** perubahan: `git commit -m 'Menambahkan fitur X'`
4. **Push** ke branch: `git push origin fitur/nama-fitur`
5. Buat **Pull Request**

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah **MIT License**. Lihat file [LICENSE](LICENSE) untuk informasi lebih lanjut.

---

<div align="center">

<h1 align="center"> FrontEnd - AYA PlayStation</h1>

<img width="1920" height="8394" alt="AYA PlayStation - Frontend Modern Gaming Lounge   Rental Console" src="https://github.com/user-attachments/assets/c9fe4ffc-d901-4a0a-8b14-de76da457329" />

<h1 align="center"> Login - AYA PlayStation</h1>

<img width="956" height="434" alt="AYA Playstation-Login " src="https://github.com/user-attachments/assets/d39297fd-4057-43a7-9320-6858405d31ce" />

<h1 align="center"> Backend Admin - AYA PlayStation</h1>

<img width="1920" height="1203" alt="Admin - AYA PlayStation" src="https://github.com/user-attachments/assets/5d4e2ec0-15f7-4351-a363-4cb3a1734190" />

<h1 align="center"> Backend Portal Pelanggan - AYA PlayStation</h1>

<img width="1920" height="1451" alt="Portal Pelanggan - AYA PlayStation" src="https://github.com/user-attachments/assets/458662eb-4cfc-4431-bc90-8008e48c0e04" />


**Dibuat dengan OK Rendy 28 menggunakan [Laravel](https://laravel.com)**

⭐ Jangan lupa beri **Star** jika proyek ini bermanfaat!

</div>
