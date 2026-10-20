<img width="3000" height="1876" alt="image" src="https://github.com/user-attachments/assets/44c0b060-a97d-4cf7-b57b-d6b4d6645e84" />

## Deskripsi
Praktikum ini bertujuan untuk menguji endpoint REST API lokal menggunakan Postman. Pada gambar, request `GET` dikirim ke `http://localhost:3000/` dan berhasil mengembalikan data mahasiswa dalam format JSON.

## Tujuan Praktikum
- Mengirim request HTTP menggunakan Postman.
- Mengakses endpoint API lokal.
- Memeriksa status respons dan data JSON yang diterima.

## Tools yang Digunakan
- **Node.js** — menjalankan server API lokal.
- **Postman** — mengirim request dan melihat respons API.
- **Server lokal** — berjalan pada `http://localhost:3000/`.

## Langkah-Langkah Praktikum
1. Jalankan server API Node.js pada komputer.
2. Buka Postman dan buat request baru.
3. Pilih metode **GET**.
4. Masukkan URL `http://localhost:3000/`.
5. Klik **Send**.
6. Periksa status respons dan isi JSON pada panel respons.

## Hasil Praktikum
Request berhasil dengan status **200 OK**. API mengembalikan tiga data mahasiswa dalam bentuk array JSON, dengan struktur objek berisi `id`, `nama`, `nim`, dan `kelas`.

Contoh respons berdasarkan hasil pada gambar:

```json
[
  {
    "id": 1,
    "nama": "jokowik",
    "nim": "20250140001",
    "kelas": "D"
  },
  {
    "id": 2,
    "nama": "Gibran Bumihancur",
    "nim": "20250140002",
    "kelas": "D"
  },
  {
    "id": 3,
    "nama": "Kaes sangkuriang",
    "nim": "20250140003",
    "kelas": "D"
  }
]
```

## Kesimpulan
Praktikum menunjukkan bahwa endpoint API lokal dapat diakses melalui Postman. Status `200 OK` menandakan request berhasil diproses, sedangkan respons JSON menunjukkan bahwa API mengirimkan daftar data mahasiswa.

