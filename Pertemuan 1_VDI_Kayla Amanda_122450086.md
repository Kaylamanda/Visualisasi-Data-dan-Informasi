**Pendahuluan**

Visualisasi data adalah cara untuk menyajikan informasi data yang kompleks menjadi lebih mudah dipahami oleh manusia yang cenderung berpikir secara visual. Ini sangat efektif untuk memberikan gambaran umum dari data dalam jumlah besar dan membantu ilmuwan data dalam interpretasi hasil analisis.

1. Perkembangan Visualisasi Data
   
Komunitas database telah meningkatkan kemampuan visualisasi data secara real-time untuk pengalaman pengguna yang lebih baik. Alur proses visualisasi data meliputi impor data, persiapan data, manipulasi data, pemetaan, dan rendering.

2. Arah Visualisasi Data
   
Terdapat tiga arah yang membuat visualisasi data lebih efisien dan relevan bagi peneliti database:

    a. Spesifikasi Visualisasi: Pengguna dapat mengatur apa yang ingin mereka visualisasikan.
    
    b. Pendekatan Efisien: Proses pembuatan visualisasi harus cepat, terutama dalam manipulasi data dan pemetaan.
    
    c. Rekomendasi Visualisasi: Sistem dapat memberikan rekomendasi cerdas untuk membantu pengguna.

**Spesifikasi Visualisasi**

Bahasa visualisasi umumnya terdiri dari data, tanda visual, dan pemetaan antar elemen tersebut. Bahasa ini dikategorikan berdasarkan tingkat kemudahan penggunaannya, semakin tinggi tingkatnya, semakin mudah digunakan. Operasi visual berbasis GUI memberikan kemudahan lebih dalam menentukan spesifikasi visualisasi, meskipun alat GUI ini kadang kurang fleksibel dalam penyesuaian detail visualisasi.
Dalam beberapa kasus, pengguna hanya memberikan "petunjuk" awal, dan tugas sistem adalah menafsirkan masukan yang tidak lengkap tersebut. Petunjuk ini bisa berbasis referensi, berbasis kata kunci, atau berbasis bahasa alami.

**Pendekatan Efisien untuk Visualisasi Data**

Dalam beberapa situasi, memberikan visualisasi yang tepat tidak selalu memungkinkan karena ukuran data yang sangat besar dan kompleksitas query yang tinggi.

1. Visualisasi Data yang Tepat
   
Menggunakan pernyataan SQL untuk memanipulasi data, kemudian menghasilkan visualisasi yang sesuai.

a. Terjemahan Query

Menggunakan kembali sistem yang sudah matang dengan menerjemahkan query visualisasi menjadi query SQL.

b. Mengintegrasikan Sistem Visualisasi dengan DBMS

Pendekatan yang menjanjikan adalah dengan mengintegrasikan pengambilan data dan rendering secara ketat.

c. Kolom Penyimpanan

Penyimpanan berbasis kolom menawarkan kinerja yang lebih baik dibandingkan dengan penyimpanan berbasis baris, terutama untuk visualisasi data.

d. Indeks

Membangun indeks berbasis pohon untuk mendukung pemfilteran data secara terus menerus.

e. Komputasi Paralel

Menggunakan komputasi paralel untuk mempercepat query agregasi pada data besar.

f. Prediksi dan Pengambilan Awal

Mempercepat eksplorasi data dengan memprediksi dan mengambil data yang mungkin diperlukan pada langkah berikutnya.

g. Studi Kasus Menggunakan Kyrix dan Tableau

Kyrix dan Tableau adalah dua alat yang digunakan dalam studi kasus untuk menunjukkan bagaimana sistem visualisasi dapat dioptimalkan. TDE dalam Tableau mengoptimalkan penyimpanan data, kompresi, dan efisiensi query.

2. Perkiraan Visualisasi Data
   
Untuk mengatasi tantangan interaktivitas dengan data besar, perkiraan visualisasi dapat dilakukan dengan menggunakan pemrosesan query perkiraan (AQP).

Tiga Pendekatan Perkiraan Visualisasi:

-Berbasis AQP: Menggunakan subset data untuk menghasilkan visualisasi perkiraan dengan cepat.

-Berbasis Pengambilan Sampel Inkremental: Visualisasi dibuat dengan sampel data yang terus meningkat untuk meningkatkan kualitas seiring waktu.

-Berbasis Persepsi Manusia: Menghasilkan visualisasi yang memenuhi batas persepsi manusia, sehingga kualitasnya tetap baik meski dengan pengambilan sampel terbatas.

3. Visualisasi Data Progresif
Membangun struktur hierarki untuk memungkinkan eksplorasi visualisasi secara bertahap dan progresif.

-Binning Berbasis Rentang
Mengubah resolusi visualisasi berdasarkan perubahan ukuran bin.

-Pengelompokan Berbasis Rentang dan Konten
Menyesuaikan algoritma konstruksi pohon agar sesuai dengan preferensi pengguna untuk pengalaman yang lebih baik.

**Rekomendasi Visualisasi**

Rekomendasi visualisasi dapat dilakukan berdasarkan spesifikasi yang tidak lengkap, perilaku pengguna, atau personalisasi berdasarkan preferensi pengguna.

**Arah Penelitian Lainnya**

Fokus lain dalam penelitian visualisasi data termasuk persiapan data, analisis bagaimana-jika, dan tolok ukur visualisasi.
