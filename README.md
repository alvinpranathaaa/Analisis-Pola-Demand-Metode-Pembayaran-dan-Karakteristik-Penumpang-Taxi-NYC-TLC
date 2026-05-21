# Analisis Pola Demand, Metode Pembayaran, dan Karakteristik Penumpang Taxi NYC TLC

## Overview

Project ini merupakan Capstone Project Module 3 Data Analysis. Analisis dilakukan menggunakan dataset **NYC TLC Trip Record** untuk memahami pola perjalanan taxi di New York City, khususnya terkait waktu dengan demand tinggi, metode pembayaran yang paling sering digunakan, karakteristik jumlah penumpang, serta performa perjalanan berdasarkan beberapa metrik utama.

Analisis ini dibuat dari sudut pandang seorang Data Analyst yang membantu stakeholder memahami pola operasional taxi agar dapat mengambil keputusan berbasis data.

## Business Problem

Operator taxi perlu memahami pola perjalanan pelanggan agar dapat mengoptimalkan strategi operasional, terutama dalam penyesuaian jumlah armada pada jam-jam dengan demand tinggi.

Tanpa analisis data perjalanan, perusahaan akan kesulitan mengetahui:
- Kapan permintaan perjalanan paling tinggi.
- Metode pembayaran apa yang paling sering digunakan pelanggan.
- Kelompok jumlah penumpang seperti apa yang mendominasi perjalanan.
- Bagaimana gambaran performa perjalanan berdasarkan total trip, average fare, average fare per mile, dan average tip.

## Objectives

Tujuan dari analisis ini adalah:

1. Mengidentifikasi pola demand perjalanan taxi berdasarkan jam pickup.
2. Mengetahui metode pembayaran yang paling sering digunakan pelanggan.
3. Menganalisis karakteristik jumlah penumpang dalam perjalanan.
4. Mengukur performa perjalanan berdasarkan KPI utama.
5. Memberikan insight dan rekomendasi yang dapat digunakan stakeholder untuk pengambilan keputusan operasional.

## Dataset

Dataset yang digunakan:

**NYC TLC Trip Record**

Dataset ini berisi informasi perjalanan taxi, seperti:
- Waktu pickup dan dropoff
- Jarak perjalanan
- Jumlah penumpang
- Metode pembayaran
- Fare amount
- Tip amount
- Total amount

## Tools

Tools yang digunakan dalam project ini:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scipy
- Looker Studio
- GitHub

## Analysis Workflow

Alur pengerjaan project:

1. Business Problem Understanding
2. Data Understanding
3. Data Cleaning
4. Feature Engineering
5. Exploratory Data Analysis
6. Statistical Testing
7. Insight & Recommendation
8. Dashboard Development

## Data Cleaning

Tahapan data cleaning yang dilakukan meliputi:

- Mengecek dan menangani missing values.
- Mengecek dan menangani data duplikat.
- Menyesuaikan format data, terutama kolom tanggal dan waktu.
- Menangani outlier atau data tidak wajar.
- Membuat kolom tambahan untuk kebutuhan analisis, seperti pickup hour dan passenger group.
- Mengekspor dataset bersih untuk digunakan pada dashboard.

## Key Metrics

Beberapa KPI utama yang digunakan dalam dashboard:

- Total Trip
- Average Fare
- Average Fare per Mile
- Average Tip
- Trip Distribution by Payment Type
- Trips by Pickup Hour
- Trips by Passenger Group

## Dashboard Summary

Dashboard dibuat menggunakan Looker Studio untuk memudahkan stakeholder membaca hasil analisis secara visual.

Dashboard menampilkan:
- Ringkasan KPI utama.
- Pola jumlah perjalanan berdasarkan jam pickup.
- Distribusi metode pembayaran.
- Distribusi jumlah penumpang.
- Filter berdasarkan payment type, passenger group, dan date range.

## Key Insights

Beberapa insight utama dari hasil analisis:

1. Demand perjalanan taxi memiliki pola tertentu berdasarkan jam pickup.
2. Perjalanan cenderung meningkat pada jam-jam sibuk.
3. Metode pembayaran credit card menjadi metode pembayaran yang paling dominan.
4. Mayoritas perjalanan dilakukan oleh 1 penumpang.
5. KPI seperti average fare, average fare per mile, dan average tip dapat membantu stakeholder memahami performa perjalanan secara umum.

## Recommendations

Berdasarkan hasil analisis, rekomendasi yang dapat diberikan adalah:

1. Operator taxi dapat menyesuaikan jumlah armada pada jam-jam dengan demand tinggi.
2. Perusahaan dapat memprioritaskan strategi layanan untuk pengguna dengan metode pembayaran digital karena credit card menjadi metode pembayaran dominan.
3. Perusahaan dapat menyesuaikan layanan berdasarkan karakteristik penumpang, terutama karena perjalanan dengan 1 penumpang mendominasi.
4. Dashboard dapat digunakan secara berkala untuk memonitor performa perjalanan dan mendukung keputusan operasional.
