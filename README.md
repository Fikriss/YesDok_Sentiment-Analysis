# Sentiment Analysis YesDok App  

Proyek ini bertujuan untuk melakukan analisis sentimen terhadap review aplikasi YesDok yang diperoleh dari Google Play Store. Analisis ini mencakup proses scraping data, preprocessing menggunakan teknik POS Tagging dan Regular Expression (Regex), serta klasifikasi sentimen.

## Overview  
Aplikasi YesDok adalah platform layanan kesehatan digital. Dengan menggunakan data review dari Google Play Store, proyek ini bertujuan untuk:  
1. Mengumpulkan data ulasan pengguna.  
2. Memproses data untuk membersihkan dan menyusun teks menggunakan Regex dan POS Tagging.  
3. Melakukan analisis sentimen untuk memahami opini pengguna terhadap aplikasi YesDok.  

## Features  
- **Data Scraping:** Mengambil ulasan dari Google Play Store secara otomatis.  
- **Text Preprocessing:**  
  - Tokenisasi.  
  - Filtering menggunakan Regular Expressions (Regex).  
  - Part-of-Speech (POS) Tagging untuk analisis sintaksis.  
- **Sentiment Classification:** Memisahkan ulasan menjadi kategori sentimen seperti *positive*, *negative*, dan *neutral*.  

## Requirements  
Sebelum memulai, pastikan Anda memiliki:  
- Python 3.8 atau lebih baru.  
- Library yang dibutuhkan:  
  - `selenium`  
  - `nltk`  
  - `pandas`  
  - `numpy`  
  - `re`  
  - `matplotlib` / `seaborn` untuk visualisasi (opsional).  
