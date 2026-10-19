1. Pengertian Bootstrap 
Bootstrap adalah framework CSS yang digunakan untuk mempermudah pembuatan tampilan website agar lebih menarik, rapi, dan responsif.
 Bootstrap menyediakan berbagai komponen dan class siap pakai, seperti tombol, navbar, form, tabel, dan sistem grid,
 sehingga developer tidak perlu membuat semua desain dari awal.

 2. Memasang Bootstrap 
Ada beberapa cara untuk menggunakan Bootstrap pada project website, yaitu:
1. Menggunakan CDN, yaitu menghubungkan file CSS dan JavaScript Bootstrap melalui link dari internet.
2. Download Bootstrap, yaitu mengunduh file Bootstrap dan menyimpannya di dalam folder project.
3. Menggunakan package manager, seperti NPM, untuk memasang Bootstrap pada project.
4. Menggunakan framework atau build tools, seperti Vite, dengan mengimpor Bootstrap melalui file JavaScript atau CSS.

 3. Grid dan Breakpoint 
Grid Bootstrap adalah sistem tata letak yang membagi halaman menjadi 12 kolom untuk mengatur posisi dan ukuran elemen website.
Grid biasanya menggunakan class container, row, dan col. Breakpoint adalah batas ukuran layar yang digunakan untuk menyesuaikan
tampilan website berdasarkan perangkat. Contohnya, sm, md, lg, xl, dan xxl. Dengan grid dan breakpoint, tampilan website dapat menyesuaikan
ukuran layar komputer, tablet, maupun HP.

4. Class Bootstrap 
Berikut beberapa class Bootstrap beserta kegunaannya:
Class Bootstrap	
container : Mengatur lebar dan posisi konten website.
row :	Membuat baris pada sistem grid.
col :	Membagi kolom untuk mengatur tata letak konten.
text-center :	Membuat teks rata tengah.
bg-success :	Memberikan warna latar belakang hijau.
btn btn-primary :	Membuat tombol berwarna biru.
form-control :	Mengatur tampilan input pada form.
img-fluid :	Membuat gambar menjadi responsif.

5. Gambar Responsif
Agar gambar pada website responsif dan menyesuaikan ukuran layar perangkat,
kita dapat menggunakan class img-fluid dari Bootstrap. Class ini membuat gambar memiliki lebar maksimal 100%
dari elemen induknya dan tinggi otomatis mengikuti proporsi gambar.
CONTOH KODE :
(<img src="gambar.jpg" class="img-fluid" alt="Gambar">)
Dengan menggunakan class img-fluid, gambar tidak akan melebihi lebar wadahnya sehingga tampilannya lebih sesuai pada layar komputer, tablet, maupun HP.
