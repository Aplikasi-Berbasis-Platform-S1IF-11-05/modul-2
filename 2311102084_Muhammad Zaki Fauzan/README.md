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
    <strong>Muhammad Zaki Fauzan</strong>
    <br>
    <strong>2311102084</strong>
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

# Dasar Teori
HTML (HyperText Markup Language) merupakan bahasa markup yang digunakan untuk membangun struktur dasar sebuah halaman web. HTML menggunakan berbagai tag untuk menampilkan elemen seperti teks, gambar, tabel, dan hyperlink pada halaman web. Setiap elemen dalam HTML memiliki fungsi tertentu yang membantu membentuk tampilan dan struktur halaman.

Pada awal perkembangan web, pengaturan tata letak halaman belum menggunakan CSS seperti saat ini. Oleh karena itu, developer sering memanfaatkan elemen HTML tertentu untuk mengatur posisi konten pada halaman. Salah satu cara yang sering digunakan adalah menggunakan tabel (`<table>`) sebagai alat untuk mengatur layout. Meskipun pada HTML modern tabel lebih dianjurkan hanya untuk menampilkan data, pada masa awal web tabel sering digunakan untuk mengatur posisi elemen di halaman.

Selain itu, HTML juga memiliki tag lama seperti `<center>` yang digunakan untuk menempatkan suatu elemen tepat di tengah halaman secara horizontal. Tag ini termasuk dalam kategori tag HTML lama yang saat ini sudah jarang digunakan karena fungsinya telah digantikan oleh CSS. Namun, tag tersebut masih dapat digunakan untuk memahami konsep dasar pengaturan tampilan pada web generasi awal.

Dalam praktikum ini, pembuatan tabel dilakukan tanpa menggunakan CSS maupun inline styling. Oleh karena itu, pengaturan posisi tabel di tengah halaman dilakukan dengan memanfaatkan tag HTML klasik seperti `<center>` serta struktur tabel (`<table>`, `<tr>`, dan `<td>`). Dengan memanfaatkan tag-tag tersebut, tabel dapat ditampilkan di tengah halaman meskipun tanpa bantuan CSS atau teknik styling modern.

## Tugas 2 - Ujian Web Purba

Bikin tampilan table dasar, tapi posisinya wajib persis di tengah layar. Nah, syarat utamanya: HARAM pakai CSS, inline style, atau styling apapun. Coba gali lagi ingatan lu soal tag-tag HTML jadul yang bisa ngakalin ini.

<!-- 2311102051
Muhammad Aulia Muzzaki Nugraha
S1IF-11-05 -->

<!DOCTYPE html>
<html>
<head>
    <title>Ujian Web Purba</title>
</head>

<body>

    <table width="100%" height="100%">
        <tr>
            <td align="center" valign="middle">

                <table border="1" width="600" cellpadding="20">
                    <tr>
                        <th>Nama</th>
                        <th>NIM</th>
                        <th>Jurusan</th>
                        <th>Kelas</th>
                    </tr>

                    <tr>
                        <td>Muhammad Zaki Fauzan</td>
                        <td>2311102084</td>
                        <td>S1 Informatika</td>
                        <td>IF-11-REG05</td>
                    </tr>

                    <tr>
                        <td>Reyhan</td>
                        <td>2311102082</td>
                        <td>S1 Informatika</td>
                        <td>IF-11-REG05</td>
                    </tr>

                    <tr>
                        <td>Alip</td>
                        <td>2311102117</td>
                        <td>S1 Informatika</td>
                        <td>IF-11-REG05</td>
                    </tr>

                    <tr>
                        <td>Apri</td>
                        <td>2311102081</td>
                        <td>S1 Informatika</td>
                        <td>IF-11-REG05</td>
                    </tr>
                </table>

            </td>
        </tr>
    </table>
</body>
</html>

Output:
<img alt="image" src="ss html.png" />