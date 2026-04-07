# Lab7web.

**Nama : M. Iqbal**

**Kelas : 124ib**

**Nim : 312410212**

# Praktikum 1

Repositori ini dibuat untuk memenuhi tugas praktikum Pemrograman Web (Lab 7). Aplikasi ini mendemonstrasikan operasi dasar **CRUD** (Create, Read, Update, Delete) pada data mahasiswa menggunakan PHP dan MySQL.

## Fitur Utama
- Menampilkan daftar mahasiswa (Read)
- Menambahkan data mahasiswa baru (Create)
- Mengubah data mahasiswa (Update)
- Menghapus data mahasiswa (Delete)

## Teknologi yang Digunakan
- PHP (Native)
- MySQL / MariaDB
- HTML5 & CSS3
- Bootstrap (untuk tampilan responsif)

## Cara Menjalankan
1. Clone repositori ini ke folder `htdocs` (jika menggunakan XAMPP) atau `www` (jika menggunakan Laragon).
2. Impor database dari file `database.sql` (jika tersedia). Jika tidak ada, buat database dengan nama `lab7web` dan tabel `mahasiswa`:
   ```sql
   CREATE TABLE mahasiswa (
       id INT(11) AUTO_INCREMENT PRIMARY KEY,
       nim VARCHAR(20) NOT NULL,
       nama VARCHAR(100) NOT NULL,
       jurusan VARCHAR(50)
   );

1. Instalasi CodeIgniter 4
   <img width="1919" height="1067" alt="image" src="https://github.com/user-attachments/assets/4d9ce3c3-92ce-48d3-bdc1-232d3b0cbed6" />
   
2. Menjalankan CLI
   <img width="1552" height="1176" alt="Screenshot 2026-04-06 162315" src="https://github.com/user-attachments/assets/45f9c0d5-bc6f-4951-bbc4-a7926b7e1515" />

3. Mengaktifkan Mode Debugging
   <img width="1622" height="583" alt="image" src="https://github.com/user-attachments/assets/96e68314-124a-4f90-bffd-75b45418aa54" />
---
   <img width="1190" height="428" alt="image" src="https://github.com/user-attachments/assets/49059b10-7c80-4d48-94cb-6bbf5ac2686c" />

4. Halaman about
<img width="1915" height="1067" alt="Screenshot 2026-04-07 105309" src="https://github.com/user-attachments/assets/ad088cb0-a61c-4a45-a5cd-256cf834db96" />

   
6. halaman contact

   <img width="1917" height="1058" alt="Screenshot 2026-04-07 105253" src="https://github.com/user-attachments/assets/aba49a76-3208-4592-86e0-99c810fe36eb" />


7. halaman faq
    <img width="1915" height="1067" alt="Screenshot 2026-04-07 105235" src="https://github.com/user-attachments/assets/65c896c6-1688-48e9-b7d6-288c3db43448" />
