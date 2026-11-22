# Lab8Web – PHP dan Database MySQL

Praktikum 8: aplikasi CRUD sederhana (Data Barang) dengan PHP + MySQL.

## Struktur File
| File | Fungsi |
|------|--------|
| `database.sql` | Membuat database `latihan1`, tabel `data_barang`, dan data awal |
| `koneksi.php` | Koneksi ke database |
| `index.php` | Menampilkan data (Read) |
| `tambah.php` | Menambah data (Create) |
| `ubah.php` | Mengubah data (Update) |
| `hapus.php` | Menghapus data (Delete) |
| `style.css` | Tampilan |
| `gambar/` | Folder penyimpanan gambar barang |

## Langkah Praktikum
1. Jalankan **Apache** dan **MySQL** di XAMPP Control Panel. *(screenshot)*
2. Buka `http://localhost/phpmyadmin/`, jalankan isi `database.sql` pada tab SQL. *(screenshot)*
3. Letakkan folder `lab8_php_database` di `htdocs`.
4. Uji koneksi: buka `koneksi.php` (uncomment `echo "Koneksi berhasil"`). *(screenshot)*
5. Buka `http://localhost/lab8_php_database/` → Read. *(screenshot)*
6. Klik **Tambah Barang** → Create. *(screenshot)*
7. Klik **Ubah** → Update. *(screenshot)*
8. Klik **Hapus** → Delete. *(screenshot)*

## Catatan
Lengkapi setiap langkah dengan screenshot, lalu commit ke repository `Lab8Web`.
