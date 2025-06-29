
# 📘 Machine Learning Overview

Machine Learning (ML) adalah cabang dari kecerdasan buatan (AI) yang memungkinkan sistem untuk **belajar dari data tanpa diprogram secara eksplisit**. Tujuan utama dari ML adalah untuk mengembangkan algoritma yang dapat *memprediksi* atau *mengambil keputusan* berdasarkan pola yang ditemukan dalam data.

---

## 🧠 Kategori Machine Learning

Machine Learning secara umum terbagi menjadi tiga jenis utama:

1. **Supervised Learning**  
   Algoritma dilatih menggunakan data berlabel (input dan output diketahui).
   - Contoh: prediksi harga rumah, klasifikasi email spam.

2. **Unsupervised Learning**  
   Algoritma mencoba menemukan pola tersembunyi dalam data tanpa label.
   - Contoh: segmentasi pelanggan, deteksi anomali.

3. **Reinforcement Learning**  
   Algoritma belajar dengan mencoba berbagai aksi untuk memaksimalkan reward.
   - Contoh: robot navigasi, game AI.

---

## 🔍 Daftar Algoritma Machine Learning

### 📌 Supervised Learning

| Nama Algoritma | Deskripsi Singkat |
|----------------|-------------------|
| [Linear Regression](https://github.com/arofiqimaulana/Statistics/tree/master/Linear%20Regression) | Memprediksi nilai kontinu berdasarkan hubungan linier antar fitur. |
| Logistic Regression | Klasifikasi biner berdasarkan probabilitas. |
| [Decision Tree](https://github.com/arofiqimaulana/Artificial-Intelligence/tree/master/Supervised%20Learning/Decision%20Tree) | Membuat model seperti pohon keputusan untuk klasifikasi dan regresi. |
| [Random Forest](https://github.com/arofiqimaulana/Artificial-Intelligence/tree/master/Ensemble%20Learning/Random%20Forest) | Ensemble dari banyak pohon keputusan untuk meningkatkan akurasi. |
| [Support Vector Machine (SVM)](https://github.com/arofiqimaulana/Artificial-Intelligence/tree/master/Supervised%20Learning/Support%20Vector%20Machine) | Mencari hyperplane terbaik yang memisahkan data antar kelas. |
| [K-Nearest Neighbors (KNN)](https://github.com/arofiqimaulana/Artificial-Intelligence/tree/master/Supervised%20Learning/K-Nearest%20Neighbor) | Mengklasifikasikan data berdasarkan tetangga terdekat. |
| [Gradient Boosting / XGBoost](https://github.com/arofiqimaulana/Artificial-Intelligence/tree/master/Ensemble%20Learning) | Model ensemble berbasis boosting untuk prediksi yang kuat. |
| [Naive Bayes](https://github.com/arofiqimaulana/Artificial-Intelligence/tree/master/Supervised%20Learning/Naive%20Bayes )| Klasifikasi berbasis teorema Bayes dengan asumsi independensi antar fitur. |

---

### 📌 Unsupervised Learning

| Nama Algoritma | Deskripsi Singkat |
|----------------|-------------------|
| K-Means Clustering | Mengelompokkan data ke dalam K cluster berdasarkan kedekatan. |
| Hierarchical Clustering | Mengelompokkan data secara bertingkat (bottom-up/top-down). |
| DBSCAN | Clustering berdasarkan densitas, cocok untuk data dengan noise. |
| PCA (Principal Component Analysis) | Reduksi dimensi untuk visualisasi atau preprocessing. |
| Autoencoder | Jaringan saraf untuk kompresi dan rekonstruksi data. |
| t-SNE / UMAP | Reduksi dimensi non-linear untuk visualisasi data kompleks. |

---

### 📌 Reinforcement Learning

| Nama Algoritma | Deskripsi Singkat |
|----------------|-------------------|
| Q-Learning | Agen belajar berdasarkan nilai Q untuk tiap aksi. |
| Deep Q Network (DQN) | Menggabungkan Q-Learning dengan deep learning. |
| Policy Gradient Methods | Belajar langsung kebijakan (policy) untuk memilih aksi. |
| Proximal Policy Optimization (PPO) | Salah satu metode RL modern dengan stabilitas tinggi. |

---

## 🛠️ Tools dan Library Populer

- **Python** (bahasa utama)
- **Scikit-Learn** – Toolkit ML klasik
- **TensorFlow** / **Keras** – Deep learning
- **PyTorch** – Framework DL fleksibel
- **XGBoost**, **LightGBM** – Boosting yang efisien

# 🛠️ Perbandingan Tools
| **Fitur**               | **Keras**                          | **TensorFlow**                       | **PyTorch**                          |
|-------------------------|------------------------------------|--------------------------------------|--------------------------------------|
| **Tingkat Abstraksi**   | Tinggi (API tingkat tinggi)        | Menyediakan fleksibilitas lebih tinggi | Sedikit lebih rendah dibanding Keras, tapi sangat fleksibel |
| **Kemudahan Penggunaan**| Sangat mudah digunakan             | Lebih sulit, tapi lebih fleksibel    | Lebih mudah dibanding TensorFlow, lebih fleksibel dibanding Keras |
| **Fleksibilitas**       | Terbatas jika dibandingkan dengan PyTorch dan TensorFlow | Sangat fleksibel, terutama untuk aplikasi skala besar | Sangat fleksibel, terutama dalam penelitian |
| **Dukungan Platform**   | Terintegrasi dengan TensorFlow, Theano, CNTK | Mendukung berbagai platform (mobile, cloud, embedded) | Kurang optimal untuk beberapa platform (terutama untuk mobile) |
| **Penggunaan Umum**     | Model dasar, prototyping cepat     | Model kompleks, deployment skala besar | Penelitian, eksperimen, prototyping cepat |
| **Dikembangkan**     | François Chollet, Google     | Google Brain Team | Facebook's AI Research (FAIR) |

---

## 📚 Referensi Belajar

- [Coursera - Machine Learning by Andrew Ng](https://www.coursera.org/learn/machine-learning)
- [Scikit-Learn Documentation](https://scikit-learn.org/)
- [DeepLearning.AI](https://www.deeplearning.ai/)
