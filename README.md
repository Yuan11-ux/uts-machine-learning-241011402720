# UTS Machine Learning: Linear Regression & Logistic Regression

## Identitas Mahasiswa
- **Nama:** Yuan Kanezar
- **NIM:** 241011402720
- **Kelas:** Reg CS
- **Mata Kuliah:** Machine Learning

## Deskripsi
Proyek ini merupakan tugas Ujian Tengah Semester (UTS) Machine Learning yang menerapkan Linear Regression untuk memprediksi penjualan berdasarkan biaya iklan dan Logistic Regression untuk mengklasifikasikan email spam.

## Dataset
1. **Ads_Data.csv**: Berisi 40 data biaya iklan dan penjualan.
2. **Email_Data.csv**: Berisi 60 data jumlah link, kata promosi, dan label spam.

## Metode yang Digunakan

### 1. Linear Regression
- Menggunakan metode Normal Equation dan Gradient Descent.
- Membagi data menjadi data training dan testing.
- Mengevaluasi model menggunakan MAE, MSE, RMSE, dan R².
- Membuat prediksi penjualan dan visualisasi garis regresi.
- Membandingkan beberapa nilai learning rate.

### 2. Logistic Regression
- Menggunakan Gradient Descent untuk klasifikasi email spam.
- Mengevaluasi model menggunakan accuracy, precision, recall, confusion matrix, dan F1-score.
- Memvisualisasikan decision boundary.
- Menguji threshold 0.3, 0.5, dan 0.7.
- Melakukan prediksi kategori email baru.

### 3. Perbandingan Model
Membandingkan hasil implementasi model secara manual dengan Scikit-learn sebagai bagian bonus.

## Ringkasan Hasil

### Linear Regression
- **R² (Testing):** 0.9334
- **RMSE (Testing):** 5.7190

### Logistic Regression
- **Accuracy:** 100%
- **Precision:** 100%
- **Recall:** 100%
- **F1-score:** 100%

Hasil evaluasi diperoleh dari output notebook menggunakan dataset yang disediakan.

## Tools dan Library
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn untuk perbandingan bonus

## Struktur Repository

```text
uts-machine-learning-241011402720/
├── README.md
├── tugas_UTS.ipynb
├── Ads_Data.csv
└── Email_Data.csv
```

## Cara Menjalankan
1. Pastikan seluruh file dataset berada di folder yang sama dengan notebook.
2. Buka `tugas_UTS.ipynb` menggunakan Jupyter Notebook, JupyterLab, atau VS Code.
3. Jalankan seluruh sel dari awal hingga akhir menggunakan **Run All**.

## Pengumpulan
Repository GitHub dibuat dengan status **Public**. Tautan repository dikumpulkan melalui halaman UTS di Mentari Universitas Pamulang.
