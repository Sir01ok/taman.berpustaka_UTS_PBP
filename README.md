## Hasil Pengerjaan UTS PBP
### Taman Berpustaka
Taman Berpustaka adalah proyek midsemester matkul PBP yang mensimulasikan fungsionalitas inti dari sebuah website e-commerce toko buku online. Proyek ini menampilkan halaman daftar produk dengan filter dinamis, halaman detail produk dengan kalkulasi harga, dan halaman checkout dengan simulasi proses pembayaran.

Proyek ini dibangun murni menggunakan HTML, CSS, dan JavaScript (vanilla), dengan framework Bootstrap untuk tata letak dan komponen yang responsif.

## Demo & Screenshot :

<img width="1894" height="994" alt="Screenshot 2025-10-21 175408" src="https://github.com/user-attachments/assets/bcfaa0fb-f6a5-4756-a1ad-133bddf84525" />

__^ Page 1 Home ^__


<img width="1901" height="990" alt="Screenshot 2025-10-21 175449" src="https://github.com/user-attachments/assets/ec13a139-fc5d-47f6-bc92-e6c8808351a7" />

__^ Page 2 Detail ^__


<img width="1898" height="972" alt="Screenshot 2025-10-21 175458" src="https://github.com/user-attachments/assets/72a99222-645c-4366-8db3-d154b352c000" />

__^ Page 3 Checkout ^__

__Link Penjelasan Kode Youtube:__


## Fitur Utama
Proyek ini dibagi menjadi tiga halaman utama dengan fitur-fitur berikut:

1. Halaman Utama (index.html)
   
- Galeri Produk: Menampilkan daftar buku dalam tata letak card (kartu) yang responsif.
- Filter Kategori: Pengguna dapat memfilter buku yang ditampilkan berdasarkan kategori (Fiksi, Non Fiksi, Biografi, dll) menggunakan checkbox.
- Filter Pencarian: Terdapat search bar yang secara dinamis menyaring produk berdasarkan teks yang diketik pengguna (mencari di judul, penulis, atau deskripsi).
- Filter Gabungan: Fitur pencarian dan filter kategori dapat bekerja secara bersamaan.
- Carousel: Komponen carousel Bootstrap untuk menampilkan promo atau highlight.

2. Halaman Detail (details.html)
   
- Informasi Rinci: Menampilkan detail satu buku, termasuk sinopsis, penulis, dan rating.
- Tombol "Read More": Menyembunyikan sinopsis yang panjang dan menampilkannya saat tombol diklik.
- Kalkulator Kuantitas: Pengguna dapat menambah atau mengurangi jumlah barang yang ingin dibeli.
- Subtotal Dinamis: Harga subtotal akan otomatis diperbarui secara real-time saat kuantitas diubah.
- Navigasi Pembelian: Tombol "Beli Langsung" dan "+ Keranjang".

3. Halaman Checkout (pembelian.html)
   
- Ringkasan Pesanan: Menampilkan alamat pengiriman, detail barang, dan rincian biaya (Subtotal, Ongkir, dan Total).
- Simulasi Pembayaran: Saat tombol "Bayar" diklik, tombol akan berubah menjadi status loading ("Memproses Pembayaran...") selama 2 detik sebelum mengarahkan pengguna kembali ke halaman utama.

## Teknologi yang Digunakan
- HTML5: Untuk struktur dan kerangka konten website.
- CSS3: Untuk styling kustom, seperti efek hover pada kartu dan pemotongan teks (text-truncate).
- Bootstrap 5.3.8: Framework CSS utama untuk layouting (grid, flex), komponen (navbar, card, carousel, button), dan responsiveness.
- JavaScript (Vanilla JS): Event listener, filter, dan kalkulasi harga, simulasi loading pada tombol.
- Font Awesome & Bootstrap Icons: Untuk di seluruh sites.
- Google Fonts: Menggunakan font 'Outfit'.
