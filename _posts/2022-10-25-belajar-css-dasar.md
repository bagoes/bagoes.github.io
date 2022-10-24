# CSS Dasar

## 1. Pendahuluan

CSS : Cascading Style stylesheet

Mekanisme sederhana yang mengatur gaya / style (contoh: huruf, warna, spasi, dll) pada halaman web.  
https://www.w3.org/Style/CSS/

- Aturan yang digunakan untuk menampilkan elemen / tag HTML.
- Dibuat terpisah dengan HTML.
- Bertujuan untuk memisahkan konten dengan style.
- 1 CSS dapat digunakan untuk banyak halaman HTML.
- 1 halaman HTML dapat terlihat berbeda jika menggunakan CSS yang berbeda pula.

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

https://developer.mozilla.org/en-US/docs/Web/CSS/Reference

https://css-tricks.com/almanac

## 3. Penempatan CSS

Embed  
`<style></style>`

Inline  
`<p style="color: lightblue;"></p>`

Eksternal  
`<link rel="stylesheet" href="style.css">`

latihan1

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

latihan2

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

latihan3

> Ini adalah rangkuman mempelajari serial CSS Dasar di WPU, untuk lebih jelas silahkan kunjungi [channel WPU](https://www.youtube.com/playlist?list=PLFIM0718LjIUBrbm6Gdh6k7ZUvPIAZm7p)