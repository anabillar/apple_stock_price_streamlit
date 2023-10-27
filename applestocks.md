# Laporan Projek Machine Learning
### Nama: Asyfa Nabilla Rahmi
### NIM: 211351033
### Kelas: Pagi A

# Domain Projek
Apple Stock Prices (AAPL) dari tahun 2015-2020 di USA adalah data historis yang mencatat pergerakan harga saham di perusahaan Apple Inc.
Data seperti ini sangat berguna untuk analisis keuangan, perdagangan saham, dan pemodelan keuangan.

## Business Understanding
Data Apple Stock Price berguna di dalam dunia keuangan dan investasi, banyak analis dan investor menggunakannya untuk mengambil keputusan berdasarkan informasi historis tentang perusahaan dan pasar.

### Problem Statement
- Data harga saham Apple sering kali tersedia dalam berbagai tingkat interval waktu, seperti harian (daily), mingguan (weekly), bulanan (monthly), dan intraday, yang memungkinkan analis untuk memeriksa perubahan harga saham di tingkat yang berbeda.
- Data ini mencakup informasi harga saham, termasuk harga pembukaan (open), harga penutupan (close), harga tertinggi (high), harga terendah (low), volume perdagangan, dan harga penutupan yang disesuaikan (adjusted close).

### Goals
- Mengidentifikasi harga saham Apple
- Investasi jangka panjang
- Data harga saham membantu dalam pemahaman pasar secara keseluruhan

    ## Solution Statement
    - Analis menggunakan data harga saham harian untuk memplot grafik harga saham Apple, menerapkan analisis teknikal, seperti moving averages, dan mengidentifikasi tren harga saham.
    - Investor mengumpulkan data harga saham bulanan Apple selama beberapa tahun terakhir dan menganalisis kinerja saham selama jangka waktu yang lama. Mereka juga menilai faktor-faktor fundamental, seperti pendapatan dan laba bersih. Dengan informasi ini, investor dapat membuat keputusan investasi jangka panjang yang lebih terarah.

## Data Understanding
Dataset Apple Stock Price (2015-2020) berisi tentang data harga saham Apple di USA. Dataset diambil dari kaggle dan bisa diakses melalui: https://www.kaggle.com/datasets/suyashlakhani/apple-stock-prices-20152020

### Variabel pada Apple Stock Price (2015-2020) dataset
- Symbol (object) = Apple stock
- Close (float(64)) = Harga penutupan
- High (float(64)) = Harga tertinggi
- Low (float(64)) = Harga terendah
- Open (float(64)) = Harga pembukaan
- Volume (int(64)) = Volume perdagangan
- AdjClose (float(64)) = Harga penutupan yang disesuaikan
- AdjHigh (float(64)) = Harga tertinggi yang disesuaikan
- AdjOpen (float(64)) = Harga pembukaan yang disesuaikan
- AdjVolume (int(64)) = Volume perdagangan yang disesuaikan
- DivCash (float(64)) = Cash dividend
- SplitFactor (float(64)) = Stock split

## Data Preparation
Data yang diambil didapatkan dari kaggle dengan judul Apple Stock Prices (2015-2020) dan link yang bisa diakses sama seperti di atas.