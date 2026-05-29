# Bookshelf API 📚

Proyek ini adalah *submission* untuk kelas **Belajar Membuat Aplikasi Back-End untuk Pemula** di Dicoding. Di sini saya membangun RESTful API sederhana untuk manajemen rak buku (Bookshelf).

Sesuai dengan kriteria penilaian, aplikasi ini dibuat menggunakan **Node.js** dengan framework **Hapi**. Penyimpanan data masih menggunakan *in-memory array* (tanpa database) agar mudah dijalankan dan diuji oleh *reviewer*.

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

1. Clone repositori ini ke komputer kamu:
```bash
git clone [https://github.com/arieffathin/bookshelf-api.git](https://github.com/arieffathin/bookshelf-api.git)
cd bookshelf-api
```

2. Install semua *dependencies* yang diperlukan:
```bash
npm install
```

3. Jalankan aplikasi dalam mode *development* (otomatis *restart* jika ada perubahan kode):
```bash
npm run start-dev
```
*(Catatan: Untuk menjalankan dalam mode *production*, gunakan perintah `npm run start` sesuai kriteria).*

Aplikasi akan berjalan di `http://localhost:9000` dan siap diuji menggunakan Postman.
