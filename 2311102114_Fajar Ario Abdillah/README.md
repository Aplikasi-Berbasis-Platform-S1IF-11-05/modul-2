<div align="center">
  <br />
  <h1>LAPORAN PRAKTIKUM <br> APLIKASI BERBASIS PLATFORM </h1>
  <br />
  <h3>MODUL 2 <br> HTML </h3>
  <br />
  <img width="512" height="512" alt="telyu" src="https://github.com/user-attachments/assets/724a3291-bcf9-448d-a395-3886a8659d79" />
  <br />
  <br />
  <br />
  <h3>Disusun Oleh :</h3>
  <p>
    <strong>Fajar Ario Abdillah</strong>
    <br>
    <strong>2311102114</strong>
    <br>
    <strong>S1 IF-11-REG05</strong>
  </p>
  <br />
  <h3>Dosen Pengampu :</h3>
  <p>
    <strong>Dedi Agung Prabowo, S.Kom., M.Kom</strong>
  </p>
  <br />
  <br />
  <h4>Asisten Praktikum :</h4>
  <strong>Apri Pandu Wicaksono </strong>
  <br>
  <strong>Hamka Zaenul Ardi</strong>
  <br />
  <h3>LABORATORIUM HIGH PERFORMANCE <br>FAKULTAS INFORMATIKA <br>UNIVERSITAS TELKOM PURWOKERTO <br>2026 </h3>
</div>

<hr>

## Dasar Teori

HTML (HyperText Markup Language) adalah bahasa standar yang digunakan untuk membuat dan menyusun halaman web. HTML berfungsi untuk menentukan struktur dasar dari sebuah halaman, seperti judul, paragraf, gambar, tabel, dan elemen lainnya yang akan ditampilkan di browser.

HTML menggunakan sistem tag (penanda) untuk membangun struktur halaman. Tag biasanya ditulis berpasangan, yaitu tag pembuka dan tag penutup, misalnya `<p>` dan `</p>` untuk membuat paragraf. Setiap elemen HTML dapat memiliki atribut yang memberikan informasi tambahan, seperti src pada gambar atau href pada tautan.

Struktur dasar HTML terdiri dari beberapa bagian utama, yaitu:
- `<html>` sebagai elemen utama  
- `<head>` yang berisi informasi halaman (judul, metadata)  
- `<body>` yang berisi konten utama yang ditampilkan kepada pengguna 

HTML sering digunakan bersama dengan CSS (untuk mengatur tampilan) dan JavaScript (untuk menambahkan interaksi) agar halaman web menjadi lebih menarik dan dinamis.

Dengan memahami HTML, seseorang dapat membuat kerangka dasar sebuah website yang dapat diakses melalui internet menggunakan browser.

## Tugas 2 - Ujian Web Purba

```
<!--

2311102114
Fajar Ario Abdillah
S1IF-11-05

-->

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tugas Modul 2 - Tabel Data Akademik</title>
</head>

<body>
    <table border="1" align="center">
        <tr>
            <th rowspan="2">Nama Lengkap</th>
            <th colspan="2">Gelar Pendidikan</th>
            <th rowspan="2">Age</th>
        </tr>

        <tr>
            <th>Sarjana</th>
            <th>Magister</th>
        </tr>

        <tr>
            <td>Fajar</td>
            <td>S.Kom</td>
            <td>M.Sc</td>
            <td>20</td>
        </tr>

        <tr>
            <td>Ario</td>
            <td>S.Kom</td>
            <td>M.T</td>
            <td>21</td>
        </tr>

        <tr>
            <td>Abdillah</td>
            <td>S.Si</td>
            <td>M.Sc</td>
            <td>22</td>
        </tr>
    </table>
</body>

</html>
```

## Screenshot Hasil
![Hasil 1](assets/Screenshot%202026-03-17%20211822.png)

## Penjelasan
Kode di atas adalah kode HTML sederhana dalam membuat Tabel Data Akademik yang berisi Nama Lengkap, Gelar Pendidikan yang terdiri dari Sarjana dan Magister, dan Age/Umur dengan menggunakan tag rowspan dan colspan untuk menggabungkan baris maupun kolom pada tabel.

Terdapat juga tag border berukuran 1 untuk membuat tabel itu sendiri dan tag align untuk memposisikan tabel tersebut berada.

Hasil dari kode tersebut bisa dibuktikan pada Screenshot Hasil sesuai dengan penjelasan di atas.