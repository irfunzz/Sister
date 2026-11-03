# Kelengkapan Portal Desa Plumbon & Gadingan Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Melengkapi seluruh konten data (monografi, demografi, aparatur pamong, BPD, lembaga, warta berita, galeri, dan potensi unggulan) pada portal Desa Plumbon dan Desa Gadingan agar setara lengkapnya dan selaras dengan Desa Palur.

**Architecture:** Memanfaatkan struktur HTML statis multi-halaman berbasis HeroBiz yang sudah terstruktur di folder `plumbon/` dan `gadingan/`, mengisi data resmi dari SID Kabupaten Sukoharjo dan BPS Mojolaban, serta mengintegrasikan interaktivitas Isotope, GLightbox, dan dinamisasi artikel via JavaScript URL parameter.

**Tech Stack:** HTML5, CSS3, Bootstrap 5.3, Bootstrap Icons, GLightbox, Isotope Layout, Swiper, Vanilla JavaScript.

## Global Constraints
- Seluruh data wajib berbasis fakta resmi (UU No. 3 Tahun 2024, SK Bupati Sukoharjo 2024, SID Sukoharjo, BPS Mojolaban).
- Nol broken links, nol placeholder "Lorem Ipsum" atau "TODO".
- Pertahankan struktur kelas CSS `palur.css` dan mobile responsive design (360px s/d 1440px).

---

### Task 1: Melengkapi Halaman Profil Desa Plumbon (`plumbon/profil.html`)
**Files:**
- Modify: `plumbon/profil.html`

- [ ] **Step 1: Isi tabel Monografi Lahan & Tata Ruang Plumbon** (Luas 215,45 Ha: sawah irigasi teknis 132 Ha, pekarangan 68 Ha, fasum 15,45 Ha).
- [ ] **Step 2: Lengkapi tabel Demografi Kependudukan Plumbon** (Pendidikan, pekerjaan, pemeluk agama, jumlah penduduk 4.820 jiwa).
- [ ] **Step 3: Tambahkan dokumentasi foto visual potensi wilayah** (pertanian sawah irigasi Bengawan Solo, budidaya perikanan, UMKM olahan pangan menggunakan aset foto resmi).
- [ ] **Step 4: Verifikasi integritas tabel & rendering HTML**.

---

### Task 2: Melengkapi Pemerintahan & Lembaga Desa Plumbon (`plumbon/pemerintahan.html`)
**Files:**
- Modify: `plumbon/pemerintahan.html`

- [ ] **Step 1: Lengkapi profil Kades Eko Hariyanto, S.E., S.Sos.** dengan dasar hukum SK Bupati No. 400.10.2/489 Tahun 2024.
- [ ] **Step 2: Susun card struktur pamong desa lengkap** (Sekdes Yusuf, Kaur TU Riki, Kaur Perencanaan Citra, Kasi Pem Sunardi, Kasi Kesra Sugeng, Kasi Pelayanan Hasan, Kadus 1 Dwi, Kadus 2 Sri Widi) beserta tupoksinya.
- [ ] **Step 3: Lengkapi kelembagaan kemasyarakatan** (Susunan BPD Plumbon, LPMD, TP-PKK, Karang Taruna Muda Mandiri, Satlinmas).
- [ ] **Step 4: Verifikasi tampilan bagan pamong & tabel kelembagaan**.

---

### Task 3: Melengkapi Galeri & Berita Desa Plumbon (`plumbon/galeri.html`, `plumbon/berita.html`, `plumbon/berita-detail.html`)
**Files:**
- Modify: `plumbon/galeri.html`
- Modify: `plumbon/berita.html`
- Modify: `plumbon/berita-detail.html`

- [ ] **Step 1: Perkaya album galeri foto kegiatan desa** di `plumbon/galeri.html` dengan filter kategori Isotope dan GLightbox.
- [ ] **Step 2: Sinkronkan daftar artikel di `plumbon/berita.html`** agar seluruh card warta memiliki link `berita-detail.html?id=...`.
- [ ] **Step 3: Lengkapi database JavaScript artikel di `plumbon/berita-detail.html`** agar seluruh artikel memuat teks isi utuh dan galeri foto.
- [ ] **Step 4: Uji klik artikel berita dan pastikan data artikel ter-render sempurna**.

---

### Task 4: Melengkapi Halaman Profil Desa Gadingan (`gadingan/profil.html`)
**Files:**
- Modify: `gadingan/profil.html`

- [ ] **Step 1: Isi rincian monografi lahan & 12 dusun administratif Gadingan** (Luas 268,70 Ha: sawah 145 Ha, pemukiman & industri 102 Ha, lain-lain 21,70 Ha).
- [ ] **Step 2: Lengkapi tabel demografi kependudukan Gadingan** (6.580 jiwa, tabel tingkat pendidikan, mata pencaharian industri & pertanian, pemeluk agama).
- [ ] **Step 3: Lengkapi etalase visual potensi unggulan** (Sentra Produsen Shuttlecock Nasional & Sentra Kerupuk Karak/Rambak Gadingan dengan dokumentasi foto).
- [ ] **Step 4: Verifikasi tampilan halaman profil Gadingan**.

---

### Task 5: Melengkapi Pemerintahan & Lembaga Desa Gadingan (`gadingan/pemerintahan.html`)
**Files:**
- Modify: `gadingan/pemerintahan.html`

- [ ] **Step 1: Lengkapi profil Kades Parji, A.Md.** dengan dasar hukum SK Bupati No. 400.10.2/425 Tahun 2024.
- [ ] **Step 2: Susun card struktur pamong desa lengkap** (Sekdes Kernadi, Kaur TU Diah, Kaur Perencanaan Yuli, Kasi Pem Erika, Kasi Kesra Guruh, Kasi Pelayanan Bagus, Kadus 1 Sutanto, Kadus 2 Sariyanto).
- [ ] **Step 3: Lengkapi kelembagaan desa resmi** (BPD Gadingan: Supilih, Surahman, Anita, Sri Mulat; LPMD: Mardiyono, S.T.; TP-PKK; Karang Taruna; RT/RW).
- [ ] **Step 4: Verifikasi tampilan struktur dan kelembagaan**.

---

### Task 6: Melengkapi Galeri & Berita Desa Gadingan (`gadingan/galeri.html`, `gadingan/berita.html`, `gadingan/berita-detail.html`)
**Files:**
- Modify: `gadingan/galeri.html`
- Modify: `gadingan/berita.html`
- Modify: `gadingan/berita-detail.html`

- [ ] **Step 1: Perkaya album galeri foto kegiatan desa** di `gadingan/galeri.html` (sentra kok, kerupuk, balai desa, posyandu).
- [ ] **Step 2: Sinkronkan daftar artikel warta di `gadingan/berita.html`**.
- [ ] **Step 3: Lengkapi artikel data store di `gadingan/berita-detail.html`**.
- [ ] **Step 4: Uji interaktivitas filter galeri dan pembaca berita**.

---

### Task 7: Sinkronisasi Navigasi Global & Verifikasi Akhir
**Files:**
- Modify / Check: Semua 24 file HTML di `.`, `plumbon/`, `gadingan/`

- [ ] **Step 1: Validasi konsistensi Topbar Switcher (`Palur | Gadingan | Plumbon`) dan Mobile Drawer** di semua halaman.
- [ ] **Step 2: Jalankan skrip pemeriksa integritas otomatis** (memeriksa zero broken links, zero missing images, zero placeholder text).
- [ ] **Step 3: Commit seluruh perubahan dengan Conventional Commits**.
