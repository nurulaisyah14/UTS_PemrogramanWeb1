# UTS_PemrogramanWeb
## PROFIL
| Variable           |             Isi            |
| -------------------|----------------------------|
| **Nama**           |         Nurul Aisyah       |
| **NIM**            |          312310476         |
| **Kelas**          |          TI.23.A.5         |
| **Mata Kuliah**    |      Pemrograman Web 1     |
| **Dosen Pengampu** | Eko Budiarto s.kom, m.kom  |


# CODE PROGRAM WEBSITE DINAMIS
![image](https://github.com/user-attachments/assets/efe01194-f17f-448e-b49e-b9746f7415af)
```
- Header: Menampilkan judul "Membuat Website Dinamis" dan navbar dari file navbar.php.
- Bagian Utama: Memuat konten berdasarkan parameter URL (page), defaultnya adalah halaman home.php.
- Formulir: Terdapat form untuk memasukkan email dan password, menggunakan desain Bootstrap.
- Footer: Menampilkan informasi kontak, tautan ke media sosial, dan alamat.
- Gaya dan JavaScript: Menggunakan CSS untuk desain dan JavaScript untuk menginisialisasi interaktivitas, seperti DataTables jika ada elemen tabel.

</html>
```
![image](https://github.com/user-attachments/assets/cae0d7b8-f1aa-4865-b57f-47cdb75b1c6e)

![image](https://github.com/user-attachments/assets/9a5b8d9e-7f33-4e2b-8aed-95c07bafcbbf)

![image](https://github.com/user-attachments/assets/2151dd93-39db-4cc5-af5a-1c1492f2680a)

![image](https://github.com/user-attachments/assets/d20912c2-d745-433d-82de-9291e6e1a0c0)
![image](https://github.com/user-attachments/assets/774ff0a7-6d20-40d7-a9ff-cd6c19e07d72)
![image](https://github.com/user-attachments/assets/383d4c8b-a6e2-4e7c-b74a-04bea87ed8e8)
![image](https://github.com/user-attachments/assets/3b51d824-5d68-448c-aad5-e7be10f55b22)
![image](https://github.com/user-attachments/assets/1ebdda68-2262-4356-9599-d940fff17ce3)
![image](https://github.com/user-attachments/assets/a0b88206-1c5c-43db-aee8-7b0f7607c25e)
![image](https://github.com/user-attachments/assets/3181fe68-9c46-4306-b3ba-a02606bdaaa1)

**Struktur HTML Dasar:**
```
- Kode dimulai dengan deklarasi <!DOCTYPE html> yang menunjukkan bahwa ini adalah dokumen HTML5.
- Elemen <html lang="en"> menandakan bahwa bahasa utama dari halaman ini adalah Inggris.
```
**Head Section:**
```
- Dalam elemen <head>, terdapat meta tag <meta charset="UTF-8"> yang mengatur karakter encoding ke UTF-8, memastikan dukungan untuk berbagai karakter.
- Judul halaman ditetapkan dengan <title>Membuat Website Dinamis</title>.
- Dua link stylesheet dimasukkan:
  - DataTables CSS: https://cdn.datatables.net/1.11.5/css/jquery.dataTables.min.css untuk styling tabel.
  - Bootstrap CSS: https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css untuk styling umum dan komponen responsif.
- Tiga skrip JavaScript diimpor:
  - jQuery: https://code.jquery.com/jquery-3.5.1.js untuk mempermudah manipulasi DOM.
  - DataTables JS: https://cdn.datatables.net/1.11.5/js/jquery.dataTables.min.js untuk memberikan fungsionalitas interaktif pada tabel.
  - Bootstrap JS: https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.bundle.min.js untuk fungsionalitas Bootstrap.
```
**Body Section:**
```
- Di dalam <body>, terdapat elemen <div class="container"> yang memberikan batas dan padding pada konten.
- Judul halaman ditampilkan dengan <h1>DataTables Example</h1>.
- Tabel utama dengan ID example didefinisikan menggunakan elemen <table>, dengan <thead>, <tbody>, dan <tfoot> yang terstruktur.
  - Header Tabel (<thead>): Berisi kolom yang menunjukkan nama, posisi, kantor, usia, tanggal mulai, dan gaji.
  - Body Tabel (<tbody>): Menampilkan data karyawan fiktif, di mana setiap <tr> (baris) berisi data untuk seorang karyawan.
  - Footer Tabel (<tfoot>): Mengulangi header tabel untuk konsistensi.
```
**Script untuk Inisialisasi DataTables:**
```
- Di bagian bawah <body>, ada skrip jQuery yang diinisialisasi dengan $(document).ready(function() { $('#example').DataTable(); });.
- Skrip ini memastikan bahwa saat halaman sepenuhnya dimuat, tabel dengan ID example akan diubah menjadi tabel DataTables, memberikan fitur pencarian, pengurutan, dan paginasi.
```
# SELESAI

