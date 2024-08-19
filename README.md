# Content-Based-Book-Recommendation-System

Membuat Book Recommendation System dengan Content Based Filtering berdasarkan Genre buku.

Dataset yang digunakan berasal dari : https://www.kaggle.com/datasets/chhavidhankhar11/amazon-books-dataset/data

Terdiri dari 3 file CSV berisi :
  1. Genre_df
      - Title : Menunjukkan Main Genre (Genre utama) buku.
      - Number of Sub-genres : Menampilkan jumlah sub-genre yang dimiliki setiap main genre.
      - URL : Menyediakan link menuju halaman Amazon tempat buku dalam genre terdaftar.
  2. Sub_Genre_df
      - SubGenre Title : Menunjukkan sub-genre spesifik dari setiap main genre
      - Main Genre : Menunjukkan genre utama yang dimiliki setiap sub-genre.
      - No. of Books : Menampilkan jumlah buku yang dikategorikan berdasarkan setiap sub-genre.
      - URL : Menyediakan link ke halaman Amazon tempat buku sub-genre terdaftar.
  3. Books_df
      - Title : Judul buku
      - Author : Menampilkan nama penulis buku atau rumah publikasinya.
      - Main Genre : Menunjukkan genre utama yang dimiliki buku.
      - Sub Genre : Menunjukkan spesifik sub genre pada buku.
      - Type : Menunjukkan format buku yang dijual.
      - Price : Menampilkan harga setiap buku.
      - Rating : Menunjukkan nilai rating rata-rata dari para user.
      - No. of People rated : Menunjukkan jumlah user yang memberi rating pada sebuah buku.
      - URLs : Menyediakan link halaman detail dan opsi pembelian buku di Amazon

Pada kasus ini :

 - Hanya dataset Books_df saja yang digunakan, karena datanya sudah cukup lengkap.
  
 - TF-IDF digunakan untuk mengubah text genre menjadi vektor.
  
 - Cosine Similarity digunakan untuk menghitung nilai kesamaan antar buku berdasarkan Genre.
