# labspy02
<p align="center">
<b>Program cari angka terbesar dari ke-3 bilangan</b>
</p>
<p>

<p align="center">
<img src="https://github.com/ariandto/labspy02/blob/main/gmb/s1.png"/>
<p align="center">
</p>

<i>Sebelum ke langkah selanjutnya kita harus pahami dulu alur algoritma dasarnya sebagai berikut:<p>
Bahwa ada 3 bilangan yang harus anda input pada program ini
- if a>b and a>c , artinya jika a lebih besar dari b dan a lebih besar dari c maka bisa dipastikan a adalah yang terbesar
- if b>a and  b>c , artinya jika b lebih besar dari a dan b lebih besar dari c maka bisa dipastikan b adalah bilangan yang terbesar
- jika diluar daripada case diatas bisa disimpulkan bilangan c adalah yang terbesar</i>

<b>2).</b> <b>Flowchart Alur Pemrograman</b>
<p align="center">
<img src="https://github.com/ariandto/labspy02/blob/main/gmb/s2.png"/>
<p align="center">
</p>

<b>3).</b> <b>Hasil Program</b>

<p align="center">
<img src="https://github.com/ariandto/labspy02/blob/main/gmb/s3.png"/>
<p align="center">
</p>

<p align="center">
<img src="https://github.com/ariandto/labspy02/blob/main/gmb/s4.png"/>
<p align="center">
</p>

<b>2).</b> <b>Source Code</b>

```python
while True:
    a=int(input("masukkan angka ke-1=>: \n"))
    b=int(input("masukkan angka ke-2=>: \n"))
    c=int(input("masukkan angka ke-3=>: \n"))
    if a>b and a>c:
        print("bilangan terbesar diantara 3 angka yang anda input adalah=>: ",a)
        lanjut=(input("ulangi program?(y/n)"))
        if lanjut=="N" or lanjut=="n":
                    break
    elif b>a and b>c:
        print("bilangan terbesar diantara 3 angka yang anda input adalah=>: ",b)
        lanjut=(input("ulangi program?(y/n)"))
        if lanjut=="N" or lanjut=="n":
                    break
    else:
        print("bilangan terbesar diantara 3 angka yang anda input adalah=>: ",c)
        lanjut=(input("ulangi program?(y/n)"))
        if lanjut=="N" or lanjut=="n":
                    break
```
<b>Terima Kasih</b>