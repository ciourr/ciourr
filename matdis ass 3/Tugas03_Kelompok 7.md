# Assignment 03

**Group members**
- Andini Permata Dewanti (10231014) (Problem 1)
- Salsabila Putri Zahrani (10231086) (Problem 2)
- Djaky Abbyyu Fauzan Timuumum (10231032) (Problem 3)
- Nazwa Amelia Zahra (10231068) (problem 4)

## Problem 1
Gambarkan K-maps untuk _sum-of-products_ berikut:
- $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$
- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$

Petunjuk: Gunakan tabel di markdown untuk menggambar K-maps.

### Answer
K-maps dari _sum-of-products_ tersebut adalah :
- $\overline {x}yz$ + $\overline {x}\, \overline {y}\, \overline {z}$

|$ $|$yz$| $y\overline{z}$  |$\overline{y}\, \overline {z}$|$\overline {y}z$|
|--|---|----|-----|------|
|$x$|  |    |     |
|$\overline{x}$|$\overline{x}yz$|     |$\overline {x}\, \overline {y}\,\overline {z}$|
|  |   |    |     |      |


- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$

|$ $|$yz$| $y\overline{z}$  |$\overline{y}\, \overline {z}$|$\overline {y}z$|
|--|---|----|-----|------|
|$x$| $xyz$ |  $xy\overline {z}$  |     |
|$\overline{x}$|   |$\overline{x}\,y\overline{z}$|     |$\overline {x}\,\overline {y}\, z$|
|  |   |    |     |      |


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


    $xy\overline{z}$ + $\overline{x}y\overline{z}$ = $y\overline{z}$

## Problem 3

Tentukan relasi $R$ dari himpunan $A = \{0, 1, 2, 3, 4\}$
ke himpunan $B = \{0, 1, 2, 3\}$ dengan aturan $(a, b) \in R$
sebagai berikut:
- $a = b$
- $a > b$

### Answer
ika a = b maka (a,b) adalah anggota dari relasi $R$


(0,0)
(1,1)
(2,2)
(3,3)
(4,4)


selanjutnya apabila a > b mengartikan bahwasanya a lebih besar dari pada b, maka (a,b) adalah anggota dari  relasi $R$
elemen-elemen yang memenuhi syarat tersebut adalah sebagai berikut
(1,0)
(2,0)
(2,1)
(3,0)
(3,1)
(3,2)
(4,0)
(4,1)
(4,3)
(4,4)

jadi relasi $R$ dari himpunan A ke himmpunan B dengan aturan $(a,b) \in R$ adalah sebagai berikut

$R$ ={(0,0),(1,0),(2,0),(2,1),(3,0)}

## Problem 4

Sebutkan semua elemen di dalam relasi 
$R = \{(a, b) \mid a \text{ habis dibagi } b\}$ pada 
himpunan $\{1, 2, 3, 4, 5, 6\}$. Gambarkan juga
relasi $R$ secara grafik (gambar titik untuk masing-masing
domain dan range dan panah berarah).


### Answer
\[
R = \{(1,1), (2,1), (2,2), (3,1), (3,3), (4,1), (4,2), (4,4), (5,1), (5,5), (6,1), (6,2), (6,3), (6,6)\}
\]

Untuk menggambarkan relasi \( R \) secara grafik, berikut adalah representasi visualnya:


1 → 1

2 → 1, 2

3 → 1, 3

4 → 1, 2, 4

5 → 1, 5

6 → 1, 2, 3, 6


Dalam representasi grafik ini, panah dari angka di sebelah kiri menunjuk ke angka-angka di sebelah kanan yang memenuhi kondisi \( a \) habis dibagi \( b \).

## Problem 5
Tentukan apakah relasi $R$ pada semua himpunan halaman web
refleksif, simetrik, dan transitif, jika diberikan $(a, b) \in R$
memenuhi aturan:  
setiap orang yang mengunjungi halaman web $a$ juga mengunjungi 
halaman web $b$.

### Answer

Relasi $R$ adalah refleksif, simetrik, dan transitif. Alasan nya adalah:

1. Refleksif: Relasi $R$ adalah refleksif jika setiap elemen $a$ dalam domain terkait dengan dirinya sendiri, yaitu $(a, a)$ ada dalam $R$ untuk setiap $a$ dalam domain. Dalam konteks ini, setiap halaman web $a$ dikunjungi oleh dirinya sendiri, sehingga refleksif.

2. Simetrik: Relasi $R$ adalah simetrik jika untuk setiap $(a, b)$ dalam $R$, ada juga $(b, a)$ dalam $R$. Dalam konteks ini, jika seseorang mengunjungi halaman web $a$ dan $b$, maka orang tersebut juga mengunjungi $b$ dan $a$, sehingga simetrik.

3. Transitif: Relasi $R$ adalah transitif jika untuk setiap $(a, b)$ dan $(b, c)$ dalam $R$, ada juga $(a, c)$ dalam $R$. Dalam konteks ini, jika seseorang mengunjungi halaman web $a$ dan $b$, dan juga $b$ dan $c$, maka orang tersebut juga mengunjungi $a$ dan $c$, sehingga transitif.