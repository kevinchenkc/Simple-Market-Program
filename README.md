# UMKM Inventory - Sales Program with Python README
## Prepared by Kevin for Purwadhika JCDS Program's Module 1 Final Project
<hr>

Setelah mempelajari *programming fundamentals* menggunakan bahasa pemograman *Python* di Modul 1 kurikulum program **_Job Connector Data Science & Machine Learning_** di **Purwadhika Digital Technology School**, setiap siswa ditugaskan untuk membuat sebuah program akhir dengan produk akhir yaitu sebuah program sederhana menggunakan Python yang memuat 4 buah function utama: **Create, Read, Delete dan Update**.

Topik yang saya dapatkan adalah untuk membuat program tersebut untuk dipergunakan dalam **transaksi di toko**. *Scope* yang saya ambil adalah sebuah toko kelontong yang menjual barang-barang kebutuhan dasar yang dibutuhkan warga sekitar toko tersebut.
Toko tersebut saya namakan Toko Kelontong JCDS, dan berikut penjelasan atas program tsb:

1. *Interface* awal terbagi menjadi menu untuk *login* sebagai karyawan toko atau *customer*, dengan pilihan *exit* di menu ke-3 yang menjadi satu-satunya jalan untuk keluar dari program ini.
- ![Capture1](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture1.JPG?raw=true)

2. Jika user memilih menu 1 untuk masuk sebagai karyawan toko,  maka program akan meminta user untuk memasukkan *password* yang sudah di-*define* sebelumnya.
- ![Capture2](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture2.JPG?raw=true)

3. Jika *password* salah, maka akan ada pemberitahuan bahwa *login* tidak bisa dilakukan dan program akan kembali
ke *interface* awal. 

- ![Capture3](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture3.JPG?raw=true)

4. Jika *password* benar, maka program akan berlanjut ke interface menu untuk pegawai, yang terdiri dari Tampilkan
Stok (*Read*), Tambah Barang (*Create*), Update Stok (*Update* dan *Delete*), dengan pilihan ke-4 untuk kembali ke Menu Utama.

- ![Capture4](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture4.JPG?raw=true)

5. Ketika user memilih menu untuk tampilkan stok, maka akan muncul 3 buah opsi tampilan, yaitu tampilan per kategori, tampilkan semua stok, dan tampilkan sesuai keyword yang diinput user.

- ![Capture5](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture5.JPG?raw=true)

6. Ketika user memilih opsi untuk menampilkan stok per kategori, maka akan muncul 3 buah kategori stok yang dipunyai toko, yaitu bahan masak, minuman dan makanan. Pada program ini, dimungkinkan untuk menambahkan kategori stok baru selain 3 kategori yang sudah ada namun belum dapat ditampilkan secara terpisah (hanya akan muncul ketika dimasukkan nama barang dimasukkan sebagai *keyword* atau ditampilkan semua).

- ![Capture6](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture6.JPG?raw=true)

7. Sebagai contoh, berikut tampilan ketika *user* memilih menampilkan stok yang masuk kategori bahan masak. Setelah stok bahan masak ditampilkan, program akan langsung menampilkan kembali menu tampilan stok.

- ![Capture7](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture7.JPG?raw=true)

8. Berikut tampilan ketika *user* ingin menampilkan semua stok di toko.

- ![Capture8](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture8.JPG?raw=true)

9. Ketika *user* memilih untuk menampilkan stok sesuai *keyword*, maka *user* akan diminta untuk memasukkan/meng*input* *keyword* barang yang ingin ditampilkan.

- ![Capture9](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture9.JPG?raw=true)

10. Ketika *user* memasukkan kata kunci dengan contoh "susu", maka semua stok yang memuat kata "susu" dalam nama barangnya akan ditampilkan (tidak peduli diketik dengan *lowercase*/*uppercase*/campuran).

- ![Capture10](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture10.JPG?raw=true)

11. Untuk alasan keamanan, setiap kali *user* ingin kembali ke menu utama, maka program akan meminta *user* untuk meng*input* kembali *password* pegawai. Jika salah, maka program akan dikembalikan ke *interface* awal.

- ![Capture11](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture11.JPG?raw=true)

12. Ketika *user* memilih menu untuk menambahkan stok baru, maka *user* akan diminta untuk memasukkan nama barang (maks 10 karakter) dan program akan menolak input nama barang baru jika nama sama dengan nama stok yang sudah ada didalam sistem. Jika semua informasi stok baru sudah dimasukkan sesuai ketentuan,
maka akan muncul sebuah *checker* apakah user yakin untuk menambahkan item. Jika memasukkan value "Y" atau "y", maka item baru beserta seluruh informasinya akan dimasukkan kedalam list stok.

- ![Capture12a](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture12a.JPG?raw=true)

- ![Capture12b](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture12b.JPG?raw=true)

13. Untuk menu *update* stok, jenis *update* terdiri dari *update* detail stok (hanya untuk barang yang sudah ada di dalam stok) dan *delete* stok.

- ![Capture13](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture13.JPG?raw=true)

14. Ketika memilih menu *update* detail barang, maka program akan meminta *user* untuk memasukkan nama barang yang ingin diupdate dari list barang yang ditampilkan. *Update* yang dapat dilakukan meliputi semua detail barang (nama, kemasan, kategori,
jumlah stok dan harga per unit). 

- ![Capture14a](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture14a.JPG?raw=true)

- ![Capture14b](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture14b.JPG?raw=true)

15. Untuk proses *delete* barang di dalam stok, user cukup memasukkan input nama barang yang ingin dibuang dari daftar stok, dan item akan dieliminasi dari daftar stok setelah konfirmasi dari user.

- ![Capture15a](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture15a.JPG?raw=true)

- ![Capture15b](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture15b.JPG?raw=true)

16. Beralih ke *interface* pembeli, tidak ada pilihan untuk memasukkan kode pegawai dan pilihan menu hanya ada 2, yaitu tampilkan daftar barang (sama persis seperti menu tampilkan
stok barang di interface karyawan) dan menu belanja. 

- ![Capture16](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture16.JPG?raw=true)

17. Dalam menu belanja, *user* akan ditampilkan stok barang yang dapat dibelanjakan. Ketika *user* memasukkan nama barang yang salah atau jumlah barang yang melebihi stok, maka program tidak mendeteksi bahwa pembelian tidak dapat dilakukan. Ketika *user* selesai berbelanja, maka program akan otomatis menampilkan keranjang belanja beserta total harga yang perlu dibayar *user*.

- ![Capture17a](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture17a.JPG?raw=true)

- ![Capture17b](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture17b.JPG?raw=true)

18. Jika *user* memasukkan uang yang lebih sedikit dari total belanja, maka program akan menolak pembayaran sampai user memasukkan uang yang sesuai atau melebihi total belanja. Program juga akan otomatis menghitung kembalian jika uang yang diserahkan
lebih dari total belanja, sekaligus mengurangi jumlah stok dari daftar stok toko.

- ![Capture18a](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture18a.JPG?raw=true)

- ![Capture18b](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture18b.JPG?raw=true)

- ![Capture18c](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture18c.JPG?raw=true)

### Video Penjelasan Dapat Diakses di Kanal Youtube Berikut:
[![Capture_Youtube](https://github.com/kevinchenkc/SimpleMarketProgram/blob/main/Capture_Youtube.JPG?raw=true)](https://www.youtube.com/watch?v=eBpQlJm8hAk)

<hr>

### *For queries or collaboration, please reach me on my social media below*:
[Instagram](https://www.instagram.com/kevinchenkc) |
[LinkedIn](https://www.linkedin.com/in/kevinchenkc/) |
[Facebook](https://www.facebook.com/kevin.chen.5688476/) |
📞: (+62)-877 8123 2862
