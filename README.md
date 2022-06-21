<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Best-README-Template</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Tentang Project UAS Visdat Ini
Indeks Pemabangunann Manusia (IPM) memiliki 3 dimensi dasar yaitu dimensi umur panjang dan hidup sehat, dimensi pengetahuan, serta dimensi standar hidup layak. Pada penelitian kali ini akan divisualisasikan salah satu dimensi IPM yaitu dimensi pengetahuan beserta variabel variabel lain yang mendukung dimensi pengetahuan tersebut. Variabel tersebut antara lain yaitu Angka Partisipasi Murni (APM), Angka Partisipasi Kasar (APK), dan Angka Partisipasi Sekolah (APS). Penelitian memiliki cakupan wilayah Kota Padang, Sumatera Barat mulai dari tahun 2012 hingga tahun 2021. Visualiasi yang sudah dibuat dari data kemudian akan dibuat dashboard sehingga informasi yang akan disampaikan akan tersampaikan dengan mudah.

<p align="right">(<a href="#top">back to top</a>)</p>

### Alat dan Sumber Data

1. Alat
   * Tableau
   * Ms. Excel
2. Sumber Data
   * [Badan Pusat Statistik](https://bps.go.id)
   * [Kemendikbud] (https://dapo.kemdikbud.go.id/sp/2/086100)
   * Dinas Pendidikan Kota Padang

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Tahapan Perancangan Dashboard

### Pengumpulan Data
Penelitian ini menggunakan data Rata-rata Lama Sekolah (RLS), Harapan Lama Sekolah (HLS), Angka Partisipasi Murni (APM), Angka Partisipasi Kasar (APK), dan Angka Partisipasi Sekolah (APS) untuk tahun 2012 hingga tahun 2021 di Kota Padang yang diambil dari website Badan Pusat Statistik Kota Padang. Data lain yang digunakan yaitu jumlah sekolah per kecamatan di Kota Padang yang didapatkan dari website kemendikbud. Serta data jumlah pengajar, jumlah siswa, jumlah sekolah di Kota Padang yang didapatkan dari Dinas Pendidikan Kota Padang.

### Penyiapan Data
Data yang telah dikumpulkan tadi akan disusun dan dikelompokkan berdasar variabel penyusunnya dan dimasukkan pada sheet yang sama pada Microsoft Excel. Data yang digunakan hanya untuk Kota Padang. Setelah itu dilakukan visualisasi data yang telah dikelompokkan tadi menggunakan aplikasi Tableau Desktop.


<p align="right">(<a href="#top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
### Visualisasi Data
Data yang sudah disiapkan kemudian diolah menggunakan Tableau sebagai berikut.
1. Stacked Barchart
   <img width="891" alt="Screen Shot 2022-06-21 at 11 36 50" src="https://user-images.githubusercontent.com/107905968/174717105-977960de-571c-473b-9acb-6ffeb7f71322.png">
2. Linechart
   <img width="891" alt="Screen Shot 2022-06-21 at 11 36 26" src="https://user-images.githubusercontent.com/107905968/174717052-c2a5396e-0072-45eb-9e4a-fb67af77eb12.png">
3. Multiple Linechart
   <img width="891" alt="Screen Shot 2022-06-21 at 11 36 38" src="https://user-images.githubusercontent.com/107905968/174717072-2512379c-29ab-4467-95ef-577934a73416.png">
4. Peta
   <img width="891" alt="Screen Shot 2022-06-21 at 11 36 12" src="https://user-images.githubusercontent.com/107905968/174717024-c4c45a4d-ddd6-4993-a7bd-7fd8e81b81a2.png">
5. Piechart
   <img width="702" alt="Screen Shot 2022-06-21 at 11 37 16" src="https://user-images.githubusercontent.com/107905968/174717167-b76be739-8f6e-45e9-9046-1be4bbdbc4e4.png">
<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->
### Pembuatan Dashboard
Semua visualisasi tadi digabungkan dalam bentuk dashboard sebagai berikut.
![Screen Shot 2022-06-21 at 11 39 52](https://user-images.githubusercontent.com/107905968/174717422-a088e3cb-f0e2-4afa-a5ff-e0c0ca83d47e.png)

Dashboard tersebut dapat diakses pada [link] (https://public.tableau.com/app/profile/hafizh.eka/viz/ProjectVisdat/Dashboard1?publish=yes)

<p align="right">(<a href="#top">back to top</a>)</p>




<!-- CONTACT -->
## Contact

Muhammad Hafizh Eka Putra - [@hafizhekaa](https://www.instagram.com/hafizhekaa/) - 221911048@stis.ac.id

Project Link: [https://github.com/hafizhekaa/ProjectVisdat](https://github.com/hafizhekaa/ProjectVisdat)

<p align="right">(<a href="#top">back to top</a>)</p>



