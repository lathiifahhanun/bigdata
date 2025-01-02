![Spotify-Logo wine](https://github.com/user-attachments/assets/637a8565-d647-4734-ba6d-22cb05fdc44d)

# Analisis Dataset Spotify Songs 
## Overview
Musik adalah bagian tak terpisahkan dari kehidupan banyak orang. Dalam era digital saat ini, layanan streaming musik seperti Spotify telah mengubah cara kita mendengarkan musik, dengan memberikan akses ke jutaan lagu di ujung jari kita. Namun, di balik pengalaman mendengarkan yang mulus, terdapat data yang kaya yang mencerminkan preferensi audiens, tren musik, dan faktor-faktor yang memengaruhi popularitas lagu.

Spotify, dengan kumpulan data besar mengenai lagu, artis, genre, dan popularitas, menawarkan peluang untuk menggali wawasan yang dapat membantu dalam memahami tren musik, perilaku pengguna, dan pola popularitas di berbagai genre dan subgenre. Wawasan ini sangat penting bagi musisi, produser, dan penyedia layanan streaming untuk menciptakan pengalaman yang lebih personal dan menarik bagi audiens mereka.
 
Proyek ini bertujuan untuk mengeksplor data dan menemukan pola yang berhubungan dengan popularitas lagu. Dengan memahami berbagai pola pada dataset ini, proyek dapat memberikan wawasan yang bermanfaat di berbagai kalangan khususnya kelompok yang bekerja pada industri musik. 

## Dataset
Dataset diambil dari tautan berikut : [Spotify Song](https://github.com/rfordatascience/tidytuesday/blob/main/data/2020/2020-01-21/readme.md)

## Library
Library yang digunakan yaitu [pandas](https://pandas.pydata.org/) untuk memanipulasi dan menganalisa data, [matplotlib](https://matplotlib.org/) untuk membuat visualisasi, animasi, [seaborn](https://seaborn.pydata.org/) untuk visualiasi dari statistik berdasarkan matplotlib, dan [sklearn](https://pypi.org/project/scikit-learn/) untuk preprocessing data, termasuk penskalaan dan pengkodean.


## Exploratory Data Analysis(EDA) & Preprocessing
Analisis dimulai dengan Exploratory Data Analysis (EDA) yang bertujuan untuk memahami data secara mendalam, memungkinkan kita untuk mendapatkan gambaran umum tentang data, dengan memeriksa tipe data dan ringkasan statistik, dan memahami hubungan antara variabel-variabel.

Lalu dilakukan Preprocessing yaitu pengecekan nilai hilang (_missing value_) dan mengisi nilai yang hilang dengan modus dari masing-masing kolom. 

## Analisis
### Analisis Kategorikal
- Distribusi Genre: Plot hitung menunjukkan distribusi berbagai genre, mengungkapkan bahwa EDM adalah genre yang paling populer dalam dataset.

- Artis Teratas: Plot batang menampilkan 10 artis paling produktif berdasarkan jumlah lagu.

- Popularitas Artis: Rata-rata popularitas lagu untuk setiap artis dihitung dan divisualisasikan.

### Analisis Temporal
- Tren Tahun Rilis: Plot garis menunjukkan tren rilis lagu dari tahun ke tahun, menunjukkan bahwa lagu-lagu terbaru cenderung memiliki popularitas yang lebih tinggi.
### Analisis Durasi
- Durasi Lagu: Histogram menggambarkan bahwa lagu dengan durasi 2-4 menit umumnya lebih populer.
### Analisis Playlist
- Popularitas Playlist: Analisis mengelompokkan lagu berdasarkan nama playlist dan genre untuk menghitung rata-rata popularitas lagu.
### Analisis Berdasarkan Waktu
Analisis tren popularitas berdasarkan tahun rilis dilakukan dengan mengonversi tanggal rilis menjadi tipe datetime dan mengekstrak tahun dari tanggal tersebut. Rata-rata popularitas lagu dihitung berdasarkan tahun rilis dan divisualisasikan untuk menunjukkan tren popularitas seiring waktu.

## Kesimpulan

Analisis ini memberikan wawasan tentang:

1. **Preferensi Genre**: Memahami genre mana yang lebih populer di kalangan pendengar.
2. **Produktivitas vs. Popularitas Artis**: Menganalisis hubungan antara jumlah lagu yang dirilis oleh seorang artis dan popularitasnya.
3. **Tren Seiring Waktu**: Mengamati bagaimana popularitas lagu telah berubah seiring waktu.
4. **Karakteristik Lagu**: Mengidentifikasi karakteristik lagu yang cenderung lebih populer, seperti durasi dan fitur audio.
