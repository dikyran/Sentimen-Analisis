# SENTIMEN ANALISIS - E-COMMERCE
Sentimen analisis adalah proses mengidentifikasi dan mengkategorikan opini yang diekspresikan dalam teks untuk menentukan sikap penulis atau pembicara terhadap topik tertentu. Analisis ini biasanya digunakan untuk mengukur sentimen positif, negatif, atau netral terhadap suatu produk, layanan, kebijakan, atau fenomena tertentu.

Di project ini saya telah memaparkan semua kebutuhan dan tahapan yang akan digunakan dalam melakukan analisis sentimen. Saya telah menyediakan file yang telah di crawling dari Google Play Scraper. Adapun langkah-langkah yang dilakuka ialah:
1. Membersihkan Data
Untuk membersikan data sehingga bisa diolah dan diterapkan menggunakan sebuah model, anda bisa mengikuti tahapan pada file "PREPROCESSING - SHOPEE". Ada 6 tahapan yang harus dilakukan untuk membersihkan data, yaitu: 
- Cleansing: Proses pembersihan teks dari elemen yang tidak diperlukan seperti tanda baca, angka, URL, atau karakter khusus.
- Case Folding: Mengubah semua karakter dalam teks menjadi huruf kecil.
- Tokenizing:  Memecah teks menjadi unit-unit terkecil yang disebut token (biasanya kata atau frasa).
- Stopword Removal: Menghapus kata-kata umum yang tidak memberikan banyak informasi (seperti "dan", "atau", "adalah").
- Stemming:  Mengurangi kata-kata ke bentuk dasarnya (akar kata).

Pada file ini kita melakukan pelabelan data untuk menilai polarity (positif atau negatif) menggunakan kamus lexicon.


2. Melakukan Pembobotan pada data dengan Transformasi TF-IDF
TF-IDF (Term Frequency-Inverse Document Frequency) adalah teknik pembobotan yang digunakan untuk menilai pentingnya sebuah kata dalam suatu dokumen relatif terhadap semua dokumen dalam kumpulan data. Pada file "2. SHOPEE- ALGORITMA-TESTING" sudah saya paparkan cara untuk melakukan pembobotan.

3. Menerapkan Model Machine Learning
Pada tahapan ini kita akan menerapkan model machine learning. Pada file "2. SHOPEE- ALGORITMA-TESTING", saya menggunakan 5 model algortima klasifikasi yakni:
- SVM (SUPPORT MACHINE VECTOR)
- RANDOM FOREST
- NAIVE BAYES
- DECISION TREE
- GRADIEN BOOSTING CLASIFICTION

Saya juga menggunakan 4 skenario data untuk melihat pembagian data apa yang paling optimal, berikut skenario data yang saya terapkan:
- skenarion 90:10
- skenario 80:20
- skenario 70:30
- skenario 60:40

