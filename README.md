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


<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/02137949-aca8-4592-81ec-12e71339be05" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/6f700fc9-dec5-42ac-858e-eae5ff2b873d" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/691ac14b-4644-4cec-99f1-f9b013a69ff9" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/7daee91a-44cd-4f2b-8922-fd2e7be2ffa0" />
