Laporan Proyek : Judul Sistem Boking Villa

1. Pendahuluan
Proyek ini adalah sebuah aplikasi web sederhana untuk memfasilitasi pemesanan vila secara online. Pengguna dapat melihat daftar vila yang tersedia, melihat detail masing-masing vila, dan melakukan pemesanan. Aplikasi ini dikembangkan menggunakan teknologi dasar web seperti HTML untuk struktur, CSS untuk gaya, dan JavaScript untuk fungsionalitas interaktif.

2. Daftar Anggota : 1. Andre Kurniawan Tirthajaya (240010067) HTML Developer  'Membuat struktur halaman'
   		    2. I Wayan Anga Wira Pratama (240010070) CSS Designer 'Mendesain tampilan website menggunakan CSS'
   		    3. I Nyoman Surya Adi (240010055) JavaScript Developer 'Menambahkan fitur interaktif menggunakan Vanilla JS'
   		    4. I Nyoman Harry Adi Suputra (240010059)Documentation Manager 'Menulis README.md yang menjelaskan project'


3.Fitur-fitur Utama
Tampilan Daftar Vila: Menampilkan daftar vila yang tersedia dengan informasi singkat seperti nama, lokasi, dan harga per malam.
Detail Vila: Pengguna dapat mengklik setiap vila untuk melihat informasi lebih detail, termasuk deskripsi lengkap, fasilitas, dan galeri gambar (jika diimplementasikan lebih lanjut).
Formulir Pemesanan: Menyediakan formulir bagi pengguna untuk memasukkan tanggal check-in, tanggal check-out, jumlah tamu, dan informasi kontak.

4. Teknologi yang Digunakan
HTML: Digunakan untuk struktur dasar halaman web, termasuk elemen-elemen untuk menampilkan daftar vila, detail, dan formulir.
CSS: Digunakan untuk styling dan tata letak aplikasi, membuat tampilan yang menarik dan responsif. Ini mencakup styling untuk kartu vila, formulir, navigasi, dan elemen UI lainnya.
JavaScript: Digunakan untuk menambahkan interaktivitas dan fungsionalitas dinamis.

5. Struktur File Proyek
	Berikut adalah struktur direktori yang direkomendasikan untuk proyek ini:
			
/nama_project
│── index.html             # Halaman utama website (wajib ada)
│── README.md              # Dokumentasi project di GitHub
│── /css                   # Folder untuk file CSS
│   ├── styles.css         # File utama untuk styling (jika menggunakan CSS murni)
│   ├── bootstrap.min.css  # (Opsional) Bootstrap jika digunakan
│── /js                    # Folder untuk file JavaScript
│   ├── script.js          # File utama untuk interaktivitas
│   ├── jquery.min.js      # jQuery (jika digunakan)
│── /media                 # Folder untuk gambar dan aset media
│   ├── logo.png           # Contoh logo
│   ├── banner.jpg         # Contoh banner

Penjelasan Struktur Folder & File:

-File index.html (Halaman Utama)
Halaman utama website yang berfungsi sebagai entry point utama.
Harus berisi tautan navigasi ke halaman lain.

-File README.md (Laporan dan Dokumentasi Project)
Wajib ada di GitHub untuk laporan dan dokumentasi project.
Sistematika laporan dijelaskan di bawah.

-Folder /css (Penyimpanan File CSS)
Berisi file CSS utama (styles.css) yang mengatur tampilan website jika menggunakan CSS murni.
Jika menggunakan Bootstrap, file Bootstrap bisa disertakan di folder ini.

-Folder /js (Penyimpanan File JavaScript)
Berisi file JS utama (script.js) yang menangani interaktivitas website.
File jquery.min.js dapat disertakan jika menggunakan jQuery.

-Folder /media (Penyimpanan Gambar & Aset Media)
Berisi gambar yang digunakan dalam project, seperti logo, ikon, banner dan gambar lainnya.
Aset media lainnya seperti audio dan video juga ditempatkan di folder ini.
File harus diberi nama yang deskriptif untuk memudahkan identifikasi.

6. Cara Menjalankan Website :
  
A.Halaman Utama
Di halaman beranda (index.html) memiliki slideshow dimana gambar villa akan berganti otomatis setiap 5 detik (bisa dikontrol manual). dan memiliki tomobol navigasi ke halaman lainnya 


B. daftar Villa
pada halaman Daftar Villa (daftar-villa.html). memiliki tombol filter untuk memilih villa berdasarkan:
Fasilitas (kolam renang, pemandangan danau).
Harga (di bawah/atas Rp 3 juta).

Klik card villa untuk melihat detail (modal popup akan muncul). 

dan memiliki tomobol navigasi ke halaman lainnya 

C. Promo
pada halaman Promo (promo.html).

memiliki tombol "Lihat Promo" pada card untuk melihat detail diskon dan kode promo.

dan memiliki tomobol navigasi ke halaman lainnya 

D. Galeri
halaman Galeri (galeri.html).

memiliki beberapa gambar outdoor/idoor/fasilitas villa 
gambar bisa di klik untuk membuka popup tampilan penuh.
dan memiliki tomobol navigasi ke halaman lainnya 

E. Reservasi/Kontak
halaman Kontak (kontak.html).

memiliki Isi formulir dengan:

Nama, email valid, tanggal menginap.

Pilih minimal 1 fasilitas.

Ketik pesan.

Submit formulir → Akan muncul alert konfirmasi.

memiliki peta untuk menunjukkan lokasi villa
Fitur Tambahan Tooltip Lokasi: Arahkan kursor ke peta di halaman kontak untuk melihat alamat villa.

7. Tautan Github Pages :  https://andretirthajaya.github.io/Website-Booking-Villa-kelompok-4/ 
   
8.Kesimpulan
Proyek ini berhasil membuat sebuah halaman pemesanan villa secara online yang sederhana dan interaktif.
