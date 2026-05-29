# Bookshelf API 

Proyek ini adalah *submission* untuk kelas **Belajar Membuat Aplikasi Back-End untuk Pemula** di Dicoding. Di sini saya membangun RESTful API sederhana untuk manajemen rak buku (Bookshelf).


## Fitur API
Aplikasi ini sudah memenuhi semua kriteria pengujian otomatis di Postman (wajib dan opsional untuk target Bintang 5):
* **Tambah Buku** (`POST /books`) beserta validasi input.
* **Tampilkan Semua Buku** (`GET /books`) dengan dukungan *query parameters* (`?name`, `?reading`, `?finished`).
* **Detail Buku** (`GET /books/{bookId}`) untuk melihat data lengkap per buku.
* **Ubah Data Buku** (`PUT /books/{bookId}`) untuk memperbarui informasi buku.
* **Hapus Buku** (`DELETE /books/{bookId}`) dari penyimpanan.

## Tech Stack
* **Runtime:** Node.js
* **Framework:** Hapi.js
* **ID Generator:** Nanoid (v3)
* **Linter:** ESLint

## Cara Menjalankan

1. Clone repositori :
```bash
git clone [https://github.com/arieffathin/bookshelf-api.git](https://github.com/arieffathin/bookshelf-api.git)
cd bookshelf-api
```

2. Install  *dependencies* :
```bash
npm install
```

3. Jalankan aplikasi :
```bash
npm run start-dev
```

