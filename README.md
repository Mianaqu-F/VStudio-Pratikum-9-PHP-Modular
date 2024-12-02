# Praktikum 9: PHP Modular

## Deskripsi
Praktikum ini bertujuan untuk memahami konsep **Modularisasi Program** menggunakan PHP. Dalam modularisasi, kode program dipecah menjadi bagian-bagian kecil (modul) untuk meningkatkan keterbacaan dan pengelolaan kode. 

## Tujuan
1. Memahami konsep dasar modularisasi program.
2. Memahami konsep fungsi pada PHP.
3. Membuat program modular sederhana menggunakan PHP.
4. Mengimplementasikan penggunaan fungsi pada PHP.

## Langkah-Langkah Praktikum
### 1. **Persiapan**
- Siapkan folder baru dengan nama `lab9_php_modular` di direktori `htdocs`.
- Pastikan webserver (XAMPP) aktif.

### 2. **Membuat Header dan Footer**
- **File `header.php`**: Berisi elemen HTML untuk header dan navigasi.
  ```php
  <!DOCTYPE html>
  <html lang="en">
  <head>
      <meta charset="UTF-8">
      <title>Contoh Modularisasi</title>
      <link href="style.css" rel="stylesheet" type="text/stylesheet" media="screen" />
  </head>
  <body>
      <div class="container">
          <header>
              <h1>Modularisasi Menggunakan Require</h1>
          </header>
          <nav>
              <a href="home.php">Home</a>
              <a href="about.php">Tentang</a>
              <a href="kontak.php">Kontak</a>
          </nav>
- File footer.php: Berisi elemen HTML untuk footer.
  ```php
  <footer>
    <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p></footer>
    </div>
  </body>
  </html>
  ```
### 3. Membuat Halaman Konten
- File home.php: Menampilkan halaman utama.
  ```php
  <?php require('header.php'); ?>
  <div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
  </div>
  <?php require('footer.php'); ?>
  ```
- File about.php: Menampilkan halaman tentang.
  ```php
  <?php require('header.php'); ?>
  <div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
  </div>
  <?php require('footer.php'); ?>
  ```
### 4. Implementasi Modularisasi di Praktikum 8
Terapkan konsep modularisasi dengan menggabungkan kode dari Praktikum 8 ke dalam template header-footer yang sudah dibuat.

### 5. Cara Menjalankan
- Salin folder lab9_php_modular ke direktori htdocs.
- Akses URL: http://localhost/lab9_php_modular/.

---
[Instagram](https://www.instagram.com/mianaqu/)
