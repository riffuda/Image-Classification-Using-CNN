# Proyek Klasifikasi Gambar - Tom & Jerry

Proyek ini bertujuan membangun model **klasifikasi gambar** menggunakan arsitektur **Convolutional Neural Network (CNN)**. Model dilatih untuk mengenali gambar dari beberapa kategori pada dataset yang telah diproses.

## Ringkasan Proyek

### Dataset

Dataset terdiri atas gambar yang dibagi ke dalam tiga subset:

- **Training set**: untuk melatih model.
- **Validation set**: untuk memantau kinerja model selama proses pelatihan.
- **Testing set**: untuk mengukur kemampuan model terhadap data baru.

Distribusi dataset dilakukan secara proporsional agar model dapat belajar secara optimal.

### Arsitektur Model

Model CNN terdiri dari beberapa tahapan utama:

- Convolutional layer dengan fungsi aktivasi
- Pooling layer untuk mereduksi dimensi fitur
- Fully connected layer (dense) untuk proses klasifikasi
- Dropout layer sebagai regularisasi
- Output layer dengan softmax activation

### Cara Menjalankan

1. Clone repositori.
2. Instalasi dependensi:

    ```bash
    pip install -r requirements.txt
    ```

3. Jalankan notebook:

    - Notebook utama: `notebook.ipynb`

4. Evaluasi hasil model.

## Hasil Akhir

- Training Accuracy: 0.9525
- Validation Accuracy: 0.9391
- Test Accuracy: 0.9162

## Teknologi yang Digunakan

- TensorFlow dan Keras untuk pengembangan dan pelatihan model
- Matplotlib dan Seaborn untuk visualisasi proses pelatihan
- Python 3 sebagai bahasa pemrograman

## Kesimpulan

Model CNN yang dikembangkan menunjukkan performa yang sangat baik, dengan akurasi tinggi pada data training, validation, dan testing. Model ini mampu melakukan klasifikasi gambar secara efektif berdasarkan pola fitur yang telah dipelajari.
