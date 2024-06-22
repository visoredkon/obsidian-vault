Tidak semua element HTML akan mewarisi sifat dari parent-nya oleh karena itu jika kita ingin membuat elemen tersebut dapat mewarisi sifat dari parent-nya, kita harus memberikan nilai `inherit` pada *property* yang diinginkan.

misalnya:
```css
body {
	color: red
}

a {
	color: inherit
}
```

Secara *default* *property* `color` pada tag `a` tidak mewarisi sifat dari parent-nya (`body`) oleh karena itu, karena kita ingin `a` memiliki warna yang sama dengan `body`, kita memberikan value `inherit` pada `a`.

<iframe
	src="https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance#understanding_inheritance"
	width="500"
	height="500"
></iframe>