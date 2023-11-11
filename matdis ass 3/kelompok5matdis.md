# Assignment 03

**Group members**
- Riqqah Khalda Karina (10231082) (Problem 1)
- Alfiani Dwiyuniarti (10231010) (Problem 2)
- David Ramadhani Pangestu (10231028) (Problem 3)
- Muhammad Irvany Saputra (10231064) (Problem 4)
- Irwan Maulana (10231046) (Problem 5)


## Problem 1
Gambarkan K-maps untuk _sum-of-products_ berikut:
- $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$
- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$

Petunjuk: Gunakan tabel di markdown untuk menggambar K-maps.

### Answer
- K-maps untuk _sum-of-products_ $\overline{x}yz$ + $\overline{x}$, $\overline{y}$, $\overline{z}$

|                | $yz$ | $y\overline{z}$ | $\overline{y},\overline{z}$ | $y\overline{z}$ |
| -------------- | ---- | --------------- | --------------------------- | --------------- |
| $x$            |      |                 |                             |                 |
| $\overline{x}$ | 1    |                 | 1                           |                 |

- K-maps untuk _sum-of-products_ $xyz$ + $xy\overline{z}$ + $\overline{x}y\overline{z}$ + $\overline{x},\overline{y}z$

|                | $yz$ | $y\overline{z}$ | $\overline{y},\overline{z}$ | $\overline{y}z$ |
| -------------- | ---- | --------------- | --------------------------- | --------------- |
| $x$            | 1    | 1               |                             |                 |
| $\overline{x}$ |      | 1               |                             | 1               |

   

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


 Relasi $R$ dapat didefinisikan sebagai himpunan
pasangan terurut $\( a, b \)$ dimana $\( a \)$ adalah anggota dari himpunan $A$ dan $\( b \)$ adalah anggota dari himpunan $B$. Dalam hal ini, aturan $(a, b) \in R$ adalah sebagai berikut:

1. $\( a = b \)$: Pasangan $\(a, b \)$ akan termasuk dalam $\( R \)$ jika $\( a \)$ dan $\( b \)$ memiliki nilai yang sama. Dalam konteks ini, setiap anggota himpunan $\( A \)$ akan memiliki relasi dengan anggota himpunan $\( B \)$ yang memiliki nilai yang sama. Misalnya, pasangan $\( 0, 0 \), \( 1, 1 \), \( 2, 2 \), \( 3, 3 \), \( 4, 4 \)$ akan masuk dalam relasi $\( R \)$.

2. $\( a > b \)$: Pasangan $\( a, b \)$ akan termasuk dalam $\( R \)$ jika $\( a \)$ lebih besar dari $\( b \)$. Dalam konteks ini, setiap anggota himpunan $\( A \)$ akan memiliki relasi dengan anggota himpunan $\( B \)$ yang memiliki nilai yang lebih kecil. Misalnya, pasangan $\( 1, 0 \), \( 2, 0 \), \( 2, 1 \), \( 3, 0 \), \( 3, 1 \), \( 3, 2 \), \( 4, 0 \), \( 4, 1 \), \( 4, 2 \), \( 4, 3 \)$ akan masuk dalam relasi $\( R \)$.

Dengan demikian, relasi $\( R \)$ dari himpunan $\( A \)$ ke himpunan $\( B \)$ dengan aturan $\( a, b \in R \)$ adalah sebagai berikut:
$\( R = \{(0, 0), (1, 0), (2, 0), (2, 1), (3, 0), (3, 1), (3, 2), (4, 0), (4, 1), (4, 2), (4, 3)\} \)$
$\( R = \{(0, 0), (1, 0), (2, 0), (2, 1), (3, 0), (3, 1), (3, 2), (4, 0), (4, 1), (4, 2), (4, 3)\} \)$

## Problem 4

Sebutkan semua elemen di dalam relasi 
$R = \{(a, b) \mid a \text{ habis dibagi } b\}$ pada 
himpunan $\{1, 2, 3, 4, 5, 6\}$. Gambarkan juga
relasi $R$ secara grafik (gambar titik untuk masing-masing
domain dan range dan panah berarah).


### Answer

$R = \{(1, 1),(2, 1),(2, 2),(3, 1),(3, 3),(4, 1),(4, 2),(4, 4),(5, 1),(5, 5),(6, 1),(6, 2),(6, 3),(6, 6)\}$


#### Grafik 
$R domain = \{1, 2, 3, 4, 5, 6\}$

$R range = \{1,2,3,4,5,6\}$

Untuk menggambarkan relasi $ \ (  R \ ) $ secara grafik, berikut adalah representasi visualnya:


1 → 1

2 → 1, 2

3 → 1, 3

4 → 1, 2, 4

5 → 1, 5

6 → 1, 2, 3, 6


## Problem 5
Tentukan apakah relasi $R$ pada semua himpunan halaman web
refleksif, simetrik, dan transitif, jika diberikan $(a, b) \in R$
memenuhi aturan:  
setiap orang yang mengunjungi halaman web $a$ juga mengunjungi 
halaman web $b$.

### Answer

Relasi R yang didefinisikan sebagai $“(a,b) \in R$ jika setiap orang yang mengunjungi halaman web a juga mengunjungi halaman web b” dapat dianalisis sebagai berikut:

1. Refleksif: Relasi ini adalah refleksif. Sebab, setiap orang yang mengunjungi halaman web a tentu juga mengunjungi halaman web a itu sendiri. Jadi, untuk setiap halaman web a, pasangan (a,a) ada dalam R.

2. Simetrik: Relasi ini tidak selalu simetrik. Misalnya, jika ada orang yang mengunjungi halaman web a dan b, maka (a,b) dan (b,a) ada dalam R. Namun, jika ada orang yang hanya mengunjungi halaman web a tetapi tidak mengunjungi b, maka (a,b) ada dalam R tetapi (b,a) tidak. Oleh karena itu, relasi ini tidak selalu simetrik.

3. Transitif: Relasi ini adalah transitif. Jika setiap orang yang mengunjungi halaman web a juga mengunjungi b, dan setiap orang yang mengunjungi b juga mengunjungi c, maka setiap orang yang mengunjungi a juga pasti mengunjungi c. Jadi, jika (a,b) dan (b,c) ada dalam R, maka (a,c) juga ada dalam R.

Jadi, relasi R ini adalah refleksif dan transitif, tetapi tidak selalu simetrik.