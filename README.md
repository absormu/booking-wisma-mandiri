# booking-wisma-mandiri
Aplikasi Sewa Ruang Serbaguna di Wisma Mandiri Jakarta Pusat

# Fitur Akses
* Login
```
  username
  password
```
* Registrasi
```
  id
  nama
  username
  password
  email
  perusahaan
  no_hp
  alamat
  level : 1 -> admin & 0 -> user
```

# Fitur Master
* Create Ruang : admin
```
  id
  nama
  harga
  luas
  image
  deskripsi
```

# Fitur Booking
* Create Booking : admin/user
```
  id
  no_order
  tgl
  id_ruang
  id_user
  periode_booking_start
  periode_booking_end
  total_qty
  total_price
  dp 50%
  status_payment : booking
  deskripsi
  * perlu ada pengecekan apakah ruangan sudah di booking atau belum 
  * jika sudah ada maka balikin ruangan sudah di pesan silahkan pilih tanggal lain
```
* List Booking by user : admin/user
```
  no_order
  periode_booking_start
  periode_booking_end
  nama_ruang : join
  nama_user : join
  total_qty
  total_price
  status_payment 
  deskripsi
  *jika level user maka menampilkan data user itu sendiri
```
* Payment/Pembayaran : admin
```
  id
  tgl
  no_order
  id_user_admin
  total_payment
  status_payment : paid
  deskripsi
```

# Fitur Report
* Report Booking by periode date/user : admin/user
```
  no_order
  periode_booking_start
  periode_booking_end
  nama_ruang : join
  nama_user : join
  total_qty
  total_price
  status_payment 
  deskripsi
  *jika level user maka menampilkan data user itu sendiri
```
* Report User : admin
```
  id
  nama
  email
  perusahaan
  no_hp
  alamat
```
