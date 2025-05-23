# Klasifikasi Pembelian Komputer dengan Naive Bayes

1. Import Library

   Pada tahap awal, berbagai library Python diimpor untuk membantu proses analisis data dan pembuatan model
   pandas untuk manipulasi data
   matplotlib & seaborn untuk visualisasi
   sklearn untuk preprocessing, training, dan evaluasi model

2. Data Loading

   Dataset dimuat ke dalam DataFrame menggunakan pd.read_csv().
   Kolom dalam dataset:

- Age: Usia pembeli (Muda, Paruh Baya, Tua)
- Income: Pendapatan (Rendah, Sedang, Tinggi)
- Student: Status mahasiswa (Ya, Tidak)
- Credit_Rating: Reputasi kredit (Buruk, Baik)
- Buys_Computer: Target (Ya, Tidak)

3. Exploratory Data Analysis (EDA)

   EDA dilakukan untuk memahami distribusi data. Visualisasi ini membantu mengetahui proporsi pembelian komputer berdasarkan kategori usia, pendapatan, dan lainnya.

4. Preprocessing Data

   Semua kolom kategorikal diubah menjadi bentuk numerik (encoding) agar dapat digunakan oleh model machine learning. Selain encoding, juga dilakukan pengecekan Nilai yang hilang.

5. Pembuatan dan Evaluasi Model Naive Bayes

   Model Naive Bayes digunakan karena cocok untuk data kategorikal. Evaluasi dilakukan dengan menghitung akurasi dan membuat confusion matrix

---

Dengan pendekatan ini, model Naive Bayes berhasil digunakan untuk memprediksi apakah seseorang akan membeli komputer atau tidak berdasarkan karakteristik demografis dan keuangannya. Proyek ini menunjukkan kekuatan metode sederhana dalam klasifikasi data kategorikal.
