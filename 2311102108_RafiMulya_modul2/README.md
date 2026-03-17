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
    <strong>Ahmad Tegar Kahfi Asyngarinanto</strong>
    <br>
    <strong>2311102083</strong>
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
  <strong>Apri Pandu Wicaksono</strong>
  <br>
  <strong>Hamka Zaenul Ardi</strong>
  <br />
  <h3>LABORATORIUM HIGH PERFORMANCE <br>FAKULTAS INFORMATIKA <br>UNIVERSITAS TELKOM PURWOKERTO <br>2026 </h3>
</div>

<hr>

# Dasar Teori

## 1. HTML

HTML (*HyperText Markup Language*) adalah bahasa markup yang dipakai untuk membuat halaman web. Cara kerjanya sederhana, kita menulis konten di dalam tag-tag tertentu dan browser akan menampilkannya sesuai aturan masing-masing tag.

HTML sendiri bukan bahasa pemrograman karena tidak ada logika seperti kondisi atau perulangan di dalamnya. HTML murni hanya mengatur struktur dan tampilan konten. Versi yang sekarang banyak dipakai adalah HTML5.

---

## 2. Struktur Dasar HTML

```html
<!DOCTYPE html>
<html>
<head>
    <title>Judul Halaman</title>
</head>
<body>
    <!-- Konten halaman di sini -->
</body>
</html>
```

- `<!DOCTYPE html>` — Penanda bahwa file ini adalah dokumen HTML5.
- `<html>` — Tag pembungkus utama seluruh isi halaman.
- `<head>` — Tempat menyimpan informasi halaman seperti judul dan charset, tidak ditampilkan di browser.
- `<title>` — Teks yang muncul di tab browser.
- `<body>` — Semua konten yang ingin ditampilkan di halaman ditulis di sini.

---

## 3. Tabel HTML

Tabel dipakai untuk menampilkan data secara terstruktur dalam bentuk baris dan kolom. Tag-tag yang digunakan:

| Tag | Fungsi |
|-----|--------|
| `<table>` | Membuat tabel |
| `<tr>` | Membuat baris |
| `<th>` | Sel header, otomatis tebal dan rata tengah |
| `<td>` | Sel isi data biasa |
| `<caption>` | Judul tabel |

Atribut yang sering dipakai:
- `border` — Ketebalan garis tabel.
- `cellpadding` — Jarak antara isi sel dengan tepi sel.
- `rowspan` — Menggabungkan beberapa baris menjadi satu sel.
- `colspan` — Menggabungkan beberapa kolom menjadi satu sel.

Pada praktikum ini, `rowspan` dan `colspan` digunakan untuk membuat header tabel bertingkat, yaitu kolom "Gelar Pendidikan" yang mencakup dua sub-kolom (Sarjana dan Magister).

---

# Tugas 2

## Code

```html
<!DOCTYPE html>
<html>
<head>
    <title>Tabel Data</title>
</head>
<body>

<center>
<table border="1" cellpadding="10">
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
        <td>Rafi</td>
        <td>S.Kom</td>
        <td>M.Kom</td>
        <td>25</td>
    </tr>
    <tr>
        <td>Mulya</td>
        <td>S.T</td>
        <td>M.T</td>
        <td>24</td>
    </tr>
    <tr>
        <td>Rizqi</td>
        <td>S.Kom</td>
        <td>M.Sc</td>
        <td>23</td>
    </tr>
</table>
</center>

</body>
</html>
```

## Output

![Bukti](Assets/skrinsut.png)
