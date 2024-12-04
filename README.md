# Transjakarta---Public-Transportation-Transaction-Analysis

## Latar Belakang
Transjakarta merupakan sistem transportasi Bus Rapid Transit (BRT) pertama di Asia Tenggara dan Asia Selatan, serta memiliki rute terpanjang di dunia (208 km). Sistem BRT ini didasarkan pada sistem TransMilenio di Bogotá, Kolombia, dan resmi beroperasi sejak 1 Februari 2004. Transjakarta menawarkan berbagai pilihan layanan transportasi, termasuk BRT, Mikrotrans, dan Royaltrans.

## Pernyataan Masalah
Transjakarta ingin mendapatkan wawasan mengenai perilaku penumpang pada bulan April 2023 berdasarkan data pada kartu pembayaran, waktu layanan, dan rute yang paling ramai berdasarkan jenis layanan. Pertanyaan yang harus dijawab adalah:

1. Bagaimana persebaran penumpang yang menggunakan Transjakarta berdasarkan data pada kartu pembayaran?
2. Bagaimana persebaran penumpang yang menggunakan Transjakarta berdasarkan waktu?
3. Bagaimana persebaran penumpang yang menggunakan Transjakarta berdasarkan rute?

## Data
Data yang digunakan terdiri dari 22 kolom, termasuk informasi transaksi, kartu pembayaran, dan rute. Data ini mencakup informasi seperti ID transaksi, jenis bank, nama koridor, waktu tap in dan tap out, serta jumlah yang dibayarkan.

## Analisis
Analisis dilakukan dalam beberapa tahap:
1. Data Cleaning: Mengatasi missing values, mengubah tipe data yang tidak sesuai, dan mengelompokkan data berdasarkan jenis layanan.
2. Analisis Persebaran Penumpang:
  - Berdasarkan data pada kartu pembayaran (umur, jenis kelamin, jenis bank).
  - Berdasarkan waktu (hari, tanggal, jam kerja).
  - Berdasarkan rute (10 rute paling banyak digunakan secara keseluruhan, berdasarkan jam kerja, dan berdasarkan jenis layanan).

## Rekomendasi
Berdasarkan hasil analisis, beberapa rekomendasi diberikan untuk mengoptimalkan pelayanan Transjakarta, termasuk optimalisasi rute dan jadwal, penambahan layanan ekspres, dan penambahan rute baru.

## File Output
- File Excel: TransjakartaCleanedVersion.xlsx
- File CSV: TransjakartaCleanedVersion.csv

## Dashboard
Untuk mengakses Dashboard, dapat menggunakan [Link](https://public.tableau.com/app/profile/daffa.dzaky.naufal/viz/TransjakartaPublicTransportationTransaction/Home?publish=yes).

## Instalasi
Untuk menjalankan analisis ini, pastikan Anda memiliki Python dan pustaka berikut terinstal:
- pandas
- numpy
- seaborn
- matplotlib

## Cara Menggunakan
1. Unduh file 'Transjakarta.csv' dan simpan di direktori yang sama dengan notebook ini.
2. Jalankan setiap sel di notebook untuk melakukan analisis.
3. Hasil analisis akan ditampilkan dalam bentuk grafik dan tabel.
