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
