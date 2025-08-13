# Ringkasan Proyek: Credit Scoring dengan Machine Learning  
**Peran:** Data Scientist Intern  
**Perusahaan:** Home Credit Indonesia  
**Metode Analisis:** Machine Learning (Logistic Regression & Model Tambahan)  

## Latar Belakang Proyek  
Home Credit menggunakan metode statistik dan Machine Learning untuk membangun **prediksi skor kredit**. Tujuannya adalah:
- Memastikan pelanggan yang layak tidak ditolak saat mengajukan pinjaman
- Menyediakan pinjaman dengan struktur **principal**, **maturity**, dan **repayment calendar** yang memotivasi pelanggan untuk sukses

## Tujuan  
Mengembangkan model Machine Learning **end-to-end** untuk memprediksi kelayakan kredit pelanggan, sehingga dapat meminimalkan risiko dan meningkatkan persetujuan pinjaman yang sehat.

## Langkah Pengerjaan  
1. **Exploratory Data Analysis (EDA)**  
   - Mengidentifikasi pola dan distribusi data
   - Menentukan fitur dengan pengaruh terbesar terhadap kelayakan kredit (*Best Feature*)
2. **Pemodelan Machine Learning**  
   - Model 1: **Logistic Regression** (baseline)
   - Model 2: Model tambahan untuk perbandingan performa
3. **Evaluasi Model**  
   - **AUC (Area Under Curve)**
   - **KS (Kolmogorov-Smirnov) Statistic**
4. **Interpretasi & Insight**  
   - Menentukan faktor kunci yang memengaruhi skor kredit
   - Memberikan rekomendasi bisnis berdasarkan hasil analisis

## Hasil  
- Model dengan performa terbaik dipilih berdasarkan **AUC** dan **KS Score** tertinggi  
- Fitur-fitur terpenting diidentifikasi untuk strategi *credit risk management*

## Rekomendasi Bisnis  
- Memprioritaskan faktor-faktor risiko utama pada penilaian kredit
- Mengoptimalkan penawaran pinjaman bagi segmen pelanggan yang berpotensi tinggi untuk melunasi tepat waktu
- Menyesuaikan kebijakan pinjaman untuk meminimalkan penolakan terhadap pelanggan layak

---
**Kesimpulan:**  
Melalui pemodelan Machine Learning end-to-end, proyek ini menghasilkan sistem prediksi yang dapat membantu Home Credit meningkatkan akurasi penilaian kredit, mengurangi risiko, dan memperbesar peluang keberhasilan pinjaman.
