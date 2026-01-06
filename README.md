# Lab9web
Nama: Den Fahmi Satria <p>
Nim: 312410523 <p>
Kelas: TI.24.A5 <p>

lab9_php_modular/
│
├── config/
│ └── database.php
│
├── layout/
│ ├── header.php
│ └── footer.php
│
├── pages/
│ └── barang/
│ ├── list.php
│ ├── tambah.php
│ ├── ubah.php
│ └── hapus.php
│
├── index.php
└── style.css
---

## Langkah-langkah Praktikum

### 1. Persiapan Lingkungan
Menjalankan Apache dan MySQL melalui XAMPP sebagai web server dan database server.

📷 *Screenshot XAMPP Control Panel*

---

### 2. Membuat Database dan Tabel
Database `latihan1` digunakan sebagai penyimpanan data barang yang akan dikelola menggunakan aplikasi CRUD.

📷 *Screenshot pembuatan database dan tabel*

---

### 3. Membuat Konfigurasi Database
File `database.php` digunakan untuk mengatur koneksi antara aplikasi PHP dan database MySQL.

📷 *Screenshot file database.php*

---

### 4. Membuat Template Tampilan (Modularisasi)
Template tampilan dibuat menggunakan:
- `header.php` untuk bagian atas halaman
- `footer.php` untuk bagian bawah halaman  

Dengan modularisasi ini, setiap halaman memiliki tampilan yang sama dan konsisten.

📷 *Screenshot file header.php dan footer.php*

---

### 5. Implementasi Routing
Routing dilakukan melalui file `index.php` dengan parameter URL `page`, sehingga halaman dapat diakses menggunakan format:


📷 *Screenshot file index.php dan contoh URL routing*

---

### 6. Menampilkan Data (Read)
File `list.php` digunakan untuk menampilkan seluruh data barang dari database ke dalam tabel HTML.

📷 *Screenshot halaman data barang*

---

### 7. Menambah Data (Create)
File `tambah.php` digunakan untuk menambahkan data barang baru ke dalam database melalui form input.

📷 *Screenshot halaman tambah data*

---

### 8. Mengubah Data (Update)
File `ubah.php` digunakan untuk mengubah data barang yang sudah tersimpan di database.

📷 *Screenshot halaman ubah data*

---

### 9. Menghapus Data (Delete)
File `hapus.php` digunakan untuk menghapus data barang berdasarkan ID yang dipilih.

📷 *Screenshot proses hapus data*

---

## Hasil Praktikum
Aplikasi CRUD berbasis PHP dan MySQL berhasil dibuat dengan konsep:
- Modularisasi template
- Routing berbasis URL
- Integrasi CRUD dengan database

Semua fungsi CRUD (Create, Read, Update, Delete) berjalan dengan baik.

---

## Kesimpulan
Dengan menerapkan konsep modularisasi dan routing, struktur program menjadi lebih terorganisir, mudah dibaca, dan mudah dikembangkan.  
Praktikum ini menunjukkan bahwa pemisahan kode dan penggunaan routing sangat membantu dalam pengembangan aplikasi web berbasis PHP.

---

## Repository
Repository ini dibuat untuk memenuhi tugas **Praktikum 9 – Pemrograman Web**.
