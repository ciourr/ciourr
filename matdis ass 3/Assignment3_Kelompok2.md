# Assignment 03

**Group members**
- Raditya Yudianto NIM 10231076  $(Problem 5)$
- Ade Ayu Kholifah Putri NIM 10231004  $(Problem 1)$
- Az-Zahra Atikah Nurhaliza NIM 10231022  $(Problem 3)$
- Muhammad Ariel Rayhan NIM 10231058  $(Problem  4)$
- Hita Higueta Pancaro NIM 10231040  $(Problem  4)$
- Zahwa Hanna Dwi Putri NIM 10231092 $(Problem  2)$

## Problem 1
Gambarkan K-maps untuk _sum-of-products_ berikut:
- $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$
- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$

Petunjuk: Gunakan tabel di markdown untuk menggambar K-maps.

### Answer
- $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$

|       | x/yz | yz  | yz̅ | y̅z̅ | y̅z |
|-------|------|-----|-----|------|-----|
| x     |      |     |     |      |     |
| x̅    | 1    |     | 1   |      |     |

- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$

|       | x/yz | yz  | yz̅ | y̅z̅ | y̅z |
|-------|------|-----|-----|------|-----|
| x     | 1    | 1   |     |      |     |
| x̅    |      | 1   |     | 1    | 1   |



## Problem 2

Sederhanakan K-maps yang ada di Problem 1 dengan aturan 
yang telah di bahas di pertemuan minggu ke-9.


### Answer

- x ̅yz+x ̅y ̅z ̅ = sudah bentuk paling sederhana sudah bentuk paling sederhana

- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$


   - xyz+xyz ̅=xy (z+z ̅ )=xy (1)=xy

   - xyz ̅+ x ̅yz ̅=(x+ x ̅ )  yz ̅=(1)yz ̅=yz ̅

   - x ̅y ̅z

## Problem 3

Tentukan relasi $R$ dari himpunan $A = \{0, 1, 2, 3, 4\}$
ke himpunan $B = \{0, 1, 2, 3\}$ dengan aturan $(a, b) \in R$
sebagai berikut:
- $a = b$
- $a > b$

### Answer

Relasi $R$ antara himpunan $A$ dan $B$ dapat ditentukan berdasarkan aturan yang diberikan:

- $a = b$: Ini berarti elemen-elemen $A$ yang sama dengan elemen-elemen $B$ akan menjadi bagian dari relasi $R$. Dalam hal ini, elemen-elemen yang ada di kedua himpunan $A$ dan $B$ yang sama adalah {0, 1, 2, 3}. Jadi, kita dapat menyatakan:

$R = {(0, 0), (1, 1), (2, 2), (3, 3)}$

- $a > b$: Ini berarti elemen-elemen $A$ yang lebih besar dari elemen-elemen $B$ juga akan menjadi bagian dari relasi $R$. Dalam hal ini, elemen-elemen $A$ yang lebih besar dari elemen-elemen $B$ adalah {4}. Jadi, kita dapat menambahkan pasangan (4, 3) ke relasi $R$:

$R = {(0, 0), (1, 1), (2, 2), (3, 3), (4, 3)}$

*Jadi, inilah relasi $R$ yang memenuhi aturan yang diberikan antara himpunan $A$ dan $B* 

## Problem 4

Sebutkan semua elemen di dalam relasi 
$R = \{(a, b) \mid a \text{ habis dibagi } b\}$ pada 
himpunan $\{1, 2, 3, 4, 5, 6\}$. Gambarkan juga
relasi $R$ secara grafik (gambar titik untuk masing-masing
domain dan range dan panah berarah).


### Answer
Dalam relasi $\ ( R = \  (a, b) \,|\, a \, \text { habis dibagi } b, \, a, b \in \ {1,2,3,4,5,6\ } \  \ )$, elemen-elemen yang memenuhi kondisi ini adalah:

$ \ [
R = \ {(1,1), (2,1), (2,2), (3,1), (3,3), (4,1), (4,2), (4,4), (5,1), (5,5), (6,1), (6,2), (6,3), (6,6) \ }
\ ]$

Untuk menggambarkan relasi $ \ (  R \ ) $ secara grafik, berikut adalah representasi visualnya:


1 → 1

2 → 1, 2

3 → 1, 3

4 → 1, 2, 4

5 → 1, 5

6 → 1, 2, 3, 6


Dalam representasi grafik ini, panah dari angka di sebelah kiri menunjuk ke angka-angka di sebelah kanan yang memenuhi kondisi $ \ ( a \ )  habis dibagi \ ( b \ )$

## Problem 5
Tentukan apakah relasi $R$ pada semua himpunan halaman web
refleksif, simetrik, dan transitif, jika diberikan $(a, b) \in R$
memenuhi aturan:  
setiap orang yang mengunjungi halaman web $a$ juga mengunjungi 
halaman web $b$.

### Answer

kita periksa apakah relasi $R$ refleksif, simetrik, dan transitif:

- Refleksif: Relasi $R$ dikatakan refleksif jika setiap elemen dalam himpunan tersebut memiliki relasi dengan dirinya sendiri. Dalam kasus ini, semua elemen di himpunan ${1, 2, 3, 4, 5, 6}$ memiliki relasi dengan dirinya sendiri, karena setiap bilangan habis dibagi oleh dirinya sendiri. Jadi, relasi ini refleksif.

- Simetrik: Relasi $R$ dikatakan simetrik jika untuk setiap $(a, b) \in R$, maka juga $(b, a) \in R$. Dalam kasus ini, jika $(a, b)$ terdaftar dalam relasi, maka $(b, a)$ juga terdaftar, karena jika $a$ habis dibagi $b$, maka $b$ habis dibagi $a$ (asalkan $a$ dan $b$ tidak sama dengan 0). Jadi, relasi ini simetrik.

- Transitif: Relasi $R$ dikatakan transitif jika untuk setiap $(a, b) \in R$ dan $(b, c) \in R$, maka $(a, c) \in R$. Dalam kasus ini, jika $a$ habis dibagi $b$ dan $b$ habis dibagi $c$, maka $a$ juga habis dibagi $c$. Jadi, relasi ini transitif.

Jadi, relasi $R$ pada himpunan ini adalah refleksif, simetrik, dan transitif.