# Detektor Wajah - Husnan

## Domain Proyek

Deteksi Wajah merupakan subjek yang sangat populer dengan berbagai macam aplikasi. Ponsel cerdas, laptop, dan tablet komputer modern kini hadir dengan perangkat lunak pendeteksi wajah yang dapat mengotentikasi identitas pengguna. Pada kesempatan ini saya membuat detektor wajah dengan algoritma Haar Cascade, Algoritma ini menggunakan fitur deteksi tepi atau garis serta menggunakan sejumlah pendekatan machine learning untuk mempelajari fungsi klasifikasi.

## Business Understanding

### Problem Statements
- Bagaimana cara memetakan, menganalisis, dan mengonfirmasi identitas wajah ?

### Goals
- Membuat Detektor Wajah dengan Algoritma Haar Cascade

## Data Understanding
Pada proyek ini saya menggunakan gambar [children.jpg](https://pixabay.com/photos/children-siblings-brother-sister-817365/)

## Step By Step
Berikut merupakan beberapa tahapan yang dilakukan pada proyek ini:
- Pilihlah gambar untuk dideteksi. Karena kita akan mendeteksi wajah, tentu gambar yang dipilih harus ada wajahnya ya!
- Unduh dan load Haar cascades fitur dari repositori [GitHub OpenCV](https://github.com/opencv/opencv/tree/3.4/data/haarcascades).
- Panggil fungsi classifier untuk mendeteksi wajah.
- Tambahkan kotak deteksi pada area wajah. 
