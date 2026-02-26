# Business-Decision-Research

## 1. Business Understanding
DQLab Sport Center adalah toko retail perlengkapan olahraga (Jaket, Baju, Tas, Sepatu) yang beroperasi sejak 2013.
Permasalahan utama bisnis di awal 2019 adalah menurunnya pelanggan yang melakukan pembelian ulang (repeat order).

🎯 Objective 

Melakukan analisis churn untuk:
- Mengidentifikasi pelanggan yang berhenti bertransaksi
- Memahami karakteristik pelanggan churn
- Membangun model prediktif churn
- Memberikan rekomendasi strategi penurunan churn

📌 Definisi Churn 

Customer dikategorikan churn apabila tidak melakukan transaksi selama 6 bulan terakhir dari tanggal transaksi maksimum di dataset.

## 2. Data Understanding
Dataset: data_retail.csv
Jumlah data: 100.000 baris
Periode: 2013 – 2019

Feature Description
| Kolom                      | Deskripsi                  |
| -------------------------- | -------------------------- |
| Customer_ID                | ID unik pelanggan          |
| Product                    | Kategori produk            |
| First_Transaction          | Tanggal transaksi pertama  |
| Last_Transaction           | Tanggal transaksi terakhir |
| Average_Transaction_Amount | Rata-rata nilai transaksi  |
| Count_Transaction          | Total transaksi pelanggan  |
