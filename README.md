# Tugas-Pertemuan11_kecerdasan-buatan
# Segmentasi Pelanggan Menggunakan K-Means Clustering
## Nama : Mohammad Azmi Abdussyukur
## NIM : 312210109
## Kelas : TI.22.A.SE.1

Repositori ini berisi implementasi analisis Customer Segmentation menggunakan metode Unsupervised Learning (K-Means Clustering). Proyek ini dibuat untuk memenuhi tugas pertemuan ke-11 mata kuliah Kecerdasan Buatan.
Tujuan utama dari analisis ini adalah untuk mengelompokkan pelanggan berdasarkan pola pembelian dan karakteristik demografis, sehingga dapat memberikan insight yang bermanfaat untuk strategi pemasaran dan customer relationship management.
Metodologi

### Analisis dilakukan melalui tahapan berikut:

1. Data Loading & Exploratory Data Analysis
2. Data Cleaning & Preprocessing
   - Menghapus kolom tidak relevan
   - Menangani missing values
   - Encoding variabel kategorikal
   - Standarisasi data
3. Clustering dengan K-Means
   - Penentuan jumlah cluster (Elbow & Silhouette)
   - Penerapan model K-Means
4. Cluster Profiling
   - Analisis rata-rata fitur tiap cluster
   - Penamaan segmen berdasarkan pola belanja
5. Visualisasi
   - PCA 2D / t-SNE
   - Grafik perbandingan antar segmen

### Hasil Utama

Analisis ini menghasilkan 5 segmen pelanggan dengan karakteristik berbeda, antara lain:
1. High-Value Premium Buyers
2. Mid-Class Family Shoppers
3. Budget Customers
4. Young Frequent Buyers
5. Occasional Premium Buyers

Detail lengkap dapat dilihat pada notebook:
# per11_kecerdasan_buatan.ipyn
