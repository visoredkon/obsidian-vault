![[span-div.png|500]]  
![[display-mdn.png|500]]  
![[display-almanac.png|500]]

*Value* dari `inline` ada 4 yaitu:
1. `inline`  
	Tidak menambahkan garis baru ketika dibuat, lebar dan tinggi elemennya sebesar konten yang ada didalamnya, kita tidak dapat mengatur tinggi dan lebar dari elemen `inline` (kecuali gambar), *margin* dan *padding* hanya mempengaruhi elemen secara horizontal, tidak vertikal.
2. `inline-block`  
	Tidak ada elemen yang secara *default* memiliki *property* `inline-block`, perilaku dasarnya sama seperti `inline`, namun `inline-block` dapat diatur tinggi dan lebarnya.
3. `block`  
	Menambahkan garis baru ketika dibuat, jika tidak diatur lebarnya, maka lebar *default* dari elemen `block` akan memenuhi lebar dari *browser*, *container* atau parent-nya, kita dapat mengatur tinggi dan lebar dari elemen `block`, didalam elemen `block` kita dapat menyimpan tag dengan berbagai elemen `display`.
4. `none`  
	Untuk menghilangkan sebuah elemen.

[List elemen `inline` dan `block`](https://www.w3schools.com/html/html_blocks.asp)

`div` memiliki display `block` sedangkan `span` memiliki display `inline`.
