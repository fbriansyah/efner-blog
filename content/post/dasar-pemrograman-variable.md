---
title: "Dasar Pemrograman: Variable"
date: 2020-09-11T12:39:48+07:00
Description: "Variable merupakan salah satu konsep penting dalam pemrograman"
Tags: ["pemrograman", "dasar"]
Categories: ["Tutorial"]
DisableComments: false
weight: 2
---

Dalam pemrograman, Variable digunakan untuk menyimpan data. Variable bisa diibaratkan seperti kotak yang menyimpan barang-barang. Variable juga bisa memiliki label atau nama sebagai penanda. Berikut ini beberapa contoh penulisan variable dalam bahasa pemrograman Javascript.

```javascript
const nama = "Febrian";
```

Pada contoh diatas, ```nama``` merupakan label atau nama variable, sedangkan ```"Febrian"``` merupakan data yang kita simpan kedalam variable. Sepertihalnya benda, data dalam pemrograman memiliki beberapa jenis. Jenis data dapat digolongkan menjadi dua, yang pertama adalah jenis data satuan dan yang kedua jenis data koleksi. Jenis data satuan seperti **number** (angka), **string** (text), **boolean** (true/false). Kemudian jenis data koleksi yaitu **array** dan **object**. Berikut ini merupakan contoh jenis data satuan pada bahasa pemrograman javascript:

```javascript
const angka = 100; // data bertipe angka
const text = "Belajar Coding"; // data bertipe string
const bool = true; // data bertipe boolean
```

Jenis data **array** sebenarnya adalah sekumpulan dari jenis data satuan (number, string, boolean). Berikut ini contoh data berjenis array dalam bahasa pemrograman javascript:
```javascript
const arrayKosong = []; // array kosong
const arrayAngka = [10,30,1,40,1991,2]; // tipe data array number
const arrayText = ["satu", "John", "Hello World"]; // tipe data array string
const arrayBoolean = [true, false]; // tipe data array boolean
```

Object bisa diibaratkan seperti benda di dunia nyata. Benda memiliki karakteristiknya masing-masing. Contohnya mobil memiliki karakteristik memiliki empat roda, memiliki bentuk kemudi lingkaran dan lain sebagainya. 

Objek dalam pemrograman juga dapat memiliki karakteristing yang disebut properti. Mobil juga memiliki fungsionalitas seperti menyalakan lampu, berbelok, mundur, dan lain-lain. Objek juga dapat memiliki fungsionalitas yang disebut dengan method. Berikut ini contoh object dalam bahasa pemrograman javascript

```javascript
const mobil = {
  warna: "Merah",
  brand: "Honda"
  pintu: 2,
  belok: function(arah) {
    console.log(`Belok ke ${arah}`);
  }
}

console.log(mobil.warna); // meng-akses properti pada object mobil
mobil.belok("Kiri"); // memangil method pada object mobil
```