# API

## Pengantar API
UChat API digunakan untuk mengambil data dari flow yang Anda bangun. Berikut adalah beberapa contoh yang dapat Anda lakukan dengan UChat API.

Tarik aliran yang telah Anda bangun dari uchat.
Buat, hapus, atau dapatkan data termasuk tag aliran, bidang aliran.
Berurusan dengan data tentang pelanggan, termasuk mendapatkan informasi pelanggan, mengedit tag atau kolom mereka serta subflow yang dikirimkan ke pelanggan.
Konfigurasikan semua data yang digunakan dalam e-niaga seperti gerobak atau produk.
Jika Anda perlu menangani data di bawah ini, bagian selanjutnya akan memperkenalkan langkah-langkah untuk menggunakan UChat API.

## Mengizinkan
Karena perlindungan data penting bagi API, API perlu menggunakan beberapa atribut untuk mengesahkan identitas Anda. Oleh karena itu, langkah pertama yang harus Anda lakukan adalah memasukkan informasi resmi. Anda perlu mengklik tombol Otorisasi, seperti yang ditunjukkan gambar berikut.

[gambar]

Lalu, ada tiga atribut yang perlu Anda isi pada textbox.

[gambar]

Berikut adalah cara untuk menemukan atribut ini di bagian berikut.

#Buat Kunci API (http, Pembawa)
Langkah 1 Setelah Anda login akun di UChat, di pojok kanan atas, akan muncul nama akun dan avatar Anda. Klik dan pilih Pengaturan Anda di daftar dropdown.

[gambar]

Langkah 2 Buka Bagian Kunci API dengan mengklik tombol di Pengaturan Pengguna. Masukkan nama kunci yang ingin Anda atur dan klik tombol Buat.

[gambar]

Langkah 3 Kemudian Anda akan mendapatkan kunci di jendela pop-up.

[gambar]

Tutup jendela Anda akan mendapatkan informasi dasar tentang kunci kecuali nilai kunci.

## Dapatkan Curl dan Minta URL
Curl digunakan dalam permintaan API. Dalam dokumentasi uchat API, Anda memerlukan beberapa operasi sebelum mendapatkan ikal di dokumentasi uchat api.

Di sini, kami menggunakan Get Flow Tag sebagai contoh.

[gambar]

Langkah 1. Klik operasi luaskan kategori, Tag Aliran dalam kasus ini. Kemudian temukan action dan fiturnya, Get /flow/tags. Klik baris dan halaman akan dropdown ditampilkan sebagai berikut.

[gambar]

Langkah 2. Logo ini berarti otorisasi. Jika Anda telah melakukan ini sebelumnya, langkah ini tidak diperlukan. Atau, Anda cukup melakukan hal yang sama seperti yang disebutkan sebelumnya di bagian Otorisasi.

Langkah 3. Klik Coba. Kemudian Anda akan melihat bahwa bagian tubuh Parameter atau Permintaan dapat dimasukkan dan Tombol Exexute ditampilkan di bagian bawah bagian ini.

[gambar]

Langkah 4. Masukkan parameter atau badan permintaan yang diperlukan dan klik Tombol Exexute. Akhirnya Anda akan mendapatkan Curl dan Request URL.

[gambar]

## Tanggapan
Bagian ini menampilkan hasil Json yang akan Anda dapatkan dari uchat API. Biasanya jika kodenya 200, itu berarti Anda berhasil mendapatkan respons. Jika kodenya 400, berarti ada kesalahan dalam respons Anda.

[gambar]

## Contoh Nilai / Skema

[gambar]

Selain nilai contoh, Anda dapat mengklik "Skema" untuk melihat detail lebih lanjut seperti nilai mana yang wajib.

[gambar]
