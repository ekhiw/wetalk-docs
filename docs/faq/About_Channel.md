# FAQ - About Channels

### Tidak dapat menghubungkan halaman Facebook / Instagram

#### Apakah halaman Facebook Anda telah dipublikasikan?
Hanya halaman Facebook yang dipublikasikan yang dapat dilihat dan dihubungkan untuk membangun chatbots.

#### Pernahkah Anda menghubungkan halaman ini ke ruang kerja lain sebelumnya?
Di UChat, jika Anda telah menghubungkan halaman Anda ke ruang kerja, Anda tidak akan dapat melihat atau menghubungkannya ke ruang kerja lain. Putuskan sambungan halaman, dan sambungkan kembali ke ruang kerja baru.

#### Apakah Anda menghubungkan ruang kerja Anda dengan banyak pengguna Facebook?
- Pertama-tama, satu ruang kerja hanya dapat terhubung ke satu pengguna Facebook. Anda dapat diundang untuk menjadi admin di banyak halaman dan membuat bot untuk halaman tersebut.
- Pembatasan sedang dalam pengembangan sebelumnya (sebelum 22/11/2021) itulah sebabnya Anda mungkin dapat menghubungkan ruang kerja Anda dengan beberapa pengguna Facebook. Ini masalah kami, untuk menebusnya, kami akan menyimpan semua koneksi lama Anda karena bot Anda sudah digunakan.
- Last but not least, bagaimana Anda bisa menambahkan halaman baru ke ruang kerja Anda mulai sekarang?
Anda dapat membuat pengguna Facebook pertama yang terhubung menambahkan halaman baru untuk ruang kerja ini.
Anda dapat menghapus semua koneksi, menghubungkannya kembali dengan pengguna Facebook baru.

#### Daftar centang untuk bot Instagram tidak muncul
1. Apakah akun Instagram ini merupakan akun Instagram Bisnis?
2. Apakah Anda menghubungkan akun Instagram ini dengan halaman Facebook?
3. Sudahkah Anda mengaktifkan "izinkan akses ke pesan" di akun Instagram?
4. Apakah Anda memilih Instagram dan halaman Facebook yang sesuai saat terhubung dengan UChat?
Untuk cara melakukan 4 langkah di atas, lihat cara mengatur bot Instagram.

### Apakah saluran Google memiliki kotak masuk seperti Facebook Messenger?
Ya, tetapi jika Anda menggunakan otomatisasi bot, kotak masuk Google akan dinonaktifkan dan sebaliknya.

### WhatsApp/360Dialog: Mengapa URL foto dari bot WhatsApp menunjukkan "Tidak Ditemukan"?
Jika Anda menggunakan kotak pasir 360Dialog, penguji kotak pasir memiliki batasan untuk mengakses medianya.

### Saat menyinkronkan bisnis Google, muncul "nama bisnis terlalu panjang".
Panjang maksimum nama bisnis adalah 100 karakter.

### Alat pertumbuhan komentar Facebook tidak berfungsi
Kemungkinan alasan:
1. Apakah Anda memberikan izin komentar ketika Anda menghubungkan halaman Facebook Anda?
2. Tidak akan berhasil jika Anda berkomentar dengan menggunakan profil halaman Anda, Anda perlu berkomentar dengan menggunakan profil pengguna.
3. Apakah Anda secara tidak sengaja mencentang "balas hanya sekali untuk setiap pengguna di setiap posting"?
4. Di sub alur balasan, Anda hanya dapat mengirim 1 pesan dengan tombol atau balasan cepat. Jangan tambahkan apa pun sebelum blok itu. Tetap sederhana.

### Dapatkah saya memutar audio untuk pertanyaan di bot Suara?
Ya, silakan periksa cara memutar audio pada langkah yang dimaksud.

### Batasan plugin obrolan pelanggan Facebook
Saat pengguna berbicara dengan bot Anda melalui plugin obrolan pelanggan, widget obrolan di situs web Anda (lihat tangkapan layar di bawah), Facebook hanya mengirimkan "user_ref" pengguna kepada kami daripada "user_id". Kami tidak dapat mengetahui "user_ref" mana yang terhubung dengan "user_id" mana, jadi kami harus membuat profil baru lagi ketika ref atau id baru masuk.

Ini terkadang dapat mengakibatkan satu pengguna memiliki 2 profil di UChat.

### Untuk mengurangi latensi, bisakah saya mengunggah semua file audio saya di bot suara UChat?
Ya, Anda dapat mengunggah file audio di UChat. Namun, latensi tidak akan berkurang, bahkan mungkin bertambah.

Ini karena, saat Anda mengunggah audio di UChat, kami masih perlu membuat URL untuk file ini dan mengirimkannya ke penyedia nomor telepon Anda, mis. Twilio. Ini Twilio menggunakan file, bukan UChat. Jadi pada dasarnya latensi tidak akan berkurang.

Mungkin ada lebih banyak latensi ketika UChat mengelola lebih banyak file audio untuk banyak bot. Jadi kami menyarankan pengguna menyimpan file di tempat lain.

### Kesalahan mengirim muatan: 2534040 (#613) Batas tarif telah terlampaui. Coba lagi setelah beberapa saat
Facebook dan Instagram memiliki batasan rate sesuai dengan jumlah followers. Kesalahan ini terjadi ketika jumlah pengikut Anda melonjak dalam waktu singkat. Facebook akan menyesuaikan batas tarif Anda setelah beberapa saat.
