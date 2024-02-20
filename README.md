# Model-Klasifikasi-Gambar-Menggunakan-Convolutional-Neural-Network-CNN-
Membuat sebuah model untuk mengklasifikasi gambar sebuah kamar dan memprediksi menggunakan model Convolutional Neural Network (CNN).

## **Tujuan**
Membuat sebuah model untuk mengklasifikasi gambar sebuah kamar dan memprediksi apakah kamar tersebut rapi atau berantakan.

## Tahapan
1. Memastikan TensorFlow yang digunakan di Google Colab adalah versi di atas 2.0.
2. Mengunduh dataset dan melakukan extract file dengan metode unzip.
3. Menampung direktori setiap kelas pada direktori train dan validasi ke dalam variabel.
4. Pre-processing data dengan image augmentation.
5. Mempersiapkan data latih yang akan dipelajari oleh model.
6. Membangun arsitektur model dengan Convolutional Neural Network (CNN).
7. Compile dan latih model dengan `model.compile` dan `model.fit` hingga mendapatkan akurasi yang diinginkan.
8. Menguji model yang telah dibuat dengan menggunakan gambar yang belum dikenali oleh model.
