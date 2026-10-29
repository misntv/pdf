# 🗂️ LOKET PDF — MISNTV

**13 Alat PDF dalam Satu Aplikasi Web**

LOKET PDF adalah aplikasi web untuk mengelola dokumen PDF dalam satu tempat. Aplikasi ini menyediakan berbagai fitur untuk menggabungkan, memisahkan, membaca, mengonversi, mengamankan, dan mengekstrak konten PDF dengan antarmuka yang praktis dan responsif.

## ✨ Fitur Utama

### 📄 Susun dan Edit PDF
- **Gabung PDF** — Menggabungkan beberapa file PDF menjadi satu dokumen.
- **Pecah PDF** — Memisahkan halaman PDF sesuai rentang yang dipilih.
- **Ubah Info PDF** — Mengubah informasi metadata dokumen PDF.
- **Watermark** — Menambahkan watermark teks atau gambar, dengan pengaturan ukuran, warna, transparansi, rotasi, tata letak, dan halaman.

### 👁️ Baca dan Pratinjau
- **Baca PDF** — Membaca PDF dengan navigasi halaman, zoom, dan rotasi.
- **Thumbnail PDF** — Membuat gambar pratinjau halaman PDF dan mengemasnya menjadi ZIP.

### 🔄 Konversi dan Ekstraksi
- **PDF ke Word** — Mengubah teks PDF menjadi dokumen Word yang dapat diedit.
- **PDF ke HTML** — Mengubah PDF menjadi halaman HTML mandiri, dengan pilihan menyertakan gambar halaman.
- **PDF ke EXE** — Membuat berkas peluncur `.bat` untuk Windows, bukan aplikasi `.exe` native.
- **Ekstrak Teks & Gambar** — Mengekstrak teks dan gambar raster dari PDF.

### 🔐 Keamanan PDF
- **Proteksi PDF** — Menambahkan kata sandi dan pembatasan izin tertentu.
- **Buka Proteksi** — Memproses PDF yang kata sandinya diketahui pengguna.

### 🪄 Magic PDF
- Menangkap tampilan layar, jendela, atau tab melalui fitur berbagi layar pada browser.
- Mengambil snapshot secara manual atau otomatis.
- Menyusun hasil tangkapan menjadi PDF atau mencetaknya.

## 🚀 Cara Menggunakan

1. Unduh atau kloning repositori ini.
2. Buka berkas HTML utama menggunakan browser modern.
3. Pilih alat PDF yang ingin digunakan.
4. Masukkan dokumen dan atur opsi sesuai kebutuhan.
5. Jalankan proses, lalu simpan hasilnya.

Jika fitur tertentu tidak berjalan saat berkas dibuka langsung, jalankan server lokal dari folder proyek:

```bash
python3 -m http.server 8000
```

Kemudian buka `http://localhost:8000` di browser.

## 🔒 Privasi Pengguna

LOKET PDF dirancang agar pemrosesan dokumen berlangsung langsung di browser, tanpa mengunggah berkas PDF ke server aplikasi.

## ⚠️ Catatan Penting

- Hasil konversi PDF ke Word dapat berbeda dari tata letak dokumen asli.
- Fitur PDF ke EXE menghasilkan berkas `.bat`, bukan executable Windows `.exe` native.
- Fitur proteksi dan buka proteksi memproses ulang halaman PDF; hasilnya dapat berbeda dari struktur PDF asli.
- Ekstraksi gambar ditujukan untuk gambar raster. Objek vektor tidak selalu dapat diekstrak sebagai gambar utuh.
- Dokumen besar atau banyak halaman dapat membutuhkan waktu pemrosesan lebih lama.
- Beberapa fitur mungkin memerlukan koneksi internet untuk memuat komponen aplikasi.

## 💻 Persyaratan

- Browser modern.
- JavaScript aktif.
- Koneksi internet jika komponen yang diperlukan belum tersedia secara lokal.
- Ruang penyimpanan yang cukup untuk menyimpan dokumen hasil.

## 📁 Struktur Proyek

```text
loket-pdf/
├── index.html
├── README.md
└── LICENSE
```

> Sesuaikan nama `index.html` dengan nama berkas HTML utama di repositori Anda.

## 🤝 Ketentuan Penggunaan dan Amal Jariyah

Kode proyek ini boleh digunakan kembali, dipelajari, dimodifikasi, dan didistribusikan, dengan ketentuan:

1. **Wajib mencantumkan atribusi dan hak cipta MISNTV** pada salinan, turunan, distribusi, atau dokumentasi proyek.
2. **Jangan menghapus atau menyamarkan pemberitahuan hak cipta MISNTV** yang sudah ada.
3. Jika kode dimodifikasi, jelaskan bahwa perubahan tersebut dibuat oleh pihak yang memodifikasi dan bukan merupakan rilis resmi MISNTV.
4. Penggunaan kembali diharapkan membawa manfaat bagi sesama, dunia, dan akhirat sebagai ikhtiar amal jariyah. Semangat berbagi ini tidak menghapus kewajiban mencantumkan hak cipta dan atribusi MISNTV.
5. Ketentuan ini berlaku untuk kode proyek yang didistribusikan bersama berkas lisensi ini. Komponen pihak ketiga, jika ada, tetap mengikuti ketentuan lisensinya masing-masing.

Lihat berkas [`LICENSE`](LICENSE) untuk ketentuan lengkap.

## 🏢 Pengembang dan Hak Cipta

**MISNTV — Media Inspirasi Sahabat Nusantara Televisi**

`Copyright © 2026 MISNTV. Hak Cipta Dilindungi.`

## 📜 Lisensi

Proyek ini menggunakan **Lisensi Penggunaan Kembali dengan Atribusi MISNTV**. Kode dapat digunakan kembali sesuai ketentuan lisensi, tetapi atribusi dan pemberitahuan hak cipta MISNTV wajib dipertahankan.
