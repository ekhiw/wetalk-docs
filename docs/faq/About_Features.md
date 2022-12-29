# FAQ - About Features

### Bagaimana UChat dibandingkan dengan Manychat, Chatfuel, Chatrace, dan platform bot lainnya?
Kami telah menyiapkan perbandingan komprehensif dengan berbagai platform berdasarkan Antarmuka, elemen Chatbot, Pengguna, Pesan, AI & NLP, Saluran, Integrasi, Pemasaran, Penetapan Harga, Analitik, E-niaga, Templat & Kloning, Optimasi & Dukungan, dll.

Sebagian besar data tentang platform lain didasarkan pada ulasan dari chatimize.
https://chatimize.com/chatbot-platform-comparison/

Harap dicatat bahwa beberapa data mungkin kedaluwarsa mengingat lanskap pasar chatbot yang berubah dengan cepat.

Perbandingan hanya untuk referensi Anda, jika Anda menemukan kesalahan atau informasi yang salah, silakan hubungi kami melalui help@uchat.com.au, kami akan melakukan perubahan yang diperlukan.

### Batasan Google Sheets
#### Saya Tidak Bisa Mendapat Baris Lebih dari 5000
Baris yang melebihi 5.000 akan diproses dengan lambat. Jadi kita hanya mengecek data dari baris 1 sampai baris 5000. Mungkin bisa menambahkan data di kolom yang berbeda.

#### Saya Tidak Bisa Membaca / Menulis Data
Google Sheet memiliki batas penggunaan. Silakan periksa https://developers.google.com/sheets/api/reference/limits (membuka jendela baru).

### Zona waktu mana yang menjadi dasar pemilih tanggal, pada langkah pertanyaan?
Saat pengguna memilih waktu, waktu akan didasarkan pada zona waktu di profil mereka terlebih dahulu. Jika mereka tidak memiliki zona waktu di profilnya, zona waktu ruang kerja akan digunakan.

### Gambar tidak muncul
Harap periksa apakah URL gambar tersebut

tautan gambar lengkap dimulai dengan "http"
tautan gambar langsung biasanya diakhiri dengan ".png", ".jpg", dll, yang menunjuk ke gambar alih-alih halaman web, lihat contoh di bawah.

Tombol URL tidak muncul
Jika Anda menggunakan tombol untuk membuka tautan URL, harap pastikan

itu adalah tautan lengkap yang dimulai dengan "http"
tanpa emoji di tautan
tanpa ruang di tautan
uji tautan dari browser Anda untuk memeriksa aksesibilitas

Tombol panggil tidak muncul
Pastikan nomor telepon dalam format yang benar, mis. +61412345678.

### Kartu / untuk-setiap galeri tidak ditampilkan
Kemungkinan alasan:

URL gambar kartu salah atau kosong. lihat FAQ - Gambar tidak ditampilkan.
URL tombol URL salah atau kosong. lihat FAQ - tombol URL tidak muncul.
nomor telepon tombol panggil salah atau kosong. lihat FAQ - Tombol panggil tidak muncul.
kartu melebihi batasan, 10.
Misalnya, saya menggunakan masing-masing untuk menampilkan 10 kartu di galeri. Judulnya adalah ITEM::$.title. Jika salah satu nilai judul dari JSON kosong, ini dapat menyebabkan seluruh galeri tidak ditampilkan. Jadi biasanya Anda dapat menambahkan kata atau emoji tambahan di judul kartu, sub-judul atau tombol seperti Judul: ITEM::$.title yang dapat mengurangi beberapa kesalahan.

Saluran mana yang tidak mendukung GIF?
Google, Instagram, dan WhatsApp.

### Tidak dapat mengirim JSON sebagai nilai saat saya menggunakan API untuk mengubah nilai variabel
Saat Anda menggunakan API untuk mengubah nilai variabel bidang pengguna atau bidang bot, ada parameter yang disebut "nilai", parameter ini hanya menerima string. Jadi tolong gunakan fungsi JSON.stringify untuk mengonversi nilai JSON Anda menjadi string.
