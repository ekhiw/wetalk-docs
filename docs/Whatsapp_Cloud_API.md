# WhatsApp Cloud API
WhatsApp Cloud API tersedia untuk semua bisnis.

[gambar]

Panduan ini akan mengajarkan Anda bagaimana menggunakan WhatsApp cloud API dengan Wetalk. 

Berikut adalah video tentang cara membuat bot WhatsApp pertama Anda dengan Cloud API

[video]

[video]

Sekarang, mari kita mulai dengan membuat Facebook Anda sendiri.

## Set Up Facebook Anda

Pertama, Anda perlu mendaftar sebagai meta developer, lalu mengaktifkan autentikasi dua faktor untuk akun Anda.

Dan kemudian Anda dapat mengklik "Create a New App" dari kanan atas dashboard Anda, lalu pilih "Business" sebagai jenis aplikasi:

[gambar]

Kemudian masukkan nama, dan tambahkan email, jika Anda ingin menghubungkan aplikasi ini ke salah satu akun bisnis Anda, Anda dapat mengklik drop-down untuk menghubungkannya.

[gambar]

Setelah itu, Anda pilih WhatsApp, lalu klik "Set Up" di  WhatsApp.

[gambar]

Dan kemudian Anda akan diarahkan ke sini, seperti gambar di bawah ini:

[gambar]

Sekarang, Anda dapat mengklik "Get Started" di bawah WhatsApp, dan kemudian Anda akan tampil seperti gambar di bawah ini:

[gambar]

Pilih akun bisnis yang memiliki nomor telepon yang ingin Anda gunakan untuk otomatisasi WhatsApp. Jika Anda tidak memiliki akun bisnis, Facebook akan secara otomatis membuatkannya untuk Anda.

Maka Anda perlu mengklik "configuration" untuk menyiapkan webhook Anda sendiri.

[gambar]

## Dapatkan Webhook Anda dari Wetalk

Sekarang, Anda ke Wetalk, lalu pilih WhatsApp cloud, klik “Connect WhatsApp Cloud”

[gambar]

Setelah Anda mengklik tombol tersebut, akan muncul halaman untuk mengotorisasi akun Facebook Anda, lalu pilih akun bisnis yang ingin Anda sambungkan.

Anda dapat menghubungkan satu akun bisnis di bawah satu workspace. Beberapa nomor dapat dihubungkan ke akun bisnis yang sama.

[gambar]

Setelah Anda memilih akun bisnis Anda, Anda bisa kembali ke Wetalk. Dan kemudian setelah Anda mengklik "List Business with WhatsApp Phone Number"

Ini akan mencantumkan semua nomor WhatsApp di akun bisnis ini. Anda dapat mengklik tombol "Select" untuk langkah berikutnya.

[gambar]

Kemudian Anda akan melihat URL dan token Webhook Anda untuk digunakan pada langkah berikutnya.

Sekarang Anda dapat kembali ke akun Facebook Developer Anda, lalu klik "Edit" di konfigurasi seperti gambar di bawah ini:

[gambar]

Di halaman pop-up, memindai URL dan token webhook Anda dari Wetalk.

[gambar]

Dan kemudian klik "verify & save".

Setelah Anda menambahkan URL webhook, sekarang Anda perlu mengklik "Manage" di bawah kolom Webhook.

[gambar]
Anda harus berlangganan "Message" sesuai gambar di bawah ini:

[gambar]

Sekarang, Anda dapat membuka Wetalk, dan menyinkronkan nomor & memilih nomor untuk membuat chatbot Anda.

Harap dicatat, Anda dapat dengan mudah mengetes dengan nomor yang telah Anda gunakan.

## Mulai dengan “Test Numbers”

Test Numbers dapat melakukan percakapan gratis tanpa batas dengan nomor telepon yang sudah terverifikasi. Anda harus terlebih dahulu memverifikasi nomor telepon Anda. Anda dapat melakukannya dengan mengklik "Add the phone number" di bawah ini:

[gambar]

Dan kemudian Anda perlu memverifikasi nomor telepon ini dengan menerima SMS dari Facebook.

[gambar]

Setelah nomor telepon Anda diverifikasi, Anda dapat mengirim pesan teks, dan preview chatbot yang Anda buat dengan “test numbers” ini.

## Bangun Chatbot dengan Mengetes nomor WhatsApp

Di Wetalk, jika Anda menyinkronkan nomor, seperti gambar di bawah, dan memilih test numbers yang ditawarkan dari Facebook, Anda dapat mulai membuat chatbot pertama Anda.

[gambar]

Dan kemudian konfirmasikan pilihan.

[gambar]

Dan kemudian Anda dapat membuat chatbot untuk mengetes koneksi.

[gambar]

Dan Anda dapat membuat flow sederhana seperti di bawah ini untuk mengetes “send message & question block”.

[gambar]

Setelah Anda membuat flow sederhana ini, klik "Preview" lalu pilih "Open in WhatsApp", dan mengetes apakah chatbot merespons atau tidak.

[gambar]

Dan kemudian Anda ikuti petunjuknya, dan melihat apakah WhatsApp ini berfungsi dengan baik atau tidak.

Anda dapat membangun otomatisasi Anda dengan test numbers, dan setelah semua di test, jika Anda siap untuk membangun chatbot Anda, Anda dapat mengikuti panduan di bawah ini.

Jika Anda tidak menerima pesan, mungkin Anda belum menambahkan nomor telepon Anda ke nomor telepon terverifikasi di akun Facebook Anda.

Untuk nomor telepon “percobaan”, Anda dapat mengirim pesan tanpa batas, tetapi hanya untuk nomor telepon yang sudah terverifikasi yang Anda tambahkan.

## Mendukung berbagai jenis pesan

## Jenis pesan “regular”

Wetalk mendukung Anda untuk mengirim teks biasa, teks + button, file, audio, gambar, dan juga card di WhatsApp.

WhatsApp Cloud API dapat berbagi berbagai macam elements, Anda dapat menonton video dibawah ini untuk mengetahui lebih lengkapnya.

[video]

[video]

Semua jenis pesan ini juga disupport di Cloud API.

## Template message

Template message harus dikirimkan untuk meminta persetujuan Facebook sebelum digunakan. Facebook lah yang akan preview setiap template untuk menghindari spam dan untuk mengecek apakah setiap pesan mematuhi aturan dari WhatsApp API.

Berikut adalah video yang menunjukkan cara menggunakan template message, Anda dapat menontonnya di sini:

[video]

Kapan dapat menggunakan template untuk di WhatsApp?
Template message dapat dikirim setiap kali berada di luar jam kerja “Customer Service”, yang berarti, jika lebih dari 24 jam sejak customer mengirimkan pesan terakhir mereka ke nomor telepon tersebut.

Anda dapat menggunakan template message untuk mengirim pemberitahuan.

Template menggunakan model placeholder yang dapat diganti sesuai kebutuhan Anda. Anda hanya perlu pikirkan bagaimana template message sebagai yang sesuai sebagai “greetings”.

## Cara agar Template Message Anda disetujui

Berikut adalah beberapa tips untuk mendapatkan template message Anda melalui proses preview:

Kejelasan: spesifik dan jelas. Hal ini untuk mengetahui bisnis Anda dan membutuhkan kejelasan lebih lanjut. Hindari promosi: upselling, cold-call messaging, mengarahkan customer untuk mengisi polling dengan tujuan untuk mengumpulkan data, dan menyertakan frasa tertentu yang terdengar promosi semuanya dianggap promosi.

Ejaan: Anda perlu memeriksa kembali ejaan dan tata bahasa dan gunakan pemformatan yang sesuai.

Nama: perjelas nama template message Anda. Daripada menggunakan nama seperti template_014, gunakan Anda bisa beri nama seperti tiket_bus_sby. Perlu And ingat bahwa pihak dari Facebook akan preview bagaimana template message Anda. Jadi, Anda harus memberikan lebih banyak kejelasan agar mudah di setujui.

Buat konteks: jika Anda ingin membuat template message untuk dibuka kembali setelah 24 jam oleh customer Anda, kami sarankan Anda untuk menyebutkan kembali percakapan sebelumnya. 

Pilih kategori yang sesuai: jangan lupa untuk menggunakan jenis template message yang tepat dan sesuai. 

## Berbagai kategori template message

Pembaruan akun: Beritahu customer tentang pembaruan atau perubahan pada akun mereka. Anda dapat menggunakan ini untuk memberitahu customer Anda tentang perubahan pada pengaturan akun mereka.

Preferensi diperbarui
Pengaturan telah berubah
Membership telah berakhir
Profil telah berubah

Update peringatan: Kirim update atau berita penting ke customer.

Appointment update: Kirim konfirmasi, reminder, atau update lainnya kepada customer tentang appointment. Sebagai contoh:

Perubahan appointment
Perubahan lokasi
Janji yang dibatalkan

Balasan Otomatis: Kirim balasan secara otomatis ke customer Anda kapanpun.

Penyelesaian masalah: Menanggapi pertanyaan, kekhawatiran, atau feedback dari customer Anda tentang bisnis Anda. Sebagai contoh:

Masalah teratasi
Status masalah diperbarui
Masalah memerlukan informasi tambahan
Beri tahu customer Anda tentang sesuatu yang informatif seperti ketersediaan jam kerja/jam 

Kata Sandi Sekali Pakai: Kirim kode verifikasi yang dibuat secara otomatis sehingga customer Anda dapat mengakses akun mereka dengan aman.

Update pembayaran: Dapat mengirim pesan ke customer Anda tentang pembayaran mereka. Sebagai contoh:

Kirim pemberitahuan kehabisan stok
Beri tahu lelang telah berakhir
Status transaksi pembayaran telah berubah
Kirim tanda terima

Update Keuangan Pribadi: Dapat mengirim pesan kepada customer Anda tentang keuangan pribadi mereka. Sebagai contoh:

Reminder pembayaran tagihan
Reminder pembayaran yang sudah terjadwalkan
Notifikasi tanda terima pembayaran
Konfirmasi transfer dana atau update
Kegiatan transaksional lainnya di bidang jasa keuangan

Update reservasi: Kirim konfirmasi, reminder, atau update lainnya kepada customer Anda tentang reservasi mereka. Sebagai contoh:

Perubahan lokasi
Pembatalan dikonfirmasi
Pemesanan hotel dibatalkan
Perubahan waktu penjemputan rental mobil
Upgrade kamar dikonfirmasi
Perubahan rencana perjalanan

Update pengiriman: Kirim update pengiriman ke customer Anda tentang pesanan mereka. Sebagai contoh:

Produk dikirim
Perubahan status menjadi transit
Produk terkirim
Pengiriman tertunda

Update tiket: Kirim update pengiriman ke customer Anda tentang pesanan mereka. Sebagai contoh:

Perubahan waktu mulai konser
Perubahan lokasi acara
Pertunjukan dibatalkan
Pengembalian dana tersedia

Update transportasi: Kirim pembaruan pengiriman ke pelanggan tentang pesanan mereka. Sebagai contoh:

Perubahan status penerbangan
Perjalanan dibatalkan
Perjalanan dimulai
Telah tiba

Jika Anda tidak memiliki kategori khusus, maka Anda dapat memilih template message untuk balasan otomatis.

[gambar]

## Membangun Bagian untuk Template Message 

Template untuk media memiliki lebih banyak fitur, dan beberapa bagian sebagai berikut:

Header: Header bersifat opsional dan berfungsi sebagai judul atau header template Anda. Di bagian header terdapat: teks, gambar, dokumen & video

Isi/Body: Di bagian ini harus berisi teks paling penting dari template Anda. Hanya teks saja yang didukung.

Footer: Footer hanya mendukung teks dan dapat digunakan untuk memberikan informasi yang kurang relevan dalam template message Anda

Tombol/Button: Tombol untuk menambahkan interaktivitas ke template Anda. Ada dua tipe utama.

Quick reply button: Digunakan untuk mendapatkan jawaban cepat dari customer Anda, max 3 quick reply button per template

Tombol Call to Action (CTA): Maksimal satu URL dan nomor telepon per template.

## Buat template message

Di bagian ini, Anda harus masuk ke akun WhatsApp Business Manager Anda. Pilih Business Manager Account dari drop-down jika ada, lalu pilih "template message"

Anda harus menggunakan nomor telepon asli yang baru untuk membuat template message baru.

[gambar]

Dan setelah Anda mengklik "Create Template Message" dari sudut kanan atas dashboard.

Anda perlu mengisi nama template dan memilih kategori pesan dan bahasa.

Buat template standar (hanya teks):

[gambar]

Di bawah ini adalah template message yang kami buat, dan setelah Anda membuat template, lalu kirimkan ke Facebook untuk di preview.

Setelah template message disetujui, Anda akan melihat ikon yang disetujui di bawah.

[gambar]

Sekarang Anda dapat kembali ke Wetalk, dan pergi ke channel WhatsApp,

[gambar]

Setelah Anda masuk ke konten, dan template message, dan klik "Sinkronkan Template WhatsApp", Anda seharusnya dapat melihat bahwa semua template yang disetujui akan disinkronkan kembali ke Wetalk untuk digunakan.

## Cara menggunakan Template Message

## Gunakan dalam flow builder

Template Message menawarkan lebih banyak fitur, seperti tombol yang dapat disambungkan ke URL eksternal & tombol panggilan telepon.

Anda dapat mengirim template message langsung di flow. 

Cara kirim pesan, pilih "Template pesan", dan jika Anda memiliki variabel dalam template message, Anda dapat memilih custom field di Wetalk.

[gambar]

[gambar]

## Gunakan dalam siaran

Anda juga dapat menggunakan template message di fitur broadcast Wetalk.

Mari pertama-tama buat flow yang ingin Anda broadcast. Anda dapat memeriksa kembali untuk memutuskan apakah Anda ingin menggunakan template message atau tidak.

[gambar]

Dalam contoh flow diatas, pertama-tama kita menggunakan kondisi untuk memeriksa apakah customer Anda masih dalam ada dalam periode 24 jam, jika ya, Anda dapat menghubungi mereka secara gratis.

Dan kemudian Anda juga dapat memilih untuk mengirimi mereka email jika Anda memiliki alamat email mereka.

Terakhir, Anda dapat memilih untuk mengirim template message yang sudah Anda buat sebelumnya kepada mereka.

Setelah Anda menyiapkan flow untuk digunakan dalam broadcast, kini Anda dapat membuka siaran dan memilih pemirsa yang Anda inginkan, lalu mengirimkan alur yang baru saja Anda buat.

[gambar]

## Gunakan dalam Live Chat

Dalam Live Chat, jika customer Anda berada di luar waktu 24 jam, Anda hanya dapat mengirimkan pesan dengan template message.

Jika Anda masuk ke dalam Live Chat, Anda akan melihat opsi "Saya ingin mengirim pesan template" atau “I want to send Template Message”.

[gambar]

Perhatikan bahwa template hanya akan dikirim jika ini adalah pesan pertama dalam subflow.

Kemudian Anda dapat menggunakan subflow untuk memulai template message.

## Gunakan di aplikasi seluler Wetalk

Setelah Anda mulai menggunakan WhatsApp Business API, Anda tidak akan dapat menggunakan nomor tersebut di WhatsApp Business atau WhatsApp pribadi Anda.

## WhatsApp Native Ecommerce - Pesan katalog produk

Anda dapat menampilkan berbagai produk dan layanan Anda dengan customer Anda agar mereka dapat melihat-lihat item dan memasukkan “keranjang” tanpa meninggalkan obrolan.

Berikut adalah beberapa video yang dapat Anda tonton:

Demo checkout eCommerce WhatsApp:

[video]

Chatbot eCommerce WhatsApp:

[video]

Chatbot eCommerce WhatsApp:

[video]

[gambar]

Namun setelah jenis pesan ini didukung, Anda juga dapat membangun “pengalaman” belanja di e-commerce yang menyenangkan dengan WhatsApp Cloud API.

Untuk saat ini, Anda juga dapat menggunakan integrasi 360Dialog.

Untuk menggunakan produk dan katalog di akun WhatsApp Business API Anda, silakan ikuti langkah-langkah selanjutnya.

## Buat katalog produk & upload inventory ke Facebook

Pertama, Anda perlu mengunggah inventaris Anda ke Facebook. Anda dapat menggunakan API atau Manajer Perdagangan Facebook untuk melakukannya.

Inventaris Anda perlu diunggah ke Facebook dalam format katalog — lihat Tentang Katalog (membuka jendela baru) untuk informasi lebih lanjut.

Jika Anda sudah menyiapkan katalog Facebook, kami sarankan Anda memanfaatkan katalog itu untuk kasus penggunaan perdagangan WhatsApp.

Jika Anda perlu membuat katalog, ada dua kemungkinan:

Buat katalog menggunakan API(membuka jendela baru)
Buat katalog menggunakan Commerce Manager(opens new window)
Anda hanya dapat mengunggah satu katalog per Akun WhatsApp Business (WABA), tetapi katalog yang sama dapat dimiliki oleh beberapa nomor telepon.

Anda dapat menonton videonya di sini:

[video]

[video]

Persyaratan khusus untuk penjualan di India Jika Anda menjual di India, Anda harus mematuhi persyaratan Facebook terkait katalog produk, lebih jelasnya, Anda dapat mengetahuinya di video di bawah ini:
[video]

Sinkronkan produk dari Facebook ke UChat Sekarang kembali ke UChat, buka saluran WhatsApp Cloud, Anda dapat mengklik "Lihat Katalog", dan kemudian akan menarik semua katalog di bawah akun bisnis Anda saat ini.

[gambar]

Dan pilih tombol "Facebook ke Lokal" sesuai tangkapan layar di atas. Anda harus dapat menyinkronkan semua produk di katalog Facebook Anda kembali ke eCommerce bawaan kami.

[gambar]

Dan yang terpenting di sini adalah pastikan “SKU” di UChat sama dengan “ContentID” dengan Katalog Facebook Anda.

[gambar]

Dan ini adalah nilai yang sama di Katalog Facebook.

[gambar]

Hubungkan katalog Produk dengan nomor WhatsApp
Anda perlu menghubungkan nomor WhatsApp Anda dengan katalog produk. Baru setelah itu, Anda bisa mengirimkan pesan katalog produk.

Anda dapat mempelajari cara melakukannya melalui video di bawah ini:

[video]

Kirim pesan katalog produk
Sekarang Anda harus menyinkronkan katalog produk ke eCommerce bawaan UChat, Anda sekarang dapat menggunakan produk kirim di node kirim pesan.

Jika Anda masuk ke WhatsApp Cloud API Anda, saat Anda mengklik "Lihat katalog", Anda akan dapat melihat ID katalog yang terhubung dengan akun WABA Anda.

[gambar]

[gambar]

Anda dapat memilih untuk mengirim pesan satu produk atau beberapa pesan produk

[gambar]

Jika Anda mengirim beberapa pesan produk, Anda dapat memilih berapa banyak bagian yang ingin Anda sertakan, lalu memilih id ritel (yaitu contentID di Katalog Facebook).

Jika Anda telah menyinkronkan Katalog Facebook dengan e-niaga UChat, Anda dapat menggunakan tindakan "Dapatkan produk" untuk mengisi ID ritel secara dinamis.

Anda dapat membuka Tindakan, lalu pilih "e-niaga", lalu "Dapatkan produk"

[gambar]

Anda dapat menggunakan filter bawaan untuk mengisi ID ritel secara dinamis untuk digunakan dalam mengirim pesan katalog produk.

Anda dapat menemukan detail lebih lanjut di sini:

[video]

Siapkan pemicu permintaan produk
Anda akan mempelajari lebih lanjut tentang menyiapkan "pemicu pertanyaan produk WhatsApp". Ini akan memicu pesan setiap kali pelanggan Anda mengirimkan permintaan pesan pada halaman detail produk.

Cek video di bawah ini untuk lebih jelasnya:

[video]

Siapkan pemicu pemesanan WhatsApp yang dibuat
Pemicu pesanan WhatsApp yang diterima akan dipicu saat pengguna mengirim keranjang.

Anda dapat menggunakan nilai di dalam pemicu ini untuk membuat tautan pembayaran bagi pengguna.

Anda dapat menemukan detail lebih lanjut dalam video di bawah ini:

[video]

Kumpulkan pembayaran
Di bagian ini, Anda akan mempelajari cara membuat tautan checkout dan mengumpulkan pembayaran untuk pesanan WhatsApp.

Kumpulkan pembayaran melalui Stripe & Paypal
Checkout dengan Paypal & Stripe didukung secara asli dengan UChat. Dalam video ini, Anda dapat mempelajari cara melakukan pembayaran dengan Paypal & Stripe

Anda dapat memeriksa videonya di sini:

[video]

Kumpulkan pembayaran melalui RazorPay
UChat memiliki opsi checkout yang sangat fleksibel, Anda dapat dengan mudah berintegrasi dengan gateway pembayaran pihak ke-3.

Anda dapat menemukan integrasi ini dari toko aplikasi mini kami.

Dalam video ini, kami akan menunjukkan cara mengintegrasikan RazorPay untuk mengumpulkan pembayaran.

Anda dapat memeriksa videonya di sini:

[video]

Checkout dengan pesan template
WhatsApp hanya mendukung tombol yang tertaut ke situs web eksternal.

UChat mendukung Anda untuk mengirim pesan template, Anda perlu mengirimkan pesan template dalam dialog 360 atau Cloud API, lalu menyinkronkan pesan template yang disetujui kembali ke UChat.

Kemudian Anda dapat mengirim pesan template ini di pembuat aliran kami.

Anda dapat memeriksa videonya di sini:

[video]

Perbarui status pesanan
##Tandai pesanan sebagai dibayar - Stripe & Paypal
Pada langkah terakhir ketika pembayaran telah selesai, Anda dapat:

tandai pesanan sebagai dibayar.
Kirim pemberitahuan
Sinkronkan informasi pesanan ke Google Sheets.
P.S: Jika Anda menggunakan Stripe & Paypal untuk melakukan pembayaran, Anda akan melihat 2 pesanan dengan nilai yang sama di UChat. Ini karena produk khusus dibuat untuk melakukan pembayaran.

Cek video di bawah ini untuk lebih jelasnya:

[video]

Tandai pesanan sebagai dibayar - RazorPay
Jika Anda menggunakan RazorPay untuk melakukan pembayaran, setelah Razorpay selesai, Anda seharusnya dapat memperbarui status pesanan. Jika Anda menggunakan gateway pembayaran lokal lain, Anda dapat melakukan hal yang sama.

Cek video di bawah ini untuk lebih jelasnya:

[video]

Tambahkan nomor telepon bisnis Anda sendiri
Pertama, Anda harus membuka aplikasi Anda di pengembang Facebook, dan menambahkan nomor telepon Anda sendiri,

Klik "Mulai" dan kemudian klik "Tambahkan nomor telepon" di langkah 5 seperti tangkapan layar di bawah ini:

[gambar]

Anda perlu memberikan informasi untuk membuat profil bisnis WhatsApp Anda

[gambar]

Dan kemudian Anda dapat menambahkan nomor telepon untuk WhatsApp, Anda perlu memverifikasi nomor telepon Anda dengan menerima pesan teks atau panggilan telepon.

[gambar]

Setelah Anda memverifikasi nomor telepon, Anda hanya perlu menunggu Facebook menyetujui nomor ini, lalu Anda dapat menyinkronkan kembali nomor tersebut ke saluran Cloud API.

Setelah Anda mengirimkan informasi, Anda akan menerima sertifikasi & konfirmasi nama tampilan dari Facebook.

Seperti screenshot di bawah ini:

[gambar]

[gambar]

Dan Anda juga akan menerima email dari Facebook tentang nomor baru yang baru saja Anda lamar.

[gambar]

Anda perlu memantau dengan cermat status di pengelola bisnis WhatsApp Anda, dan pastikan sudah terhubung, bukan pending.

Anda akan dapat berpindah saat statusnya Connected, bukan pending.

[gambar]

Tolong dicatat:

Anda tidak dapat menggunakan nomor WhatsApp yang ada di WhatsApp Cloud API.
Anda harus menghapus akun WhatsApp yang ada dan kemudian Anda dapat menggunakan nomor yang sama di WhatsApp Cloud API atau Anda perlu mendapatkan nomor yang benar-benar terpisah untuk akun WhatsApp Cloud API.

Kami menyarankan Anda mendapatkan nomor baru untuk WhatsApp Cloud API.

Anda tetap bisa menggunakan nomor tersebut untuk keperluan sehari-hari, seperti menelepon dan menerima pesan setelah mendaftarkannya di Platform WhatsApp Business.

Setelah Anda menggunakan ponsel untuk Otomatisasi WhatsApp, Anda tidak dapat lagi menggunakan nomor tersebut di Aplikasi WhatsApp Business atau aplikasi pribadi WhatsApp.

Jika Anda masih ingin membalas pesan pengguna di telepon, Anda dapat mengunduh aplikasi seluler UChat untuk melakukannya.

Unduh aplikasi Android di sini: https://play.google.com/store/apps/details?id=com.uchat.application

Unduh aplikasi iOS di sini: https://apps.apple.com/us/app/uchat-live-chat/id1622962059

Alihkan alur dari nomor telepon Pengujian ke nomor telepon bisnis Anda
Pada langkah ini, Anda akan dapat mengalihkan alur chatbot yang Anda buat dengan nomor pengujian ke nomor bisnis Anda sendiri yang baru saja Anda tambahkan.

##Batalkan tautan bot
Pada langkah ini, pertama-tama Anda dapat membatalkan tautan bot dari nomor pengujian Anda.

[gambar]

Saat Anda mengeklik ikon batalkan tautan, ketik "UNLINK" pada tangkapan layar di bawah:

[gambar]

Setelah Anda mengklik tombol "YES, Unlink", Anda seharusnya dapat menghapus nomor pengujian ini dengan mengklik "x" pada tangkapan layar di bawah:

[gambar]

Setelah Anda menghapus nomor telepon pengujian, jangan khawatir tentang alur yang sudah Anda buat, itu tidak dihapus.

Anda masih dapat menemukan alurnya jika Anda membuka "Semua bot", Kami akan menautkan alur ini kembali ke nomor telepon bisnis sebenarnya yang baru saja Anda tambahkan ke aplikasi Anda.

[gambar]

Sinkronkan nomor bisnis asli ke cloud WhatsApp
Sekarang Anda dapat melakukan proses yang sama seperti sebelumnya untuk menyinkronkan nomor tes ke UChat, alih-alih memilih nomor tes, kali ini Anda akan memilih nomor telepon bisnis yang sebenarnya untuk ditambahkan ke UChat.

[gambar]

Tautkan aliran dengan nomor bisnis nyata
Setelah Anda memilih dan mengonfirmasi nomor telepon, Anda dapat mengklik ikon "LINK" untuk menautkan aliran Anda sebelumnya kembali ke nomor Whatsapp bisnis nyata ini.

Dan kemudian pilih alur yang sebelumnya Anda buat dengan nomor WhatsApp uji seperti tangkapan layar di bawah ini:

[gambar]

Dan kemudian Anda dapat mengetik "LINK" untuk menautkan aliran dengan nomor baru.

[gambar]

Kemudian Anda dapat menghubungkan aliran yang ada ke nomor bisnis Anda yang sebenarnya.

[gambar]

Sekarang Anda telah berhasil mengganti chatbot WhatsApp Anda dari nomor telepon pengujian ke nomor telepon asli Anda.

Harga
Harga ##UChat
UChat tidak mengenakan biaya tambahan untuk mengirim dan menerima segala jenis pesan menggunakan saluran WhatsApp. UChat menawarkan uji coba gratis selama 14 hari dan akses ke semua fitur pro, dan Anda dapat membuat chatbot di saluran cloud WhatsApp.

Untuk paket bisnis dasar kami, $10 per bulan untuk 1 bot, 1000 pengguna bot & 5 anggota.

Harga API cloud WhatsApp
Dengan model penetapan harga berbasis percakapan, percakapan WhatsApp Business Platform terbagi dalam 2 kategori dengan harga berbeda:

Diprakarsai pengguna: Percakapan yang dimulai sebagai respons terhadap pesan pengguna. Setiap kali bisnis membalas pengguna dalam jendela layanan pelanggan 24 jam, pesan tersebut akan dikaitkan dengan percakapan yang dimulai pengguna. Bisnis dapat mengirim pesan bentuk bebas dalam jendela layanan pelanggan 24 jam ini.

Diprakarsai bisnis: Percakapan yang dimulai dari bisnis yang mengirimkan pesan kepada pengguna di luar jendela layanan pelanggan 24 jam. Pesan yang memulai percakapan yang dimulai oleh bisnis akan memerlukan template pesan.

Semua percakapan diukur dalam sesi tetap 24 jam. Percakapan dimulai saat pesan bisnis pertama dalam percakapan dikirim, baik dimulai oleh bisnis atau sebagai balasan pesan pengguna dan berakhir 24 jam kemudian. Bisnis dan pengguna dapat bertukar pesan dalam jumlah berapa pun, termasuk pesan template, dalam sesi percakapan 24 jam tanpa dikenakan biaya tambahan. Setiap sesi percakapan 24 jam menghasilkan satu kali pengisian daya.

Harga bervariasi berdasarkan lokasi geografis penerima. Jika Anda mengirim pesan ke pengguna di India, biaya pengiriman Anda akan relatif lebih rendah daripada mengirim pesan ke pengguna di AS.

Anda dapat memeriksa struktur harga terperinci melalui tautan di bawah ini. https://developers.facebook.com/docs/whatsapp/pricing

Sesi
Semua percakapan diukur dalam peningkatan atau "sesi" 24 jam, seperti yang akan kami rujuk di sini. Sesi dimulai setiap kali pesan pertama dikirim oleh bisnis, baik sebagai tanggapan atas pertanyaan pengguna atau jika templat pesan yang diprakarsai bisnis dikirimkan.

Aturan
Kebijakan tersebut mewajibkan penggunaan pesan template setiap kali mengirim pesan ke pengguna lebih dari 24 jam setelah pesan terakhir mereka. Jadi, sesi baru dimulai.

Jika Anda mengirim pesan bentuk bebas di luar jendela dukungan pelanggan, Anda tidak mengikuti kebijakan, sehingga pengiriman pesan ini akan gagal. Namun, ini membuka percakapan yang diprakarsai bisnis yang mungkin dikenakan biaya.

Gratis 1000 pesan sesi
1.000 percakapan pertama setiap bulan gratis. Jika Anda ingin mengirim lebih dari 1.000 percakapan, Anda perlu menambahkan kartu kredit ke akun Anda.

Selain itu, Facebook menawarkan nomor telepon pengujian gratis untuk setiap aplikasi, sangat mudah bagi Anda untuk membuat demo bot WhatsApp dengan nomor pengujian, dan juga memanfaatkan pesan 1000 sesi gratis untuk klien orientasi.

Harap diperhatikan bahwa pesan 1000 sesi gratis ditawarkan di level WABA. Jika Anda memiliki beberapa nomor di bawah WABA yang sama, maka semua nomor ini akan berbagi batas 1000 pesan sesi gratis.

Batas akan diperbarui setiap bulan.

Percakapan titik masuk gratis
Percakapan tidak dikenakan biaya saat pengguna mengirim pesan ke bisnis menggunakan tombol ajakan bertindak pada Iklan yang Mengklik di WhatsApp atau tombol ajakan bertindak Halaman Facebook. Percakapan titik masuk gratis hanya dapat dimulai oleh pengguna. Percakapan pertama yang dimulai dari titik masuk tidak dikenai biaya, dan kemudian percakapan selanjutnya dengan pengguna dikenai biaya.

Harga standar berlaku untuk Iklan yang Klik di WhatsApp. Percakapan yang dimulai dari iklan itu gratis, tetapi bukan iklan itu sendiri.

Batas verifikasi bisnis
##Batas bisnis tidak terverifikasi
Tidak wajib menyelesaikan verifikasi bisnis Facebook untuk mulai membangun chatbot WhatsApp pertama Anda.

Namun jika bisnis Anda belum diverifikasi, Anda dapat:

Kirim pesan template ke hingga 50 pengguna unik dalam periode bergulir 24 jam.
Respons terhadap percakapan tak terbatas yang dimulai oleh pelanggan
Anda harus menyelesaikan verifikasi bisnis jika ingin memulai lebih dari 50 percakapan prakarsa bisnis dalam jangka waktu 24 jam.

Batas bisnis terverifikasi
Setelah bisnis diverifikasi, Anda dapat mulai mengirim pesan ke hingga 1000 pengguna unik dalam periode bergulir 24 jam. Batas secara otomatis ditingkatkan ke angka yang lebih tinggi saat Anda mengirim lebih banyak pesan berkualitas. Batas tertinggi yang diizinkan saat ini adalah 100.000 percakapan dengan pengguna unik dalam periode bergulir 24 jam. Anda bisa mendapatkan detail lebih lanjut di sini: https://developers.facebook.com/docs/whatsapp/messaging-limits##messaging

Bagaimana cara memverifikasi bisnis Anda?
Verifikasi bisnis memungkinkan Anda mendapatkan peningkatan batas pengiriman. Tanpa verifikasi, Anda dapat mengirim pesan ke hingga 50 nomor unik per hari. Setelah verifikasi, batas meningkat untuk mengirim pesan ke 1000 nomor unik per hari.

Untuk memiliki akses ke tingkat akun yang lebih tinggi di akun WhatsApp Business API, Anda harus menyelesaikan Verifikasi Bisnis di dalam Pengelola Bisnis. Ini berarti Anda harus memberikan beberapa dokumen kepada Facebook untuk membuktikan keberadaan dan legitimasi bisnis Anda.

Meskipun Verifikasi Bisnis diperlukan oleh Meta agar perusahaan memiliki akses ke tingkat akun WhatsApp Business API yang lebih tinggi, proses ini sama sekali tidak terkait dengan WhatsApp.

Untuk dukungan tentang masalah Pengelola Bisnis (membuka jendela baru), harap hubungi dukungan Meta langsung melalui "?" (bantuan) ikon di sudut kiri bawah halaman.

Proses Verifikasi Pengelola Bisnis
##Akses Pusat keamanan manajer bisnis
Untuk memulai proses verifikasi, buka Pusat Keamanan (membuka jendela baru)dan klik Mulai Verifikasi di bagian Verifikasi bisnis.

[gambar]

Pilih bisnis Anda
##Jika bisnis Anda sudah terdaftar
Konfirmasi detail bisnis Anda

Pilih nomor telepon yang dapat Anda akses dari menu tarik-turun dan klik Berikutnya.

Periksa kembali kesalahan ketik atau kesalahan lainnya: Anda tidak akan dapat mengedit informasi ini setelah dikirimkan.

Dapatkan kode verifikasi

Pilih untuk menerima kode verifikasi di nomor telepon bisnis Anda melalui pesan teks, panggilan telepon, atau email. Opsi nomor telepon mungkin tidak tersedia di semua negara.

Pastikan email yang didaftarkan memiliki domain yang sama dengan website.

Contoh yang diterima Email: name@business.com Situs: www.business.com

Contoh tidak diterima Email: name@gmail.com atau name@otherbusiness.com Situs: www.business.com

Atau verifikasi domain Anda

Jika domain Anda sudah diverifikasi, klik Gunakan Verifikasi Domain. Jika tidak, selesaikan proses verifikasi domain, lalu kembali ke Security Center dan pilih Continue.

Masukkan kode verifikasi (tidak berlaku jika Anda menggunakan verifikasi domain)

Masukkan kode verifikasi Anda. Klik Kirim.

Anda dapat melewati langkah 3 & 4 yang tersisa di bawah ini.

##Jika bisnis Anda tidak terdaftar
Jika Anda tidak dapat melihat bisnis Anda dalam daftar, pilih Tidak satu pun dari yang cocok. Kemudian lanjutkan dengan Langkah 3 & 4 di bawah ini.

Verifikasi nama bisnis resmi
Anda mungkin diminta pada langkah 3 untuk memberikan dokumentasi resmi nama resmi bisnis Anda. Unggah dokumen resmi yang cocok dengan nama resmi bisnis yang Anda masukkan di langkah 1, seperti izin usaha, anggaran dasar, atau pendaftaran pajak bisnis.

Verifikasi Alamat Bisnis atau Nomor Telepon
Unggah dokumen yang menunjukkan nama resmi bisnis Anda dan alamat surat atau nomor telepon yang ditampilkan di layar.

Setelah Anda mengunggah dokumen, Meta akan meninjaunya secepat mungkin. Ini mungkin memakan waktu beberapa hari. Anda dapat memeriksa status verifikasi Anda saat ini dengan membuka Pusat Keamanan.

Ketika bisnis Anda diverifikasi, Anda akan diberi tahu dan Anda juga akan melihat status terverifikasi di akun Anda.

[gambar]

Dokumen yang diperlukan untuk Verifikasi Bisnis
Karena adanya perbedaan antara dokumen hukum antar negara/distrik, Facebook telah menyediakan daftar dokumen khusus yang perlu dikirimkan menurut negara/distrik masing-masing. Silakan lihat di bawah ini.

Dokumen yang tidak diterima adalah:

Faktur
Order pembelian
Aplikasi yang diisi sendiri untuk perusahaan
Pengembalian pajak yang diajukan oleh Anda atau perusahaan Anda
Cetak situs web

Indonesia

Pernyataan bank bisnis
Izin Usaha Mikro Kecil (IUMK)
Nomar Induk Berusaha (NIB))
Surat Izin Usaha Perdagangan (SIUP)
Surat Pengukuhan Pengusaha Kena Pajak (SPPKP
Tanda Daftar Perusahaan (TDP
tagihan utilitas

Daftar Periksa untuk Verifikasi Bisnis
Untuk meningkatkan peluang perusahaan diverifikasi oleh Meta, penting bahwa:

Website perusahaan aktif dan lengkap, berisi nama dan alamat perusahaan
Email akun berasal dari domain yang sama dengan situs web perusahaan yang disediakan dalam dokumentasi
Jika verifikasi akan dilakukan melalui nomor telepon, pastikan Anda dapat menerima panggilan tersebut. Jika ponsel memiliki IVR, nonaktifkan sementara
Nama dagang perusahaan dalam dokumentasi sama dengan yang digunakan di situs web dan halaman Facebook. Jika berbeda, nama-nama tersebut harus terkait dengan cara tertentu di situs web. Misalnya, di footer, masukkan "Perusahaan ABC yang didukung oleh perusahaan D"

Jika tombol Mulai Verifikasi tidak tersedia
Pengelola Bisnis Anda mungkin tidak memenuhi syarat untuk verifikasi. Dalam hal ini, Anda tidak akan dapat mengeklik tombol Mulai Verifikasi:

[gambar]

Untuk mengaktifkan tombol, harap:

Isi semua informasi di halaman Info Bisnis, di dalam pengaturan Facebook Business Manager
Buat aplikasi di akun pengembang Facebook Anda.

[video]

Permintaan Verifikasi Bisnis saya ditolak: Apa yang harus dilakukan sekarang?
Jika permintaan verifikasi bisnis Anda ditolak oleh tim Facebook, Anda akan menerima email pemberitahuan yang menyatakan bahwa dokumen yang Anda lampirkan tidak lulus proses verifikasi.

[gambar]

Di halaman baru, Anda akan melihat nomor tiket/kasus Anda.

[gambar]

Jika Anda mengklik tombol 'Baca Selengkapnya', Anda dapat mulai berinteraksi langsung dengan Dukungan Facebook untuk mengetahui apa yang hilang atau dokumen mana yang tidak benar.

Apakah Verifikasi Bisnis sama dengan centang hijau?
Tidak.

Verifikasi bisnis berbeda dengan lencana terverifikasi, juga dikenal sebagai cek hijau atau Akun Bisnis Resmi (OBA).

Dokumentasi Facebook Resmi
Anda dapat menemukan detail lebih lanjut dari dokumentasi Facebook resmi:

https://www.facebook.com/business/help/2058515294227817?id=180505742745347
https://www.facebook.com/business/help/1095661473946872?id=180505742745347
https://www.facebook.com/business/help/159334372093366

Panduan nama tampilan
Saat Anda menambahkan nomor telepon baru ke akun bisnis WhatsApp Anda, Anda harus memberinya nama tampilan.

Semua nama tampilan harus memiliki hubungan dengan bisnis Anda dan tidak boleh melanggar WhatsApp Commerce (membuka jendela baru) dan kebijakan Bisnis (membuka jendela baru). Memiliki nama tampilan yang sesuai dengan pedoman WhatsApp diperlukan untuk mengirim pesan menggunakan API WhatsApp Business atau memenuhi syarat untuk akun bisnis resmi WhatsApp.

Sebelum menyelesaikan pendaftaran, Anda dapat mengubah nama tampilan sebanyak yang Anda inginkan. Setelah pendaftaran, Anda harus menunggu 30 hari di antara permintaan perubahan nama tampilan.

Di bawah ini adalah prinsip untuk nama tampilan:

Kepatuhan terhadap kebijakan
Nama tampilan tidak boleh melanggar kebijakan Perdagangan dan Bisnis WhatsApp. Contoh toko yang menjual gelas anggur:

Diterima: Gelas Anggur ABC
Tidak diterima: Anggur ABC
Di dalam perusahaan Anda, Anda mungkin memiliki akun bisnis WhatsApp terpisah untuk divisi yang berbeda; hanya divisi yang mematuhi Kebijakan Perdagangan WhatsApp yang dapat memiliki akun bisnis WhatsApp.

Representasi yang akurat dari bisnis Anda
Nama tampilan harus mewakili:

Bisnis atau layanan, produk, atau departemennya
Akun percobaan atau akun demo dan harus menjaga hubungan dengan bisnis (mis., Tes Produk Segar)
Nama tampilan tidak boleh:

Nama lengkap individu
Istilah umum (misalnya, Fashion)
Lokasi geografis umum (misalnya, New York)
Slogan atau deskripsi panjang
Organisasi dengan afiliasi pemerintah memerlukan persetujuan tim WhatsApp. Nama tampilan harus berisi minimal 3 karakter.

Konsistensi dengan branding eksternal
Nama tampilan harus memiliki pencitraan merek yang konsisten dengan sumber eksternal (mis., situs web atau pemasaran perusahaan). Contoh lini produk bernama "Fresh Produce Cold Pressed Juices":

Diterima: Jus Cold Pressed Hasil Segar (bagaimana mereknya di situs web Anda)
Tidak diterima: Jus Produk Segar (Anda mengubah merek dengan menghapus "Cold Pressed")
Tidak diterima: FP Cold Pressed Juices (Anda menambahkan singkatan ke nama perusahaan yang tidak sesuai dengan branding eksternal)
Nama tampilan harus memiliki kapitalisasi yang benar secara tata bahasa, dan harus cocok dengan kapitalisasi yang digunakan dalam branding eksternal Anda. Jangan ubah spasi dan jangan tambahkan tanda baca, emoji, atau simbol karakter tambahan
Hubungan yang jelas dengan bisnis Anda
Nama tampilan harus memiliki hubungan yang jelas dengan bisnis Anda (harus disebutkan di situs web bisnis atau referensi media eksternal). Sebagai contoh:

Diterima: Nama badan amal yang disebutkan di situs web organisasi nirlaba
Tidak diterima: Nama badan amal yang tidak disebutkan di situs web eksternal mana pun
Jika hubungan antara perusahaan Anda dan merek tidak jelas, tunjukkan hubungan tersebut menggunakan "oleh [nama perusahaan]".

Tidak diterima: Cemilan Buah (Produk Segar memiliki merek Cemilan Buah tetapi keterkaitannya tidak disebutkan di situs web eksternal mana pun)
Diterima: Cemilan Buah dari Produk Segar
Jika nama tampilan mewakili bisnis tempat perusahaan bekerja sama (yaitu, jika bisnis tersebut adalah agen, distributor, mitra, atau perusahaan induk), maka hubungan antara bisnis yang diwakili dalam nama tampilan dan bisnis klien akhir harus jelas dan jelas di situs web bisnis kedua belah pihak. Misalnya, jika Global Voyager mendaftar ke WhatsApp dan ingin menggunakan nama tampilan Commercial Air, mereka harus mengirimkan tautan ke kedua situs web yang menyatakan bahwa Commercial Air adalah anak perusahaan Global Voyager.

Badan hukum di footer
Jika nama resmi (badan hukum) perusahaan dalam dokumen yang digunakan untuk Verifikasi Bisnis dan penamaan di situs web berbeda, kami sarankan untuk menambahkan penyebutan badan hukum ke situs web, misalnya di footer: "Bisnis ABC didukung oleh CDE bisnis"

Situs web yang berfungsi
Nama tampilan tidak dapat disetujui tanpa situs web yang berfungsi. Situs web harus diverifikasi oleh Pengelola Bisnis Facebook Anda. Jika situs web perusahaan Anda telah diubah, situs web baru harus diserahkan untuk verifikasi.

## FAQ:
Bagaimana saya bisa membalas klien di ponsel saya? Setelah Anda menghubungkan nomor telepon dengan API cloud WhatsApp, Anda tidak akan dapat menggunakan nomor ini di bisnis WhatsApp atau aplikasi pribadi WhatsApp.
Anda dapat masuk ke platform UChat, lalu mengobrol langsung untuk membalas klien Anda di desktop, atau mengunduh aplikasi seluler UChat untuk membalas langsung di ponsel Anda.

[gambar]

Anda dapat mengunduh aplikasi seluler kami di sini:

Unduh aplikasi Android di sini: https://play.google.com/store/apps/details?id=com.uchat.application

Unduh aplikasi iOS di sini: https://apps.apple.com/us/app/uchat-live-chat/id1622962059

Bisakah saya menggunakan nomor WhatsApp seluler saya saat ini di WhatsApp cloud API? Anda tidak dapat menggunakan nomor WhatsApp yang ada di WhatsApp Cloud API. Anda harus menghapus akun WhatsApp yang ada dan kemudian Anda dapat menggunakan nomor yang sama di WhatsApp Cloud API atau Anda perlu mendapatkan nomor yang benar-benar terpisah untuk akun WhatsApp Cloud API.
Kami menyarankan Anda mendapatkan nomor baru untuk WhatsApp Cloud API.

Bagaimana cara menghapus nomor telepon dari akun bisnis? Anda dapat merujuk ke tautan di bawah untuk menghapus nomor telepon dari akun bisnis Anda. https://developers.facebook.com/docs/whatsapp/phone-numbers##delete-phone-number-from-a-business-account

Saya menggunakan 360Dialog saat ini, apakah saya perlu beralih ke Cloud API? Berikut perbedaan antara 360Dialog & WhatsApp cloud API, berikut tabel untuk referensi Anda:

[gambar]

Singkatnya, dengan 360dialog, klien memiliki akses ke penawaran WhatsApp yang berbeda (Cloud API, Business API, on-premise), peningkatan hosting dan kinerja (Paket Premium, hosting lokal, multicore), dan tingkat dukungan dan SLA yang berbeda - tidak ada yang ditawarkan oleh Meta secara langsung.

Jika Anda menggunakan API cloud WhatsApp, ini sedikit lebih murah. Anda dapat memulai dengan mudah dengan nomor telepon uji & 1000 pesan sesi gratis.

Anda dapat membuat keputusan sendiri berdasarkan informasi di atas.

Saya tidak dapat menghubungkan akun bisnis saya di WhatsApp cloud API? Saat ini, Anda hanya dapat menghubungkan akun bisnis ke salah satu ruang kerja UChat. Jika Anda perlu beralih ke ruang kerja lain, Anda harus memutuskan sambungan dan menghubungkan kembali ke ruang kerja baru.
