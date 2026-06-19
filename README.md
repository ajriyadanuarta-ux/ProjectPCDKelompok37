# Klasifikasi Penyakit Daun Singkong Menggunakan Ekstraksi Fitur GLCM dengan Model SVM, Random Forest dan KNN
## Nama Anggota

### Overview

Penyakit daun singkong merupakan salah satu faktor yang dapat menurunkan produktivitas dan kualitas hasil panen. Identifikasi penyakit secara manual sering kali memerlukan waktu, tenaga, dan keahlian khusus sehingga kurang efisien apabila diterapkan pada skala yang lebih luas. Oleh karena itu, diperlukan suatu sistem yang mampu membantu proses identifikasi penyakit daun singkong secara otomatis dengan memanfaatkan teknologi pengolahan citra digital dan machine learning.

Penelitian ini bertujuan untuk mengklasifikasikan penyakit daun singkong menggunakan fitur tekstur yang diekstraksi dengan metode Gray Level Co-occurrence Matrix (GLCM). Dataset yang digunakan terdiri dari lima kelas citra daun singkong, yaitu Cassava_bacterial_blight, Cassava_brown_streak_disease, Cassava_green_mottle, Cassava_healthy, dan Cassava_mosaic_disease. Kelima kelas tersebut merepresentasikan berbagai kondisi daun singkong, baik yang sehat maupun yang terinfeksi penyakit.

Metode GLCM digunakan untuk memperoleh karakteristik tekstur dari citra daun melalui perhitungan hubungan antar piksel pada beberapa arah. Dari proses ekstraksi tersebut dihasilkan sejumlah fitur tekstur, yaitu Contrast, Homogeneity, Dissimilarity, Entropy, ASM, Energy, dan Correlation. Fitur-fitur tersebut kemudian digunakan sebagai representasi numerik yang menggambarkan pola tekstur pada setiap citra daun singkong.

Selanjutnya, dilakukan proses seleksi fitur untuk mengurangi redundansi data dan mempertahankan fitur yang paling relevan. Data hasil ekstraksi fitur kemudian dibagi menjadi data training dan data testing untuk membangun serta mengevaluasi model klasifikasi. Pada penelitian ini digunakan tiga algoritma machine learning, yaitu Support Vector Machine (SVM), Random Forest, dan K-Nearest Neighbor (KNN). Ketiga algoritma tersebut dipilih karena memiliki pendekatan yang berbeda dalam proses klasifikasi sehingga dapat digunakan untuk membandingkan performa dalam mengenali penyakit daun singkong.

Evaluasi model dilakukan menggunakan metrik accuracy, precision, recall, f1-score, dan confusion matrix. Melalui hasil evaluasi tersebut dapat diketahui kemampuan masing-masing algoritma dalam mengklasifikasikan penyakit daun singkong berdasarkan fitur tekstur yang diperoleh. Hasil penelitian ini diharapkan dapat memberikan gambaran mengenai efektivitas penggunaan fitur GLCM dan algoritma machine learning dalam mendukung proses identifikasi penyakit daun singkong secara otomatis.


### Inaz Putri Kamila : F1D02410056
### Muharromi Ali Ilham : F1D02410082
### Ajriya Danuarta : F1D02410101