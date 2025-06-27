# Klasifikasi Wine Menggunakan Algoritma Random Forest

Proyek ini bertujuan untuk mengklasifikasikan jenis wine berdasarkan kandungan kimia yang dimilikinya. Dataset yang digunakan adalah **Wine Dataset** dari **UCI Machine Learning Repository**, yang sering digunakan dalam tugas pembelajaran mesin karena strukturnya yang jelas dan fitur yang cukup informatif.

---

## Tentang Dataset

Dataset wine ini berisi:
- **178 sampel wine**
- **3 kelas wine (target)** yang direpresentasikan sebagai 0, 1, dan 2
- **13 fitur kimia**, seperti:
  - `alcohol` – kandungan alkohol
  - `malic_acid` – tingkat keasaman dari asam malat
  - `magnesium` – kandungan magnesium
  - `flavanoids` – jenis fenol yang memengaruhi warna dan rasa
  - `color_intensity` – intensitas warna wine
  - dan lainnya

Setiap fitur mewakili karakteristik kimia dari wine yang dapat diukur secara kuantitatif.

---

## Tujuan Proyek

Tujuan utama dari proyek ini adalah:
- Untuk **memprediksi jenis wine** dari fitur kimianya
- Membangun model klasifikasi yang **akurat dan dapat dijelaskan**
- **Mengidentifikasi fitur mana yang paling penting** dalam proses klasifikasi

---

## Mengapa Menggunakan Random Forest?

Random Forest adalah algoritma berbasis *ensemble learning* yang membangun banyak *decision tree* dan menggabungkan hasilnya melalui voting. Algoritma ini dipilih karena:

- Memiliki **akurasi tinggi**
- Tahan terhadap **overfitting**
- Mendukung **analisis fitur penting**
- Mudah digunakan dan efektif dalam berbagai jenis dataset

---

## Hasil dan Evaluasi

Model Random Forest yang dilatih pada dataset ini menunjukkan performa yang sangat baik:

- **Akurasi tinggi** pada data uji
- **Confusion matrix** menunjukkan prediksi yang tepat untuk ketiga kelas
- Fitur paling berpengaruh dalam klasifikasi antara lain:
  - `flavanoids`
  - `alcohol`
  - `color_intensity`

Dengan visualisasi heatmap dan bar chart, kita dapat dengan mudah memahami **seberapa baik model bekerja** dan **fitur mana yang paling banyak digunakan dalam pengambilan keputusan**.

---

## Kesimpulan

> "Dengan memanfaatkan algoritma Random Forest, kita dapat membangun model yang andal untuk mengklasifikasikan jenis wine hanya dari data kimia. Ini menunjukkan bagaimana machine learning dapat diterapkan di dunia nyata, seperti dalam kontrol kualitas produk atau analisis karakteristik minuman."

---

## Catatan

- Dataset berasal dari: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine)
- Proyek ini bersifat edukatif dan eksploratif, cocok untuk belajar klasifikasi dan interpretasi model berbasis pohon.


