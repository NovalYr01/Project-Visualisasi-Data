# Project-Visualisasi-Data
Dokumentasi mengenai perancangan dan pengembangan dashboard

Dalam perancangan dan pengembangan dashboard terdapat beberapa step yang dilakukan, yaitu sebagai berikut :
1. Pengumpulan dan pengolahan data
2. Perancangan visualisasi data
3. Perancangan dashboard

## 1. Pengumpulan dan pengolahan Data
  Data yang digunakan dalam perancangan dashboard ini adalah data jumlah kasus penyakit menular menurut jenis penyakit DKI Jakarta pada tahun 2017 – 2020 yang diperoleh dari website [Jakarta Open Data](https://data.jakarta.go.id/).  
  Data yang diperoleh dari website tersebut terdapat 4 file , dimana masing-masing file itu memiliki periode tahun yang berbeda, sehingga file data tersebut di compile agar menjadi 1 file , kemudian melakukan pemodelan data untuk melakukan visualisasi data.  
  Kemudian setelah pengolahan tersebut, data yang akan digunakan untuk perancangan dashboard memiliki 4 variabel. Variabel tersebut terdiri dari tahun, nama wilayah, penyakit dan jumlah kasus, dengan rincian sebagai berikut.
  1. Variabel Tahun  
     Variabel tersebut menjelaskan periode data yang digunakan yaitu dimulai dari tahun 2017 hingga tahun 2020.
  2. Variabel Nama Wilayah  
     Variabel tersebut menjelaskan nama wilayah kota di provinsi DKI Jakarta yang terdiri atas Jakarta Timur, Jakarta Barat, Jakarta Selatan, Jakarta Utara dan Kepulauan   Seribu
  3. Variabel Jenis Penyakit  
     Variabel tersebut menjelaskan jenis penyakit menular yang terdapat di wilayah provinsi DKI Jakarta. Dari data tersebut jenis penyakit tersebut memiliki 18 jenis       penyakit dengan rincian jenis penyakit akan ditampilkan dalam dashboard
  4. Variabel Jumlah Kasus  
     Variabel tersebut menjelaskan jumlah kasus penyakit yang terjadi sesuai dengan jenis penyakit, nama wilayah dan tahun.

 ## 2. Perancangan visualisasi data
  Setelah melakukan pengolahan dan pemodelan data, proses selanjutnya membuat visualisasi data pada database dengan menggunakan bantuan software Tableau Desktop. Langkah awal setelah software tersebut dibuka adalah pemilihan data source, kemudian membuat visualisasi sesuai dengan list dan kebutuhan.Visualisasi tersebut nantinya akan digunakan sebagai rancangan dashboard. Berikut jenis visualisasi yang dirancang untuk membangun dashboard.
  1. *7 Highest Number of Infectious Disease Cases in DKI Jakarta*  
  ![Sheet 1](https://user-images.githubusercontent.com/107663531/174699177-a0a8398c-2ffb-422e-8e61-a5ba8448d834.png)
    Visualisasi data yang pertama dirancang dengan jenis visualisasi yang digunakan adalah bubble chart ditambah dengan color legend di sisi kanan sebagai keterangan untuk bubble chart. Visualisasi tersebut bertujuan untuk menampilkan informasi mengenai 7 jumlah kasus penyakit menular tertinggi di DKI Jakarta.

  2.	*The Evolution of Disease Types by Region*  
  ![Sheet 2](https://user-images.githubusercontent.com/107663531/174699298-8bfa354f-5c1b-48c2-9eab-acb292bd8c7a.png)
    Selanjutnya untuk visualisasi data dirancang dengan jenis visualisasi yang digunakan yaitu line chart  , hal ini dikarenakan jenis    data yang digunakan yaitu data runtun waktu ( time series ). Dimana waktu yang digunakan yaitu tahun , dari tahun 2017-2020. Visualisasi tersebut bertujuan untuk melihat dan mengetahui informasi mengenai evolusi jumlah penyakit berdasarkan wilayah di DKI Jakarta.
    
  3.	*Proportion of Types of Infectious Diseases by Region in DKI Jakarta*  
  ![Sheet 3](https://user-images.githubusercontent.com/107663531/174699368-57a2f659-631d-4c69-85fd-432fb312841a.png)
    Kemudian untuk visualisasi data dirancang dengan jenis visualisasi yang digunakan yaitu bar chart  , hal ini ingin membandingkan nilai antar beberapa kategori untuk menunjukkan nilai terkecil dan terbesar dari suatu data. Visualisasi tersebut bertujuan untuk melihat dan membandingkan proporsi jenis penyakit menular berdasarkan region di DKI Jakarta. 

  4.	*Proportion of Types of Infectious Diseases by Year and Region*  
![Sheet 4](https://user-images.githubusercontent.com/107663531/174700452-5b8bd98a-fd18-445b-bb8e-c936429b0d63.png)
    Dan untuk visualisasi data yang dirancang dengan jenis visualisasi yang digunakan yaitu bar chart  , hal ini ingin membandingkan nilai antar beberapa kategori untuk menunjukkan nilai terkecil dan terbesar dari suatu data. Visualisasi tersebut bertujuan untuk melihat dan membandingkan proporsi jenis penyakit menular berdasarkan region dan tahun di DKI Jakarta.   
  
  Untuk semua visualisasi menggunakan format warna dan tulisan yang sama. Seperti warna latar belakang yaitu warna biru muda dan font tulisan yaitu tableau semibold dengan size sebesar 12px dan warna chart yang digunakan yaitu Brown.

## 3. Perancangan Dashboard
  Setelah melakukan visualisasi, hasil visualisasi tersebut dilanjutkan untuk perancangan dashboard system informasi. Perancangan dashboard terdiri dari 4 visualisasi ditambah dengan keterangan seperti color legend. Pada dashboard tersebut memiliki beberapa format seperti warna background hitam , font style title nya yaitu tableau book dengan ukuran 15 dan font color nya yaitu hijau. Dan terdapat juga filter yang berguna untuk membuat dashboard tersebut menjadi lebih interaktir. Berikut filter yang tersedia.
  1.	Filter Nama Wilayah  
    Filter tersebut digunakan pada visualisasi data yang pertama , kedua dan keempat. Dimana filter tersebut berisi wilayah yang terdapat pada Provinsi DKI Jakarta, yaitu Jakarta Barat, Jakarta Utara, Jakarta Timur, Jakarta Pusat, Jakarta Selatan dan Kepulauan Seribu. Sehingga visualisasi data yang pertama , kedua dan keempat dapat di filter berdasarkan nama kota di Provinsi DKI Jakarta.

  2.	Filter Tahun  
   Kemudian untuk filter tahun, filter tersebut digunakan pada visualisasi data keempat. Dengan pilihan yang disediakan filter yaitu tahun 2017,2018,2019 dan 2020 atau semua tahun. Sehingga visualisasi data tersebut dapat menampilkan chart sesuai tahun yang dipilih.

  3.	Filter Jenis Penyakit  
   Selanjutnya untuk filter jenis penyakit, filter tersebut digunakan padavisualisasi data yang pertama , kedua dan ketiga. Dengan pilihan yang disediakan chart yaitu 18 jenis penyakit menular seperti diare, TB Paru, pneumonia, kusta, malaria dan seterusnya. Sehingga chart tersebut dapat menampilkan informasi yang sesuai dengan filter yang dipilih.  
  
Filter-filter tersebut telah dilakukan penyesuaian agar 1 filter dapat berfungsi untuk beberapa chart dan beberapa filter dapat dikombinasikan untuk menampilkan informasi pada chart yang diinginkan.  

## Kontak

Nauval Yusuf Restigam S - 221910951@stis.ac.id

Project Link: [Dashboard Jenis Penyakit Menular di DKI Jakarta](https://public.tableau.com/views/3SD2-221910951-DashboardJenisPenyakitMenular/Dashboard22?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

<p align="right">(<a href="#top">back to top</a>)</p>


