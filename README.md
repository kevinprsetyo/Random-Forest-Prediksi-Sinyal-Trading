# Prediksi Sinyal Trading Saham Sektor Kesehatan Menggunakan Random Forest

## Deskripsi

Repository ini berisi implementasi algoritma **Random Forest** untuk memprediksi sinyal trading saham sektor kesehatan yang terdaftar di Bursa Efek Indonesia (BEI).

Model dibangun menggunakan data historis saham yang diperoleh dari Yahoo Finance, kemudian dilakukan proses *feature engineering* menggunakan indikator teknikal, pelatihan model klasifikasi, serta evaluasi strategi melalui proses *backtesting*.

Seluruh proses analisis, mulai dari pengambilan data hingga evaluasi model, disajikan dalam bentuk Jupyter Notebook.

---

## Tujuan

Proyek ini bertujuan untuk:

- Mengumpulkan data historis saham sektor kesehatan.
- Melakukan Exploratory Data Analysis (EDA).
- Membuat fitur berdasarkan indikator teknikal.
- Membangun model Random Forest untuk klasifikasi sinyal trading.
- Memprediksi sinyal BUY, HOLD, dan SELL.
- Mengevaluasi performa strategi menggunakan Backtesting.

---

## Dataset

Dataset diperoleh dari **Yahoo Finance** menggunakan library `yfinance`.

Saham yang digunakan merupakan saham sektor kesehatan yang terdaftar di Bursa Efek Indonesia (BEI).

---

## Metodologi

Tahapan penelitian meliputi:

1. Pengambilan data historis saham.
2. Pembersihan data.
3. Exploratory Data Analysis (EDA).
4. Feature Engineering.
5. Pembuatan label klasifikasi.
6. Pelatihan model Random Forest.
7. Evaluasi model.
8. Prediksi sinyal trading.
9. Backtesting strategi trading.

---

## Feature Engineering

Beberapa indikator teknikal yang digunakan sebagai fitur antara lain:

- Relative Strength Index (RSI)
- Exponential Moving Average (EMA)
- Triple Exponential Moving Average (TEMA)
- Bollinger Bands
- Daily Return
- Moving Average
- Volume

---

## Algoritma

Model Machine Learning yang digunakan adalah:

- Random Forest Classifier

Output model berupa tiga kelas:

| Label | Keterangan |
|--------|------------|
| BUY | Sinyal membeli saham |
| HOLD | Menahan posisi |
| SELL | Sinyal menjual saham |

---

## Evaluasi

Model dievaluasi menggunakan beberapa metrik klasifikasi, seperti:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

Selain itu dilakukan proses **Backtesting** untuk membandingkan performa strategi trading yang dihasilkan model terhadap pergerakan harga saham.

---

## Library yang Digunakan

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- yfinance
- pandas-ta
- Backtesting.py

---

## Isi Repository

Repository ini terdiri dari beberapa notebook Jupyter yang berisi proses analisis dan eksperimen model.

```
Random-Forest-Prediksi-Sinyal-Trading
│
├── Prediksi_Backtest_Saham_Kesehatan_....ipynb
├── Prediksi_Backtest_Saham_Kesehatan_....ipynb
└── Prediksi_Backtest_Saham_Kesehatan_....ipynb
```

Setiap notebook berisi tahapan mulai dari pengambilan data, preprocessing, pelatihan model, hingga proses backtesting.

---

## Cara Menjalankan

1. Clone repository.

```bash
git clone https://github.com/kevinprsetyo/Random-Forest-Prediksi-Sinyal-Trading.git
```

2. Install seluruh library yang dibutuhkan.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn yfinance pandas-ta backtesting
```

3. Buka salah satu notebook menggunakan:

- Jupyter Notebook
- Visual Studio Code
- Google Colab

4. Jalankan setiap sel secara berurutan.

---

## Hasil

Notebook pada repository ini menghasilkan:

- Data historis saham.
- Visualisasi data.
- Indikator teknikal.
- Model Random Forest.
- Prediksi sinyal BUY, HOLD, dan SELL.
- Confusion Matrix.
- Classification Report.
- Hasil Backtesting.

---

## Hasil Kinerja Keuntungan Strategi Trading
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/0a0b0f1e-98fe-4c65-aa84-f3c92030e8be" />

## Hasil Kinerja Evaluasi Model 
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/b687cf65-636a-4aa6-92ca-84fff9c0ee0b" />


## Pengembangan Selanjutnya

Pengembangan yang dapat dilakukan antara lain:

- Membandingkan Random Forest dengan algoritma lain seperti XGBoost atau LightGBM.
- Menambahkan Hyperparameter Optimization.
- Menggunakan Walk Forward Validation.
- Mengembangkan sistem prediksi secara real-time.
- Membangun dashboard visualisasi berbasis web.

---
