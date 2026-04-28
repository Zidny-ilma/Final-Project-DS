**Final Porject Data Science - Understanding Zara’s Sales Drivers Through Predictive Modelling**
-
Nama : Zidny Ilma Zain

Bootcamp : Dibimbing.id

Program : Data Science

Batch : 35

**Business Problem**
-
Zara sebagai perusahaan ritel fashion global menghadapi tantangan besar dalam mengelola persediaan produk agar tetap selaras dengan permintaan pasar yang dinamis.

Kesalahan dalam memprediksi volume penjualan dapat menyebabkan dua risiko utama:

- Overstock → stok berlebih yang meningkatkan biaya penyimpanan
- Understock → kekurangan stok yang menyebabkan kehilangan peluang penjualan

Untuk meminimalkan risiko tersebut, diperlukan analisis mendalam terhadap faktor-faktor yang memengaruhi volume penjualan produk agar perusahaan dapat membuat keputusan bisnis yang lebih akurat dan strategis.

**Objective**
-
Project ini bertujuan untuk menganalisis faktor-faktor yang memengaruhi volume penjualan produk Zara menggunakan pendekatan predictive modelling guna membantu perusahaan dalam:

- Mengidentifikasi variabel yang paling berpengaruh terhadap penjualan
- Memahami hubungan antara harga dan volume penjualan
- Mengoptimalkan strategi promosi dan positioning produk
- Mengurangi risiko overstock dan understock
- Mendukung pengambilan keputusan berbasis data dalam manajemen inventory

**Dataset**
-
Dataset yang digunakan merupakan data penjualan produk Zara yang berisi informasi atribut produk dan faktor pendukung penjualan.

Variables Used:
- Product Position
- Promotion
- Seasonal
- Terms (Jenis Pakaian)
- Section
- Season
- Material
- Origin
- Price
- Sales Volume (Target Variable)
- Tools Used

**Tools yang digunakan dalam project ini:**
-
- Python : Data Cleaning, Preparation, EDA, Modelling, Evaluation
- Machine Learning : Random Forest Regression
- GitHub : Project Documentation & Portfolio

**Libraries yang digunakan:**
-
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Process

Tahapan analisis yang dilakukan dalam project ini:

1. Data Cleaning
- Memeriksa missing values
- Menangani data duplikat
- Menstandarkan format kategori
- Encoding variabel kategorikal
- Menyiapkan data untuk modelling
  
2. Exploratory Data Analysis (EDA)
- Menganalisis distribusi total penjualan berdasarkan kategori produk
- Mengidentifikasi pola penjualan berdasarkan promotion dan seasonal
- Menganalisis hubungan antara harga dan sales volume
- Melihat pengaruh karakteristik produk terhadap performa penjualan
  
3. Predictive Modelling

Menggunakan model:

**Linear Regression, Ridge, Lasso, Decision Tree, Random Forest Regression**

untuk memprediksi volume penjualan berdasarkan variabel-variabel yang tersedia.

4. Model Evaluation

Melakukan evaluasi performa model menggunakan:

- R² Score
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
  
5. Feature Importance Analysis

Mengidentifikasi variabel yang paling berpengaruh terhadap volume penjualan menggunakan feature importance dari model Random Forest.

**Key Findings**
-
Beberapa insight utama yang ditemukan dari hasil analisis:

- Promotion memiliki pengaruh signifikan terhadap peningkatan volume penjualan
- Product Position sangat memengaruhi performa penjualan produk
- Seasonal factor berkontribusi besar terhadap fluktuasi demand
- Harga memiliki hubungan tertentu terhadap volume penjualan, namun tidak selalu menjadi faktor dominan
- Beberapa kategori produk menunjukkan performa penjualan yang jauh lebih tinggi dibanding kategori lainnya

Hasil feature importance menunjukkan bahwa strategi positioning dan promosi menjadi faktor yang sangat krusial dalam meningkatkan sales performance.

**Recommendation**
-
Berdasarkan hasil analisis, beberapa rekomendasi strategis yang dapat diberikan:

- Memprioritaskan promosi pada kategori produk dengan potensi penjualan tertinggi
- Mengoptimalkan product positioning untuk meningkatkan visibility produk
- Menyesuaikan inventory planning berdasarkan pola seasonal demand
- Menggunakan predictive modelling sebagai alat bantu forecasting penjualan
- Mengurangi risiko overstock dengan strategi stok berbasis data

Dengan pendekatan ini, perusahaan dapat meningkatkan efisiensi operasional sekaligus memaksimalkan profitabilitas bisnis.
