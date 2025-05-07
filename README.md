
# Projek Analisis Sentimen Aplikasi myBCA (Bahasa Indonesia)

Repository ini berisi proyek analisis sentimen terhadap ulasan aplikasi **myBCA** yang diambil dari Google Play Store menggunakan teknik web scraping, kemudian dilakukan analisis sentimen dengan model Machine Learning dan Natural Language Processing (NLP).

## 🔍 Deskripsi

- Data dikumpulkan melalui **scraping ulasan** menggunakan library `google-play-scraper` (hanya ulasan berbahasa Indonesia).
- Proses dilanjutkan dengan **pembersihan data teks**, tokenisasi, stopword removal, dan TF-IDF.
- Dibuat 3 model untuk analisis sentimen:
  1. Logistic Regression (N-gram + 70/30)
  2. Support Vector Machine (BoW + 80/20)
  3. Deep Neural Network (TF-IDF + 80/20)

## 🛠 Teknologi dan Library

- Python 3
- Jupyter Notebook
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
├── models/                # Model machine learning dan deep learning
├── data/                  # Dataset hasil scraping (format CSV)
└── README.md
```

## 🚀 Cara Menjalankan

1. Clone repository ini:
   ```bash
   git clone https://github.com/Lahen194/ProyekAnalisisSentimen-MyBca.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan file scraping terlebih dahulu untuk mendapatkan data.
4. Lanjutkan ke tahap preprocessing dan training model.

## 🎯 Tujuan Proyek

Mengidentifikasi opini pengguna (positive, negative, dan neural) terhadap aplikasi myBCA dan mengevaluasi performa model NLP untuk klasifikasi sentimen. Projek ini dilakukan untuk memenuhi penugasan pembelajaran 'Pengembangan Machine Learning' dicoding.

## 📌 Catatan

- Proyek ini hanya menganalisis ulasan dalam **bahasa Indonesia**.
- Dataset bersifat publik hasil scraping, bukan dataset resmi dari BCA.
- Projek ini berhasil mendapat 4 bintang dari reviewer tim Dicoding.
