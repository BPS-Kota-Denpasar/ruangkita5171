# 📋 RUANG KITA
> **Ruang Konsultasi dan Informasi Mitra Sensus Ekonomi 2026**  
> BPS Kota Denpasar

[![GitHub Pages](https://img.shields.io/badge/Live-GitHub%20Pages-brightgreen)](https://bps-kota-denpasar.github.io/ruangkita5171/)

---

## 📖 Tentang Aplikasi

**Ruang Kita** adalah aplikasi berbasis web yang menjadi sarana komunikasi antara **Mitra Petugas Sensus Ekonomi 2026** dengan **Tim Admin BPS Kota Denpasar**. Aplikasi ini memungkinkan petugas lapangan mengirimkan pertanyaan atau kendala secara terstruktur, yang kemudian dapat dijawab oleh admin secara individual maupun massal.

### Fitur Utama
- 📚 **FAQ** — Pertanyaan umum yang dikelompokkan per topik, lengkap dengan pencarian dan filter; tampil sebagai tab utama saat login
- 📩 **Buat Pertanyaan** — Kirim pertanyaan baru via tombol **Buat Pertanyaan** (FAB) di tab bar atau pojok kanan bawah layar (mobile); dilengkapi lampiran gambar opsional
- 🕐 **Riwayat** — Pantau semua pertanyaan yang pernah dikirim beserta status terkininya
- 💬 **Forum Diskusi** — Lihat kumpulan pertanyaan dari seluruh mitra yang dikelompokkan otomatis berdasarkan tema (AI-powered)
- 🔔 **Pemberitahuan** — Ringkasan status terbaru pertanyaan Anda; badge merah muncul jika ada jawaban baru
- 🛠️ **Panel Admin** — Kelola, filter, balas, dan tutup pertanyaan secara individual maupun massal; dapat diakses via **Role Filter** setelah login sebagai admin

---

## 🔗 Akses Aplikasi

| Lingkungan | URL |
|---|---|
| Produksi (Live) | [https://bps-kota-denpasar.github.io/ruangkita5171/](https://bps-kota-denpasar.github.io/ruangkita5171/) |
| Repository | [https://github.com/BPS-Kota-Denpasar/ruangkita5171](https://github.com/BPS-Kota-Denpasar/ruangkita5171) |

---

## 👤 Panduan Pengguna (Mitra)

### 1. Login
1. Buka aplikasi di browser HP atau komputer.
2. Masukkan **email** yang terdaftar di Data Mitra.
3. Klik **Masuk**.
4. Jika email terdaftar, Anda langsung masuk ke tab **FAQ**.

> ⚠️ Jika muncul pesan "Login gagal", pastikan email yang digunakan sudah terdaftar di sistem BPS Kota Denpasar.

---

### 2. FAQ
1. Setelah login, tab **FAQ** otomatis terbuka.
2. Gunakan **filter topik** (Semua / Fasih / Konsep Lapangan / Lainnya) untuk menyempurnakan tampilan.
3. Gunakan **kotak pencarian** untuk menemukan jawaban berdasarkan kata kunci.
4. Klik judul pertanyaan untuk membuka/menutup jawabannya.
5. Jika pertanyaan belum ada di FAQ, klik **+ Buat Pertanyaan Baru** di bagian bawah.

---

### 3. Buat Pertanyaan
1. Klik tombol **Buat Pertanyaan** di tab bar (desktop/tablet) atau di pojok kanan bawah layar (mobile).
2. Data diri (Nama, HP, SOBAT ID, Email) terisi otomatis dari profil Anda.
3. Pilih **Topik** yang sesuai:
   - **Fasih** — pertanyaan seputar penggunaan aplikasi Fasih
   - **Konsep Lapangan** — pertanyaan seputar konsep atau definisi di lapangan
   - **Lainnya** — pertanyaan di luar dua topik di atas
4. Tambahkan **lampiran gambar** jika diperlukan (opsional).
5. Tulis **pertanyaan** Anda (maks. 2.000 karakter).
6. Klik **Kirim Pertanyaan** — atau klik **Batal** untuk menutup formulir tanpa mengirim.

> ✅ Setelah terkirim, pertanyaan langsung berstatus **Baru Masuk** dan muncul di tab Riwayat.

---

### 4. Riwayat
1. Klik tab **Riwayat** di bar navigasi.
2. Semua pertanyaan yang pernah Anda kirim ditampilkan lengkap dengan status terkini dan jawaban admin.

**Arti Status Pertanyaan:**

| Status | Arti |
|---|---|
| 🟠 Baru Masuk | Pertanyaan sudah diterima, belum diproses |
| 🟢 Sudah Dibalas | Admin sudah memberikan jawaban |
| ⚪ Selesai | Pertanyaan telah ditutup |

---

### 5. Forum Diskusi
1. Klik tab **Forum** di bar navigasi.
2. Pertanyaan dari seluruh mitra dikelompokkan otomatis berdasarkan tema yang mirip (diproses AI).
3. Gunakan forum ini untuk melihat apakah pertanyaan Anda sudah pernah dibahas sebelumnya.

---

### 6. Pemberitahuan
1. Klik tab **Pemberitahuan** di bar navigasi.
2. Ringkasan status pertanyaan Anda ditampilkan di sini.
3. Jika ada jawaban baru dari admin, badge merah 🔴 muncul di ikon tab Pemberitahuan.

---

### 7. Logout
- Klik tombol **Logout** di bagian atas untuk keluar dari aplikasi.
- Sesi login tersimpan otomatis di browser selama cache tidak dihapus.

---

## 🛠️ Panduan Admin

### 1. Login sebagai Admin
1. Masukkan email yang terdaftar sebagai **ADMIN**.
2. Setelah login, bar **Mode tampilan** akan muncul di bawah tombol Logout.
3. Pilih **🔧 Tampilan Admin** untuk membuka tab panel admin.

---

### 2. Kelola Pertanyaan (Tab "Kelola Pertanyaan")

#### Ringkasan (Summary)
Di bagian atas panel, tersedia **3 kartu ringkasan**:
- **Total Pertanyaan** — jumlah seluruh pertanyaan yang masuk
- **Baru Masuk** — pertanyaan yang belum diproses
- **Dibalas & Selesai** — pertanyaan yang sudah ditangani

#### Filter dan Pencarian
- **Cari pertanyaan** — cari berdasarkan nama, email, SOBAT ID, atau isi pertanyaan.
- **Filter Status** — saring berdasarkan: Semua / Baru Masuk / Sudah Dibalas / Selesai.
- **Filter Topik** — saring berdasarkan: Semua / Fasih / Konsep Lapangan / Lainnya.
- **Urutkan** — tampilkan pertanyaan terbaru atau terlama terlebih dahulu.

#### Balas Satu Pertanyaan
1. Temukan pertanyaan yang ingin dijawab.
2. Isi kolom jawaban di bagian bawah kartu pertanyaan.
3. Klik **Balas** untuk mengirim jawaban (status → Sudah Dibalas).
4. Klik **Tutup** jika pertanyaan sudah selesai ditangani (status → Selesai).

#### Balas Banyak Pertanyaan Sekaligus (Bulk)
1. Centang pertanyaan yang ingin dijawab (atau gunakan **Pilih Semua**).
2. Isi jawaban di masing-masing kolom pertanyaan yang sudah dicentang.
3. Klik **Kirim Jawaban Terpilih** untuk mengirim semua jawaban sekaligus.
4. Gunakan **Batal Pilih** untuk membatalkan semua centang.

---

### 3. Forum Admin (Tab "Forum Admin")
1. Klik tab **Forum Admin**.
2. Tampil kumpulan pertanyaan yang sudah dikelompokkan otomatis berdasarkan tema.
3. Gunakan ini untuk memantau **pola pertanyaan** yang sering muncul dari mitra lapangan.

---

### 4. Kembali ke Tampilan Pengguna
- Pilih **👤 Tampilan Pengguna** di bar Mode tampilan untuk menyembunyikan tab admin dan kembali ke tampilan mitra.

---

## 🔔 Notifikasi Toast

Aplikasi menampilkan notifikasi singkat (toast) di pojok kanan bawah layar untuk setiap aksi:

| Warna | Arti |
|---|---|
| 🟢 Hijau | Aksi berhasil |
| 🔴 Merah | Aksi gagal |
| 🔵 Biru | Informasi |
| 🟡 Kuning/Oranye | Peringatan |

**Contoh pesan toast:**
- `Pertanyaan berhasil dikirim. Lampiran tersimpan.`
- `Jawaban terkirim untuk pertanyaan ini.`
- `Pertanyaan ditandai selesai.`
- `Isi jawaban terlebih dahulu.`

---

## 🗂️ Struktur Topik

| Topik | Deskripsi |
|---|---|
| Fasih | Pertanyaan seputar aplikasi Fasih (error, instalasi, penggunaan) |
| Konsep Lapangan | Pertanyaan seputar konsep, definisi, atau prosedur pencacahan |
| Lainnya | Pertanyaan di luar dua topik di atas |

---

## ⚙️ Teknologi

| Komponen | Teknologi |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Backend / Database | Google Apps Script + Google Sheets |
| Penyimpanan Lampiran | Google Drive |
| Hosting | GitHub Pages |
| AI Pengelompokan Forum | Google Gemini (via Apps Script) |

---

## 📁 Struktur Repositori

```
ruangkita5171/
├── index.html        # Aplikasi utama (single-page)
└── README.md         # Dokumentasi ini
```

---

## 🔒 Catatan Keamanan

- Login menggunakan **email saja** tanpa password — akses terbatas untuk email yang terdaftar di Data Mitra atau Admin.
- Sesi login disimpan di `localStorage` browser.
- Data pertanyaan tersimpan di **Google Sheets** yang hanya dapat diakses via Apps Script.
- Lampiran gambar disimpan di **Google Drive** dengan izin akses terbatas.

---

## 📞 Kontak & Dukungan

Jika mengalami kendala teknis, hubungi Tim IT BPS Kota Denpasar melalui jalur koordinasi resmi atau kirim pertanyaan melalui topik **Lainnya** di aplikasi ini.

---

*Dikembangkan untuk keperluan internal BPS Kota Denpasar — Sensus Ekonomi 2026.*
