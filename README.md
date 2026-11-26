# EcoVein

Platform website peduli lingkungan yang berfungsi sebagai pusat informasi dan edukasi isu lingkungan hidup, sekaligus mewadahi partisipasi aktif masyarakat melalui fitur donasi dan pendaftaran relawan, dengan dashboard transparansi yang terbuka untuk publik. Platform ini dilengkapi dengan antarmuka edukasi, formulir partisipasi, tampilan panel pengelolaan konten, serta dashboard transparansi interaktif untuk mendukung keterbukaan informasi publik.

> Teknik Multimedia Digital, Politeknik Negeri Jakarta, 2026.

---

## Anggota Kelompok 4

| Nama | NIM | Peran |
|---|---|---|
| Ahmad Husein | 2507431079 | pengembang dan perancang bagian admin & 5 management views |
| Frytsar Oriscky Nurrachman | 2507431041 | Analis & pengelola konten, Penguji & dokumentator |
| Narindra Panji Dwitama | 2507431045 | Analis & pengelola konten, Perancang HTML, Perancang & Pengembang CSS |
| Rama Jundi Andela | 2507431046 | Perancang & pengembang HTML, Penguji & dokumentator |
| Sigit Ariyanto | 2507431015 | Perancang & pengembang HTML, Pengembang CSS |
| Izzan Zhillan Irham | 2507431049 | Perancang HTML, Perancang JS, Penguji |

---

## Tujuan Platform

1. **Menyediakan Pusat Informasi Lingkungan**: Menyajikan informasi dan edukasi terstruktur mengenai berbagai isu lingkungan hidup bagi masyarakat luas.
2. **Mewadahi Partisipasi Aktif Masyarakat**: Memfasilitasi antarmuka donasi dan pendaftaran relawan yang mudah diakses oleh pengunjung.
3. **Menjunjung Tinggi Akuntabilitas dan Transparansi**: Menyajikan tampilan dashboard transparansi interaktif agar pengunjung dapat memantau dampak serta laporan penggunaan dana secara terbuka.
4. **Menghadirkan Antarmuka Pengelolaan yang Terstruktur**: Merancang tampilan panel admin untuk kebutuhan pengelolaan konten edukasi, data donatur, laporan, dan kegiatan relawan secara terpusat.

---

## Halaman

| Halaman | File | Akses | Deskripsi |
|---|---|---|---|
| Beranda | `index.html` | Publik | Hero section, ringkasan misi, CTA menuju halaman lain |
| Edukasi | `edukasi.html` | Publik | Konten informasi lingkungan dalam empat topik utama |
| Transparansi | `transparansi.html` | Publik | Dashboard transparansi: laporan dana dan dokumentasi kegiatan |
| Register | `register.html` | Publik | Formulir pembuatan akun pengguna baru |
| Login | `login.html` | Publik | Formulir masuk untuk pengguna terdaftar |
| Donasi | `donasi.html` | Login | Formulir donasi finansial |
| Relawan | `relawan.html` | Login | Formulir pendaftaran volunteer |
| Panel Admin | `admin/index.html` | Admin | Dashboard admin: kelola donatur, relawan, laporan, dan konten |

---

## Struktur Direktori

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
│   ├── main.js
│   └── dashboard.js
├── assets/
│   ├── images/
│   └── icons/
├── docs/
│   ├── requirements.md
│   └── wireframe.pdf
└── README.md
```

---

## Teknologi

| Lapisan | Teknologi |
|---|---|
| Frontend | HTML5, CSS3, JavaScript (tanpa framework CSS) |

---

## Peran Pengguna

| Peran | Hak Akses |
|---|---|
| Tamu (Guest) | Beranda, Edukasi, Transparansi |
| Pengguna (User) | Semua akses tamu + Donasi dan Relawan |
| Admin | Semua akses pengguna + Panel Admin |

---

## Cara Menjalankan

1. Clone repositori ini
   ```bash
   git clone [https://github.com/N-DraPZSr/EcoVein.git](https://github.com/N-DraPZSr/EcoVein.git)
   cd EcoVein
   ```
2. Buka file `index.html` langsung di browser (Chrome atau Firefox), atau jalankan menggunakan ekstensi **Live Server** pada Visual Studio Code.

---

## Viewport Uji

| Perangkat | Lebar |
|---|---|
| Ponsel kecil | 360 px |
| Ponsel | 390 px |
| Tablet | 768 px |
| Desktop | 1366 px |

---

**Hasil Survei Kebutuhan Data Untuk Web**
[https://docs.google.com/forms/d/1B6WvQln0b2qAN3GwVTJuonNm2h4s0nWe-sdsTmsHGfw/edit#responses](https://docs.google.com/forms/d/1B6WvQln0b2qAN3GwVTJuonNm2h4s0nWe-sdsTmsHGfw/edit#responses)
