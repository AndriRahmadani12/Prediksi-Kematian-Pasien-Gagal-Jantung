# Analisis Fitur dan Prediksi Kematian Pasien Gagal Jantung: Perbandingan Random Forest dan Bagging

## Tujuan

(For Educational Purposes Only)

1. **Mengidentifikasi Fitur Penting dalam Prediksi Kematian Pasien Gagal Jantung:**
   - Melakukan analisis fitur untuk menentukan faktor-faktor utama yang berkontribusi terhadap kematian pasien gagal jantung.
   - Menjelaskan metode yang digunakan untuk memilih dan mengevaluasi fitur penting dalam dataset.

2. **Membandingkan Metode Prediksi: Random Forest dan Bagging:**
   - Menjelaskan cara kerja algoritma Random Forest dan teknik Bagging dalam konteks prediksi medis.
   - Membandingkan kinerja kedua model berdasarkan metrik evaluasi utama seperti akurasi dan AUC.

3. **Evaluasi Kinerja Model untuk Pengambilan Keputusan:**
   - Menyajikan hasil akurasi dan AUC dari model Random Forest dan Bagging.
   - Memberikan rekomendasi berdasarkan hasil evaluasi.

## Dataset

**Heart Failure Clinical Records**. (2020). UCI Machine Learning Repository. https://doi.org/10.24432/C5Z89R.

## Metodologi

### 1. Data Preprocessing

Menyiapkan dataset dengan langkah-langkah berikut:
- **Pembersihan Data:** Menangani missing values dan outliers.
- **Transformasi Data:** Melakukan normalisasi atau standarisasi jika diperlukan.
- **Pembagian Data:** Memisahkan dataset menjadi training set dan testing set.

### 2. Analisis Fitur

Mengidentifikasi fitur penting dengan menggunakan teknik seperti:
- **Feature Importance dari Random Forest:** Menggunakan fitur penting dari model Random Forest untuk menentukan kontribusi masing-masing fitur.
- **Correlation Analysis:** Menganalisis korelasi antara fitur dan target variabel.

### 3. Model Building

Membangun dan melatih dua model utama:
- **Random Forest:**
  - Memahami cara kerja ensemble learning dengan Random Forest.
  - Menggunakan fitur penting untuk membangun model prediksi.
- **Bagging:**
  - Menggunakan teknik Bagging untuk membuat model prediksi alternatif.
  - Membandingkan performa dengan model Random Forest.

### 4. Evaluasi Model

Mengukur kinerja model dengan metrik utama:
- **Akurasi:** Menghitung persentase prediksi benar dari keseluruhan prediksi.
- **AUC (Area Under the ROC Curve):** Mengukur kemampuan model untuk membedakan antara kelas positif dan negatif.


### Diskusi

- Menganalisis perbedaan kinerja antara Random Forest dan Bagging.
- Mengidentifikasi fitur mana yang paling berpengaruh terhadap prediksi kematian pasien gagal jantung.
- Memberikan rekomendasi berdasarkan hasil evaluasi untuk penggunaan model dalam konteks medis.

## Kesimpulan

Proyek ini menunjukkan pentingnya analisis fitur dan pemilihan model dalam prediksi kematian pasien gagal jantung. Random Forest dan Bagging memberikan hasil yang kompetitif, namun satu model mungkin lebih cocok tergantung pada konteks penggunaannya.

## Catatan

- **Dataset:** Heart Failure Clinical Records. (2020). UCI Machine Learning Repository. https://doi.org/10.24432/C5Z89R.
