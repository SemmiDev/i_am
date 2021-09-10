---
author:
  name: "Sammi Aldhi Yanto"
description: Semester 3 📚 Materi 2 - Struktur Data Array
date: 2021-09-07
linktitle: Materi 2 - Struktur Data Array 
type:
- post
- posts
title: ASD ☕ Materi 2 - Struktur Data Array
weight: 10
series:
- Java
- ASD
tags:
- Java
categories:
- Java
- Materials
---

# Bagian 1

## Pengantar
- Array adalah kumpulan item dengan tipe yang sama dan disimpan di lokasi memori yang berdekatan
- Posisi elemen array ditunjukkan oleh index
- Array dibagi menjadi array 1D, 2D dan 3D
- Manipulasi array menggunakan pernyataan pengulangan
- Operasi terhadap elemen di array dilakukan dengan pengaksesan langsung
- Jenis array adalah **statis** dan **dinamis**

### Array Statis
- Array yang ukuran datanya tetap
- Kekurangannya adalah datanya tidak dapat ditambah pada saat array di proses

### Array Dinamis
- Array yang ukuran datanya dapat bertambah atau berkurang mengikuti banyaknya data yang sedang disimpan
- Kelebihannya adalah kemampuannya dalam menyesuaikan ukuran sehingga kebutuhan memori disesuaikan dengan banyaknya elemen

## Array 1D
- Deklarasi array di pseudo-code:
```
new integer[n+1]
```
- Inisialisasi array bertipe integer dengan n+1 elemen, yang terdefinisi dari elemen ke-0 sampai dengan n
- Contoh deklarasi array 1D
```
A <- new integer[5]
```
- Representasi Array di memory komputer
{{< image src="/assets/arr1.png" alt="array" position="center" style="border-radius: 10px 10px 10px 10px;" >}}

- Representasi Array 1D
{{< image src="/assets/arr2.png" alt="array" position="center" style="border-radius: 10px;" >}}

## Array 2D
- Deklarasi array di pseudo-code:
```
new integer[m+1][n+1]
```
- Array 2D dapat dibayangkan sebagai
matriks (tabel)
- Contoh deklarasi array 2D
```
A <- new integer[3][4]
```
- Representasi Array di memory komputer
{{< image src="/assets/arr3.png" alt="array" position="center" style="border-radius: 10px;" >}}

- Tiap elemen array ditulis dengan notasi: 
```
A[0][0],  A[1][1], ...,  A[2][3]
```
- Representasi Array 2D
{{< image src="/assets/arr4.png" alt="array" position="center" style="border-radius: 10px;" >}}

## Array 3D
- Array 3D adalah array 2D yang disusun
secara berlapis
- Bentuk umumnya terdiri atas baris, kolom
dan banyaknya lapisan
- Contoh deklarasi:
```
mat3D <- new integer[3][3][2]
```
- Representasi Array 3D
{{< image src="/assets/arr5.png" alt="array" position="center" style="border-radius: 10px;" >}}

## Array Dinamis
- Membuat array dinamis, sama dengan array biasa hanya ukuran array disimpan dalam variable **maxSize**
- Inisialisasi nilai **maxSize** dengan nilai yang kecil
- Deklarasi parameter size yang menyatakan banyak elemen yang telah disimpan
- Tetapkan nilai awal dari size 0
- Pada array dinamis, terdapat operasi penyisipan elemen sebagai elemen terakhir yang disebut **push**

## Prinsip Kerja Penyisipan Elemen pada Array Dinamis
- Ketika dilakukan operasi push, terdapat dua kemungkinan kasus:
 1. **Size** < **maxSize**
    - Pada kasus ini, simpan elemen terbaru di index  size dan nilai size + 1
 2. **Size** = **maxSize**
    - Array tidak dapat menyimpan elemen yang baru
    - Untuk mengatasinya, buat array baru dengan ukuran dua kali maxSize, lalu salin seluruh isi array lama ke array baru
    - Hapus array lama, lalu ubah referensi ke array baru
    - Ukuran maxSize menjadi berlipat ganda dan dapat menyimpan elemen baru dengan melakukan langkah seperti kasus sebelumnya

## Implementasi Array Dinamis
- Implementasi array dinamis diwujudkan dengan deklarasi **array**, **variabel size**, dan **maxSize**
- Elemen array dapat diakses langsung

{{< image src="/assets/arr6.png" alt="array" position="center" style="border-radius: 10px;" >}}

## Studi Kasus
    Bagaimana menghitung rata-rata dari 5 data  berat badan siswa? dan bagaimana menampilkan data berat badan siswa yang ke 3?
{{< image src="/assets/arr7.png" alt="array" position="center" style="border-radius: 10px;" >}}

###

{{< image src="/assets/arr8.png" alt="array" position="center" style="border-radius: 10px;" >}}

## 

{{< image src="/assets/arr9.png" alt="array" position="center" style="border-radius: 10px;" >}}
 
### 

{{< image src="/assets/arr10.png" alt="array" position="center" style="border-radius: 10px;" >}}

## Rangkuman
- Array menyimpan item dengan tipe yang sama
- Elemen array ditunjukkan oleh index
- Array statis ukurannya tetap
- Array dinamis, array yang ukurannya dapat bertambah atau berkurang mengikuti banyaknya data yang sedang disimpan
- Array ditampilkan secara lojik dalam bentuk 1D, 2D dan 3D

# Bagian 2
## Array Dinamis
- Pada bahasa pemrograman Java, dynamic array disediakan berupa class ArrayList
- ArrayList memiliki operasi yang lebih lengkap, dibandingkan dengan array biasa
- ArrayList merupakan java library yang menjadi bagian dari Java Util
- ArrayList dapat menambah data baru secara dinamis tanpa harus menentukan ukurannya di awal

## Operasi ArrayList
- **size()** mencari panjang ArrayList
- **add()** menambah elemen baru
- **get()** mengambil elemen pada indeks tertentu
- **isEmpty()** memeriksa apakah ArrayList kosong atau tidak
- **indexOf()** mengetahui indeks dari suatu nilai
- **contains()** memeriksa apakah suatu nilai ada dalam ArrayList
- **set()** menimpa nilai pada indeks tertentu
- **remove()** menghapus nilai pada indeks tertentu

## Traverse
- This operation is to traverse through the elements of an array
- Print all the array elements one by one

{{< image src="/assets/arr11.png" alt="array" position="center" style="border-radius: 5px;" >}}

###

{{< image src="/assets/arr12.png" alt="array" position="center" style="border-radius: 5px;" >}}

## Insert
- Insert operation is to insert one or more data elements into an array
- Based on the requirement, a new element can be added at the beginning, end, or any given index of array.

{{< image src="/assets/arr13.png" alt="array" position="center" style="border-radius: 5px;" >}}
###
{{< image src="/assets/arr14.png" alt="array" position="center" style="border-radius: 5px;" >}}

## Update
- Update operation refers to updating an existing element from the array at a given index.

{{< image src="/assets/arr15.png" alt="array" position="center" style="border-radius: 5px;" >}}
###
{{< image src="/assets/arr16.png" alt="array" position="center" style="border-radius: 5px;" >}}

## Delete
- Deletion refers to removing an existing element from the array and re-organizing all elements of an array
- Please write java code for this part and 
send it to classroom as [**Quiz 1 material**](https://sammidev.netlify.app/posts/2021/09/asd-quiz-1-struktur-data-array/)
- Gunakan SD array statis
