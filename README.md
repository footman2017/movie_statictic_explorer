# movie_statictic_explorer
Raey Faldo - 1301218679

Untuk final project mata kuliah visualisasi data ini saya menggunakan dataset "Film Genre Statistics" (https://www.kaggle.com/datasets/thedevastator/film-genre-statistics). Dataset tersebut berisi statistik genre untuk film-film yang dirilis antara tahun 1995 dan 2018.
pada project ini, ada dua visualisasi data interaktif yang dibuat. visualisasi data pertama yaitu berupa grafik garis yang memperlihatkan statistik genre film. Dengan sumbu x nya merupakan tahun dan sumbu y nya merupakan data yang ingin dilihat yang dapat dipilih melalui dropdown yang disediakan. Grafik garis dipilih karena dapat menunjukkan tren seiring waktu pada data yang dipilih (Jumlah Film Dirilis, Pendapatan Kotor, Tiket Terjual). grafik ini menurut saya cukup efektif untuk menggambarkan perubahan dan perbandingan. kemudian untuk element interaktifnya saya mengimplementasikan dropdown untuk genre, tahun awal, tahun akhir, dan jenis data untuk filtering data yang ramah pengguna. Serta menambahkan tooltip untuk memberikan informasi detail tentang titik data saat mengarahkan kursor ke grafik garis. Sebelum memilih grafik garis saya sempat mencoba untuk menggunakan grafik bar, hanya saja ketika dicobakan hasilnya tidak sesuai dengan yang diharapkan dikarenakan keterbatasan library yang digunakan.

visualisasi data kedua yaitu berupa grafik batang yang memperlihatkan statistik genre film untuk semua kategori. Dengan sumbu x nya merupakan data statistik yang ingin dilihat yang dapat dipilih melalui dropdown yang disediakan dan sumbu y yang terdiri dari semua genre movie yang ada. Grafik batang dipilih karena grafik tipe ini merupakan grafik yang paling sesuai setelah mencoba beberapa option tipe grafik yang ada. Untuk element interaktifnya saya mengimplementasikan dropdown untuk  tahun awal, tahun akhir, dan jenis data untuk filtering data yang ramah pengguna. Serta menambahkan tooltip untuk memberikan informasi detail tentang titik data saat mengarahkan kursor ke grafik garis. sebelum memilih grafik batang ini saya sempat ingin menggunakan grafik pie, hanya saja library yang digunakan tidak menyediakan grafik dengan tipe tersebut.

An overview of development process:
1. memilih dataset yang akan digunakan. saya mencari dataset pada website keagle. dan akhirnya memilih dataset"Film Genre Statistics".
2. melakukan exploratory analysis, untuk mencari hal apa yang dapat di visualisasikan
3. ekplorasi library yang akan digunakan untuk visualisasi data
4. ObservableHQ menjadi pilihan setelah eksplorasi yang dilakukan. ObservableHQ adalah platform komputasi interaktif yang memungkinkan pengguna untuk membuat dan berbagi notebook interaktif secara online. Dibuat oleh tim pengembang Mike Bostock, yang juga merupakan salah satu pencipta D3.js (sebuah pustaka JavaScript untuk membuat visualisasi data interaktif), ObservableHQ dirancang untuk mempermudah visualisasi data dan analisis data secara kolaboratif.
5. eksplorasi penggunaan ObservableHQ.
6. pengmbangan visualisasi data menggunakan ObservableHQ.
7. mengembangkan halaman html sederhana, yang didalamnya menggunakan element embeded dari ObservableHQ. jadi setelah visualisasi data bersahsil dikembangkan pada ObservableHQ. visualisasi tersebut dapat dijadikan element embeded. dimana elemenet tersebut dapat digunakan di code html manapun dan tetap menampilkan visualisasi data yang telah dibuat sebelumnya di ObservableHQ.
8. setelah halaman selesai, file html di push ke github.

pengembangan final project ini saya lakukan seorang diri, kira kira dengan total estimasi waktu yang dibutuhkan hingga push ke github yaitu 6 jam. dan proses yang paling banyak memakan waktu adalah saat eksplorasi platform ObservableHQ.

berikut adalah link untuk notebook ObservableHQ
https://observablehq.com/d/61abf0d419607a07
