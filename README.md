<h1 align="center"> NLP Dengan Huggingface Transforer </h1>
<p align="center"> Jupyter Notebook untuk mempelajari tentang regresi, klasifikasi dan clustering</p>

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">
<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black">

</div>

### Regresi
- Linear Regression
- Ridge 
- Lasso
- ElasticNet

### Klasifikasi
- Logistic Regression
- K-Nearest Neighbors
- Support Vector Machine (SVM)

### Clustering
- K-Means Clustering
- Agglomerative Clustering
- DBSCAN (Density-based Spatial Clustering of Application with Noise)


Analisis Pipeline 🔍

1. Zero-Shot Classification
![alt text](image.png)
Analisis:
Zero-Shot Classification sangat menarik karena fleksibilitasnya. Model tidak memerlukan data berlabel dan mampu memberikan probabilitas kecocokan untuk beberapa kategori. Di sini, teks berhasil diklasifikasikan dengan label "technology" sebagai hasil tertinggi.

2. Text Generation
![alt text](image-1.png)
Text Generation menghasilkan variasi teks kreatif dengan pengaturan temperature yang membuat hasil lebih beragam. Ini berguna untuk membuat konten otomatis atau melengkapi teks.

3. Fill-Mask
![alt text](image-2.png)
Pipeline ini memprediksi kata seperti "AI", "new", atau "advanced" sebagai kandidat terbaik untuk menggantikan [MASK]. Berguna dalam menyempurnakan atau melengkapi teks.

4. Named Entity Recognition (NER)
![alt text](image-3.png)
NER berhasil mengenali "Hugging Face" sebagai organisasi, "2016" sebagai waktu, dan "New York" sebagai lokasi. Ini berguna untuk ekstraksi informasi dalam teks.

5. Question Answering (QA)
![alt text](image-4.png)
Model berhasil memberikan jawaban "senyawa kimia", menunjukkan keakuratan pipeline ini untuk menjawab pertanyaan berbasis konteks.

6. Sentiment Analysis
![alt text](image-5.png)
Sentimen positif berhasil dideteksi dengan confidence score yang tinggi. Ini berguna untuk analisis opini atau ulasan pengguna.


7. Text Summarization
![alt text](image-6.png)
Ringkasan yang dihasilkan efektif untuk menyederhanakan teks panjang menjadi poin-poin penting.
