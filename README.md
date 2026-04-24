# Analisis Pengaruh Iklim terhadap Hasil Pertanian
### Machine Learning - Regresi 
### Sumber Data: https://www.kaggle.com/datasets/samuelotiattakorah/agriculture-crop-yield
---
## Deskripsi Proyek
Proyek ini bertujuan untuk memprediksi hasil panen tanaman (ton/hektare)
berdasarkan faktor iklim dan kondisi lahan menggunakan pendekatan Machine Learning Regresi.
Dataset yang digunakan terdiri dari 1.000.000 data pertanian yang dibagi menjadi
800.000 data training dan 200.000 data testing.

---

## Algoritma yang Digunakan
- Linear Regression (Baseline)
- Decision Tree (RandomizedSearchCV)
- Random Forest (RandomizedSearchCV)

---

## Tahapan Pengerjaan
1. Data Understanding
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Data Splitting (70-30 / 80-20 / 90-10)
5. Model Building & Hyperparameter Tuning
6. Evaluasi Model (MAE, MSE, RMSE, R² Score)
7. Perbandingan Model
8. Inference pada data testing

---

## Hasil Terbaik
Model terbaik yang dihasilkan adalah **Linear Regression** dengan R² Score ~0.92
pada data validasi dan R² = 0.91 pada data testing.
