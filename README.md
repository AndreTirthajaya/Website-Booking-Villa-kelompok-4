# Laporan Proyek: Sistem Booking Villa

## 1. Pendahuluan
Proyek ini adalah sebuah aplikasi web sederhana untuk memfasilitasi pemesanan vila secara online. Pengguna dapat:

- Melihat daftar vila yang tersedia.
- Melihat detail masing-masing vila.
- Melakukan pemesanan.

Aplikasi ini dikembangkan menggunakan teknologi dasar web seperti:

- *HTML* untuk struktur,
- *CSS* untuk gaya,
- *JavaScript* untuk fungsionalitas interaktif.

---

## 2. Daftar Anggota

| No | Nama                                 | NIM         | Peran                | Tugas                                 |
|----|--------------------------------------|-------------|----------------------|----------------------------------------|
| 1  | Andre Kurniawan Tirthajaya           | 240010067   | HTML Developer       | Membuat struktur halaman               |
| 2  | I Wayan Anga Wira Pratama            | 240010070   | CSS Designer         | Mendesain tampilan website menggunakan CSS |
| 3  | I Nyoman Surya Adi                   | 240010055   | JavaScript Developer | Menambahkan fitur interaktif menggunakan Vanilla JS |
| 4  | I Nyoman Harry Adi Suputra           | 240010059   | Documentation Manager| Menulis README.md yang menjelaskan proyek |

---

## 3. Fitur-fitur Utama

- *Tampilan Daftar Vila*  
  Menampilkan daftar vila yang tersedia dengan informasi seperti nama, lokasi, dan harga per malam.

- *Detail Vila*  
  Klik vila untuk melihat informasi lengkap (deskripsi, fasilitas, galeri gambar).

- *Formulir Pemesanan*  
  Pengguna dapat memasukkan tanggal check-in, check-out, jumlah tamu, dan info kontak.

---

## 4. Teknologi yang Digunakan

- *HTML*: Struktur dasar halaman web.
- *CSS*: Styling dan tata letak, termasuk tampilan yang responsif.
- *JavaScript*: Menambahkan interaktivitas dan fitur dinamis.

---

## 5. Struktur File Proyek

/nama_project
│── index.html # Halaman utama website
│── README.md # Dokumentasi project
│
├── /css
│ ├── styles.css # File utama untuk styling
│ ├── bootstrap.min.css # (Opsional) Bootstrap jika digunakan
│
├── /js
│ ├── script.js # File utama JavaScript
│ ├── jquery.min.js # jQuery (opsional)
│
└── /media
├── logo.png # Contoh logo
├── banner.jpg # Contoh banner

### Penjelasan Struktur:

- *index.html*: Halaman utama, berisi navigasi ke seluruh bagian.
- *README.md*: Laporan dan dokumentasi proyek.
- */css*: Folder untuk file styling.
- */js*: Folder untuk skrip JavaScript.
- */media*: Gambar dan aset visual (ikon, logo, banner).

---

## 6. Cara Menjalankan Website

### A. Halaman Utama (index.html)
- Slideshow gambar villa (otomatis tiap 5 detik & kontrol manual).
- Tombol navigasi ke halaman lain.

### B. Daftar Villa (daftar-villa.html)
- Fitur filter berdasarkan:
  - *Fasilitas*: Kolam renang, pemandangan danau.
  - *Harga*: Di bawah / atas Rp 3 juta.
- Klik card vila → muncul *modal popup* detail.
- Tombol navigasi ke halaman lain.

### C. Promo (promo.html)
- Tombol "Lihat Promo" untuk melihat detail diskon dan kode.
- Navigasi ke halaman lainnya.

### D. Galeri (galeri.html)
- Galeri gambar (outdoor, indoor, fasilitas).
- Klik gambar untuk tampilan penuh (popup).
- Navigasi ke halaman lainnya.

### E. Reservasi / Kontak (kontak.html)
- Formulir:
  - Nama
  - Email valid
  - Tanggal menginap
  - Pilih fasilitas
  - Pesan
- Submit → muncul *alert konfirmasi*.
- Peta lokasi villa.
- *Tooltip Lokasi*: Arahkan kursor ke peta → muncul alamat villa.

---

## 7. Tautan GitHub Pages

🔗 [Website Booking Villa Kelompok 4](https://andretirthajaya.github.io/Website-Booking-Villa-kelompok-4/)

---

## 8. Kesimpulan
Proyek ini berhasil membuat sebuah halaman pemesanan vila secara *online* yang *sederhana, **interaktif*, dan memudahkan pengguna dalam menjelajah, memilih, serta memesan vila secara digital.

---



