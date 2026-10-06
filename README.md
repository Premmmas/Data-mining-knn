# Data-mining-knn
# Klasifikasi K-Nearest Neighbor (K-NN)

Repositori ini berisi latihan klasifikasi menggunakan algoritma K-Nearest Neighbor (K-NN) pada dataset *Social Network Ads* untuk memenuhi tugas Mata Kuliah Data Mining.

## Informasi Mahasiswa
* **Nama**: [Nama Kamu]
* **NIM**: [NIM Kamu]
* **Kelas**: Data Mining

## Deskripsi Proyek
Program ini bertujuan untuk memprediksi apakah seorang pengguna akan membeli produk berdasarkan atribut umur (*Age*) dan perkiraan gaji (*Estimated Salary*).

## Spesifikasi & Penyesuaian Model (Adjustments)
- **Dataset**: `Social_Network_Ads.csv` (400 data)
- **Fitur (X)**: Age, EstimatedSalary
- **Target (y)**: Purchased (0 = Tidak Beli, 1 = Beli)
- **Rasio Split Data**: 80% Training set, 20% Test set (`test_size = 0.20`)
- **Model K-NN**: 
  - `n_neighbors`: 3 (\(K=3\))
  - `metric`: Euclidean

## File dalam Repositori
- `knn.ipynb`: File Jupyter Notebook/Google Colab yang berisi script full dari pra-proses data hingga visualisasi.
- `Social_Network_Ads.csv`: Dataset yang digunakan.
