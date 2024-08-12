# Implementasi Text Mining pada Ulasan Aplikasi Flip dengan Klasifikasi Support Vector Machine (SVM)

## Deskripsi Proyek
Project ini merupakan project kelompok dari mata kuliah Analisis Big Data. Project ini bertujuan untuk menganalisis ulasan positif, netral, dan negatif dari aplikasi flip yang kemudian diklasifikasikan menggunakan _Support Vector Machine_ (SVM). 

## Alat 
**Google Colab**

## Langkah-Langkah
1. **Data Scraping** : mengumpulkan ulasan aplikasi flip dari google play store.
2. **Preprocessing Data**
     - Tokenization : proses pemecahan teks ulasan menjadi unit-unit terkecil, proses cleansing (menghapus angka, tanda baca, karakter yang tidak diperlukan), normalization (mengoreksi ejaan), case folding (merubah huruf kapital menjadi huruf kecil).
3. **Ekstraksi Fitur** : Term Frequency-Inverse Document Frequency (TF-IDF) untuk mengubah teks menjadi numerik.
4. **Pelatihan Model** : membagi data menjadi train dan test yang kemudian dilatih dengan SVM.
5. **Evaluasi Model** : mengukur performa model dengan menggunakan akurasi.
6. **Kesimpulan** : interpretasi dari hasil analisis.

## Query
1. Scraping Data [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1_rGrUlgm57WMpSnaruPCCzfZ0dyXlmpt?usp=sharing)
2. Sentiment Analysis [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1j2nRwV5IgdY2NkiyJLdQpDAUzSMxyWVG?usp=sharing)

## Hasil
[![Documentation Status](https://readthedocs.org/projects/ansicolortags/badge/?version=latest)](https://github.com/aqielafasya/Python_Project/blob/master/Flip-Sentimen-Analysis/5.%20Sentiment%20Analysis%20of%20Flip%20App.pdf)
![image](https://github.com/user-attachments/assets/83269e43-ec96-482e-aa77-d737886135a6)


