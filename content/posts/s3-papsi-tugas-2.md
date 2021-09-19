---
author:
  name: "Sammi Aldhi Yanto"
description: Semester 3 📗 Tugas 2 - PAPSI
date: 2021-09-17
linktitle: Tugas 2 - PAPSI
type:
- post
- posts
title: PAPSI 📗 Tugas 2 - HTML Dasar Part 2
weight: 10
series:
- PAPSI
tags:
- PAPSI
categories:
- PAPSI
---

## Soal
{{< image src="/assets/papsi/papsi-2-soal.png" alt="soal tugas papsi 2" position="center" style="border-radius: 20px 20px 20px 20px;" >}}

### Struktur file

{{< image src="/assets/papsi/papsi-2-a.png" alt="tugas papsi 2" position="center" style="border-radius: 10px 10px 10px 10px;" >}}


### Bagian 1

{{< image src="/assets/papsi/papsi-2-b.png" alt="tugas papsi 2" position="center" style="border-radius: 10px 10px 10px 10px;" >}}

### Code Bagian 1
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Tugas 1 - Bagian 1</title>
</head>
<body>
<ol>
  <li>Indonesia</li>
  <ul style="list-style-type:disc">
    <li>Jakarta</li>
    <ul style="list-style-type:square">
      <li>Jakarta Pusat</li>
      <li>Jakarta Selatan</li>
    </ul>
    <li>Surabaya</li>
  </ul>
  <li>Inggris</li>
    <ul>
      <li>London</li>
      <li>Manchester</li>
    </ul>
  <li>Amerika</li>
  <ul style="list-style-type:square">
      <li>New York</li>
      <li>Los Angeles</li>
    </ul>
</ol>
</body>
</html>
```

### Bagian 2

{{< image src="/assets/papsi/papsi-2-c.png" alt="tugas papsi 2" position="center" style="border-radius: 10px 10px 10px 10px;" >}}

### Code Bagian 2
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Tugas 1 - Bagian 2</title>
</head>
<body>
  <br>
  <br>
  <br>
  <table border="1px" align="center">
    <thead>
      <th colspan="3" align="center">Profil Website</th>  
    </thead>

    <tbody>
      <tr>
      <td rowspan="4">
        <img src="coffee.jpg" width="20px" height="20px">
      </td>
      <td height="30px">Nama</td>
      <td>Kopoding.in</td>
    </tr>
    <tr>
      <td height="30px">Pemilik</td>
      <td>Kuro Neko</td>
    </tr>
    <tr>
      <td>Menu</td>
      <td>
        <ul style="list-style-type:square">
          <li>Beranda</li>
          <li>Tutorial</li>
          <li>Blog</li>
          <li>Kontak</li>
          <li>Tentang</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td height="30px">Alamat</td>
      <td><a href="https://kopiding.in" target="_blank">https://kopiding.in</a></td>
    </tr>
    </tbody>
  </table>
</body>
</html>
```

### Bagian 3

{{< image src="/assets/papsi/papsi-2-d.png" alt="tugas papsi 2" position="center" style="border-radius: 10px 10px 10px 10px;" >}}

### Code Bagian 3
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Tugas 1 - Bagian 3</title>
</head>
<body>
  <table border="1px">
    <thead>
      <th>Judul kolom 1</th>
      <th>Judul kolom 2</th>
      <th>Judul kolom 3</th>
    </thead>
    <tbody>
      <tr>
        <td style="background-color: #2089ef;">baris 1 kolom 1</td>
        <td colspan="2" align="right">gabungan kolom 2 dan 3 di baris 1</td>
      </tr>
      <tr>
        <td style="background-color: #ff8900" colspan="2">gabungan kolom 1 dan 2 di baris 2</td>
        <td rowspan="2" style="background-color: #ff5555; vertical-align: bottom;">
          gabungan baris 2 dan 3 di kolom 3
        </td>
      </tr>
      <tr>
        <td>baris 3 kolom 1</td>
        <td style="background-color: green;">baris 3 kolom 2</td>
      </tr>
    </tbody>
  </table>
</body>
</html>
```

### Bagian 4

{{< image src="/assets/papsi/papsi-2-e.png" alt="tugas papsi 2" position="center" style="border-radius: 10px 10px 10px 10px;" >}}

### Code Bagian 4
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Tugas 1 - Bagian 4</title>
</head>
<body>
  <center>
    <font style="font-weight: bold;">DATA MAHASISWA</font>
  </center>
  <br>
  <center>
    <font style="font-weight: bold;">UNIVERSITAS KOMPUTER INDONESIA</font>
  </center>
  <hr>
  <div style="margin-left: 200px; margin-top: 50px;">
    <form action="#" method="post">
      <table align="left">
        <tr>
          <td width="200px">NIM</td>
          <td>: <input type="text" name="nim" size="30px"></td>
        </tr>
        <tr>
          <td>NAMA</td>
          <td>: <input type="text" name="nim" size="50px"></td>
        </tr>
        <tr>
          <td>JENIS KELAMIN</td>
          <td>: 
            <select name="jenis-kelamin">
              <option>Laki - Laki</option>
              <option>Perempuan</option>
            </select>
          </td>
        </tr>
        <tr>
          <td>AGAMA</td>
          <td>:
            <select name="agama">
              <option>islam</option>
              <option>kristen</option>
              <option>hindu</option>
              <option>buddha</option>
            </select>
          </td>
        </tr>
        <tr>
          <td>STATUS</td><br>
          <td>
            <input type="radio" name="menikah"> Belum Menikah
            <br>
            <input type="radio" name="menikah" checked> Menikah 
          </td>
        </tr>
        <tr>
          <td>PRGRAM STUDI</td>
          <td>:
            <select name="program-studi">
              <option>Manajemen</option>
              <option>SI</option>
              <option>MI</option>
              <option>Fisika</option>
              <option>Kimia</option>
              <option>Biologi</option>
              <option>Matematika</option>
            </select>
          </td>
        </tr>
        <tr>
          <td>KOMENTAR</td>
          <td>:<textarea name="komentar" rows="5" cols="50"></textarea></td>
        </tr>
        <tr>
          <td>
          </td>
          <td>
            <br><br><br>
            <button type="submit" name="submit" value="submit">submit</button>
            <button type="reset" name="reset" value="reset">reset</button>
          </td>
        </tr>
      </table>
    </form>
  </div>
</body>
</html>
```
