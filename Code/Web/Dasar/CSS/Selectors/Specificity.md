Setiap *selector* yang kita buat memiliki berat yang berbeda, berat tersebut akan menentukan seberapa spesifik sebuah elemen dapat dipilih oleh *selector*.

Cara menghitung *specificity*:

| *Selector*     | id  | class | element |
| -------------- | :-: | :---: | :-----: |
| div            |  0  |   0   |    1    |
| div.list       |  0  |   1   |    1    |
| div.list ul#li |  1  |   1   |    2    |
Jadi, semakin besar angkanya semakin spesifik sebuah elemen dapat dipilih oleh *selector*. Sebagai catatan, *inline* CSS akan dihitung paling besar.