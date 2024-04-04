# Tugas 2
# Praktikum Pemrograman Web 1

Tugas 2 berisi tentang

- HTML
- CSS
- JavaScript
  
## Isi File

- Berisi tentang dasar-dasar pengkodean HTML, CSS dan JavaScript yang telah saya pelajari
- Berisi tentang cara membuat tabel dengan HTML, serta membuat style CSS baik menggunakan inline, internal, maupun external
- Berisi tentang Bagaimana cara membuat sebuah function pada JavaScript dengan mengambil nilai variabel untuk menghitung/Arithmatic
- Berisi tentang cara mengoutputkan kembali hasil dari variabel melalui Javascript alert

## Contoh Membuat List Pada HTML

- Untuk membuat list hari Senin
```sh
<li style="color:green">Senin</li>
```

- Untuk membuat ordered list pada hari Senin
```sh
<ol type="a">
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ol>
```

- Untuk membuat list hari Selasa
```sh
 <li style="color:blue">Selasa</li>
```

- Untuk membuat ordered list pada hari Selasa
```sh
<ol type="I">
    <li style="color: brown;">Bootstrap</li>
```

- Untuk membuat list pada Bootstrap di dalam hari Selasa
```sh
<ol>
    <li>Introduction</li>
    <li>Customize</li>
    <li>Layout</li>
</ol>
```

- Untuk membuat lanjutan list pada hari Selasa
```sh
  <li>PHP</li>
  <li>MySQL</li>
</ol>
```

- Berikut adalah contoh input dari HTML List di atas
![alt text](https://github.com/IlhamBudimansyah/Praktikum-Web1/blob/main/SS%20Input%20HTML.png)

- Berikut adalah contoh output dari HTML List di atas
![alt text](https://github.com/IlhamBudimansyah/Praktikum-Web1/blob/main/SS%20OUTPUT%20HTML.png)

## Contoh Membuat Tabel Pada CSS

- Untuk membuat tabel
```sh
    table {
  font-family:'Times New Roman', Times, serif;
  border-collapse: collapse;
  width: 100%;
  font-weight: lighter;
    }
```

- Untuk membuat tulisan "Daftar Mahasiswa" menjadi di tengah dan berwarna biru
```sh
    h1 {
        text-align: center;
        color : rgb(87, 87, 218)
    }
```

- Untuk mewarnai garis pinggir pinggir pada tabel menjadi warna merah dan teks menjadi ke kiri
```sh
    td, th {
  border: 1px solid red;
  text-align: left;
  padding: 8px;
}
```

- Untuk membuat warna tabel genap menjadi warna biru
```sh
tr:nth-child(even) {
  background-color: #59ddd5;
}
```

- Untuk membuat CSS pada header tabel
```sh
.judul{
    background-color: rgb(87, 87, 218);
    color : white
}
```

- Untuk membuat hover pada tabel pada saat mouse di arahkan ke dalam tabel
```sh
.highlight:hover {
  color: black;
  font-size: 22px;
  background-color: greenyellow;
}
```

- Untuk membuat keterangan pada bagian bawah
```sh
    <h4>Keterangan:</h4>
    <ol>
        <li>Warna Heading dan Table Header adalah <b>rgb(87, 87, 218)</b></li>
        <li>Warna Baris Genap adalah <b>#59ddd5</b></li>
        <li>Warna saat hover adalah <b>greenyellow</b></li>
        <li>Pada saat hover, ukuran font <b>lebih besar 120%</b>, dan berubah menjadi <b>BOLD</b></li>
    </ol>
```

- Untuk membuat isi dalam pada tabel
```sh
    <h1>Daftar Mahasiswa</h1>
    <table>
        <tr class="judul">
            <th>Nama</th>
            <th>Program Studi</th>
            <th>Kelas</th>
        </tr>
        <tr class="highlight">
            <th>John Doe</th>
            <th>Teknik Informatika</th>
            <th>A-01</th>
        </tr>
        <tr class="highlight">
            <th>Jane Smith</th>
            <th>Sistem Informasi</th>
            <th>B-02</th>
        </tr>
        <tr class="highlight">
            <th>Alice Johnson</th>
            <th>Teknik Komputer</th>
            <th>A-03</th>
        </tr>
        <tr class="highlight">
            <th>Bob Brown</th>
            <th>Teknik Elektro</th>
            <th>C-01</th>
        </tr>
        <tr class="highlight">
            <th>Emily Davis</th>
            <th>Manajemen Informatika</th>
            <th>D-02</th>
        </tr>
    </table>
```

- Berikut adalah contoh input dari CSS di atas
![alt text]()
