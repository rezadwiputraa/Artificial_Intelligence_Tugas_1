# Reza Dwi Putra - 20220801472

# Analisis Penjualan Vape Oxva

Proyek ini melakukan analisis data penjualan produk vape dari merek Oxva menggunakan algoritma K-Nearest Neighbors (KNN) untuk memprediksi produk yang terjual berdasarkan fitur jumlah terjual dan harga per unit.

## Deskripsi Dataset

Dataset terdiri dari informasi penjualan produk vape, dengan kolom-kolom sebagai berikut:

- **Tanggal**: Tanggal penjualan.
- **Nama_Produk**: Nama produk vape yang dijual.
- **Jumlah_Terjual**: Jumlah unit produk yang terjual.
- **Harga_Per_Unit**: Harga per unit produk.
- **Total_Penjualan**: Total pendapatan dari penjualan (Jumlah_Terjual x Harga_Per_Unit).

## Langkah-langkah

1. **Import Libraries**
   - Mengimpor pustaka yang diperlukan seperti Pandas, Seaborn, Matplotlib, dan Scikit-learn.

2. **Membaca Data**
   - Membuat dataset penjualan vape dan mengubahnya menjadi DataFrame.

3. **Eksplorasi Data**
   - Menampilkan beberapa baris awal data dan statistik deskriptif.
   - Visualisasi distribusi penjualan produk menggunakan grafik count plot.

4. **Persiapan Data**
   - Memilih fitur (`Jumlah_Terjual`, `Harga_Per_Unit`) dan target (`Nama_Produk`).
   - Membagi dataset menjadi data latih dan data uji (80/20).

5. **Normalisasi Data**
   - Menggunakan `StandardScaler` untuk menormalkan fitur.

6. **Modeling**
   - Menginisialisasi model K-Nearest Neighbors (KNN) dan melatih model dengan data latih.

7. **Evaluasi Model**
   - Menghitung akurasi model dan menghasilkan matriks kebingungan serta laporan klasifikasi.

## Kesimpulan 
   - Kode ini melakukan analisis dan prediksi terhadap data penjualan produk vape menggunakan KNN.
   - Anda dapat melihat seberapa baik model dapat memprediksi produk berdasarkan fitur yang ada.
   - Mengingat ukuran dataset yang kecil, hasil mungkin tidak sepenuhnya representatif. Mengumpulkan data lebih banyak atau melakukan validasi silang dapat membantu meningkatkan akurasi dan keandalan model.
   
## Cara Menjalankan Proyek

Untuk menjalankan proyek ini, pastikan Anda telah menginstal semua dependensi yang diperlukan. Anda dapat menggunakan `pip` untuk menginstalnya:

```bash
pip install pandas seaborn matplotlib scikit-learn
