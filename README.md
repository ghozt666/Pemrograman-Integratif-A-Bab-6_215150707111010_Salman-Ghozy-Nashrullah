# Pemrograman-Integratif-A-Bab-6_215150707111010_Salman-Ghozy-Nashrullah

<h1>Model, Controller dan Request-
Response Handler</h1>
<h2>Langkah Percobaan</h2>
<h3>Model</h3>
<p>1. Pastikan terdapat tabel <i>users</i> yang dibuat menggunakan <i>migration</i> pada bab
sebelumnya. Berikut informasi kolom yang harus ada</p>
<table border="1">
<tr> 
<td>id</td>
<tr>
<td>createdAt</td>
<tr>
<td>updatedAt</td>
<tr>
<td>name</td>
<tr>
<td>email</td>
<tr>
<td>password</td>
</table>
<br>
<img src="gambar/1.PNG">

<br>
<p>2. Bersihkan isi <i>User.php</i> yang ada sebelumnya dan isi dengan baris kode berikut</p>
<img src="gambar/2.PNG">

<h3>Controller</h3>
<p>1. Buatlah salinan <i>ExampleController.php</i> pada <i>folder app/Http/Controllers</i> dengan
nama <i>HomeController.php</i> dan buatlah fungsi <i>index()</i> yang berisi</p>
<img src="gambar/3.PNG">

<br>
<p>2. Ubah <i>route /</i> pada <i>file routes/web.php</i> menjadi seperti ini</p>
<img src="gambar/4.PNG">

<br>
<p>3. Jalankan aplikasi</p>
<img src="gambar/5.PNG">

<h3>Request Handler</h3>
<p>1. Lakukan <i>import library Request</i> dengan menambahkan baris berikut di bagian atas
<i>file</i></p>
<img src="gambar/6.PNG">

<br>
<p>2. Ubah fungsi <i>index</i> menjadi</p>
<img src="gambar/7.PNG">

<br>
<p>3. Jalankan aplikasi</p>
<img src="gambar/8.PNG">

<h3>Response Handler</h3>
<p>1. Lakukan <i>import library Response</i> dengan menambahkan baris berikut di bagian
atas file</p>
<img src="gambar/9.PNG">

<br>

<p>2. Buatlah fungsi <i>hello()</i> yang berisi</p>
<img src="gambar/10.PNG">

<br>

<p>3. Tambahkan <i>route /hello</i> pada <i>file routes/web.php</i></p>
<img src="gambar/11.PNG">

<br>

<p>4. Jalankan aplikasi pada <i>route /hello</i></p>
<img src="gambar/12.PNG">

<h3>Penerapan</h3>
<p>1. Lakukan <i>import model User</i> dengan menambahkan baris berikut di bagian atas file</p>
<img src="gambar/13.PNG">

<br>

<p>2. Tambahkan ketiga fungsi berikut di <i>HomeController.php</i></p>
<img src="gambar/14.PNG">

<br>
<img src="gambar/14(a).PNG">

<br>

<p>3. Tambahkan ketiga <i>route</i> pada <i>file routes/web.php</i> menggunakan <i>group route</i></p>
<img src="gambar/15.PNG">

<br>

<p>4. Jalankan aplikasi pada <i>route /users/default</i> menggunakan <i>Postman</i></p>
<img src="gambar/16.PNG">

<p>5. Jalankan aplikasi pada <i>route /users/new</i> dengan mengisi <i>body</i> sebagai berikut</p>

<table border="1">
<tr> 
<td>name</td>
<td>Cyno</td>
<tr>
<td>email</td>
<td>cyno@akademiya.ac.id</td>
<tr>
<td>password</td>
<td>mahamatra</td>
</table>

<br>
<img src="gambar/17.PNG">

<p>6. Jalankan aplikasi pada <i>route /users/all</i></p>
<img src="gambar/18.PNG">