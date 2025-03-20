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
feat(login): menambahkan autentikasi login menggunakan bycrypt
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


### Penggabungan antara Pull Request dan Refs

Conventional commits juga menyeragamkan pesan
contoh
```
feat(ui): menambahkan layout untuk page login

menambahkan login dengan warna hitam menggunakan tailwind

Reviewed-by: @yogaardiansyah
Refs #1
```

penjelasan :
- feat(ui): – Ini menunjukkan bahwa commit ini adalah fitur baru (feat) dan bagian yang diubah adalah bagian UI (user interface).
- menambahkan layout untuk page login – Deskripsi singkat tentang perubahan yang dilakukan, dalam hal ini menambahkan layout untuk halaman login.
- menambahkan login dengan warna hitam menggunakan tailwind – Ini adalah penjelasan lebih lanjut (body) yang memberi informasi lebih detail tentang - perubahan yang dilakukan.
- Reviewed-by: @yogaardiansyah – Ini adalah tag yang menunjukkan siapa yang telah melakukan review untuk commit tersebut. Tag ini langsung menyebutkan - username GitHub reviewer, yang akan menjadi tautan aktif ke profil GitHub mereka jika melihat commit di GitHub.
- Refs #1 – Ini adalah referensi ke issue atau PR lain yang terkait dengan commit ini. #1 mengacu pada issue atau PR dengan nomor 1.

<!--Versi 1.0.1 20/03/2025-->
<!--Menambahkan bagian Penggapungan antara Pull Request dan Refs>