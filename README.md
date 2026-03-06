# Introduction to Machine Learning with Python

Repository ini dibuat untuk memenuhi **Tugas 1 (Pengayaan)** pada kelas Machine Learning dan Deep Learning. Isinya adalah reproduksi kode dan pendalaman teori dari buku *Introduction to Machine Learning with Python* karya Andreas C. Müller & Sarah Guido (O'Reilly).

## Identitas
- **Nama:** Kei [Ganti dengan Nama Lengkap]
- **NIM:** [Isi NIM Kamu]
- **Kelas:** [Isi Kelas Kamu]

## Rangkuman Bab

### [Chapter 1: Introduction](./All_Chapter.ipynb)
Pada bab ini, saya mempelajari konsep dasar Machine Learning dan alur kerja pembuatan model melalui studi kasus klasifikasi bunga Iris.

**Library Utama yang Saya Gunakan:**
* **scikit-learn**: Berisi algoritma machine learning yang saya gunakan.
* **NumPy & Pandas**: Untuk pengolahan data angka dan tabel.
* **Matplotlib**: Untuk visualisasi data.

### [Chapter 2: Supervised Learning](./All_Chapter.ipynb)
Bab ini merupakan bagian terdalam di mana saya mempelajari berbagai algoritma untuk memprediksi target berdasarkan data berlabel. Fokus utama saya adalah memahami keseimbangan antara *Overfitting* dan *Underfitting*.

**Dua Tipe Utama yang Saya Pelajari:**
1. **Classification (Klasifikasi)**: Memprediksi kategori (misal: menentukan jenis kanker).
2. **Regression (Regresi)**: Memprediksi angka kontinu (misal: harga rumah).

**Algoritma yang Saya Implementasikan:**
* **k-Nearest Neighbors**: Algoritma berbasis jarak untuk klasifikasi dan regresi.
* **Linear Models**: Saya menggunakan *Ordinary Least Squares*, teknik regularisasi (*Ridge* & *Lasso*), serta model klasifikasi seperti *Logistic Regression*.
* **Decision Trees & Ensembles**: Saya menerapkan pohon keputusan serta model tingkat lanjut seperti *Random Forests* dan *Gradient Boosted Decision Trees* (GBDT).
* **Kernelized SVM**: Saya menggunakan *RBF Kernel* untuk menangani pola data yang tidak bisa dipisahkan secara linear.
* **Neural Networks**: Saya mempelajari dasar *Deep Learning* melalui *Multilayer Perceptrons* (MLP) dan pentingnya penskalaan data.

### [Chapter 3: Unsupervised Learning and Preprocessing](./All_Chapter.ipynb)
Dalam bab ini, saya mengeksplorasi teknik untuk menemukan pola dalam data yang tidak memiliki label. Saya mempelajari bagaimana melakukan transformasi data dan mengelompokkan data berdasarkan kemiripan strukturnya.



**Topik & Algoritma yang Saya Pelajari:**
* **Preprocessing & Scaling**: Saya menerapkan berbagai metode penskalaan seperti `MinMaxScaler` dan `StandardScaler` untuk menyiapkan data sebelum diolah oleh model.
* **Dimensionality Reduction**: Saya menggunakan *Principal Component Analysis* (PCA) untuk mereduksi dimensi data dan memvisualisasikan dataset kompleks ke dalam ruang 2D.
* **Manifold Learning**: Saya mengimplementasikan `t-SNE` untuk menangkap struktur lokal pada data dimensi tinggi yang lebih rumit.
* **Clustering**: Saya membandingkan tiga algoritma pengelompokan utama:
    * **K-Means**: Mengelompokkan data berdasarkan jarak ke pusat massa (centroid).
    * **Agglomerative Clustering**: Membangun hierarki kelompok data secara berurutan.
    * **DBSCAN**: Mengidentifikasi kelompok berdasarkan kepadatan titik data dan mendeteksi noise.
* **Evaluasi Clustering**: Saya menggunakan metrik seperti *Adjusted Rand Index* (ARI) untuk memvalidasi kualitas pengelompokan yang saya buat.

**Poin-poin Penting:**
* **k-Nearest Neighbors**: Algoritma berbasis jarak untuk klasifikasi dan regresi.
* **Linear Models**: Mempelajari *Ordinary Least Squares*, teknik regularisasi (*Ridge* & *Lasso*), serta model klasifikasi seperti *Logistic Regression*.
* **Decision Trees & Ensembles**: Implementasi pohon keputusan dan model tingkat lanjut seperti *Random Forests* dan *Gradient Boosted Decision Trees* (GBDT).
* **Kernelized SVM**: Menggunakan *RBF Kernel* untuk menangani pola data yang tidak bisa dipisahkan secara linear.
* **Neural Networks**: Pengenalan dasar *Deep Learning* melalui *Multilayer Perceptrons* (MLP) dan pentingnya prapemrosesan data (*scaling*).

---

## Cara Menggunakan
Setiap file notebook (`.ipynb`) dapat dibuka langsung di GitHub atau dijalankan melalui Google Colab.
