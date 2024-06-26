```html
<div>Text yang panjang disini...</div>
```

```css
div {
	width: 50px;
	height: 50px;
}
```

Jika terdapat sebuah konten didalam elemen yang kita atur [dimensi](Dimension)nya dengan nilai yang absolut, konten yang ada didalam elemen tersebut akan keluar menembus dimensi, sebagai contoh, konten teks pada elemen `div` diatas akan keluar "box" (batas/*parent*) elemen `div` tersebut, dikarenakan nilai dimensi yang ditetapkan terlalu kecil untuk menampung semua konten yang ada didalam elemennya. Untuk mengatasi hal ini, kita dapat menggunakan *property* `overflow` untuk mengatur perilaku elemen yang kasusnya seperti diatas.

*Value* dari `overflow` utamanya ada 4 yaitu:
1. `visible` (*default*)  
	Konten yang keluar dari parent-nya maka akan diperlihatkan.
2. `auto`  
	Otomatis menambahkan *scroll* ketika kontennya tidak dapat ditampung lagi oleh parent-nya.
3. `hidden`  
	Konten yang keluar dari parent-nya maka akan disembunyikan.
4. `scroll`  
	*Scroll* akan terus muncul meskipun konten masih dapat ditampung oleh parent-nya.
