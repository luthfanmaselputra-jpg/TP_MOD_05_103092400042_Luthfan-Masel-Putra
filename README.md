1. Bootstrap adalah framework CSS yang digunakan untuk membuat tampilan website menjadi lebih menarik, rapi, dan responsif. Bootstrap menyediakan berbagai class, komponen, dan utility yang mempermudah pengembangan website tanpa harus menulis banyak kode CSS sendiri. Kegunaannya adalah mempercepat pembuatan tampilan website, mempermudah pengaturan tata letak, dan membuat website dapat menyesuaikan ukuran layar perangkat.

2. Ada beberapa cara untuk menggunakan Bootstrap dalam project, yaitu:
   a.  Menggunakan CDN: Menghubungkan file CSS dan JavaScript Bootstrap melalui URL CDN.
   b.  Download Bootstrap: Mengunduh file Bootstrap, kemudian menghubungkannya ke file HTML.
   c.  Menggunakan npm: Memasang Bootstrap melalui package manager npm untuk project berbasis Node.js.
   d.	 Menggunakan package manager lainnya: Memasang Bootstrap melalui pengelola paket yang mendukung Bootstrap.

4. Grid adalah sistem tata letak Bootstrap yang membagi halaman menjadi 12 kolom. Grid menggunakan class seperti .container, .row, dan .col untuk mengatur posisi serta lebar elemen pada halaman website. Breakpoint adalah ukuran lebar layar yang digunakan sebagai batas perubahan tampilan website agar sesuai dengan perangkat yang digunakan.
Contoh breakpoint Bootstrap 5:
Breakpoint	  Ukuran layar
    sm	   ≥     576 px
    md	   ≥     768 px
    lg	   ≥     992 px
    xl	   ≥     1200 px
    xxl	   ≥     1400 px
Dengan grid dan breakpoint, tampilan website dapat menyesuaikan ukuran layar komputer, tablet, maupun ponsel.

5. Berikut lima contoh class Bootstrap beserta kegunaannya.
Class	                 Kegunaan
.container	           Membuat wadah konten dengan lebar responsif.
.row	                 Membuat baris dalam sistem grid.
.col	                 Mengatur kolom dalam grid.
.btn	                 Memberikan tampilan tombol.
.text-center	         Membuat teks rata tengah.
.bg-primary	           Memberikan warna latar biru utama Bootstrap.
.form-control	         Mengatur tampilan input pada formulir.
.shadow	               Memberikan efek bayangan pada elemen.
	
6. Agar gambar pada website dapat menyesuaikan ukuran layar perangkat, gunakan class .img-fluid pada elemen gambar.
Contoh kode:
<img src="gambar.jpg" class="img-fluid" alt="Gambar">
Class .img-fluid memberikan properti max-width: 100% dan height: auto, sehingga gambar tidak melebihi lebar wadahnya dan mempertahankan rasio ukuran aslinya.

7. Tampilan Bootstrap layar besar dan layar kecil
   <img width="959" height="446" alt="image" src="https://github.com/user-attachments/assets/add33656-8c80-45b8-b991-551016c60547" />
   <img width="515" height="444" alt="image" src="https://github.com/user-attachments/assets/141ae828-a06d-4e5b-8d34-3a40f6da6a78" />


   
