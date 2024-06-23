```html
<div>Text yang panjang disini...</div>
```

```css
div {
	width: 50px;
	height: 50px;
}
```

Jika terdapat sebuah konten didalam elemen yang kita atur [dimensi](Dimension)nya dengan nilai yang absolut, konten yang ada didalam elemen tersebut akan keluar menembus dimensi, sebagai contoh, konten teks pada elemen `div` diatas akan keluar "box" (batas) elemen `div` tersebut dikarenakan nilai dimensi yang ditetapkan terlalu kecil untuk menampung semua konten yang ada didalam elemennya. Untuk mengatasi hal ini, kita dapat menggunakan *property* `overflow` untuk mengatur.

