---
author:
  name: "Sammi Aldhi Yanto"
description: PAPSI ~ CSS Dasar
date: 2021-09-08
linktitle: Tugas 2 - PAPSI
type:
- post
- posts
title: PAPSI ~ CSS Dasar
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

## Code

### HTML

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>tugas 2 PAPSI</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <div class="wrap">
    <marquee>
      <h1 class="atas_sammi">Latihan CSS Dasar</h1>
    </marquee>

    <h2 id="atas_2003113948">2003113948_SAMMI ALDHI YANTO</h2>
    
    <hr size="10px">

    <h3 class="bawah_sammi">
      Menurut <u>Niagahoster</u>, website merupakan halaman-halaman yang dibuat dengan maksud tertentu yang bisa diakses di <u>internet</u> menggunakan sebuah <u>browser. </u>Sebuah website berjalan dengan Protocol Hypertext Transfer Protokol (HTTP).
    </h3>

    <img src="xixixi.png" class="contrib-meme">

    <br>

    <table border="1px" align="center" style="border-color: black;">
      <thead>
        <tr style="background-color: orange;">
          <th rowspan="2" style="background-color: #ffd966;" width="50px">NO</th>
          <th rowspan="2" style="background-color: #ffd966;" width="130px">NAMA OBAT</th>
          <th colspan="3" style="background-color: #ffd966;">JENIS OBAT</th>
        </tr>

        <tr style="background-color: orange;">
          <th style="background-color: #ffd966;" width="70px">SYRUP</th>
          <th style="background-color: #ffd966;" width="70px">TABLET</th>
          <th style="background-color: #ffd966;" width="70px">GEL</th>
        </tr>
      </thead>

      <tbody>
        <tr align="center">
          <td class="num">1</td>
          <td class="nama_obat">PANADOL</td>
          <td rowspan="2" style="background-color: white">*</td>
          <td style="background-color: white">*</td>
          <td style="background-color: red;"></td>
        </tr>

        <tr align="center">
          <td class="num">2</td>
          <td class="nama_obat">MIGRARIP</td>
          <td style="background-color: red;"></td>
          <td style="background-color: white">*</td>
        </tr>
        
        <tr align="center">
          <td class="num">3</td>
          <td class="nama_obat">PARACETAMOL</td>
          <td style="background-color: red;"></td>
          <td rowspan="2" style="background-color: white">*</td>
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

    <u>Halaman-halaman yang ditampilkan pada website biasanya adalah :</u>
    
    <ul id="satu_sammi">
      <li style="font-style: italic;">Teks</li>
        <ol type="a">
          <li>Huruf</li>
          <li>Kalimat</li>
        </ol>
      <li style="font-style: italic;">Video, Audio</li>
      <li style="font-style: italic;">Animasi</li>
      <li style="font-style: italic;">Grafik/Gambar</li>
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
      <h1 class="bawah_sammi">
        LATIHAN CSS DASAR – SAMMI ALDHI YANTO - RUMAH
      </h1>
    </div>

  </div>
</body>
</html>
```
### CSS

```css
* {
  background-color: lightgreen;
}

.wrap {
  margin: 50px;
}

h1.atas_sammi {
  font-family: algerian;
  color: blue;
  animation-direction: alternate;
}

h2#atas_2003113948 {
  font-family: "Comic Sans";
  color: darkgrey;
  font-weight: bold;
  text-align: center;
}

hr {
  background-color: red;
  border-style: none;
}

h3.bawah_sammi {
  font-family: "Comic Sans";
  color: mediumpurple;
  text-align: justify;
}

.contrib-meme {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 25%;
}

.num {
  background-color: #9cc2e3;
}

.nama_obat {
  background-color: yellow;
  text-align: left;
}


ul#satu_sammi {
  list-style: square;
}

p#dua_sammi {
  font-family: "arial black";
  color: yellow;
  font-weight: bold;
}


h1.bawah_sammi {
  text-align: center;
  font-style: italic;
}
```

> DOWNLOAD [ZIP](https://sammidev.netlify.app/assets/paps/tugas-2.zip)