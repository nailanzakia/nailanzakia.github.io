Laporan Praktikum: Jekyll dan Ruby
1. Judul Praktikum
Membangun Website Statis dengan Jekyll dan Ruby

2. Tujuan Praktikum
Memahami cara kerja Jekyll sebagai generator situs statis berbasis Ruby.

Mempelajari dasar-dasar bahasa pemrograman Ruby.

Membangun situs web statis sederhana menggunakan Jekyll dan Ruby.

3. Alat dan Bahan
Editor Teks: Visual Studio Code, Sublime Text, atau editor teks lainnya.

Peramban Web: Google Chrome, Mozilla Firefox, atau peramban web lainnya.

Terminal atau Command Prompt: Untuk menjalankan perintah instalasi dan server lokal.

4. Langkah-Langkah Praktikum
a. Persiapan Lingkungan Pengembangan
Instalasi Ruby: Unduh dan instal Ruby dari situs resmi ruby-lang.org. Pastikan versi Ruby yang diinstal adalah 2.7.0 atau lebih tinggi.

Instalasi Jekyll dan Bundler:

bash
Salin
Edit
gem install jekyll bundler
b. Membuat Situs Web Baru dengan Jekyll
Membuat Proyek Baru:

bash
Salin
Edit
jekyll new mysite
cd mysite
Menjalankan Server Lokal:

bash
Salin
Edit
bundle exec jekyll serve

Buka peramban dan akses http://localhost:4000 untuk melihat situs yang telah dibuat.

c. Menambahkan Konten dan Menyesuaikan Tampilan
Menambahkan Halaman Baru: Buat file baru dengan ekstensi .md atau .html di direktori root proyek untuk menambahkan halaman baru.

Menyesuaikan Layout: Edit file di direktori _layouts untuk menyesuaikan struktur halaman.

Menambahkan Gaya CSS: Tambahkan file CSS di direktori assets/css dan link-kan ke dalam file layout.

5. Hasil Praktikum
Pembuatan Situs Web Statis: Berhasil membuat situs web statis sederhana menggunakan Jekyll.

Penambahan Konten: Berhasil menambahkan halaman baru dan menyesuaikan tampilan situs.

Pemahaman Ruby: Memahami dasar-dasar penggunaan Ruby dalam konteks Jekyll.
Kinsta®

6. Kesimpulan
Jekyll: Merupakan generator situs statis yang memanfaatkan Ruby, memungkinkan pembuatan situs web tanpa memerlukan database.

Ruby: Bahasa pemrograman yang digunakan oleh Jekyll, dikenal dengan sintaksis yang sederhana dan mudah dipahami.

Keuntungan: Menggunakan Jekyll dan Ruby memungkinkan pembuatan situs web yang cepat, aman, dan mudah dikelola.

/* style.css */
body {
    font-family: "Helvetica Neue", sans-serif;
    margin: 0;
    padding: 0;
    background-color: #fff;
}

h1 {
    color: #3498db;
    text-align: center;
}

a {
    color: #e74c3c;
    text-decoration: none;
}

![htmllinkdanlists](/assets/images/jekyll.png)
![htmllinkdanlists](/assets/images/ruby.png)