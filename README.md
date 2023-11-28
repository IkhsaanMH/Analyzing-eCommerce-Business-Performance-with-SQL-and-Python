# Analyzing-eCommerce-Business-Performance
Dalam sebuah perusahaan, pengukuran kinerja bisnis sangat penting untuk melacak, memonitor, dan mengevaluasi keberhasilan atau kegagalan dari setiap proses bisnis.
Oleh karena itu, makalah ini akan menganalisis kinerja bisnis dari sebuah perusahaan e-commerce dengan memperhitungkan beberapa metrik bisnis,
yaitu pertumbuhan aktivitas pelanggan, kualitas produk, dan metode pembayaran.

# Prerequisites

1. Dataset download [`here`](https://drive.google.com/file/d/1X8V5mEAvJUqF5yXvv394_GG8E66UMEvJ/view?usp=sharing).

## Tentang Dataset
Dataset ini dimiliki oleh salah satu perusahaan e-commerce besar di Amerika Utara. Perusahaan ini bertujuan untuk menghubungkan mikroperusahaan dengan pelanggan mereka.
Dataset ini berisi lebih dari 99440 catatan transaksi dari tahun 2016 hingga 2018.

## Preparation Process
1. Pada tahap persiapan data ini, terdapat beberapa langkah.
2. Untuk memulai, instal [`postgresql`](https://www.postgresql.org/).
3. Setelah beberapa konfigurasi, buka pgAdmin untuk mengakses alat-alatnya.
4. Buat database baru dengan mengklik kanan pada Databases > Create > Database… kemudian masukkan nama database baru. Saya menggunakan 'Project_Ecommerce' sebagai nama database.
5. Buat tabel untuk setiap dataset menggunakan sintaks CREATE TABLE, dan tentukan tipe data yang paling sesuai di sini atau Anda mungkin akan mendapatkan kesalahan pada langkah selanjutnya.
6. Impor setiap dataset dengan mengklik kanan pada nama tabel (Anda dapat menemukan tabel tersebut di Schemas) dan pilih Import/Export Data. Ada 8 dataset dalam proyek ini. Catatan: Anda juga dapat menggunakan COPY untuk mengimpor dataset jika diperlukan.
7. Gunakan ALTER TABLE untuk menambahkan CONSTRAINT baik itu kunci utama atau kunci asing. Catatan: mengatur kunci utama atau kunci asing juga dapat dilakukan pada langkah membuat tabel.
8. Buat ERD dengan mengklik kanan pada 'Project_Ecommerce' dan pilih Generate ERD.

