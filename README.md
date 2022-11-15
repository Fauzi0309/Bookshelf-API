# Bookshelf-API

### Kriteria 1 : API dapat menyimpan buku
API yang Anda buat harus dapat menyimpan buku melalui route:
* Method : POST
* URL : /books

### Kriteria 2 : API dapat menampilkan seluruh buku
API yang Anda buat harus dapat menampilkan seluruh buku yang disimpan melalui route:
* Method : GET
* URL: /books

### Kriteria 3 : API dapat menampilkan detail buku
API yang Anda buat harus dapat menampilkan seluruh buku yang disimpan melalui route:
* Method : GET
* URL: /books/{bookId}

### Kriteria 4 : API dapat mengubah data buku
API yang Anda buat harus dapat mengubah data buku berdasarkan id melalui route:
* Method : PUT
* URL : /books/{bookId}

Kriteria 5 : API dapat menghapus buku
API yang Anda buat harus dapat menghapus buku berdasarkan id melalui route berikut:
* Method : DELETE
* URL: /books/{bookId}

### Tambahkan fitur query parameters pada route GET /books (Mendapatkan seluruh buku).
* ?name : Tampilkan seluruh buku yang mengandung nama berdasarkan nilai yang diberikan pada query ini. Contoh /books?name=”dicoding”, maka akan menampilkan daftar buku yang mengandung nama “dicoding” secara non-case sensitive  (tidak peduli besar dan kecil huruf).
* ?reading : Bernilai 0 atau 1. Bila 0, maka tampilkan buku yang sedang tidak dibaca (reading: false). Bila 1, maka tampilkan buku yang sedang dibaca (reading: true). Selain itu, tampilkan buku baik sedang dibaca atau tidak.
* ?finished : Bernilai 0 atau 1. Bila 0, maka tampilkan buku yang sudah belum selesai dibaca (finished: false). Bila 1, maka tampilkan buku yang sudah selesai dibaca (finished: true). Selain itu, tampilkan buku baik yang sudah selesai atau belum dibaca.

### Menerapkan CORS pada seluruh resource yang ada.
### Menggunakan ESLint dan salah satu style guide agar gaya penulisan kode JavaScript lebih konsisten.
