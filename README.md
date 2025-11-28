# Data Overview
### 📊 Berikut Preview Singkat dari Data Supermarket.
Banyaknya pelanggan yang berkunjung ke Supermarket adalah 2240 pelanggan (tidak ada data yang terduplikat). Detail dijelaskan kolom-kolom yang berjumlah 29 kolom (baris=2240, kolom=29).

---

### 👤 Data Pribadi Pelanggan:
- 🆔**ID**: Nomor Identitas pelanggan di Supermarket (sebanyak 2240 data)
- 🎂**Year_Birth**: Tahun lahir pelanggan (range dari tahun 1893 sampai dengan tahun 1996)
- 🎓**Education**: Tingkat pendidikan pelanggan dari (2n Cycle (Diploma), Graduation, PhD, Master, Basic (SD-SMA))
- 💍**Marital_Status**: Status pernikahan pelanggan (Single, Together, Married, Divorced, Widow, Alone, Absurd, YOLO)
- 💰**Income**: Pendapatan pelanggan per tahun (terdapat 24 data kosong (sebanyak 1%) dari
2240; range pendapatan: $ 1730 s.d $ 666666 dengan rata-rata: 52247.251354). Data kosong berdasarkan Education:
  - 2n Cycle       3 orang
  - Graduation    11 orang
  - Master         5 orang
  - PhD            5 orang
- 🧒**Kidhome**: Jumlah anak kecil di rumah pelanggan (dari 0 s.d 2 anak)
- 🧑‍🦱**Teenhome**: Jumlah remaja di rumah pelanggan (dari 0 s.d 2 anak)

---

### 🗓️ Lamanya Pelanggan sudah menjadi pelanggan di Supermarket
- 🗓️**Dt_Customer**: Tanggal pelanggan mulai terdaftar di perusahaan
- ⏳**Recency**: Jumlah hari sejak terakhir kali pelanggan melakukan pembelian (0 s.d 99 hari)

---
  
### 🛒Total Pembelian dari masing-masing produk yang dijual di Supermarket (Selama 2 tahun terakhir)
 - 🍷**MntWines**: Total pengeluaran untuk wine  (range: $ 0 s.d $ 1493)
 - 🍎**MntFruits**: Total pengeluaran untuk buah (range: $ 0 s.d $ 199)
 - 🍖**MntMeatProducts**: Total pengeluaran untuk daging (range: $ 0 s.d $ 1725)
 - 🐟**MntFishProducts**: Total pengeluaran untuk ikan (range: $ 0 s.d $ 259)
 - 🍬**MntSweetProducts**: Total pengeluaran untuk makanan manis (range: $ 0 s.d $ 263)
 - 💎**MntGoldProds**: Total pengeluaran untuk produk emas dalam (range: $ 0 s.d $ 362)

---

### 🧠 Perilaku Pelanggan 
- 🏷️**NumDealsPurchases**: Jumlah pembelian yang dilakukan dengan diskon (range 0 s.d 15 kali)
- 📢**AcceptedCmp1**: 1. pelanggan menerima penawaran pada promosi pertama, 0. tidak
- 📢**AcceptedCmp2**: 1. pelanggan menerima penawaran pada promosi kedua, 0. tidak
- 📢**AcceptedCmp3**: 1. pelanggan menerima penawaran pada promosi ketiga, 0. tidak
- 📢**AcceptedCmp4**: 1. pelanggan menerima penawaran pada promosi keempat, 0. tidak
- 📢**AcceptedCmp5**: 1. pelanggan menerima penawaran pada promosi kelima, 0. tidak
- 📢**Response**: 1. pelanggan menerima penawaran pada promosi terakhir, 0. tidak
- 🌐**NumWebPurchases**: Jumlah pembelian melalui website perusahaan (range 0 s.d 27 kali)
- 📚**NumCatalogPurchases**: Jumlah pembelian melalui katalog (range 0 s.d 28 kali)
- 🛍️**NumStorePurchases**: Jumlah pembelian di toko (range 0 s.d 13 kali)
- 👀**NumWebVisitsMonth**: Jumlah kunjungan ke website perusahaan dalam sebulan terakhir (range 0 s.d 20 kali)
- 😡**Complain**: 1. pelanggan pernah mengajukan keluhan dalam 2 tahun terakhir, 0. tidak

---

### 📈 Lainnya
- 🔵**Z_CostContact**: Biaya pengiriman penawaran promosi ke pelanggan
- 🟢**Z_Revenue**: Total Pendapatan Supermarket
- **angka yang ditampilkan disini adalah angka standar score dari Supermarket karena merupakan data confidential**

---

## Data Ini akan digunakan untuk menjawab pertanyaan sebagai berikut.
- 🔍 Karakteristik Pelanggan yang berbelanja di Supermarket, termasuk latar belakang dan segmentasi pelanggan yang perlu mendapatkan perhatian khusus.
- ❗ pemilik ingin tahu apakah pelanggan yang pernah komplain merupakan pelanggan loyal yang sering berbelanja.
- 🚀 Evaluasi efektivitas campaign yang telah dijalankan dalam meningkatkan penjualan..
- 📦 Produk apa saja yang paling banyak dibeli oleh pelanggan.
- 🎟️ Evaluasi efektivitas strategi diskon yang selama ini diterapkan.
- 🧺 Marketplace mana yang paling diminati dan paling banyak digunakan oleh pelanggan.
- 🌐 Seberapa menarik website supermarket dalam mendorong pembelian, melalui performa conversion rate.

---

📚 *Dibuat sebagai Capstone Project Modul II - Data Analysis — oleh Vivi Novela.*
