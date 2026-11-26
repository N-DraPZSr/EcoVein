# 🌿 EcoVein

Platform website peduli lingkungan yang berfungsi sebagai pusat informasi dan edukasi isu lingkungan hidup, sekaligus mewadahi partisipasi aktif masyarakat melalui fitur donasi dan pendaftaran relawan, dengan dashboard transparansi yang terbuka untuk publik. Platform ini diperkuat dengan sistem autentikasi pengguna, database terpusat, panel admin untuk pengelolaan konten, serta dashboard transparansi interaktif, semuanya demi menjaga kepercayaan dan akuntabilitas publik.

> Teknik Multimedia Digital, Politeknik Negeri Jakarta, 2026.

---

## 👥 Anggota Kelompok 4

| Nama | NIM | Peran |
|---|---|---|
| Ahmad Husein | 2507431079 | Analis & pengelola konten, Pengembang CSS |
| Frytsar Oriscky Nurrachman | 2507431041 | Analis & pengelola konten, Penguji & dokumentator |
| Narindra Panji Dwitama | 2507431045 | Analis & pengelola konten, Perancang & pengembang HTML |
| Rama Jundi Andela | 2507431046 | Perancang & pengembang HTML, Penguji & dokumentator |
| Sigit Ariyanto | 2507431015 | Perancang & pengembang HTML, Pengembang CSS |
| Izzan Zhillan Irham | 2507431049 | Pengembang CSS, Penguji & dokumentator |

---

## 🎯 Tujuan Platform

1. **Menyediakan Pusat Informasi Lingkungan**: Menyajikan informasi dan edukasi terstruktur mengenai berbagai isu lingkungan hidup bagi masyarakat luas.
2. **Mewadahi Partisipasi Aktif Masyarakat**: Memfasilitasi donasi dan pendaftaran relawan melalui akun pengguna yang terverifikasi.
3. **Menjunjung Tinggi Akuntabilitas dan Transparansi**: Menyajikan dashboard transparansi berbasis data real-time agar donatur dan relawan dapat memantau dampak serta penggunaan dana secara terbuka.
4. **Menghadirkan Pengelolaan Sistem yang Terintegrasi**: Membangun panel admin untuk mengelola data pengguna, konten edukasi, laporan donasi, dan kegiatan relawan secara terpusat.

---

## 📄 Halaman

| Halaman | File | Akses | Deskripsi |
|---|---|---|---|
| Beranda | `index.html` | Publik | Hero section, ringkasan misi, CTA menuju halaman lain |
| Edukasi | `edukasi.html` | Publik | Konten informasi lingkungan dalam empat topik utama |
| Transparansi | `transparansi.html` | Publik | Dashboard transparansi: laporan dana dan dokumentasi kegiatan |
| Register | `register.html` | Publik | Formulir pembuatan akun pengguna baru |
| Login | `login.html` | Publik | Formulir masuk untuk pengguna terdaftar |
| Donasi | `donasi.html` | Login | Formulir donasi finansial; data tersimpan di database |
| Relawan | `relawan.html` | Login | Formulir pendaftaran volunteer; data tersimpan di database |
| Panel Admin | `admin/index.html` | Admin | Dashboard admin: kelola donatur, relawan, laporan, dan konten |

---

## 🗂️ Struktur Direktori

```
EcoVein/
├── index.html
├── edukasi.html
├── donasi.html
├── relawan.html
├── transparansi.html
├── login.html
├── register.html
├── admin/
│   ├── login.html
│   ├── index.html
│   ├── donatur.html
│   ├── relawan.html
│   ├── laporan.html
│   └── konten.html
├── css/
│   ├── base.css
│   ├── components.css
│   └── layout.css
├── js/
│   ├── auth.js
│   ├── main.js
│   └── dashboard.js
├── backend/
│   ├── db.js
│   └── routes/
├── assets/
│   ├── images/
│   └── icons/
├── docs/
│   ├── requirements.md
│   └── wireframe.pdf
└── README.md
```

---

## 🛠️ Teknologi

| Lapisan | Teknologi |
|---|---|
| Frontend | HTML5, CSS3, JavaScript (tanpa framework CSS) |
| Backend | Node.js / PHP |
| Database | MySQL / PostgreSQL |
| Autentikasi | JWT / Session Cookie + bcrypt |

---

## 👤 Peran Pengguna

| Peran | Hak Akses |
|---|---|
| Tamu (Guest) | Beranda, Edukasi, Transparansi |
| Pengguna (User) | Semua akses tamu + Donasi dan Relawan (setelah login) |
| Admin | Semua akses pengguna + Panel Admin |

---

## 🗄️ Skema Database

| Tabel | Kolom Utama | Keterangan |
|---|---|---|
| users | id, nama, email, password_hash, role, created_at | Semua akun pengguna dan admin |
| donatur | id, user_id, nominal, program, status, created_at | Data donasi terhubung ke akun pengguna |
| relawan | id, user_id, kontak, lokasi, jenis_kegiatan, status, created_at | Data relawan terhubung ke akun pengguna |
| laporan | id, judul, jenis, konten, tanggal, admin_id, created_at | Entri laporan transparansi dari admin |

---

## 🚀 Cara Menjalankan

1. Clone repositori ini
   ```bash
   git clone https://github.com/N-DraPZSr/EcoVein.git
   cd EcoVein
   ```
2. Sesuaikan konfigurasi database di file `.env` atau `config.php`
3. Jalankan server lokal, contoh dengan Node.js:
   ```bash
   node backend/server.js
   ```
4. Buka `http://localhost:3000` di browser (Chrome atau Firefox)

---

## 📐 Viewport Uji

| Perangkat | Lebar |
|---|---|
| Ponsel kecil | 360 px |
| Ponsel | 390 px |
| Tablet | 768 px |
| Desktop | 1366 px |

---

**Hasil Survei Kebutuhan Data Untuk Web**

[https://docs.google.com/forms/d/1B6WvQln0b2qAN3GwVTJuonNm2h4s0nWe-sdsTmsHGfw/edit#responses](https://docs.google.com/forms/d/1B6WvQln0b2qAN3GwVTJuonNm2h4s0nWe-sdsTmsHGfw/edit#responses)
