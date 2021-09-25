---
author:
  name: "Sammi Aldhi Yanto"
description: Semester 3 📗 Tugas 2 - PAPSI
date: 2021-09-17
linktitle: Tugas 2 - PAPSI
type:
- post
- posts
title: PAPSI 📗 Tugas 2 - CSS Dasar
weight: 10
series:
- PAPSI
tags:
- PAPSI
categories:
- PAPSI
---

## Soal
{{< image src="/assets/papsi/papsi-3-a.png" alt="soal papsi 2" position="center" style="border-radius: 20px 20px 0px 0px;" >}}

{{< image src="/assets/papsi/papsi-3-b.png" alt="soal papsi 2" position="center" style="border-radius: 0px 0px 20px 20px;" >}}

### Code

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>tugas 2</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <marquee>
    <h1 class="atas_sammi">Latihan CSS Dasar</h1>
  </marquee>

  <h2 id="dua_sammi">2003113948_SAMMI ALDHI YANTO</h2>
  <hr size="10px">
  <h3 class="bawah_nama">
    Menurut  <a href="#">Niagahoster</a>, website merupakan halaman-halaman yang dibuat dengan maksud tertentu yang bisa diakses di <i><a href="#">internet</a></i> menggunakan sebuah <i><a href="#">browser.</a></i> Sebuah website berjalan dengan <i>Protocol Hypertext Transfer Protokol (HTTP)</i>.
  </h3>
  <img src="cat.jpg" class="meong">
  <br>
  <table border="1px" align="center" style="border-color: black;">
    <thead>
      <tr style="background-color: orange;">
        <th rowspan="2" style="background-color: orange;" width="50px">NO</th>
        <th rowspan="2" style="background-color: orange;" width="130px">NAMA OBAT</th>
        <th colspan="3" style="background-color: orange;">JENIS OBAT</th>
      </tr>
      <tr style="background-color: orange;">
        <th style="background-color: orange;" width="70px">SYRUP</th>
        <th style="background-color: orange;" width="70px">TABLET</th>
        <th style="background-color: orange;" width="70px">GEL</th>
      </tr>
    </thead>
    <tbody>
      <tr align="center">
        <td class="num">1</td>
        <td class="nama_obat">PANADOL</td>
        <td rowspan="2">*</td>
        <td>*</td>
        <td style="background-color: red;"></td>
      </tr>
      <tr align="center">
        <td class="num">2</td>
        <td class="nama_obat">MIGRARIP</td>
        <td style="background-color: red;"></td>
        <td>*</td>
      </tr>
      <tr align="center">
        <td class="num">3</td>
        <td class="nama_obat">PARACETAMOL</td>
        <td style="background-color: red;"></td>
        <td rowspan="2">*</td>
        <td style="background-color: red;"></td>
      </tr>
      <tr align="center">
        <td class="num">4</td>
        <td class="nama_obat">EMBOOST</td>
        <td style="background-color: lightgreen;"></td>
        <td style="background-color: lightgreen;"></td>
      </tr>
    </tbody>
  </table>
  <br>

  <u>Halaman-halaman yang ditampilkan pada website biasanya adalah:</u>
  <ul id="satu_sammi">
    <li>Teks</li>
      <ol type="a">
        <li>Huruf</li>
        <li>Kalimat</li>
      </ol>
    <li>Video, Audio</li>
    <li>Animasi</li>
    <li>Grafik/Gambar</li>
    <ol>
      <li>jpg/jpeg</li>
      <li>TIF</li>
      <li>GIF</li>
    </ol>
  </ul>

  <p id="dua_sammi">
    Manusia membutuhkan O<sub>2</sub> untuk bernafas dan merupakan hal yang paling penting dalam kehidupan. H<sub>2</sub>SO<sub>4</sub> merupakan senyawa kimia. Contoh rumus matematika : x<sup>2</sup> + y<sup>2</sup>
  </p>

  <div style="border-style: solid; border-color: black; size: 20px">
    <h1 class="bawah_nama">
      UJIAN WEB DASAR – SAMMI ALDHI YANTO - RUMAH
    </h1>
  </div>
</body>
</html>
```


```css
* {
  background-color: darkkhaki;
}

h1.atas_sammi {
  font-family: algerian;
  color: blue;
  text-align: center;
}

h2#dua_sammi {
  font-family: "arial black";
  color: yellow;
  font-weight: bold;
  text-align: center;
}

p#dua_sammi {
  font-family: "arial black";
  color: yellow;
  font-weight: bold;
}

ul#satu_sammi {
  list-style: square;
}

hr {
  background-color: red;
  border-style: none;
}

h3.bawah_nama {
  font-family: "Comic Sans";
  color: mediumpurple;
  text-align: justify;
}

.meong {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 40%;
}

h1.bawah_nama {
  text-align: center;
  font-style: italic;
}

.num {
  background-color: lightblue;
}

.nama_obat {
  background-color: yellow;
  text-align: left;
}
```