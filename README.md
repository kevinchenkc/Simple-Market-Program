Kevin - Purwadhika JCDS Program's Module 1 Final Project README

Setelah mempelajari programming fundamentals menggunakan bahasa pemograman Python di Modul 1
kurikulum program Job Connecton Data Science & Machine Learning di Purwadhika Digital Technology School,
setiap siswa ditugaskan untuk membuat sebuah program akhir dengan produk akhir yaitu sebuah program
sederhana menggunakan Python yang memuat 4 buah function utama: Create, Read, Delete dan Update.

Topik yang saya dapatkan adalah untuk membuat program tersebut untuk dipergunakan dalam transaksi di toko.
Scope yang saya ambil adalah sebuah toko kelontong yang menjual barang-barang kebutuhan dasar yang dibutuhkan
warga sekitar toko tersebut.
Toko tersebut saya namakan Toko Kelontong JCDS, dan berikut penjelasan atas program tsb:

(1) Interface awal terbagi menjadi menu untuk login sebagai karyawan toko atau customer, dengan pilihan
exit di menu ke-3 yang menjadi satu-satunya jalan untuk keluar dari program ini.
--------------------------------------
SELAMAT DATANG DI TOKO KELONTONG JCDS
-------------------------------------- 

Masuk Sebagai: 
1. Karyawan Toko Kelontong JCDS 
2. Customer 
3. Exit Program 

Masukkan Menu Login(1-3): 

(2) Jika user memilih menu 1 untuk masuk sebagai karyawan toko, maka program akan meminta user untuk memasukkan
password yang sudah didefine sebelumnya.
--------------------------------------
SELAMAT DATANG DI TOKO KELONTONG JCDS
-------------------------------------- 

Masuk Sebagai: 
1. Karyawan Toko Kelontong JCDS 
2. Customer 
3. Exit Program 

Masukkan Menu Login(1-3): 1
Masukkan Kode Pegawai: 

(3) Jika password salah, maka akan ada pemberitahuan bahwa login tidak bisa dilakukan dan program akan kembali
ke interface awal. 

Kode Pegawai yang Dimasukkan Salah. Login Tidak Bisa Dilakukan
--------------------------------------
SELAMAT DATANG DI TOKO KELONTONG JCDS
-------------------------------------- 

Masuk Sebagai: 
1. Karyawan Toko Kelontong JCDS 
2. Customer 
3. Exit Program 

Masukkan Menu Login(1-3): 

(4) Jika password benar, maka program akan berlanjut ke interface menu untuk pegawai, yang terdiri dari Tampilkan
Stok (Read), Tambah Barang (Create), Update Stok (Update dan Delete), dengan pilihan ke-4 untuk kembali ke Menu Utama.

Masukkan Menu Login(1-3): 1
Masukkan Kode Pegawai: 13579
------------
PEGAWAI TOKO
------------ 

-----MAIN MENU----- 
1. Tampilkan Stok Barang 
2. Tambah Barang 
3. Update Stok 
4. Kembali ke Menu Utama 

Input Menu Yang Ingin Dipilih (1-4): 

(5) Ketika user memilih menu untuk tampilkan stok, maka akan muncul 3 buah opsi tampilan, yaitu tampilan per kategori,
tampilkan semua stok, dan tampilkan sesuai keyword yang diinput user.

Input Menu Yang Ingin Dipilih (1-4): 1
-----TAMPILAN STOK----- 
1. Tampilkan Per Kategori  
2. Tampilkan Semua 
3. Cari Dengan Keyword 
4. Kembali ke Menu Utama 

Tampilan Stok Yang Ingin Dipilih (1-4): 

(6) Ketika user memilih opsi untuk menampilkan stok per kategori, maka akan muncul 3 buah kategori stok yang dipunyai toko,
yaitu bahan masak, minuman dan makanan. Pada program ini, dimungkinkan untuk menambahkan kategori stok baru selain 3 kategori
yang sudah ada namun belum dapat ditampilkan secara terpisah (hanya akan muncul ketika dimasukkan nama barang dimasukkan
sebagai keyword atau ditampilkan semua).

Tampilan Stok Yang Ingin Dipilih (1-4): 1
-----PILIHAN KATEGORI----- 
1. Bahan Masak  
2. Minuman  
3. Makanan 
4. Kembali ke Menu Utama 

Kategori Yang Ingin Ditampilkan (1-4): 

(7) Sebagai contoh, berikut tampilan ketika user memilih menampilkan stok yang masuk kategori bahan masak.
Setelah stok bahan masak ditampilkan, program akan langsung menampilkan kembali menu tampilan stok.

Kategori Yang Ingin Ditampilkan (1-4): 1
Daftar Barang 
	  |Nama Barang 	| Kemasan 	| Kategori 	| Qty 	| Harga/unit
	  |Margarin 	| Kotak 200gr 	| Bahan Masak 	| 5 	| 15000
	  |Gula 	| Pouch 500gr 	| Bahan Masak 	| 30 	| 12000
	  |Minyak Grg 	| Pouch 2L 	| Bahan Masak 	| 90 	| 48000
-----TAMPILAN STOK----- 
1. Tampilkan Per Kategori  
2. Tampilkan Semua 
3. Cari Dengan Keyword 
4. Kembali ke Menu Utama 

Tampilan Stok Yang Ingin Dipilih (1-4): 

(8) Berikut tampilan ketika user ingin menampilkan semua stok di toko.

Tampilan Stok Yang Ingin Dipilih (1-4): 2
Daftar Barang 
	  |Nama Barang 	| Kemasan 	| Kategori 	| Stok 	| Harga/unit
	  |Susu Cair 	| Kotak 1L 	| Minuman 	| 10 	| 20000
	  |Margarin 	| Kotak 200gr 	| Bahan Masak 	| 5 	| 15000
	  |Gula 	| Pouch 500gr 	| Bahan Masak 	| 30 	| 12000
	  |Minyak Grg 	| Pouch 2L 	| Bahan Masak 	| 90 	| 48000
	  |Susu Bubuk 	| Kaleng 1kg 	| Minuman 	| 23 	| 100000
	  |Kopi 	| Bks 5 Sachet 	| Minuman 	| 20 	| 5000
	  |Roti Tawar 	| 1 Sisir 	| Makanan 	| 12 	| 17000
	  |Beras 	| Sak 10kg 	| Makanan 	| 7 	| 140000
-----TAMPILAN STOK----- 
1. Tampilkan Per Kategori  
2. Tampilkan Semua 
3. Cari Dengan Keyword 
4. Kembali ke Menu Utama 

Tampilan Stok Yang Ingin Dipilih (1-4): 

(9) Ketika user memilih untuk menampilkan stok sesuai keyword, maka user akan diminta untuk memasukkan/
menginput keyword barang yang ingin ditampilkan.

Tampilan Stok Yang Ingin Dipilih (1-4): 3
Masukkan kata kunci barang yang ingin ditampilkan: 

(10) Ketika user memasukkan kata kunci dengan contoh "susu", maka semua stok yang memuat kata "susu"
dalam nama barangnya akan ditampilkan (tidak peduli diketik dengan lowercase/uppercase/campuran).

Masukkan kata kunci barang yang ingin ditampilkan: susu
Daftar Barang 
	  |Nama Barang 	| Kemasan 	| Kategori 	| Qty 	| Harga/unit
	  |Susu Cair 	| Kotak 1L 	| Minuman 	| 10 	| 20000
	  |Susu Bubuk 	| Kaleng 1kg 	| Minuman 	| 23 	| 100000
-----TAMPILAN STOK----- 
1. Tampilkan Per Kategori  
2. Tampilkan Semua 
3. Cari Dengan Keyword 
4. Kembali ke Menu Utama 

Tampilan Stok Yang Ingin Dipilih (1-4): 

(11) Untuk alasan keamanan, setiap kali user ingin kembali ke menu utama, maka program akan meminta user
untuk menginput kembali password pegawai. Jika salah, maka program akan dikembalikan ke interface awal.

Tampilan Stok Yang Ingin Dipilih (1-4): 4
Masukkan Kode Pegawai: 

(12) Ketika user memilih menu untuk menambahkan stok baru, maka user akan diminta untuk memasukkan nama
barang (maks 10 karakter) dan program akan menolak input nama barang baru jika nama sama dengan nama
stok yang sudah ada didalam sistem. Jika semua informasi stok baru sudah dimasukkan sesuai ketentuan,
maka akan muncul sebuah checker apakah user yakin untuk menambahkan item. Jika memasukkan value "Y"
atau "y", maka item baru beserta seluruh informasinya akan dimasukkan kedalam list stok.

Masukkan Kode Pegawai: 13579
------------
PEGAWAI TOKO
------------ 

-----MAIN MENU----- 
1. Tampilkan Stok Barang 
2. Tambah Barang 
3. Update Stok 
4. Kembali ke Menu Utama 

Input Menu Yang Ingin Dipilih (1-4): 2
Masukkan Nama Produk yang Ingin Ditambahkan: Kopi
Kami sudah mempunyai item yang sama dengan input anda, tidak dapat menambahkan item
--------------
Masukkan Nama Produk yang Ingin Ditambahkan: Kopi Bubuk
Masukkan Kemasan dari Produk Baru: Sachet 10
Masukkan Kategori dari Produk Baru: Minuman
Masukkan Jumlah Stok dari Produk Baru: 10
Masukkan Harga per Unit dari Produk Baru: 13000
Apakah anda yakin ingin menambahkan produk Kopi Bubuk Minuman dengan jumlah 10 dan harga 13000? (Y/N): y
Daftar Barang 
	  |Nama Barang 	| Kemasan 	| Kategori 	| Stok 	| Harga/unit
	  |Susu Cair 	| Kotak 1L 	| Minuman 	| 10 	| 20000
	  |Margarin 	| Kotak 200gr 	| Bahan Masak 	| 5 	| 15000
	  |Gula 	| Pouch 500gr 	| Bahan Masak 	| 30 	| 12000
	  |Minyak Grg 	| Pouch 2L 	| Bahan Masak 	| 90 	| 48000
	  |Susu Bubuk 	| Kaleng 1kg 	| Minuman 	| 23 	| 100000
	  |Kopi 	| Bks 5 Sachet 	| Minuman 	| 20 	| 5000
	  |Roti Tawar 	| 1 Sisir 	| Makanan 	| 12 	| 17000
	  |Beras 	| Sak 10kg 	| Makanan 	| 7 	| 140000
	  |Kopi bubuk 	| Sachet 10 	| Minuman 	| 10 	| 13000
Masukkan Kode Pegawai: 

(13) Untuk menu update stok, jenis update terdiri dari update detail stok (hanya untuk barang yang sudah ada
di dalam stok) dan delete stok.

Masukkan Kode Pegawai: 13579
------------
PEGAWAI TOKO
------------ 

-----MAIN MENU----- 
1. Tampilkan Stok Barang 
2. Tambah Barang 
3. Update Stok 
4. Kembali ke Menu Utama 
Input Menu Yang Ingin Dipilih (1-4): 3

-----UPDATE STOK----- 
1. Update Produk 
2. Delete Produk 
3. Kembali ke Menu Utama 

Update yang Ingin Dipilih (1-3): 

(14) Ketika memilih menu update detail barang, maka program akan meminta user untuk
memasukkan nama barang yang ingin diupdate dari list barang yang ditampilkan.
Update yang dapat dilakukan meliputi semua detail barang (nama, kemasan, kategori,
jumlah stok dan harga per unit). 

Update yang Ingin Dipilih (1-3): 1
Daftar Barang 
	  |Nama Barang 	| Kemasan 	| Kategori 	| Stok 	| Harga/unit
	  |Susu Cair 	| Kotak 1L 	| Minuman 	| 10 	| 20000
	  |Margarin 	| Kotak 200gr 	| Bahan Masak 	| 5 	| 15000
	  |Gula 	| Pouch 500gr 	| Bahan Masak 	| 30 	| 12000
	  |Minyak Grg 	| Pouch 2L 	| Bahan Masak 	| 90 	| 48000
	  |Susu Bubuk 	| Kaleng 1kg 	| Minuman 	| 23 	| 100000
	  |Kopi 	| Bks 5 Sachet 	| Minuman 	| 20 	| 5000
	  |Roti Tawar 	| 1 Sisir 	| Makanan 	| 12 	| 17000
	  |Beras 	| Sak 10kg 	| Makanan 	| 7 	| 140000
	  |Kopi bubuk 	| Sachet 10 	| Minuman 	| 10 	| 13000
Masukkan nama item yang mau diupdate: Roti Tawar
-----UPDATE FIELD----- 
1. Nama Barang 
2. Kemasan 
3. Kategori 
4. Unit 
5. Harga/unit 
6. Kembali ke Menu Utama 
Field yang ingin diupdate(1-6): 1
Masukkan nama item baru: Roti
Apakah anda yakin ingin menambahkan update nama Roti Tawar menjadi Roti? (Y/N): y
Daftar Barang 
	  |Nama Barang 	| Kemasan 	| Kategori 	| Stok 	| Harga/unit
	  |Susu Cair 	| Kotak 1L 	| Minuman 	| 10 	| 20000
	  |Margarin 	| Kotak 200gr 	| Bahan Masak 	| 5 	| 15000
	  |Gula 	| Pouch 500gr 	| Bahan Masak 	| 30 	| 12000
	  |Minyak Grg 	| Pouch 2L 	| Bahan Masak 	| 90 	| 48000
	  |Susu Bubuk 	| Kaleng 1kg 	| Minuman 	| 23 	| 100000
	  |Kopi 	| Bks 5 Sachet 	| Minuman 	| 20 	| 5000
	  |Beras 	| Sak 10kg 	| Makanan 	| 7 	| 140000
	  |Kopi bubuk 	| Sachet 10 	| Minuman 	| 10 	| 13000
	  |Roti 	| 1 Sisir 	| Makanan 	| 12 	| 17000
Masukkan Kode Pegawai: 

(15) Untuk proses delete barang di dalam stok, user cukup memasukkan input nama barang yang
ingin dibuang dari daftar stok, dan item akan dieliminasi dari daftar stok setelah
konfirmasi dari user.

Input Menu Yang Ingin Dipilih (1-4): 3
-----UPDATE STOK----- 
1. Update Produk 
2. Delete Produk 
3. Kembali ke Menu Utama 

Update yang Ingin Dipilih (1-3): 2
Daftar Barang 
	  |Nama Barang 	| Kemasan 	| Kategori 	| Stok 	| Harga/unit
	  |Susu Cair 	| Kotak 1L 	| Minuman 	| 10 	| 20000
	  |Margarin 	| Kotak 200gr 	| Bahan Masak 	| 5 	| 15000
	  |Gula 	| Pouch 500gr 	| Bahan Masak 	| 30 	| 12000
	  |Minyak Grg 	| Pouch 2L 	| Bahan Masak 	| 90 	| 48000
	  |Susu Bubuk 	| Kaleng 1kg 	| Minuman 	| 23 	| 100000
	  |Kopi 	| Bks 5 Sachet 	| Minuman 	| 20 	| 5000
	  |Beras 	| Sak 10kg 	| Makanan 	| 7 	| 140000
	  |Kopi bubuk 	| Sachet 10 	| Minuman 	| 10 	| 13000
	  |Roti 	| 1 Sisir 	| Makanan 	| 12 	| 17000
Masukkan nama produk yang ingin dibuang: GULA
Apakah anda yakin ingin membuang seluruh informasi untuk produk GULA? (Y/N): y
Daftar Barang 
	  |Nama Barang 	| Kemasan 	| Kategori 	| Stok 	| Harga/unit
	  |Susu Cair 	| Kotak 1L 	| Minuman 	| 10 	| 20000
	  |Margarin 	| Kotak 200gr 	| Bahan Masak 	| 5 	| 15000
	  |Minyak Grg 	| Pouch 2L 	| Bahan Masak 	| 90 	| 48000
	  |Susu Bubuk 	| Kaleng 1kg 	| Minuman 	| 23 	| 100000
	  |Kopi 	| Bks 5 Sachet 	| Minuman 	| 20 	| 5000
	  |Beras 	| Sak 10kg 	| Makanan 	| 7 	| 140000
	  |Kopi bubuk 	| Sachet 10 	| Minuman 	| 10 	| 13000
	  |Roti 	| 1 Sisir 	| Makanan 	| 12 	| 17000
Masukkan Kode Pegawai: 

(16) Beralih ke interface karyawan, tidak ada pilihan untuk memasukkan kode pegawai dan
pilihan menu hanya ada 2, yaitu tampilkan daftar barang (sama persis seperti menu tampilkan
stok barang di interface karyawan) dan menu belanja. 

--------------------------------------
SELAMAT DATANG DI TOKO KELONTONG JCDS
-------------------------------------- 

Masuk Sebagai: 
1. Karyawan Toko Kelontong JCDS 
2. Customer 
3. Exit Program 

Masukkan Menu Login(1-3): 2
---------
PELANGGAN
---------

-----MAIN MENU----- 
1. Tampilkan Daftar Barang 
2. Belanja 
3. Kembali ke Menu Utama 

Input Menu Yang Ingin Dipilih (1-3): 

(17) Dalam menu belanja, user akan ditampilkan stok barang yang dapat dibelanjakan.
Ketika user memasukkan nama barang yang salah atau jumlah barang yang melebihi stok,
maka program tidak mendeteksi bahwa pembelian tidak dapat dilakukan.
Ketika user selesai berbelanja, maka program akan otomatis menampilkan keranjang belanja
beserta total harga yang perlu dibayar user. 

Input Menu Yang Ingin Dipilih (1-3): 2
Daftar Barang 
	  |Nama Barang 	| Kemasan 	| Kategori 	| Stok 	| Harga/unit
	  |Susu Cair 	| Kotak 1L 	| Minuman 	| 10 	| 20000
	  |Margarin 	| Kotak 200gr 	| Bahan Masak 	| 5 	| 15000
	  |Minyak Grg 	| Pouch 2L 	| Bahan Masak 	| 90 	| 48000
	  |Susu Bubuk 	| Kaleng 1kg 	| Minuman 	| 23 	| 100000
	  |Kopi 	| Bks 5 Sachet 	| Minuman 	| 20 	| 5000
	  |Beras 	| Sak 10kg 	| Makanan 	| 7 	| 140000
	  |Kopi bubuk 	| Sachet 10 	| Minuman 	| 10 	| 13000
	  |Roti 	| 1 Sisir 	| Makanan 	| 12 	| 17000
Masukkan Nama Barang Yang Ingin Dibeli: 
Barang yang ingin dibeli tidak ditemukan
Masukkan Nama Barang Yang Ingin Dibeli: Beras
Masukkan Jumlah Yang Ingin Dibeli: 8
Stok tidak cukup. Stok Beras sisa 7
Keranjang Belanja 
	  |Nama Barang 	| Kemasan 	| Qty 	| Harga 	| Total Harga
Apakah Ingin Membeli Item Lain? (Y/N): y
Masukkan Nama Barang Yang Ingin Dibeli: Margarin
Masukkan Jumlah Yang Ingin Dibeli: 4
Keranjang Belanja 
	  |Nama Barang 	| Kemasan 	| Qty 	| Harga 	| Total Harga
	  |Margarin 	| Kotak 200gr 	| 4 	| 15000    	| 60000
Apakah Ingin Membeli Item Lain? (Y/N): y
Masukkan Nama Barang Yang Ingin Dibeli: roti
Masukkan Jumlah Yang Ingin Dibeli: 10
Keranjang Belanja 
	  |Nama Barang 	| Kemasan 	| Qty 	| Harga 	| Total Harga
	  |Margarin 	| Kotak 200gr 	| 4 	| 15000    	| 60000
	  |Roti 	| 1 Sisir 	| 10 	| 17000    	| 170000
Apakah Ingin Membeli Item Lain? (Y/N): n
Keranjang Belanja 
	  |Nama Barang 	| Kemasan 	| Qty 	| Harga 	| Total Harga
	  |Margarin 	| Kotak 200gr 	| 4 	| 15000    	| 60000
	  |Roti 	| 1 Sisir 	| 10 	| 17000    	| 170000
Total Yang Harus Dibayar = 230000
Masukkan jumlah uang : 

(18) Jika user memasukkan uang yang lebih sedikit dari total belanja, maka program
akan menolak pembayaran sampai user memasukkan uang yang sesuai atau melebihi total
belanja. Program juga akan otomatis menghitung kembalian jika uang yang diserahkan
lebih dari total belanja, sekaligus mengurangi jumlah stok dari daftar stok toko.

Keranjang Belanja 
	  |Nama Barang 	| Kemasan 	| Qty 	| Harga 	| Total Harga
	  |Margarin 	| Kotak 200gr 	| 4 	| 15000    	| 60000
	  |Roti 	| 1 Sisir 	| 10 	| 17000    	| 170000
Total Yang Harus Dibayar = 230000
Masukkan jumlah uang : 200000
Uang anda kurang sebesar 30000
Total Yang Harus Dibayar = 230000
Masukkan jumlah uang : 250000
Terima kasih sudah berbelanja di Toko Kelontong JSDC 

Uang kembalian anda : 20000
---------
PELANGGAN
---------

-----MAIN MENU----- 
1. Tampilkan Daftar Barang 
2. Belanja 
3. Kembali ke Menu Utama 

Input Menu Yang Ingin Dipilih (1-3): 2
---------
PELANGGAN
---------

-----MAIN MENU----- 
1. Tampilkan Daftar Barang 
2. Belanja 
3. Kembali ke Menu Utama 

Input Menu Yang Ingin Dipilih (1-3): 1
-----TAMPILAN STOK----- 
1. Tampilkan Per Kategori  
2. Tampilkan Semua 
3. Cari Dengan Keyword 
4. Kembali ke Menu Utama 

Tampilan Stok Yang Ingin Dipilih (1-4): 2

Daftar Barang 
	  |Nama Barang 	| Kemasan 	| Kategori 	| Stok 	| Harga/unit
	  |Susu Cair 	| Kotak 1L 	| Minuman 	| 10 	| 20000
	  |Margarin 	| Kotak 200gr 	| Bahan Masak 	| 1 	| 15000
	  |Minyak Grg 	| Pouch 2L 	| Bahan Masak 	| 90 	| 48000
	  |Susu Bubuk 	| Kaleng 1kg 	| Minuman 	| 23 	| 100000
	  |Kopi 	| Bks 5 Sachet 	| Minuman 	| 20 	| 5000
	  |Beras 	| Sak 10kg 	| Makanan 	| 7 	| 140000
	  |Kopi bubuk 	| Sachet 10 	| Minuman 	| 10 	| 13000
	  |Roti 	| 1 Sisir 	| Makanan 	| 2 	| 17000
-----TAMPILAN STOK----- 
1. Tampilkan Per Kategori  
2. Tampilkan Semua 
3. Cari Dengan Keyword 
4. Kembali ke Menu Utama 

Tampilan Stok Yang Ingin Dipilih (1-4): 
