# Aplikasi Pengelola Penjualan Dan Pembelian Ikan Berbasis Mobile


![DIGRAM BLOK](https://user-images.githubusercontent.com/80630206/162011383-ac8f8e49-e466-4d67-b0b2-c724faf5755b.jpeg)


# Deskripsi_Proyek
Aplikasi ini di buat untuk mempermudahkan para nelayang dan para membeli, dengn Fitur-Fitur sebagai berikut:
1. Melakukan pemesanan Ikan 
2. Melihat Setok ikan Yang tersedia
3. Mencatat riwayat pemesanan ikan
4. Melakukan pembayaran ikan 
5. Mencatat riwayat transaksi pembayaran Ikan

## Entitas dan Atribut

Admin
1. Id_admin
2. Email
3. Password


User ( 
1. ID_user
2. Email
3. Password
4. Nama lengkap
5. no_telepon
6. Alamat


Pemesanan
1. Id_pemesanan
2. Id_user
3. Id_pembayaran
4. Tanggal
5. Status
6. Total harga

Nelayan
1. Id_nelayan
2. Nama
3. Jenis kelamin
4. Jumlah ikan

Gudang IKAN
1. Setok Ikan
2. Jenis ikan


##USER 

1. id user INT NOY NULL
2. email CHAR(50) NOT NULL
3. password CHAR (256) NOT NUL
4. nama_ lengkap CHAR(50)
5. no_telepon.CHAR(50).
6. alamat CHAR(253)

 Pemesanan
1. pemesanan INT NOT NULL
2. user INT NOT NULL
3. id_pembayaran INT NOT NULL
4. status INT
5. total_harga INT

Detail pemesanan
1. id detail pem INT NOT NULL
2. id_pemesanan INT NOT NULL
3. id_loket INT NOT NULL
4. jenis ikan INT NOT NULL
5. jumlah INT
6. tota__harga INT


Pembayaran
1. id pembayaran INT NOT NULL
2. kode pembayaran CHAR(24) NOT NULL 
3. ama_pembayar CHAR(24) NOT NULL
4. jenis pembayaran CHAR(24) NOT NULL

jenis
1. id ikan INT NOT NULL
2. ikan harha INT NOT NULL
3. harga INT NOt NULI


jenis ikan
1. id jenis ikan INT NOT NULL
2. denis ikan INT NOT NULL
3. nama CHAR(24) NOT NUL
