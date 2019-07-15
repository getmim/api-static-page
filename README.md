# api-static-page

## Instalasi

Jalankan perintah di bawah di folder aplikasi:

```
mim app install api-static-page
```

## Endpoints

### `APIHOST/page`

Mengambil semua halaman yang terdaftar. Endnpoint ini menerima pagination query ( page, rpp ). Selain itu juga menerima query string `q` untuk memfilter halaman dari properti `title`.

### `APIHOST/page/(id|slug)`

Mengambil properti lengkap suatu halaman.