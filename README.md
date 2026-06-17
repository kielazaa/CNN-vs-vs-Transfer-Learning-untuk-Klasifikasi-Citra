# CNN from Scratch vs Transfer Learning

## Deskripsi Proyek

Proyek ini merupakan implementasi dan perbandingan dua pendekatan Deep Learning untuk klasifikasi citra, yaitu CNN from Scratch dan Transfer Learning menggunakan MobileNetV2.

Eksperimen dilakukan untuk memahami perbedaan performa, kebutuhan data, serta karakteristik masing-masing metode dalam menyelesaikan tugas klasifikasi gambar.

## Dataset

### 1. CIFAR-10

Digunakan untuk implementasi CNN from Scratch dengan dua kelas kendaraan.

### 2. Dogs vs Cats

Dataset diperoleh dari Kaggle dan digunakan untuk implementasi Transfer Learning menggunakan MobileNetV2.

## Metode

### CNN from Scratch

* Convolution Layer
* Max Pooling Layer
* ReLU Activation
* Flatten Layer
* Dense Layer
* Dropout Layer

### Transfer Learning

* MobileNetV2 (Pretrained ImageNet)
* Feature Extraction
* Global Average Pooling
* Dense Layer
* Dropout Layer

## Hasil Eksperimen

### CNN from Scratch

* Test Accuracy: 95.40%
* Test Loss: 0.1513

### Transfer Learning (MobileNetV2)

* Accuracy: 76.76%
* Loss: 0.4734

## Tools

* Python
* TensorFlow
* Google Colab
* NumPy
* Matplotlib
* Scikit-Learn

## Author

[Nama Kamu]

[NIM Kamu]

Teknik Informatika
