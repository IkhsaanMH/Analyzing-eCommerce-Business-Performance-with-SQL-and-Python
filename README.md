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

## Analysis

### Customer Activity

**1. Rata-rata Pengguna Aktif Bulanan:**

Pada tahun 2016, platform ini memiliki rata-rata sekitar 27 pengguna aktif per bulan. Hal ini menunjukkan bahwa platform ini memiliki tingkat keterlibatan pengguna yang relatif rendah selama tahun tersebut.
Pada tahun 2017, terjadi peningkatan signifikan dalam rata-rata pengguna aktif bulanan, mencapai sekitar 3.643 pengguna per bulan. Ini menunjukkan pertumbuhan substansial dalam keterlibatan pengguna dan menunjukkan bahwa platform ini menjadi lebih populer.
Pada tahun 2018, tren peningkatan keterlibatan pengguna terus berlanjut, dengan rata-rata sekitar 4.396 pengguna aktif per bulan. Peningkatan aktivitas pengguna ini dapat disebabkan oleh berbagai faktor, seperti upaya pemasaran, perbaikan produk, atau pertumbuhan basis pelanggan.

**2. Jumlah Pelanggan Baru:** 

Pada tahun 2016, platform ini berhasil mendapatkan 326 pelanggan baru. Ini merupakan jumlah yang relatif modest dan mungkin menunjukkan awal yang lambat bagi bisnis selama tahun tersebut.
Pada tahun 2017, terjadi lonjakan signifikan dalam akuisisi pelanggan baru, dengan 43.708 pelanggan baru bergabung dengan platform. Ini menunjukkan strategi pemasaran yang berhasil atau peningkatan kesadaran merek.
Tren pertumbuhan berlanjut pada tahun 2018, dengan penambahan 52.062 pelanggan baru. Ini menunjukkan pertumbuhan berkelanjutan dan aliran masuk pengguna baru yang sehat.

**3. Jumlah Pelanggan dengan Pemesanan Berulang:**

Pada tahun 2016, hanya 3 pelanggan yang melakukan pemesanan berulang. Ini adalah angka yang sangat rendah dan mungkin menunjukkan perlunya meningkatkan strategi retensi pelanggan.
Pada tahun 2017, jumlah pelanggan dengan pemesanan berulang meningkat secara signifikan menjadi 1.256. Ini adalah tanda positif karena menunjukkan bahwa sebagian besar basis pelanggan kembali untuk pembelian tambahan.
Pada tahun 2018, platform berhasil mempertahankan jumlah pelanggan yang melakukan pemesanan berulang dengan baik, yaitu sebanyak 1.157 pelanggan. Ini menunjukkan bahwa upaya retensi pelanggan berhasil.

**4. Rata-rata Jumlah Pesanan per Pelanggan:**

Pada tahun 2016, rata-rata setiap pelanggan melakukan sedikit lebih dari satu pesanan (sekitar 1,009). Ini menunjukkan bahwa pelanggan melakukan pembelian terbatas secara rata-rata.
Pada tahun 2017, rata-rata jumlah pesanan per pelanggan sedikit meningkat menjadi 1,031. Meskipun peningkatan ini tidak signifikan, hal ini menunjukkan bahwa pelanggan sedikit lebih terlibat dan melakukan pembelian berulang.
Pada tahun 2018, rata-rata jumlah pesanan per pelanggan tetap relatif stabil di angka 1,023. Hal ini menunjukkan bahwa pelanggan terus melakukan pembelian berulang dengan tingkat yang sama.

**Insight Keseluruhan:**
Platform ini mengalami pertumbuhan substansial baik dalam hal pengguna aktif maupun akuisisi pelanggan baru dari tahun 2016 hingga 2018.
Peningkatan jumlah pelanggan yang melakukan pemesanan berulang menunjukkan adanya perbaikan dalam strategi retensi pelanggan.
Meskipun rata-rata jumlah pesanan per pelanggan tetap relatif stabil, penting untuk fokus pada peningkatan keterlibatan pelanggan dan mendorong pembelian yang lebih sering.

Untuk melanjutkan tren pertumbuhan, bisnis sebaiknya mempertimbangkan strategi untuk mengubah lebih banyak pengguna aktif menjadi pelanggan dan mendorong pemesanan berulang. Penting untuk secara teratur memantau metrik-metrik ini dan menyesuaikan strategi secara sesuai untuk menjaga dan meningkatkan aktivitas pelanggan.
