# Prorek Akhir Submission Proyek Klasifikasi Gambar

Proyek ini adalah Submission Belajar Pengembangan Machine Learning. Proyek ini bertujuan untuk membuat model klasifikasi gambar yang mampu mengklasifikasikan penyakit pada daun apel.

## Deskripsi Proyek

Proyek ini menggunakan pendekatan Deep Learning dengan memanfaatkan model Convolutional Neural Network (CNN), dengan  split dataset 80:10:10, menggunakan callbacks, serta konversi ke savedmodel,tflite, dan tfjs

### Fitur Utama
- **Dataset**: Dataset yang digunakan dapat ditemukan di [Augmented Apple Disease Dataset](https://www.kaggle.com/datasets/rm1000/augmented-apple-disease-detection-dataset).
- **Model**: Dibangun menggunakan CNN .
- **Format Model**:
  - `SavedModel` (TensorFlow)
  - `TF-Lite` (untuk perangkat mobile)
  - `TFJS` (untuk aplikasi berbasis web)

## Cara Menggunakan

1. **Instalasi Dependencies**
   Pastikan Anda telah menginstal dependencies yang diperlukan:
   ```bash
   pip install -r requirements.txt
   ```

2. **Pengunduhan Dataset**
   Unduh dataset dari [tautan ini](https://www.kaggle.com/datasets/rm1000/augmented-apple-disease-detection-dataset) dan letakkan di direktori yang sesuai.


3. **Training Model**
   Jalankan notebook untuk melatih model:


4. **Ekspor Model**
   Model yang telah dilatih dapat diekspor ke berbagai format untuk digunakan di platform yang berbeda.


## Teknologi yang Digunakan

- Python
- TensorFlow
- Keras
- Scikit-learn
- Jupyter Notebook

