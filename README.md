# Latihan 1

- pertama kita buat input terlebih dahulu contohnya seperti dibawah ini:
```
a = int(input('Masukan bilangan pertama : '))
```
```
b = int(input('Masukan bilangan kedua : '))
```
- kemudian masukan **if** untuk menjalani program yang sebelumnya dan tambahkan **a > b :** kemudian **print('Bilangan terbesar = ', a)**

- tambahkan **else** untuk menambahkan aksi untuk menentukan bahwa **a lebih besar dari b**
```
else :
print("Bilangan terbesar = ", b)
```
- kemudian masukan bilangan pertama dan bilangan kedua,
- dan tekan enter, untuk melihat hasilnya seperti contoh gambar berikut:

![Gambar1]
![Gambar1]

# latihan 2

- pertama mendefiniskan terlebih dahulu contohnya seperti dibawah ini:
```
def angka_terbesar (a, b, c):
    if a>b and a>c :
        return a
    elif b>a and b>c:
        return b
    return c
def angka_terkecil (a, b, c):
    if a<b and a<c :
        return a
    elif b<a and b<c :
        return b
    return c
def angka_tengah (a, b, c):
    if (b > a > c ) or (c > a > b):
        return a
    elif (a > b > c) or (c > b > a):
        return b
    return c
```
- setelah didefinisikan, lalu kita menentukan 3 variabel : 
```
a, b, c = (
    int(input('masukan nilai a :')),
    int(input('masukan nilai b :')),
    int(input('masukan nilai c :'))
)
```
- saya menggunakan sistem deklarasi yang dimana kita mendeklarasikan ketiganya langsung dalam satu ekspresi
- lalu kita menggunakan sistem array
```
i1 = angka_terkecil(a, b, c)
i2 = angka_tengah(a, b, c)
i3 = angka_terbesar(a, b, c)
print(f'{i1}, {i2}, {i3}')
```
- dan saat running kita input bilangan yang ingin kita urutkan lalu hasil running nya seperti gambar berikut:

![Gambar1]
![Gambar1]

# Latihan 3 

- buat codingannya dulu seperti berikut:
```
for i in range(0, 10):
    for j in range(0, 10):
        product = i+j
        print(f"{product:>3}", end='')
    print()
print()
```
- maka runingannya akan seperti gambar berikut:

![Gambar1]
![Gambar1]

# Latihan 4

- pertama kita buat codingannya dulu seperti berikut:
```
n = int(input("masukan nilai n : "))
import random
for i in range(n):
    a = random.uniform(0.0, 0.9)
    print("data ke :", i+1, "=> ", a)
```
- setelah runing akan diminta masukan nilai n, disini saya memasukan nilai n-nya 9 dan hasil runningannya akan seperti gambar berikut:

![Gambar1]
![Gambar1]

# Latihan 5

![Gambar1]

- jadi masukan i, j, k sebagai inputan, untuk memasukan bilangan lalu tambahkan **if** menandakan bahwa **i lebih besar dari j** lalu tambahkan titik dua jadi seperti ini **If i > j :** lakukan juga pada **r** dan **d** lalu print dan ketik masukan bilangan terbesar, kemudian selanjutnya tambahkan **elif dan else** yaitu untuk menambah aksi untuk menentukan bahwa **i lebih besar dari k** dan **j lebih besar dari k**, setelah menjalani codingan seperti penjelasan dan gambar di atas kemudian di running.
![Gambar1](fotoss/ss5.1.png)
- setelah running masukan bilangan dari yang terbesar hingga terkecil, hasil akhirnya menununjukan bilangan terbesar dari tiga bilangan yang di masukan

# Latihan 6
![Gambar1](fotoss/ss6.png)
- kita akan membuat sebuah program yang dimana kita bisa menginputkan bilangan integer berapapun dan di akhiri oleh = **0**
```
max = 0
while True:
    x=int(input("masukan bilangan:"))
    if max<x:
        max = x
    if x==0:
        break
print("bilangan terbesarnya adalah:", max)
```
- jadi **max** adalah variabel yang telah diberi nilai = **0**
- dan **x** adalah variabel untuk menampilkan sebuah ekspresi untuk anda memasukan bilangan
- kita menggunakan **break** agar program memiliki titik akhir.
![Gambar1]
- disini kita bisa melihat hasilnya bahwa kita menginput berapapun bilangan yang kita inginkan dan jika ingin mengakhiri tinggal menginputkan titik akhir, yaitu **0**

# Latihan 7
![Gambar1]
- masukkan codingan seperti diatas adalah untuk menghitung laba dari bulan ke-1 hingga ke-8
![Gambar1]
