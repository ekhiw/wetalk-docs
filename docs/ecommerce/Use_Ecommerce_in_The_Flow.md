# Use E-commerce in The Flow

[gambar]

Anda dapat memeriksa "Template E-niaga" ini untuk mendapatkan inspirasi setelah menyiapkan sistem e-niaga Anda.

## Show Products

[gambar]

Pada langkah Kirim Pesan, temukan "E-niaga"(1), "Produk"(2), lalu klik "Edit"(3). Tombol yang ditambahkan di area 4 akan ditampilkan di bawah setiap produk. Dan jangan lupa untuk menempatkan prompt di area 5 jika tidak ada produk yang cocok.

[gambar]

pilih berapa banyak produk yang akan ditampilkan dari 1 sampai 10
pilih kondisi penyortiran sesuai dengan pilihan pengguna
atur filter dengan kondisi sebanyak yang diperlukan.

## Add to Chart

[gambar]

Pilih "Tambahkan ke troli" saat tombol ditekan. Adalah baik untuk meminta apa yang ditambahkan juga. Dapatkan informasi tentang produk yang ditambahkan dari variabel JSON "SHOP".

## Show Cart

[gambar]

Temukan "Keranjang Belanja" di bawah "E-niaga", klik "Edit". Sekali lagi, tombol apa pun yang diletakkan di area 4 akan ditampilkan dengan setiap produk.

[gambar]

Halaman edit "showing cart" mirip dengan halaman "showing product". Tapi ini sedikit lebih rumit. Karena keranjang harus menunjukkan setiap produk untuk ditinjau sebelum checkout.

## Remove from Cart

Pilih "Hapus dari troli" saat tombol ditekan. Anda mungkin ingin menggunakan langkah Goto untuk masuk ke keranjang lagi untuk menyegarkan, karena ada jumlah yang ditampilkan dengan produk yang berbeda dengan menampilkan menu statis.

## Empty Cart

[gambar]

Pilih "Keranjang Kosong" saat balasan cepat ditekan. Mengapa tidak tombol? Karena dapat menjadi mubazir untuk memiliki lebih dari satu keranjang kosong yang mengikuti semua produk. Selain itu, "Keranjang Kosong" ada di langkah Tindakan, bukan tindakan tombol. Jadi, Anda harus memilih langkah Tindakan sebagai langkah selanjutnya untuk membalas cepat.

## Checkout

Kami baru saja berbicara tentang berlebihan untuk memiliki tombol "Keranjang Kosong" dengan setiap produk tetapi mengapa menempatkan beberapa "Checkout"? Ini karena, tindakan pada langkah Tindakan diproses di backend sementara "Checkout" memerlukan frontend untuk membuka situs web, halaman checkout. Jadi Anda hanya dapat memanggil "Checkout" di sebuah tombol.

Jika Anda tidak ingin mencantumkan "Checkout" di bawah setiap produk, coba tambahkan satu lagi informasi jenis teks setelah menampilkan keranjang:

[gambar]

Saat pengguna melakukan pembayaran, daftar produk akan ditampilkan dengan jumlah dan harga terlebih dahulu, diikuti dengan area untuk meninggalkan detail kontak pengguna:

[gambar]

Terus gulir ke bawah Anda akan melihat opsi pengiriman, kode kupon, dan ringkasan pesanan.

[gambar]

Terakhir, dengan memilih opsi pembayaran dan mengklik "Bayar $xx.xx", halaman akan diarahkan ke Stripe.com. Jika Anda berada dalam mode teks, Anda akan melihat ini:

[gambar]

Klik "AUTHORIZE TEST PAYMENT" atau "FAIL TEST PAYMENT" untuk mengetes seperti apa jadinya jika pembayaran berhasil atau gagal.

[gambar]

Konfirmasi pesanan akan dikirim saat pembayaran berhasil. Klik konfirmasi untuk melihat detail pesanan.

## “Buy” Only One Product

[gambar]

"Beli" sebenarnya adalah fitur yang tidak ada hubungannya dengan sistem e-niaga bawaan. Setelah menyiapkan Integrasi Stripe Anda, pengguna dapat membeli satu produk (bisa dari akun Stripe Anda) dengan satu klik pada tombol "Beli" tanpa pengaturan sistem e-niaga sama sekali.

Fitur ini cocok untuk produk tiket tanpa opsi atau membayar biaya berlangganan, dll.

## How to use System JSON Variable

Ada beberapa bidang sistem yang menyimpan informasi tentang sistem e-niaga. Biasanya, sistem akan memberi tahu Anda di mana menemukan menurut data seperti ini:

[gambar]

Anda dapat mengaksesnya di mana pun Anda melihat "</>":

[gambar]

## System JSON - "SHOP"

"SHOP" menyimpan semua informasi tentang pengaturan e-niaga Anda.

[gambar]

## System JSON - "ORDER"

"ORDER" menyimpan pesanan terakhir pengguna. Anda hanya mendapatkan pesanan setelah checkout.

[gambar]

## System JSON - "CART"

"CART" menyimpan keranjang belanja pengguna.

[gambar]

## System JSON - "SELECT"

Saat Anda memilih "Pilih" saat tombol ditekan, item yang dipilih disimpan di "PILIH".

SELECT.produk:

[gambar]

PILIH.sku:

[gambar]
