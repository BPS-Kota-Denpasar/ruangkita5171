# 📋 RUANG KITA
> **Ruang Informasi dan Konsultasi Mitra Sensus Ekonomi 2026**  
> BPS Kota Denpasar

[![GitHub Pages](https://img.shields.io/badge/Live-GitHub%20Pages-brightgreen)](https://bps-kota-denpasar.github.io/ruangkita5171/)

---

## 📖 Tentang Aplikasi

**Ruang Kita** adalah aplikasi berbasis web yang menjadi sarana komunikasi antara **Mitra Petugas Sensus Ekonomi 2026** dengan **Tim Admin BPS Kota Denpasar**. Aplikasi ini memungkinkan petugas lapangan mengirimkan pertanyaan, kendala, atau permintaan informasi secara terstruktur dalam bentuk **tiket**, yang kemudian dapat dijawab oleh admin secara langsung.

### Fitur Utama
- 📩 **Buat Tiket** — Kirim pertanyaan atau kendala dengan topik tertentu, lengkap dengan lampiran gambar
- 📂 **Riwayat Tiket** — Pantau status tiket yang telah dikirim
- 💬 **Forum Diskusi** — Lihat kumpulan pertanyaan yang dikelompokkan otomatis berdasarkan tema
- 🔔 **Pemberitahuan** — Ringkasan status terbaru tiket Anda
- 🛠️ **Panel Admin** — Kelola, filter, balas, dan tutup tiket secara individual maupun massal

---

## 🔗 Akses Aplikasi

| Lingkungan | URL |
|---|---|
| Produksi (Live) | [https://bps-kota-denpasar.github.io/ruangkita5171/](https://bps-kota-denpasar.github.io/ruangkita5171/) |
| Repository | [https://github.com/BPS-Kota-Denpasar/ruangkita5171](https://github.com/BPS-Kota-Denpasar/ruangkita5171) |

---

## 👤 Panduan Pengguna (User / Mitra)

### 1. Login
1. Buka aplikasi di browser HP atau komputer.
2. Masukkan **email** yang terdaftar di MasterPetugas.
3. Klik **Masuk**.
4. Jika email terdaftar, Anda akan langsung masuk ke halaman utama.

> ⚠️ Jika muncul pesan "Login gagal", pastikan email yang digunakan sudah terdaftar di sistem MasterPetugas BPS Kota Denpasar.

---

### 2. Buat Tiket
1. Setelah login, klik tab **Buat Tiket**.
2. Data diri (Nama, HP, SOBAT_ID, Email) akan terisi otomatis.
3. Pilih **Topik** yang sesuai:
   - **Fasih** — pertanyaan seputar penggunaan aplikasi Fasih
   - **Konsep Lapangan** — pertanyaan seputar konsep atau definisi di lapangan
   - **Lainnya** — pertanyaan lain di luar topik di atas
4. Tambahkan **lampiran gambar** jika diperlukan (opsional).
5. Tulis **pertanyaan** Anda di kolom yang tersedia (maks. 2000 karakter).
6. Klik **Kirim Tiket**.

> ✅ Setelah tiket terkirim, status akan langsung muncul sebagai **Baru masuk**.

---

### 3. Riwayat Tiket
1. Klik tab **Riwayat Tiket**.
2. Semua tiket yang pernah Anda kirim akan ditampilkan lengkap dengan status terkini.

**Arti Status Tiket:**

| Status | Arti |
|---|---|
| 🟠 Baru masuk | Tiket sudah diterima, belum diproses |
| 🟢 Sudah dibalas | Admin sudah memberikan jawaban |
| ⚪ Selesai | Tiket telah ditutup |

---

### 4. Forum Diskusi
1. Klik tab **Forum Diskusi**.
2. Pertanyaan dari seluruh mitra dikelompokkan secara otomatis berdasarkan tema yang mirip.
3. Gunakan forum ini untuk melihat apakah pertanyaan Anda sudah pernah ditanyakan dan dijawab sebelumnya.

---

### 5. Pemberitahuan
1. Klik tab **Pemberitahuan**.
2. Ringkasan status tiket Anda akan ditampilkan di sini.
3. Jika ada jawaban baru dari admin, akan terlihat di bagian ini.

---

### 6. Logout
- Klik tombol **Logout** di bagian atas untuk keluar dari aplikasi.
- Sesi login tersimpan otomatis selama browser tidak ditutup atau cache tidak dihapus.

---

## 🛠️ Panduan Admin

### 1. Login sebagai Admin
1. Masukkan email yang terdaftar sebagai **ADMIN**.
2. Setelah login, tombol **Tampilan Admin** akan muncul di bagian atas.
3. Klik **Tampilan Admin** untuk membuka panel kelola tiket.

---

### 2. Kelola Tiket

#### Ringkasan (Summary)
Di bagian atas panel admin, tersedia **3 kartu ringkasan**:
- **Total tiket** — jumlah seluruh tiket yang masuk
- **Baru masuk** — tiket yang belum diproses
- **Sudah dibalas / Selesai** — tiket yang sudah ditangani

#### Filter dan Pencarian
- Gunakan kolom **Cari tiket** untuk mencari berdasarkan nama, email, pertanyaan, atau topik.
- Gunakan **Filter Status** untuk menyaring tiket berdasarkan status.
- Gunakan **Filter Topik** untuk menyaring berdasarkan Fasih / Konsep Lapangan / Lainnya.
- Gunakan **Urutkan** untuk menampilkan tiket terbaru atau terlama terlebih dahulu.

#### Balas Satu Tiket
1. Temukan tiket yang ingin dijawab.
2. Isi kolom jawaban di bagian bawah kartu tiket.
3. Klik **Balas** untuk mengirim jawaban.
4. Klik **Tutup** jika tiket sudah selesai ditangani.

#### Balas Banyak Tiket Sekaligus (Bulk)
1. Centang tiket-tiket yang ingin dijawab.
2. Isi jawaban di masing-masing kartu yang sudah dicentang.
3. Klik **Kirim Jawaban Terpilih** untuk mengirim semua jawaban sekaligus.
4. Gunakan **Pilih Semua** atau **Batal Pilih** untuk kemudahan seleksi.

---

### 3. Forum Admin
1. Klik tab **Forum Admin**.
2. Tampil kumpulan pertanyaan yang sudah dikelompokkan otomatis berdasarkan tema.
3. Gunakan ini untuk memantau **pola pertanyaan** yang sering muncul dari mitra lapangan.

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
- `Tiket berhasil dikirim. Lampiran tersimpan.`
- `Jawaban tersimpan untuk tiket ini.`
- `Tiket ditandai selesai.`
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

- Login menggunakan **email saja** tanpa password — akses terbatas untuk email terdaftar di MasterPetugas atau Admin.
- Sesi login disimpan di `localStorage` browser.
- Data tiket tersimpan di **Google Sheets** yang hanya dapat diakses via Apps Script.
- Lampiran gambar disimpan di **Google Drive** dengan izin akses terbatas.

---

## 📞 Kontak & Dukungan

Jika mengalami kendala teknis, hubungi Tim IT BPS Kota Denpasar melalui jalur koordinasi resmi atau kirim tiket melalui topik **Lainnya** di aplikasi ini.

---

*Dikembangkan untuk keperluan internal BPS Kota Denpasar — Sensus Ekonomi 2026.*
