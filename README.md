# Conventional Commit
Repository ini bisa menjadi acuan untuk teman-teman dalam penggunaan conventional commit dalam version control

## Apa itu Conventional Commit?
Conventional Commit adalah standar dalam penulisan pesan commit yang bertujuan untuk menjaga konsistensi, memudahkan pembacaan riwayat commit, serta memungkinkan otomatisasi dalam pengelolaan versi aplikasi.

## Format Penulisan
Format dasar Conventional Commit adalah sebagai berikut:
```
(type)(scope):(deskripsi)
```
Penjelasan:
- type (wajib) → Jenis perubahan yang dilakukan.
- scope (opsional) → Bagian kode atau modul yang terpengaruh.
- pesan singkat (wajib) → Deskripsi singkat tentang perubahan yang dilakukan.

contoh
```
feat(login): Menambahkan autentikasi login menggunakan bycrypt
```

### Macam - macam type
| Kategori   | Deskripsi |
|------------|-----------|
| feat       | Menambahkan fitur baru |
| fix        | Memperbaiki bug |
| refactor   | Perubahan kode tanpa mengubah fungsionalitas |
| chore      | Perubahan kecil yang tidak berpengaruh pada kode produksi (misalnya: pembaruan dependensi) |
| test       | Menambahkan atau memperbaiki pengujian |
| docs       | Perubahan dokumentasi |
| style      | Perubahan tampilan atau format kode tanpa mengubah logika |
| perf       | Peningkatan performa |
| ci         | Perubahan pada konfigurasi CI/CD |

<!--Versi 1.0.0 20/03/2025-->
