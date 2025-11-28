# Lab9Web
PemrogramanWebPertemuan11
### Aplikasi CRUD Sederhana Data Barang (PHP Native + MySQL)

<p align="center">
  <img src="https://img.shields.io/badge/PHP-8.0%2B-blue?style=for-the-badge&logo=php"/>
  <img src="https://img.shields.io/badge/MySQL-8.0-blue?style=for-the-badge&logo=mysql"/>
  <img src="https://img.shields.io/badge/XAMPP-v8.2-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Selesai-brightgreen?style=for-the-badge"/>
</p>

**Nama**           : Dhani Naufal Habibie (312410300)
**Kelas**          : TI.24.A4
**Mata Kuliah**    : Pemrograman Web  
**Dosen Pengampu** : Agung Nugroho, S.Kom., M.Kom.  
**Email Dosen**    : agung@pelitabangsa.ac.id  
**Universitas**    : Universitas Pelita Bangsa  
**Repository**     : Lab8Web (Praktikum 8)

---

## Tujuan Praktikum
1. Mahasiswa mampu memahami konsep dasar Modularisasi Program.
2. Mahasiswa mampu memahami konsep dasar Fungsi pada PHP.
3. Mahasiswa mampu membuat program Modular sederhana menggunakan PHP.
4. Mahasiswa mampu mengimplementasikan penggunaan fungsi pada PHP

## Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama lab9_php_modular pada docroot webserver (htdocs)
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

## Studi Kasus
Aplikasi manajemen **Data Barang** (tabel `data_barang`) dengan fitur:
- Create (Tambah barang + upload gambar)
- Read (Tampilkan semua data)
- Update (Ubah data barang)
- Delete (Hapus barang)

# Langkah-langkah Praktikum
### 1.Buat file baru dengan nama header.php 
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
    <link rel="stylesheet" href="style.css?v=<?php echo time(); ?>">
</head>

<body>
<div class="container">

<header class="app-header">
    <h1>PHP Modular</h1>
</header>

<div class="nav-table-container">
    <table class="nav-table">
        <tr>
            <td><a href="index.php?page=home">Beranda </a></td>
            <td><a href="index.php?page=about">Tentang</a></td>
            <td><a href="index.php?page=user/list">Data Barang</a></td>
            <td><a href="index.php?page=kontak">Kontak</a></td>
        </tr>
    </table>
</div>
<div class="content">
```

### 2. Buat file baru dengan nama footer.php
```
</div>

<footer>
    <p>&copy; 2025 - Universitas Pelita Bangsa | Mamskie</p>
</footer>

</div>
</body>
</html>
```

### 3. Buat file baru dengan nama home.php
```
<h2>Halaman Home</h2>
<p>Ini adalah halaman utama modular PHP.</p>
```

### 4. Buat file baru dengan nama about.php
```
<h2>Halaman About</h2>
<p>Aplikasi ini dibuat untuk belajar - Pemrograman Mobile Web 1.</p>
```

# Pertanyaan dan Tugas
Implementasikan konsep modularisasi pada kode program praktikum 8 tentang database, 
sehingga setiap halamannya memiliki template tampilan yang sama. Dan terapkan 
penggunaan Routing agar project menjadi lebih modular.
Gunakan struktur direktory seperti berikut:

1. Routing menggunakan url: index.php?page=user/list
2. Opsional: Gunakan htaccess agar url lebih SEO Friendly.
3. Contoh URL: (base-domain)/user/list

# Laporan Praktikum 
1. Buatlah repository baru dengan nama Lab9Web.
2. Kerjakan semua latihan yang diberikan sesuai urutannya.
3. Screenshot setiap perubahannya.
4. Buatlah file README.md dan tuliskan penjelasan dari setiap langkah praktikum 
beserta screenshotnya.
5. Commit hasilnya pada repository masing-masing.
6. Kirim URL repository pada e-learning ecampus

<p align="center">
  <img src="https://img.shields.io/badge/PHP-8.0%2B-blue?style=for-the-badge&logo=php"/>
  <img src="https://img.shields.io/badge/MySQL-8.0-blue?style=for-the-badge&logo=mysql"/>
  <img src="https://img.shields.io/badge/XAMPP-v8.2-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Selesai-brightgreen?style=for-the-badge"/>
</p>
