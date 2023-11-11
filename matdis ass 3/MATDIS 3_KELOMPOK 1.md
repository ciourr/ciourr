# Assignment 02

**Group members**
- Achmad Zaki Zaidan (10231002) (Problem 1)
- Putri Rahmawati (10231074) (Problem 2)
- Arya Wijaya S (10231020) (Problem 3)
- Firni Fauziah Ramadhini (10231038) (Problem 4)
- Muhammad Alif Setiawan (10231056) (Problem 5)

## Problem 1
Gambarkan K-maps untuk _sum-of-products_ berikut:
- $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$
- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$

Petunjuk: Gunakan tabel di markdown untuk menggambar K-maps.

### Answer
- $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$

    |               | $yz$    | $y\overline{z}$ | $\overline{y}\, \overline{z}$                | $\overline{y}z$ |
    |---------------|---------|-----------------|----------------------------------------------|-----------------|
    |$x$            |         |                 |                                              |                 |
    |$\overline{x}$ |$\overline{x}yz$ |         | $\overline{x}\, \overline{y}\, \overline{z}$ |                 |


- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$ 

    |               | $yz$    | $y\overline{z}$ | $\overline{y}\, \overline{z}$          | $\overline{y}z$                              |
    |---------------|---------|-----------------|----------------------------------------|----------------------------------------------|
    |$x$            | $xyz$   | $xy\overline{z}$|                                        |                                              |
    |$\overline{x}$ |         | $\overline{x}y\overline{z}$|                             | $\overline{x}\,\overline{y}z$                |

## Problem 2

Sederhanakan K-maps yang ada di Problem 1 dengan aturan 
yang telah di bahas di pertemuan minggu ke-9.


### Answer
- $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$

    |               | $yz$    | $y\overline{z}$ | $\overline{y}\, \overline{z}$                | $\overline{y}z$ |
    |---------------|---------|-----------------|----------------------------------------------|-----------------|
    |$x$            |         |                 |                                              |                 |
    |$\overline{x}$ |$ 0 $ |         | $0$ |                 |
    $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$ =
    Sudah sederhana
- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$ 

    |               | $yz$    | $y\overline{z}$ | $\overline{y}\, \overline{z}$          | $\overline{y}z$                              |
    |---------------|---------|-----------------|----------------------------------------|----------------------------------------------|
    |$x$            | $0$   | $0$|                                        |                                              |
    |$\overline{x}$ |         | $0$|                             | $0$                |


    $xy\overline{z}$ + $\overline{x}y\overline{z}$ = $y\overline{z}$

## Problem 3

Tentukan relasi $R$ dari himpunan $A = \{0, 1, 2, 3, 4\}$
ke himpunan $B = \{0, 1, 2, 3\}$ dengan aturan $(a, b) \in R$
sebagai berikut:
- $a = b$
- $a > b$

### Answer
Relasi \(R\) dari himpunan \(A = \{0, 1, 2, 3, 4\}\) ke himpunan \(B = \{0, 1, 2, 3\}\) dengan aturan \( (a, b) \in R \) apabila \(a = b\) atau \(a > b\), dapat direpresentasikan sebagai berikut:

\(R = \{(0, 0), (1, 0), (2, 0), (2, 1), (3, 0), (3, 1), (3, 2), (4, 0), (4, 1), (4, 2), (4, 3)\}\)

Penjelasan:

- Pasangan (0, 0) termasuk dalam \(R\) karena 0 = 0.
- Pasangan (1, 0) termasuk dalam \(R\) karena 1 > 0.
- Pasangan (2, 0) termasuk dalam \(R\) karena 2 > 0.
- Pasangan (2, 1) termasuk dalam \(R\) karena 2 > 1.
- Pasangan (3, 0) termasuk dalam \(R\) karena 3 > 0.
- Pasangan (3, 1) termasuk dalam \(R\) karena 3 > 1.
- Pasangan (3, 2) termasuk dalam \(R\) karena 3 > 2.
- Pasangan (4, 0) termasuk dalam \(R\) karena 4 > 0.
- Pasangan (4, 1) termasuk dalam \(R\) karena 4 > 1.
- Pasangan (4, 2) termasuk dalam \(R\) karena 4 > 2.
- Pasangan (4, 3) termasuk dalam \(R\) karena 4 > 3.

Jadi, ini adalah representasi dari relasi \(R\) dengan aturan yang diberikan.

## Problem 4

Sebutkan semua elemen di dalam relasi 
$R = \{(a, b) \mid a \text{ habis dibagi } b\}$ pada 
himpunan $\{1, 2, 3, 4, 5, 6\}$. Gambarkan juga
relasi $R$ secara grafik (gambar titik untuk masing-masing
domain dan range dan panah berarah).


### Answer
dalam relasi $\ ( R = \  (a, b) \,|\, a \, \text { habis dibagi } b, \, a, b \in \ {1,2,3,4,5,6\ } \  \ )$, elemen-elemen yang memenuhi kondisi ini adalDah:

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
Transitif, untuk setiap pasangan (a, b) € R dan (b, c) € R, juga berlaku (a, c) € R. Dalam konteks ini, jika setiap orang yang mengunjungi halaman web a juga mengunjungi halaman web b, dan setiap orang yang mengunjungi halaman web b juga mengunjungi halaman web c, maka setiap orang yang mengunjungi halaman web a juga harus mengunjungi halaman web c. Oleh karena itu, R adalah transitif, karena aturan yang diberikan dalam definisi R memenuhi sifat transitif, yaitu jika seseorang mengunjungi halaman web a dan b, maka dia juga harus mengunjungi halaman web c.