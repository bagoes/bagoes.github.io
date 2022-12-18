---
layout: post
title:  "Belajar HTML Dasar"
date:   2022-10-23 04:00:00 +0700
update: 2022-11-14 02:00:00 +0700
category: "web"
tag: "html"
author: Bagoes
---
Berikut ini merupakan rangkuman saya untuk belajar HTML, lebih jelasnya kunjungi tautan referensi pada akhir tulisan ini.

## 1. Pendahuluan

HTML : Hypertext Markup Language

Tim Berners-Lee : HTTP, HTML, WWW, Web Browser, Web Server, Web Page

W3C : World Wide Web Consortium

<https://www.w3.org>{:target="_blank"}

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

Latihan 1: [pratinjau][1]{:target="_blank"}

---
## 3. Code Editor

- Sublime Text
- Notepad++
- VS Code Editor

Latihan 2: [pratinjau 1][2-1]{:target="_blank"}, [pratinjau 2][2-2]{:target="_blank"}

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

Latihan 3: [pratinjau][3]{:target="_blank"}

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

Latihan 4: [pratinjau][4]{:target="_blank"}

---
## 7. List

- Ordered List

  `<ol></ol>`

- Unordered List

  `<ul></ul>`

- Definition List

  `<dl></dl>`

Latihan 5: [pratinjau][5]{:target="_blank"}

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

Latihan 6: [pratinjau 1][6-1]{:target="_blank"}, [pratinjau 2][6-2]{:target="_blank"}, [pratinjau 3][6-3]{:target="_blank"}, [pratinjau 4][6-4]{:target="_blank"}, [pratinjau 5][6-5]{:target="_blank"}

---
## 9. Image

`<img src="">`

- internal resource
- external resource

attribute: src, alt, title, width, height

`<img src="" alt="" title="" width="" height="">`

Latihan 7: [pratinjau][7]{:target="_blank"}

---
## 10. Table

struktur tabel: baris & kolom
- baris: kotak-kotak yang berada pada garis horizontal
- kolom: kotak-kotak yang berada pada garis vertikal
- cell: kotak yang berada pada perpotongan atau pertemuan baris dan kolom 

`<table></table>`

```html
<table>
  <tr> // table row
    <td>...</td> // table data
  </tr>
</table>
```

---
## 11. Table Merging

`colspan`

`rowspan`

Latihan 8: [pratinjau 1][8-1]{:target="_blank"}, [pratinjau 2][8-2]{:target="_blank"}, [pratinjau 3][8-3]{:target="_blank"}

---
## 12. Form

`<form></form>`

```html
<form>
  ...
    <!-- elemen form -->
  ...
</form>
```

Elemen Form

`input`

`<input type="">`

attribute: text, password, radio, checkbox, ~~submit~~, ~~reset~~, ~~button~~

`button`

`<button type=""></button>`

attribute: submit, reset, button

`label`

---
## 13. Form (lanjutan)

`textarea`

`<textarea></textarea>`

`select`

`<select></select>`

Latihan 9: [pratinjau 1][9-1]{:target="_blank"}, [pratinjau 2][9-2]{:target="_blank"}

---
Selain tautan untuk melihat pratinjau setiap latihan di codepen, berikut ini disertakan tautan [source code](https://github.com/bagoes/belajar-html/tree/master/WPU/) di GitHub.

Referensi:

[Channel WPU](https://www.youtube.com/playlist?list=PLFIM0718LjIVuONHysfOK0ZtiqUWvrx4F)


[1]: https://codepen.io/bagoes-the-bold/pen/ExpYGBv
[2-1]: https://codepen.io/bagoes-the-bold/pen/qByWGNY
[2-2]: https://codepen.io/bagoes-the-bold/pen/xxJKNqj
[3]: https://codepen.io/bagoes-the-bold/pen/rNrBgwG
[4]: https://codepen.io/bagoes-the-bold/pen/vYaBwZP
[5]: https://codepen.io/bagoes-the-bold/pen/gOjObPv
[6-1]: https://codepen.io/bagoes-the-bold/pen/XWBWJdJ
[6-2]: https://codepen.io/bagoes-the-bold/pen/vYaYEGJ
[6-3]: https://codepen.io/bagoes-the-bold/pen/QWBWwNz
[6-4]: https://codepen.io/bagoes-the-bold/pen/rNrNaLa
[6-5]: https://codepen.io/bagoes-the-bold/pen/gOjObMe
[7]: https://codepen.io/bagoes-the-bold/pen/PoBowGe
[8-1]: https://codepen.io/bagoes-the-bold/pen/WNKNbGL
[8-2]: https://codepen.io/bagoes-the-bold/pen/eYjYmBY
[8-3]: https://codepen.io/bagoes-the-bold/pen/oNMNgYZ
[9-1]: https://codepen.io/bagoes-the-bold/pen/zYLYxNr
[9-2]: https://codepen.io/bagoes-the-bold/pen/RwBwNKx