# Aplikasi Pengelola Penjualan Dan Pembelian Ikan Berbasis Mobile


![DIGRAM BLOK](https://user-images.githubusercontent.com/80630206/162011383-ac8f8e49-e466-4d67-b0b2-c724faf5755b.jpeg)

![WhatsApp Image 2022-06-14 at 16 55 30](https://user-images.githubusercontent.com/80630206/173550428-155dea8a-3f74-4c7b-830b-cd748281749e.jpeg)

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
3. jenis ikan INT NOT NULL
4. jumlah INT
5. tota__harga INT


Pembayaran
1. id pembayaran INT NOT NULL
2. kode pembayaran CHAR(24) NOT NULL 
3. nama_pembayar CHAR(24) NOT NULL
4. jenis pembayaran CHAR(24) NOT NULL

jenis
1. id ikan INT NOT NULL
2. ikan harha INT NOT NULL
3. harga INT NOt NULI


jenis ikan
1. id jenis ikan INT NOT NULL
2. denis ikan INT NOT NULL
3. nama CHAR(24) NOT NUL


