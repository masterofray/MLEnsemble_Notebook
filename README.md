# Konstruksi Perangkat Pembelajaran *Modern Prediction and Machine Learning* di Prodi Statistika Universitas Cenderawasih Tahun 2022

## Gagasan Kreatif Penyelesaian Core Issue
Dalam tahapan ini, saya memberikan beberapa rekomendasi gagasan kreatif guna menyelesaikan core issue yang terjadi di Program Studi Statistika Universitas Cenderawasih yaitu “Belum adanya mata kuliah yang menyangkut Artificial Intelligence (AI)”, dengan gagasan pemecahan isu : “Konstruksi Perangkat Pembelajaran Mata Kuliah Modern Prediction and Machine Learning untuk Mahasiswa Prodi Statistik Universitas Cenderawasih”, dengan tahapan kegiatan sebagai berikut.

1.	Konstruksi silabus MK Modern Prediction and Machine learning.
  *	Konsultasi dengan mentor.
  *	Menelusuri referensi pendukung.
  *	Membuat Silabus.
  *	Review konstruksi silabus.
2.	Pembuatan RPS MK. Modern Prediction and Machine learning.
  *	Konsultasi dengan mentor.
  *	Menelusuri referensi pendukung.
  *	Membuat RPS MK. Modern Prediction and Machine learning.
  *	Review konstruksi RPS.
3.	Pembuatan Bahan Ajar MK. Modern Prediction and Machine learning.
  *	Konsultasi dengan mentor.
  *	Menelusuri referensi pendukung.
  *	Membuat bahan ajar berbasis digital untuk membantu perkuliahan mahasiswa di MK. Modern Prediction and Machine learning.
  *  Mencoba membuat proto tipe *source code* untuk digunakan oleh mahasiswa

## Algoritma - Machine Learning Lanjutan - Ensemble Methods

### Apa itu Metode Ensemble Learning?
Ensemble learning adalah paradigma pembelajaran mesin di mana beberapa model (sering disebut `Weak Learner`) dilatih untuk memecahkan masalah yang sama dan digabungkan untuk mendapatkan hasil yang lebih baik. Hipotesis utamanya adalah ketika model yang lemah digabungkan dengan benar, kita dapat memperoleh model yang lebih akurat dan/atau kuat.

Dua keluarga metode ensemble biasanya dibedakan:

1. Dalam metode rata-rata, prinsip penggeraknya adalah membangun beberapa estimator secara independen dan kemudian merata-ratakan prediksinya. Rata-rata, estimator gabungan biasanya lebih baik daripada estimator basis tunggal karena variansnya berkurang. Contoh: Metode bagging-Random Forest

2. Sebaliknya, dalam metode boosting, estimator dasar dibangun secara berurutan dan salah satu mencoba untuk mengurangi bias dari estimator gabungan. Motivasinya adalah untuk menggabungkan beberapa model yang lemah untuk menghasilkan ansambel yang kuat. Contoh: Metode peningkatan-XGBoost.

Di sini kita membahas algoritma lanjutan berikut: 
1. Bagging
2. AdaBoost
3. GBM- Gradient Boosting Machines
4. Light BGM
5. XGBoost (Extreme Gradient)
6. CatBoost
