---
layout: post
title:  "Belajar HTML Dasar"
date:   2022-10-23 04:00:00 +0700
update: 2022-11-12 22:00:00 +0700
tag: "web"
author: bagoes
---
# HTML Dasar
---
## 1. Pendahuluan

HTML : Hypertext Markup Language

Tim Berners-Lee : HTTP, HTML, WWW, Web Browser, Web Server, Web Page

W3C : World Wide Web Consortium

<https://www.w3c.org>{:target="_blank"}

---
## 2. Hello World!

Struktur dasar HTML

```html
    <!DOCTYPE html>
    <html>
    <head>
        <title></title>
    </head>
    <body>

    </body>
    </html>
```

[latihan1][link1]

---
## 3. Code Editor

- Sublime Text
- Notepad++
- VS Code Editor

[latihan2][link2]

---
## 4. Tag

### tag `<HTML>`

### bagian `<head>`

- judul halaman
  
  `<title></title>`

- CSS
  
  `<style></style>`

- javascript
  
  `<script></script>`

- metadata
  
  `<meta></meta>`

### bagian `<body>`

- teks
  
  `<h1>, <h2>, <h3>, <h4>, <h5>, <h6>, <p>, ...`

- pendukung teks
  
  `<br>, <hr>, <em>, <strong>, ...`

- gambar
  
  `<img>`

- hyperlink
  
  `<a>`

- list (bullets & numbering)
  
  `<ul>, <ol>, <li>, <dl>, <dt>, <dd>`

- tabel
  
  `<table>, <thead>, <tbody>, ...`

- form
  
  `<form>, <input>, <select>, <button>, ...`

- script
  
  `<script>`

- object
  
  `<object>`

- grouping
  
  `<div>, <span>`

- komentar
  
  `<!-- isi komentar -->`

### struktur tag

```html
    <namatag atribut="nilai">
    <body bgcolor="lightblue">
```

### artibut global

- accesskey
- class
- id
- dir
- lang
- style
- tabindex
- title

---
## 5. Paragraf

- tag p, br dan hr

  `<p></p>, <br>, <hr>`

- tag b, i dan u

  `<b></b>, <i></i>, <u></u>`

- tag strong dan em

  `<strong></strong>, <em></em>`

[latihan3][link3]

---
## 6. Heading

```html
  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h6>
```

[latihan4][link4]

---
## 7. List

- Ordered List

  `<ol></ol>`

- Unordered List

  `<ul></ul>`

- Definition List

  `<dl></dl>`

[latihan5][link5]

---
## 8. Hyperlink

- anchor

  `<a></a>`
  
  `<a href=""></a>`

- external link

  `www.google.com`

  `https://bagoes.github.io/`

- internal link / relative url

  `halaman1.html`

  `../admin/halaman4.html`

- page anchor
  
  `#about`

  `index.html#contact`

- attribute
  
  `<a href="" target=""></a>`

  `_self`

  `_blank` untuk membuka pada tab baru pada browser

  `_parent`

  `_top`

[latihan6][link6]

---
## 9. Image

`<img src="">`

- internal resource
- external resource

attribute: src, alt, title, width, height

`<img src="" alt="" title="" width="" height="">`

[latihan7][link7]

---
## 10. Table

struktur tabel: baris & kolom
- baris yang berada pada haris horizontal
- kolom yang berada pada baris vertikal
- cell yang berada pada perpotongan atau pertemuan baris dan kolom 

[latihan8][link8]

---
## 11. Table Merging

[latihan9][link9]

---
Referensi:

[Channel WPU](https://www.youtube.com/playlist?list=PLFIM0718LjIVuONHysfOK0ZtiqUWvrx4F)


[link1]: https://github.com/bagoes/belajar-html/tree/master/WPU/latihan1
[link2]: https://github.com/bagoes/belajar-html/tree/master/WPU/latihan2
[link3]: https://github.com/bagoes/belajar-html/tree/master/WPU/latihan3
[link4]: https://github.com/bagoes/belajar-html/tree/master/WPU/latihan4
[link5]: https://github.com/bagoes/belajar-html/tree/master/WPU/latihan5
[link6]: https://github.com/bagoes/belajar-html/tree/master/WPU/latihan6
[link7]: https://github.com/bagoes/belajar-html/tree/master/WPU/latihan7
[link8]: https://github.com/bagoes/belajar-html/tree/master/WPU/latihan8
[link9]: https://github.com/bagoes/belajar-html/tree/master/WPU/latihan9