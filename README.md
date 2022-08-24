# Memulai nodejs express prisma dan nodemon

Projek ini menggunakan nodejs, express dan prisma sebagai ORM [panduan prisma](https://prisma.io), [panduan nodemon](https://nodemon.io/)

## Langkah-langkah

Buat folder Project kemudian didalam folder tersebut jalankan cmd, selanjutnya ketikkan perintah:

### `npm init -y`

Untuk inisiasi project nodejs

### `npm i express cors dotenv`

Untuk install framework express cors dan dotenv

### `npm i -D prisma`

Untuk install prisma di devDependencies

### `npm i @prisma/client`

Untuk install prisma client

### `npx prisma init`

Untuk generate configurasi prisma, setelah menjalankan script ini akan menggenerate folder prisma beserta schema.prisma dan .env 

Proses selanjutnya configurasi schema.prisma dan update koneksi database di .env

### `npx prisma migrate dev`

Untuk generate table di database, sebelum menjalankan command ini, pastikan database sudah running.

### `npm i -g nodemon`

Unuk install nodemon secara global, nodemon inin untuk nge running script nodejs tanpa harus di restart jika update script.

### `nodemon index`

Untuk menjalankan aplikasi.


## Testing API

Untuk mencoba rest API bisa menggunakan postman atau menggunakan extention REST Client di VSCode. Untuk contoh dengan menggunakan REST Client bisa dilihat di pada file `request.rest`