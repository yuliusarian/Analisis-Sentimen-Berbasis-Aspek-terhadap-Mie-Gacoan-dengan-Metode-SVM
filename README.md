# Analisis-Sentimen-Berbasis-Aspek-terhadap-Mie-Gacoan-dengan-Metode-SVM
Penelitian ini menggunakan dataset yang diambil dari Twitter

Data yang berhasil dikumpulkan sebanyak 3289 data, kemudian dilakukan proses preprocessing dengan urutan :
1. Case Folding dan Cleaning
2. Tokenizing
3. Normalisasi
4. Stemming

Kemudian data yang bersih akan dilakukan pelabelan sentimen secara manual, hal ini dilakukan untuk mengurangi misklasifikasi
dalam proses ini. Selain pelabelan sentimen, kemudian pada data dilakukan pelabelan aspek dengan batasan pada aspek food, price, dan service.
Setelah langkah ini didapatkan untuk aspek food sebanyak 258, price sebanyak 102 , dan service sebanyak 139 data.
Dari ketiga aspek tersebut kemudian akan masuk ke klasifikasi dengan SVM

Langkah Klasifikasi SVM:
1. Pembobotan Kata TF-IDF
2. K-Fold CV
3. Pembentukan model SVM
4. Pengukuran performa

Load Model
Langkah ini adalah proses pengujian dengan data yang baru ( di luar dataset ) menggunakan model terbaik dari variasi pengujian dan akan menghasilkan output 
hasil klasifikasinya
