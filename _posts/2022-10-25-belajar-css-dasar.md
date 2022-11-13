---
layout: post
title:  "Belajar CSS Dasar"
date:   2022-10-25 04:00:00 +0700
update: 2022-11-14 02:30:00 +0700
category: "web"
tag: "css"
author: Bagoes
---
## 1. Pendahuluan

CSS : Cascading Style stylesheet

Mekanisme sederhana yang mengatur gaya / style (contoh: huruf, warna, spasi, dll) pada halaman web.  
<https://www.w3.org/Style/CSS/>{:target="_blank"}

- Aturan yang digunakan untuk menampilkan elemen / tag HTML.
- Dibuat terpisah dengan HTML.
- Bertujuan untuk memisahkan konten dengan style.
- 1 CSS dapat digunakan untuk banyak halaman HTML.
- 1 halaman HTML dapat terlihat berbeda jika menggunakan CSS yang berbeda pula.

---
## 2. Anatomi CSS 

`selector { property: value; }`  
contoh:  
`h1 { color: blue; }`

### Selector 
- Digunakan untuk memilih dan memanipulasi elemen spesifik pada HTML. 
- Elemen HTML dipilih berdasarkan tag, id, class bahkan pola / patttern.
- Semakin kompleks struktur HTML, selector juga bisa semakin kompleks / spesifik.

### Property dan value
Terdapat banyak sekali lebih dari 350, referensinya bisa mengunjungi link berikut:

<https://developer.mozilla.org/en-US/docs/Web/CSS/Reference>{:target="_blank"}

<https://css-tricks.com/almanac>{:target="_blank"}

---
## 3. Penempatan CSS

Embed  
`<style></style>`

Inline  
`<p style="color: lightblue;"></p>`

Eksternal  
`<link rel="stylesheet" href="style.css">`

[latihan1]

---
## 4. Font Styling

- **font-family**  
  mengatur jenis huruf yang akan digunakan
- **font-size**  
  mengatur ukuran huruf
- **font-weight**  
  mengatur ketebalan huruf
- **font-variant**  
  mengubah huruf menjadi small caps
- **font-style**  
  mengubah huruf menjadi bercetak miring
- **line-height**  
  mengatur spasi antar baris

[latihan2]

---
## 5. Text Styling

- **color**  
  memberi warna pada tulisan
- **text-align**  
  mengatur format paragraf / teks
- **text-indent**  
  memberi indentasi pada paragraf / teks
- **text-decoration**  
  mengatur dekorasi pada teks
- **text-transform**  
  mengubah jenis huruf menjadi huruf besar, kecil / kapital
- **letter-spacing**  
  mengatur spasi antar huruf
- **word-spacing**  
  mengatur spasi antar kata

[latihan3]

---
## 6. Background

- **background-color**  
  mengatur warna pada background
- **background-image**  
  mengatur gambar yang akan digunakan pada background
- **background-position**  
  mengatur posisi gambar pada background
- **background-repeat**  
  mengatur jenis pengulangan gambar pada background

[latihan4]

---
## 7. Selector

digunakan pada CSS untuk mengenali sebuah elemen HTML yang akan diberi style

**elemen HTML**

**id**  
- Sebuah elemen HTML hanya boleh memiliki 1 id
- Setiap halaman hanya boleh memiliki 1 elemen dengan id tersebut
- Dapat digunakan sebagai penanda halaman untuk link
- Digunakan juga untuk javascript
- Sebaiknya tidak digunakan untuk CSS (lebih baik gunakan class)

**class**

**complex selector**

[latihan5]

---
## 8. Pseudo Class

kelas semu yang dimiliki oleh sebuah elemen HTML, yang membuat kita dapat mendefinisikan style pada *"keadaan tertentu"* dari elemen tersebut

- **pseudo-class yang berhubungan dengan link**

  **:link**  
  style default pada sebuah link (a yang memiliki href)

  **:hover**  
  style ketika kursor mouse berada diatas sebuah link / elemen

  **:active**  
  style ketika sebuah link di-klik (keadaan aktif)

  **:visited**  
  style ketika sebuah link sudah pernah dikunjungi sebelumnya (menggunakan browser yang sama)

- **pseeudo-class yang berhubungan dengan posisi elemen (1)**

  **:first-child**  
  memilih elemen pertama dari sebuah parent (elemen pembungkusnya)

  **:last-child**  
  memilih elemen terakhir dari sebuah parent (elemen pembungkusnya)

  **:nth-child (n)**  
  memilih elemen ke-n dari sebuah parent (elemen pembungkusnya), n bisa berarti urutan (1), (2), ... atau pola (2n), (3n+2), (4n-1) atau ganjil dan genap (even) & (odd)

- **pseeudo-class yang berhubungan dengan posisi elemen (2)**

  **:first-of-type**  
  memilih elemen pertama dari sebuah jenis / tipe tag

  **:last-of-type**  
  memilih elemen terakhir dari sebuah jenis / tipe tag

[latihan6]

---
## 9. Inheritance

sebuah elemen mewarisi **beberapa** nilai dari properti yang dimiliki oleh elemen parent-nya

**properti yang diwariskan**

- color
- font
- letter-spacing
- line-height
- list-style
- text-align
- text-indent
- text-transform
- visibility
- white-space

[latihan7]

---
## 10. Specificity

setiap deklarasi CSS (selector) memiliki **berat** yang berbeda. Berat tersebut menentukan seberapa spesifik sebuah elemen dapat dipilih oleh selector

- buat elemen yang diinginkan agar menjadi lebih **spesifik**
- tambahkan beban pada elemen tersebut agar semakin **berat**

---
Referensi:

[channel WPU](https://www.youtube.com/playlist?list=PLFIM0718LjIUBrbm6Gdh6k7ZUvPIAZm7p)

[latihan1]: https://github.com/bagoes/belajar-css/tree/master/WPU/latihan1
[latihan2]: https://github.com/bagoes/belajar-css/tree/master/WPU/latihan2
[latihan3]: https://github.com/bagoes/belajar-css/tree/master/WPU/latihan3
[latihan4]: https://github.com/bagoes/belajar-css/tree/master/WPU/latihan4
[latihan5]: https://github.com/bagoes/belajar-css/tree/master/WPU/latihan5
[latihan6]: https://github.com/bagoes/belajar-css/tree/master/WPU/latihan6
[latihan7]: https://github.com/bagoes/belajar-css/tree/master/WPU/latihan7
[latihan8]: https://github.com/bagoes/belajar-css/tree/master/WPU/latihan8