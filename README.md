# # Segmentasi Perilaku Pemain Game Online Menggunakan K-Means

## Deskripsi Proyek

Proyek ini merupakan tugas mata kuliah Machine Learning yang bertujuan untuk mengelompokkan perilaku pemain game online menggunakan algoritma K-Means Clustering. Pengelompokan dilakukan berdasarkan pola waktu bermain, frekuensi sesi bermain, dan rata-rata durasi setiap sesi.

Proyek ini menggunakan Python dan Jupyter Notebook untuk melakukan pengolahan data, eksplorasi data, penerapan algoritma clustering, visualisasi, serta evaluasi hasil pengelompokan.

## Tujuan Proyek

1. Memahami proses pengolahan data dalam Machine Learning.
2. Menerapkan algoritma K-Means Clustering pada data perilaku pemain game.
3. Mengidentifikasi karakteristik setiap kelompok pemain.
4. Menentukan jumlah cluster menggunakan metode Elbow dan Silhouette Score.
5. Memvisualisasikan dan mengevaluasi hasil clustering.

## Dataset

Dataset yang digunakan adalah **Online Gaming Behavior Dataset** dari Rabie El Kharoua.

Sumber dataset:  
https://www.kaggle.com/datasets/rabieelkharoua/predict-online-gaming-behavior-dataset

Dataset ini berisi informasi mengenai perilaku pemain game online. Dataset bersifat sintetis sehingga hasil analisis digunakan untuk keperluan pembelajaran dan tidak secara langsung mewakili perilaku pemain game di dunia nyata.

## Fitur yang Digunakan

Proses clustering menggunakan tiga fitur utama:

1. `PlayTimeHours` — informasi waktu bermain sesuai definisi pada dataset.
2. `SessionsPerWeek` — jumlah sesi bermain per minggu.
3. `AvgSessionDurationMinutes` — rata-rata durasi sesi bermain dalam menit.

Kolom identitas pemain tidak digunakan sebagai fitur clustering. Kolom `EngagementLevel` juga tidak digunakan dalam pembentukan cluster.

## Metode yang Digunakan

Tahapan pengerjaan proyek meliputi:

1. Memuat dan memeriksa dataset.
2. Memeriksa nilai kosong, duplikasi, dan tipe data.
3. Membersihkan data yang digunakan dalam analisis.
4. Melakukan eksplorasi data dan visualisasi distribusi fitur.
5. Melakukan standardisasi menggunakan `StandardScaler`.
6. Menentukan jumlah cluster dengan metode Elbow dan Silhouette Score.
7. Menerapkan algoritma K-Means Clustering.
8. Mengevaluasi hasil clustering menggunakan Silhouette Score.
9. Menganalisis karakteristik setiap cluster berdasarkan nilai rata-rata dan median.
10. Memvisualisasikan hasil clustering menggunakan PCA.
11. Menyimpan hasil analisis ke dalam file CSV.

## Tools dan Library

Proyek ini menggunakan:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Cara Menjalankan Proyek

1. Unduh atau clone repository ini.
2. Pastikan Python dan Jupyter Notebook sudah terpasang.
3. Instal library yang diperlukan dengan perintah berikut:

   `pip install -r requirements.txt`

4. Unduh dataset dari tautan sumber yang tersedia di bagian Dataset.
5. Simpan file CSV di lokasi yang sesuai dengan kode notebook.
6. Buka file `Clustering_Perilaku_Pemain.ipynb` menggunakan Jupyter Notebook atau JupyterLab.
7. Jalankan seluruh sel notebook secara berurutan.
8. Periksa grafik, evaluasi model, profil cluster, dan file hasil yang dihasilkan.

## Hasil Proyek

Proyek ini menghasilkan pengelompokan pemain ke dalam tiga cluster sebagai konfigurasi awal model. Karakteristik setiap cluster dianalisis berdasarkan waktu bermain, frekuensi sesi, dan rata-rata durasi sesi.

Hasil analisis juga mencakup visualisasi distribusi data, grafik Elbow, perbandingan Silhouette Score, profil cluster, dan visualisasi PCA.

Interpretasi akhir perlu disesuaikan dengan hasil aktual yang diperoleh ketika notebook dijalankan.

## Batasan Proyek

- Dataset yang digunakan bersifat sintetis.
- Hasil clustering bergantung pada fitur dan jumlah cluster yang dipilih.
- Silhouette Score digunakan untuk membantu mengevaluasi pemisahan cluster, tetapi tidak menjadi satu-satunya dasar penilaian kualitas model.
- Hasil clustering tidak secara langsung menunjukkan tingkat keterampilan, loyalitas, atau kualitas seorang pemain.

## Author

Nama: [Nama Kamu]  
Mata Kuliah: Machine Learning

