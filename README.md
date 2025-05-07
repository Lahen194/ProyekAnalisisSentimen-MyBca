
# 📝 Sentiment Analysis of myBCA App Reviews (Bahasa Indonesia)

Repository ini berisi proyek analisis sentimen terhadap ulasan aplikasi **myBCA** yang diambil dari Google Play Store menggunakan teknik web scraping dan Natural Language Processing (NLP).

## 🔍 Deskripsi

- Data dikumpulkan melalui **scraping ulasan** menggunakan library `google-play-scraper` (hanya ulasan berbahasa Indonesia).
- Proses dilanjutkan dengan **pembersihan data teks**, tokenisasi, stopword removal, dan TF-IDF.
- Dibuat 3 model untuk analisis sentimen:
  - Model **Machine Learning** (misalnya SVM, Naive Bayes)
  - Model **Deep Learning** (misalnya LSTM)
  - Perbandingan hasil akurasi antar model

## 🛠 Teknologi dan Library

- Python 3
- `google-play-scraper`
- `pandas`, `numpy`
- `scikit-learn`
- `nltk`, `Sastrawi`
- `TensorFlow` / `Keras`
- `matplotlib`, `seaborn`

## 📁 Struktur Folder

```
.
├── scraping/              # Notebook atau script untuk scraping data ulasan
├── preprocessing/         # Proses pembersihan dan normalisasi teks
├── models/                # Model machine learning dan deep learning
├── data/                  # Dataset hasil scraping (format CSV)
└── README.md
```

## 🚀 Cara Menjalankan

1. Clone repository ini:
   ```bash
   git clone https://github.com/username/nama-repo.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan file scraping terlebih dahulu untuk mendapatkan data.
4. Lanjutkan ke tahap preprocessing dan training model.

## 🎯 Tujuan Proyek

Mengidentifikasi opini pengguna terhadap aplikasi myBCA dan mengevaluasi performa model NLP untuk klasifikasi sentimen.

## 📌 Catatan

- Proyek ini hanya menganalisis ulasan dalam **bahasa Indonesia**.
- Dataset bersifat publik hasil scraping, bukan dataset resmi dari BCA.
