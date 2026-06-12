# Nama  : Satria Badrus Salam Al Muhibbin
# NIM   : 240605110201
# Kelas : Pemrograman Web Teori [B]

# aplikasi-blog-240605110201 #

## Pengembangan Aplikasi Blog (Tugas UAS)

Proyek ini merupakan pengembangan lebih lanjut dari Sistem Manajemen Konten (CMS) Blog yang telah dibangun pada Modul 10. Pada tahap UAS ini, aplikasi dilengkapi dengan **Halaman Publik (Pengunjung)** berbasis framework **Laravel** yang terintegrasi dengan database `db_blog` dari CMS.

Halaman publik ini dapat diakses oleh siapa saja secara terbuka tanpa perlu melakukan proses login, dengan tampilan tema yang bersih, sederhana, konsisten, dan elegan menggunakan Bootstrap/CSS.

## Fitur Utama Halaman Pengunjung

### 1. Halaman Utama (Home Page)
* **Artikel Terbaru**: Menampilkan 5 artikel paling update yang dikelola dari CMS.
* **Widget Kategori**: Bilah samping (sidebar) yang menampilkan daftar kategori artikel.
* **Filter Kategori**: Pengunjung dapat menyaring dan menampilkan artikel berdasarkan kategori tertentu yang diklik pada widget.

### 2. Halaman Detail Artikel (Detail Page)
* **Konten Lengkap**: Menampilkan isi artikel secara utuh beserta informasi penulis dan tanggal rilis.
* **Artikel Terkait**: Bilah samping (sidebar) yang merekomendasikan 5 artikel lain dari kategori yang sama untuk meningkatkan keterbacaan.

## Teknologi yang Digunakan
* **Framework Backend**: Laravel
* **Database**: MySQL (`db_blog`)
* **Frontend**: Blade Templating, HTML5, CSS3, Bootstrap

## Fitur CMS Eksisting (Modul 10)
Sebelumnya, sistem ini telah memiliki fitur internal khusus penulis (wajib login) yang meliputi:
* Manajemen Artikel (CRUD)
* Manajemen Penulis/User (CRUD)
* Manajemen Kategori Artikel (CRUD)
