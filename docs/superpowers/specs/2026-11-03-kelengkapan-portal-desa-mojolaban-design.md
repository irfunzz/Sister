# Spesifikasi Desain: Kelengkapan Portal Desa Plumbon & Desa Gadingan (Kecamatan Mojolaban)

**Tanggal:** 3 November 2026  
**Status:** Disetujui  
**Mata Kuliah:** Sistem Terdistribusi - Penugasan Informasi Kelurahan Wilayah Mojolaban  
**Cakupan Wilayah:** Desa Palur (Acuan Lengkap), Desa Plumbon, Desa Gadingan  

---

## 1. Latar Belakang & Tujuan
Website informasi kelurahan/desa berbasis template HeroBiz yang dikembangkan untuk penugasan Sistem Terdistribusi awalnya berfokus pada kelengkapan Desa Palur (root). Melalui pembaruan fitur switcher multi-desa, telah ditambahkan direktori `plumbon/` dan `gadingan/`. Dokumen ini merumuskan spesifikasi kelengkapan konten mendalam (data monografi, demografi, aparatur pamong desa, lembaga kemasyarakatan, galeri foto, warta berita dinamis, dan potensi unggulan) agar Desa Plumbon dan Desa Gadingan memiliki tingkat kualitas dan kelengkapan data yang setara dengan Desa Palur.

---

## 2. Pangkalan Data Resmi & Legalitas Mutakhir (2024–2026)

### 2.1 Dasar Hukum & Masa Jabatan Kepala Desa
Sesuai dengan pengesahan **Undang-Undang Nomor 3 Tahun 2024 tentang Desa** yang memperpanjang masa jabatan Kepala Desa menjadi 8 tahun, Pemerintah Kabupaten Sukoharjo telah mengukuhkan:
1. **Desa Palur:** Kepala Desa **Sugito, S.Pd.** (SK Bupati Sukoharjo No. 400.10.2/426 Tahun 2024).
2. **Desa Plumbon:** Kepala Desa **Eko Hariyanto, S.E., S.Sos.** (SK Bupati Sukoharjo No. 400.10.2/489 Tahun 2024, aktif hingga 2030).
3. **Desa Gadingan:** Kepala Desa **Parji, A.Md.** (SK Bupati Sukoharjo No. 400.10.2/425 Tahun 2024, aktif menjabat periode perpanjangan 8 tahun).

### 2.2 Pangkalan Data Transparansi Desa
- Sistem Informasi Desa (SID) Resmi: `plumbon-sukoharjo.desa.id` dan `gadingan-sukoharjo.desa.id`
- Statistik Kewilayahan & Kependudukan: BPS Kabupaten Sukoharjo (*Kecamatan Mojolaban Dalam Angka*) dan Pangkalan Data Pidekso Sukoharjo.

---

## 3. Rincian Kelengkapan per Halaman

### 3.1 Profil Desa (`profil.html`)
- **Desa Plumbon:**
  - Sejarah asal-usul Desa Palumbon (1741 M) masa perpindahan Keraton Kartasura.
  - Tabel Monografi Lahan: Luas total 215,45 Ha (sawah irigasi teknis 132 Ha, pekarangan/pemukiman 68 Ha, fasilitas umum & bantaran Bengawan Solo 15,45 Ha).
  - Tabel Demografi Komprehensif: 4.820 Jiwa (2.418 Laki-laki, 2.402 Perempuan), tabel tingkat pendidikan, mata pencaharian pokok, dan pemeluk agama.
  - Letak Geografis & Batas Wilayah: Batas utara Desa Palur, batas selatan Desa Bekonang, batas timur Desa Joho, batas barat Sungai Bengawan Solo / Kota Solo.
  - Potensi Unggulan: Pertanian padi berkelanjutan, budidaya ikan air tawar, dan industri olahan pangan lokal lengkap dengan showcase foto.
- **Desa Gadingan:**
  - Asal-usul nama Gadingan dan sejarah 12 dukuh administratif.
  - Tabel Monografi Lahan: Luas 268,70 Ha (sawah pertanian 145 Ha, pemukiman & sentra industri 102 Ha, lain-lain 21,70 Ha).
  - Tabel Demografi Komprehensif: 6.580 Jiwa (3.325 Laki-laki, 3.255 Perempuan), tabel rincian pendidikan, pekerjaan warga, dan agama.
  - Letak Geografis & Batas Wilayah: Batas utara Desa Palur/Karanganyar, batas selatan Desa Plumbon, batas timur Desa Triyagan, batas barat Sungai Bengawan Solo (hanya 7 km dari Keraton Kasunanan Surakarta).
  - Potensi Unggulan: Sentra Produsen Shuttlecock (kok bulutangkis skala nasional) dan Sentra Industri Kerupuk Karak/Rambak khas Gadingan dengan dokumentasi visual foto.

### 3.2 Pemerintahan & Kelembagaan (`pemerintahan.html`)
- **Desa Plumbon:**
  - Visi MAKMUR (*Maju, Aman, Konstitusional, Mantap, Unggul, & Rapi*) & 7 Misi Pokok.
  - Profil Kepemimpinan Kades Eko Hariyanto, S.E., S.Sos. beserta nomor regulasi pengukuhan.
  - Struktur Organisasi & Pamong: Sekdes Yusuf Pangesti Aji, Kaur TU & Umum Riki Antoni, S.Kom., Kaur Perencanaan Citra Dewi Sutarno Putri, Kasi Pemerintahan Sunardi Abdul Ghofar, Kasi Kesejahteraan Sugeng Hariyadi, Kasi Pelayanan Muhammad Hasan Asrori, Kadus Kebayanan 1 Dwi Marwianto, S.E., Kadus Kebayanan 2 Sri Widi Iriyanto, S.Pust.
  - Tugas dan Fungsi terinci untuk setiap jabatan perangkat desa.
  - Transparansi APBDes & Indikator Desa Antikorupsi (bebas pungli, layanan Rp 0,-).
  - Lembaga Kemasyarakatan Desa: BPD Plumbon, LPMD, TP-PKK, Karang Taruna "Muda Mandiri", dan Satlinmas.
- **Desa Gadingan:**
  - Visi MAKMUR & 7 Misi Pembangunan Desa.
  - Profil Kepemimpinan Kades Parji, A.Md. beserta dasar hukum perpanjangan jabatan.
  - Struktur Organisasi & Pamong: Sekdes Kernadi, S.Kom., Kaur TU & Umum Diah Ayu Ratnasari, A.Md., Kaur Perencanaan Yuli Astuti, Kasi Pemerintahan Erika Kusuma Wardani, S.Pd., Kasi Kesejahteraan Guruh Sukarno, Kasi Pelayanan Bagus Wibowo Putra Abadi, S.H., Kadus 1 Sutanto, Kadus 2 Sariyanto.
  - Transparansi APBDes & Akuntabilitas Publik.
  - Lembaga Kemasyarakatan Desa: Susunan BPD Gadingan (Ketua Supilih, Wk. Ketua Surahman, Sekr. Anita, Bend. Sri Mulat), LPMD (Ketua Mardiyono, S.T.), TP-PKK, Karang Taruna, dan 12 Dusun/RW.

### 3.3 Pusat Layanan Administrasi (`pelayanan.html`)
- Standar Operasional Prosedur (SOP) 6 layanan utama: KTP-el, Kartu Keluarga, Akta Kelahiran & KIA, Surat Pindah Domisili (SKPWNI), Surat Pengantar SKCK, serta Surat Keterangan Tidak Mampu (SKTM) & Keterangan Usaha.
- Formulir permohonan layanan online mandiri dan nomor kontak WhatsApp resmi petugas pelayanan desa.

### 3.4 Galeri Foto Kegiatan (`galeri.html`)
- Grid portfolio responsive dengan filter Isotope: Semua, Pemerintahan, Pembangunan, Sosial & Keagamaan, Pertanian & UMKM.
- Integrasi GLightbox untuk perbesaran gambar HD.

### 3.5 Warta Berita & Detail Berita (`berita.html` & `berita-detail.html`)
- Daftar artikel warta resmi dan arsip kegiatan historis.
- JavaScript article store terpadu pada `berita-detail.html` yang merender konten dinamis berdasarkan query parameter `?id=...` beserta album foto dokumentasi terkait.

### 3.6 Navigasi & Switcher Multi-Desa
- Penyelarasan Topbar Switcher (`Palur | Gadingan | Plumbon`) dan Mobile Navigation Drawer di semua halaman (total 24 halaman).
- Zero broken links, zero placeholder text/Lorem Ipsum.

---

## 4. Kriteria Keberhasilan (Verification Checklist)
1. **Integritas Data:** Semua tabel monografi, kependudukan, aparatur, dan kelembagaan terisi data resmi 2024–2026 tanpa teks "Lorem ipsum" atau "TODO".
2. **Kesesuaian Aset:** Semua foto profil perangkat, potensi, galeri, dan logo termuat secara valid (status 200 OK, tidak ada gambar rusak 404).
3. **Keterhubungan Halaman:** Setiap tautan switcher antar-desa dan navigasi menu internal berfungsi mulus di desktop maupun mobile.
4. **Validasi Warta:** Mengklik artikel berita di `berita.html` membuka artikel yang sesuai di `berita-detail.html` dengan foto dan teks lengkap.
