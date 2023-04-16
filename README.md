# Python Kasir Mandiri

![image](https://github.com/klinikdata/Project-Pacmann-Python-Kasir-Mandiri/blob/main/images/Cover.png)


## Latar Belakang
Kasir adalah profesi yang bertugas mengurus transaksi dan menyimpan pembayaran berupa uang tunai. Kasir dapat kita temukan di berbagai tempat seperti pada supermarket, coffee shop, toko buku dan masih banyak lagi. Kasir memiliki tugas dan tanggung jawab diantaranya seperti mencatat data penjualan, melakukan proses transaksi penjualan, membuat laporan rutin dan merekap laporan transaksi penjualan. Proyek kali ini akan membuat  sistem kasir self-service (Kasir Mandiri) dimana para pembeli/customer dapat menginputkan item yang ingin diorder secara mandiri. Hal ini bertujuan agar system ini nantinya dapat menimalisir cost yang harus dibayarkan, sehingga upah dari kasir dapat dialokasikan ke bagian lain, seperti meningkatkan kualitas produk yang dijual, promosi dll.

## Requirements
Berikut adalah beberapa fitur yang mungkin dibutuhkan dalam program Kasir Mandiri menggunakan Python :
1.	Membuat ID transaksi customer
2.	Input barang : Program harus memungkinkan pengguna memasukkan nama barang, jumlah barang dan harga barang yang dibeli. 
3.	Jika terjadi kesalahan dalam penginputan, customer dapat melakukan : update nama barang, jumlah barang dan harga barang 
4.	JIka customer batal melakukan transaksi, customer dapat menghapus sebagian item/barang yang ingin di delete atau ingin menghapus seluruhnya (reset).
5.	Jika customer ingin melakukan crosscek kembali hasil barang yang sudah dipesan/input, customer dapat melakukan pengecekan dengan ketentuan :  “Pemesanan sudah benar”, jika tidak ada kesalahan input dan “Terdapat kesalahan input data”,  jika terjadi kesalahan input
6.	Menampilkan tabel output pemesanan yang telah disorder dimana program harus dapat menghitung total harga barang yang dibeli berdasarkan harga dan jumlah barang yang dimasukkan.
7.	Diskon: Program harus memungkinkan pengguna menerapkan diskon pada total harga berdasarkan persentase diskon yang dimasukkan.


Adapun ketentuan diskonnya adalah :

a. Total belanja > Rp. 200.000 : diskon 5%
b. Total belanja > Rp. 300.000 : diskon 6%
c. Total belanja > Rp. 500.000 : diskon 7%

## Flowchart
Berikut adalah beberapa fitur yang mungkin dibutuhkan dalam program kasir self-service menggunakan Python :
![image](https://github.com/klinikdata/Project-Pacmann-Python-Kasir-Mandiri/blob/main/images/Flowchart.png)

## Penjelasan dari Function
Proyek ini terdiri dari 2 file yaitu main.py dan modul.py yang masing-masing memiliki kegunaan.
•	file main.py digunakan sebagai file utama untuk menjalankan program Kasir Mandiri.
•	file modul.py digunakan sebagai modul yang berisi class, function dan attributes. 
•	file requirements.txt digunakan sebagai daftar dependensi atau pustaka Python yang diperlukan oleh suatu proyek.

1.	init() : Fungsi inisialisasi untuk class Transaction, 
Data_order = dictionary untuk menyimpan data tranasaksi

2.	add_item : method untuk menambahkan item ke dalam dictionary transaksi

3.	update_item_name : method untuk mengubah nama item yang sudah diinput di dictionary transaksi

4.	update_item_qty : method untuk mengubah jumlah item yang sudah diinput di dictionary transaksi

5.	update_item_price : method untuk mengubah harga item yang sudah diinput di dictionary transaksi

6.	delete_item : method untuk menghapus nama item termasuk jumlah dan harga yang sudah diinput di dictionary transaksi

7.	reset_transaction : method untuk menghapus semua data pesanan yang telah terinput

8.	check_order : method untuk menampilkan dan memeriksa semua pesanan yang sudah di input di dictionary transaksi, termasuk jika mendapatkan diskon.

9.	total_price: method untuk menampilkan total belanja

## Test Case
Berikut adalah beberapa fitur yang mungkin dibutuhkan dalam program kasir self-service menggunakan Python : 

Test 1:
Customer ingin menambahkan dua item/barang baru menggunakan method add_item(). Item yang ditambahkan adalah sebagai berikut :

•	Nama Item: Ayam Goreng, Qty: 2, Harga: 20000
•	Nama Item: Pasta Gigi, Qty: 3, Harga: 15000

Expected Output :
![image](https://github.com/klinikdata/Project-Pacmann-Python-Kasir-Mandiri/blob/main/images/Test%201.%20Menambahkan%20Item.png)

Test 2:
Customer menggunakan method delete_item() untuk menghapus item. Item yang ingin dihapuskan adalah Pasta Gigi
Expected Output :
![image](https://github.com/klinikdata/Project-Pacmann-Python-Kasir-Mandiri/blob/main/images/Test%202.%20Menghapus%20Item.png)

Test 3:
Menghapus semua data transaksi dengan method reset_transaction().
Expected Output :
![image](https://github.com/klinikdata/Project-Pacmann-Python-Kasir-Mandiri/blob/main/images/Test%203.%20%20Menghapus%20Semua%20Data%20Trx.png)


Test 4:
Mengubah nama produk dengan method update_item_name().
Expected Output :
![image](https://github.com/klinikdata/Project-Pacmann-Python-Kasir-Mandiri/blob/main/images/Test%204.%20%20Mengubah%20Nama%20Produk.png)


Test 5:
Mengubah kuantitas produk dengan method update_item_qty().
Expected Output :
![image](https://github.com/klinikdata/Project-Pacmann-Python-Kasir-Mandiri/blob/main/images/Test%205.%20%20Mengubah%20Jumlah%20Produk.png)


Test 6:
Mengubah harga produk dengan method update_item_price().

Expected Output :
![image](https://github.com/klinikdata/Project-Pacmann-Python-Kasir-Mandiri/blob/main/images/Test%206.%20%20Mengubah%20Harga%20Produk.png)


Test 7:
Memeriksa data order dengan method check_order().

Expected Output :
![image](https://github.com/klinikdata/Project-Pacmann-Python-Kasir-Mandiri/blob/main/images/Test%207.%20%20Memeriksa%20Pesanan%20Kembali.png)


Test 8:
Menampilkan total belanja dengan method total_price()

Expected Output :
![image](https://github.com/klinikdata/Project-Pacmann-Python-Kasir-Mandiri/blob/main/images/Test%208.%20%20Menghasilkan%20Total%20Harga.png)

![image](https://github.com/klinikdata/Project-Pacmann-Python-Kasir-Mandiri/blob/main/images/Test%208.%20%20Menghasilkan%20Total%20Harga%20Setelah%20Diskon.png)

Test 9:
Keluar dari aplikasi Kasir Mandiri

Expected Output :
![image](https://github.com/klinikdata/Project-Pacmann-Python-Kasir-Mandiri/blob/main/images/Test%209.%20Keluar%20dari%20Aplikasi%20Kasir%20Mandiri.png)

## Kesimpulan
Sistem kasir self-service atau Kasir Mandiri pada supermarket telah memberikan kemudahan bagi pelanggan dalam melakukan transaksi secara mandiri. Namun, sistem ini perlu ditingkatkan performanya dan diperbaiki tampilannya agar lebih menarik dan mudah digunakan. Dengan demikian, supermarket dapat terus memberikan pelayanan yang baik bagi pelanggan dan memperkuat posisinya sebagai tempat belanja yang dapat diandalkan.
