# Analisis Regresi Poisson, Geographically Weighted Poisson Regression, EDA, dan Analisis Klaster
Analisis ini bertujuan untuk menguji hubungan antara faktor-faktor yang terdiri dari luas taman nasional (dalam hektar), jumlah spesies konservasi, jumlah spesies asing (bukan spesies asli), dan jumlah kelimpahan spesies dengan jumlah keragaman spesies di taman nasional Amerika. Selain itu, juga dilakukan eksplorasi data (EDA) dan analisis klaster terhadap kategori spesies.

# Deskripsi Data
Data yang digunakan dalam analisis ini terdiri dari variabel-variabel berikut:

* Luas taman nasional: variabel numerik yang menunjukkan luas taman nasional dalam hektar.
* Jumlah spesies konservasi: variabel numerik yang menggambarkan jumlah spesies konservasi yang ada di taman nasional.
* Jumlah spesies asing: variabel numerik yang mewakili jumlah spesies asing (bukan spesies asli) di taman nasional.
* Jumlah kelimpahan spesies: variabel numerik yang mengindikasikan jumlah kelimpahan spesies di taman nasional.
* Kategori spesies: variabel kategorikal yang mengelompokkan spesies ke dalam kategori tertentu, seperti mammalia, aves, reptilia, dan lainnya.
* Jumlah spesise: variabel numerik yang menggambarkan jumlah spesies yang ada di taman nasional

# Metode Analisis
* Eksplorasi Data (EDA): Melakukan eksplorasi data untuk memahami karakteristik, distribusi, dan hubungan antara variabel-variabel yang ada. Dilakukan visualisasi data, statistik deskriptif, dan analisis univariat serta bivariat.
* Regresi Poisson: Dilakukan analisis regresi Poisson untuk menguji hubungan antara faktor-faktor yang disebutkan sebelumnya dengan jumlah keragaman spesies di taman nasional. Regresi Poisson digunakan karena variabel respons (jumlah keragaman spesies) adalah variabel diskrit dan dapat dianggap sebagai distribusi Poisson.
* Geographically Weighted Poisson Regression (GWPR): Selanjutnya, dilakukan analisis GWPR untuk memperhitungkan adanya variasi spasial dalam hubungan tersebut. GWPR memperhitungkan kemungkinan terjadinya pola spasial dan memodelkannya secara lokal di setiap lokasi pengamatan.
* Analisis Klaster: Dilakukan analisis klaster terhadap kategori spesies, seperti mammalia, aves, reptilia, dan lainnya, untuk mengidentifikasi pola kelompok yang ada dalam data berdasarkan karakteristik spesies.

Lomba TECHFEST Big Data Competition (Tim SERRRRRRR)
