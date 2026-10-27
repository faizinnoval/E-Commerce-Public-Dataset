# Proyek Analisis Data E-Commerce

## Deskripsi Proyek

Proyek ini merupakan submission analisis data menggunakan dataset e-commerce. Analisis dilakukan untuk memahami tren pendapatan, kategori produk dengan kontribusi pendapatan tertinggi, serta segmentasi pelanggan berdasarkan RFM.

Dashboard interaktif dibuat menggunakan Streamlit untuk membantu menampilkan hasil analisis secara lebih mudah dan informatif.

## Pertanyaan Bisnis

1. Bagaimana tren total nilai pembayaran per bulan selama periode 2016–2018, serta kategori produk apa yang memberikan kontribusi pendapatan tertinggi?
2. Bagaimana segmentasi pelanggan berdasarkan Recency, Frequency, dan Monetary (RFM) selama periode 2016–2018, serta bagaimana kontribusi masing-masing segmen terhadap total pendapatan?

## Struktur Folder

submission
├── dashboard
│   ├── main_data.csv
│   └── dashboard.py
├── data
│   ├── orders_dataset.csv
│   ├── order_payments_dataset.csv
│   ├── customers_dataset.csv
│   ├── order_items_dataset.csv
│   └── products_dataset.csv
├── notebook.ipynb
├── README.md
├── requirements.txt
└── url.txt

## Cara Menjalankan Dashboard

1. Buka terminal.

2. Masuk ke folder utama submission.

```bash
cd submission