# CAPSTONE-PROJECT-3---BIKE-SHARING

## **BUSINESS PROBLEM UNDERSTANDING**

### **CONTEXT**

Sistem bike sharing merupakan salah satu sistem penyewaan sepeda yang dikelola menggunakan sistem terkini. Prosesnya saat ini sudah otomatis, mulai dari pendaftaran, penyewaan, hingga pengembalian sepeda. User bisa dengan mudah mengambil sepeda di satu lokasi dan mengembalikannya di lokasi lain. Saat ini, ada lebih dari 500 program Bike Sharing di seluruh dunia dengan total lebih dari 500 ribu sepeda. Sistem ini semakin populer karena dianggap punya peran penting dalam mengurangi masalah lalu lintas, menjaga lingkungan, dan meningkatkan kesehatan.

Selain praktis, data yang dihasilkan dari sistem ini menarik untuk dijadikan bahan penelitian. Berbeda dengan transportasi umum seperti bus atau kereta, sistem ini mencatat secara detail mulai dari jam disewa, kondisi cuaca, jumlah penyewa, dan lainnya. Data ini menjadikan sistem berbagi sepeda seperti jaringan sensor virtual yang bisa digunakan untuk memantau mobilitas di kota. Jadi, berbagai peristiwa penting di kota bisa terdeteksi melalui analisis data ini.

Adapun data ini merupakan data yang bersumber dari Capital Bikeshare (CaBi) yang melayani penyewaan sepeda di wilayah Washington, D.C., dan sekitarnya. Per Januari 2023, Capital Bikeshare memiliki lebih dari 700 stasiun dan 5.400 sepeda. Adapun data ini juga sudah terintegrasi dengan data cuaca yang berasal dari web freemateo.

Original Source: http://capitalbikeshare.com/system-data </br>
Weather Information: http://www.freemeteo.com


![image-2.png](attachment:image-2.png)

### **BUSINESS PROBLEM**

Untuk mewujudkan tujuannya, capital bike share perlu menentukan jumlah sepeda yang perlu tersedia pada stasiun dan waktu tertentu. Namun untuk mengetahui jumlah kebutuhan sepeda diperlukan prediksi atau perkiraan jumlah penyewa sepeda dalam waktu tertentu agar kebutuhan pengguna dapat terpenuhi tanpa menimbulkan kelebihan atau kekurangan yang berdampak negatif pada operasional dan kepuasan pelanggan


### **GOALS**

Berdasarkan business problem di atas, dibutuhkan sebuah tool yang dapat memprediksi jumlah penyewa sepeda dalam kondisi tertentu

### **ANALYTICAL APPROACH**

Pendekatan analitik yang dilakukan untuk memprediksi jumlah penyewaan sepeda dimulai dengan menganalisis data historis dan data cuaca untuk menemukan pola permintaan. Selanjutnya, fitur-fitur yang memiliki relavansi terhadap jumlah penyewaan sepeda akan dipilih seperti fitur yang menjelaskan jam sibuk, kondisi musim atau cuaca, hari dan tanggal

Setelah itu akan dibangun model regresi yang digunakan untuk memprediksi jumlah penyewa sepeda pada kondisi tertentu. Model ini dievaluasi menggunakan metrik yang ditentukan dan hasil prediksi kemudian dapat dimanfaatkan oleh capital bike share untuk mengoptimalkan distribusi sepeda, sehingga layanan lebih efisien dan memadai.
