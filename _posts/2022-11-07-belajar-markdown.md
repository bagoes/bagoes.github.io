---
layout: post
title: "Belajar Markdown"
date: 2022-11-07 21:00:00 +0700
tag: "web"
author: bagoes
---
# Markdown

## Apa itu Markdown?

Makrdown adalah *lightweight markup language* bahasa *markup* yang lebih ringan dari HTML untuk *formatting* teks.

Dikembangkan oleh John Gruber & Aaron Swartz 2004

## File Markdown

File markdown disimpan dengan ekstensi `.markdown` atau `.md`

Contoh : `belajar.markdown` atau `belajar.md`

---
## Format dasar Markdown

*Heading* atau judul dibuat menggunakan tanda pagar `#`

Contoh :
```md
    # Heading 1
    ## Heading 2
    ### Heading 3
```
Hasilnya:

# Heading 1
## Heading 2
### Heading 3

Bisa juga menggunakan simbol minus `-` dan samadengan `=`

Contoh :
```markdown
    Heading 1
    ---------

    Heading 2
    =========
```
Hasilnya:

Heading 1
---------

Heading 2
=========

---
## Format Teks

Menulis teks *bolt* atau tebal
```markdown
    **tebal**

    __tebal__
```
Hasilnya:

**tebal**

__tebal__

Menulis teks *tilt* atau miring
```markdown
    *miring*

    _miring_
```
Hasilnya:

*miring*

_miring_

Menulis teks *strikline* atau dicoret
```markdown
    ~~dicoret~~
```
Hasilnya:

~~dicoret~~

---
## Membuat Link

Dibuat menggunakan tanda kurung
```markdown
    [ini link](https://www.bagoes.github.io/)
```
Hasilnya:

[ini link](https://www.bagoes.github.io/)

menambah *tooltips*
```markdown
    [ini link](https://www.bagoes.github.io/ "menuju link")
```
Hasilnya:

[ini link](https://www.bagoes.github.io/ "menuju link")

atau menulis langsung URL
```markdwon
    https://www.bagoes.github.io
```
Hasilnya:

https://www.bagoes.github.io

Pada web ini ditambah tanda `<` dan `>` diantara URL

```md
    <https://www.bagoes.github.io>
```
Hasilnya:

<https://www.bagoes.github.io>

agar dibuka pada tab baru

```md
    <https://www.bagoes.github.io>{:target="_blank"}
```
Hasilnya:

<https://www.bagoes.github.io>{:target="_blank"}

---
## Menyisipkan Gambar

Seperti membuat link, ditambahkan tanda seru `!` didepannya
```markdwon
    ![ini gambar](https://www.bagoes.github.io/img/bgs-avatar.png)
```
Hasilnya:


![ini gambar](https://www.bagoes.github.io/img/bgs-avatar.png)

---
## Membuat List

Contoh :
```markdown
    * Nasi Goreng
    * Mie Goreng
    * Nasi Kuning
    * Bubur Ayam

    1. Susu
    2. Kopi
    3. Teh Manis

    - Roti
    - Gorengan
```
Hasilnya:

  * Nasi Goreng
  * Mie Goreng
  * Nasi Kuning
  * Bubur Ayam

  1. Susu
  2. Kopi
  3. Teh Manis

  - Roti
  - Gorengan

---
## Membuat To Do List atau Check List
```markdown
    **Kegiatan Hari Ini**
    [x] Bangun tidur
    [ ] Solat
    [ ] Ngaji

    - [ ] Makan
    - [x] Mandi
    - [ ] Kerja
```
Hasilnya:

**Kegiatan Hari Ini**
[x] Bangun tidur
[ ] Solat
[ ] Ngaji

- [ ] Makan
- [x] Mandi
- [ ] Kerja

---
## Membuat Quote
```markdown
    > Ini untuk membuat *quote*
```
Hasilnya:

> Ini untuk membuat *quote*

---
## Menulis Inline Code

Menggunakan tanda (`)
```md
    Ini contoh kode pada HTML `<data:post.body/>`
```
Hasilnya:

Ini contoh kode pada HTML `<data:post.body/>`

---
## Menulis Source Code

Tanda ``` untuk menulis *source code* ditambah nama bahasa pemrogramannya

```markdown
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
```
Hasilnya:

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

Dan agar teksnya berwarna menggunakan [Prism.js](https://prismjs.com/){:target="_blank"} untuk *syntax hightlighting*

Referensi:

- <https://www.petanikode.com/markdown-pemula/>{:target="_blank"}
- <https://blog.ghost.org/markdown/>{:target="_blank"}
- <https://en.wikipedia.org/wiki/Markdown>{:target="_blank"}