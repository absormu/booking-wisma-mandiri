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
  password
  email
  perusahaan
  no_hp
  alamat
```

```
  Login ada 2 level admin & user
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
```
* List Booking by user : admin/user
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
* Report Booking by periode date : admin
* Report Booking by periode user : admin/user
* Report User : admin
