# Assignment 03

*Group members*
- Ariel Itsbat Nurhaq (10231018) (Problem #3)
- Noviansyah (10231072) (Problem #4)
- Muchlis Wahyu Saputra (10231054) (Problem #5)
- Eka Kusuma Yanti (10231036) (Problem #1)
- Verina Rahma Dinah (10231090) (Problem #2)

## Problem 1
Gambarkan K-maps untuk sum-of-products berikut:
- $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$
- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$

Petunjuk: Gunakan tabel di markdown untuk menggambar K-maps.

### Answer

K-Maps 3 Variabel Boolean

- $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$

    |              |$yz$    | $y\overline{z}$ | $\overline{y}\,\overline{z}$             | $\overline{y}z$|
    |--------------|--------|-----------------|------------------------------------------|----------------|
    |$x$           |        |                 |                                          |                |
    |$\overline{x}$|$\overline{x}yz$|         |$\overline{x}\,\overline{y}\,\overline{z}$|                |

- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$

    |              |$yz$    | $y\overline{z}$           | $\overline{y}\,\overline{z}$ | $\overline{y}z$             |
    |--------------|--------|---------------------------|------------------------------|-----------------------------|
    |$x$           |$xyz$   |$xy\overline{z}$           |                              |                             |
    |$\overline{x}$|        |$\overline{x}y\overline{z}$|                              |$\overline{x}\,\overline{y}z$|

## Problem 2

Sederhanakan K-maps yang ada di Problem 1 dengan aturan 
yang telah di bahas di pertemuan minggu ke-9.


### Answer

K-Maps 3 Variabel Boolean

- $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$

    |              |$yz$    | $y\overline{z}$ | $\overline{y}\,\overline{z}$             | $\overline{y}z$|
    |--------------|--------|-----------------|------------------------------------------|----------------|
    |$x$           |        |                 |                                          |                |
    |$\overline{x}$|$.$|         |$.$|                |

  $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$ = $\overline{x}$ ($yz$ + $\overline{y}$ $\overline{z}$  ) = $\overline{x}$


- $xyz+ xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$

    |              |$yz$    | $y\overline{z}$           | $\overline{y}\,\overline{z}$ | $\overline{y}z$             |
    |--------------|--------|---------------------------|------------------------------|-----------------------------|
    |$x$           |$.$   |$.$           |                              |                             |
    |$\overline{x}$|        |$.$|                              |$.$|

    
  - $xyz + xy\overline{z}$ = $xy ( z + \overline{z})$ = $xy(1)$ = $xy$

    $xy\overline{z} + \overline{x}y\overline{z}$ = $( x + \overline{x})y\overline{z}$ = $(1)y\overline{z}$ = $y\overline{z}$

     $xy$ + $y\overline{z}$
   
  - $\overline{x}y\overline{z} + \overline{x}\,\overline{y}z$

    $\overline{x}$($y\overline{z} + \overline{y}z$) = $\overline{x}$

  - $xy$ + $y\overline{z}$ + $\overline{x}$
  
    $y(x+\overline{z})$+ $\overline{x}$
    
    $y$ + $\overline{x}$

jadi, hasil penyederhanaannya ialah $\overline{x}$ + $y$

## Problem 3

Tentukan relasi $R$ dari himpunan $A = \{0, 1, 2, 3, 4\}$
ke himpunan $B = \{0, 1, 2, 3\}$ dengan aturan $(a, b) \in R$
sebagai berikut:
- $a = b$
- $a > b$

### Answer

- $a = b$ 

Relasi $R$ dari himpunan $A = \{0, 1, 2, 3, 4\}$ ke himpunan $B = \{0, 1, 2, 3\}$ dengan menggunakan $(a, b) \in R$ jika $a$ = $b$

$R = \{(0, 0), (1, 1), (2, 2), (3, 3)\}$ 

- $a > b$

Relasi $R$ dari himpunan $A = \{0, 1, 2, 3, 4\}$ ke himpunan $B = \{0, 1, 2, 3\}$ dengan menggunakan $(a, b) \in R$ jika $a > b$ 

$R = \{(1, 0), (2, 0), (2, 1), (3, 0), (3, 1), (3, 2), (4, 0), (4, 1), (4, 2), (4, 3)\}$ 

Kesimpulanya adalah jika relasi $R$ dari himpunan $A$ ke $B$ jika $a = b$ dan $a > b$ 

$R = \{(1, 0), (2, 0), (2, 1), (3, 0), (3, 1), (3, 2), (4, 0), (4, 1), (4, 2), (4, 3)\}$


## Problem 4

Sebutkan semua elemen di dalam relasi 
$R = \{(a, b) \mid a \text{ habis dibagi } b\}$ pada 
himpunan $\{1, 2, 3, 4, 5, 6\}$. Gambarkan juga
relasi $R$ secara grafik (gambar titik untuk masing-masing
domain dan range dan panah berarah).


### Answer

di dalam relasi R, di mana a habis dibagi b, dan elemen-elemen tersebut berasal dari himpunan {1, 2, 3, 4, 5, 6}.

Kita harus menemukan semua pasangan (a, b) yang memenuhi syarat tersebut. Mari kita cek satu persatu:

a = 1, b = 1 (karena 1 habis dibagi 1)

a = 2, b = 1 (karena 2 habis dibagi 1)

a = 3, b = 1 (karena 3 habis dibagi 1)

a = 4, b = 1 (karena 4 habis dibagi 1)

a = 5, b = 1 (karena 5 habis dibagi 1)

a = 6, b = 1 (karena 6 habis dibagi 1)

a = 2, b = 2 (karena 2 habis dibagi 2)

a = 4, b = 2 (karena 4 habis dibagi 2)

a = 6, b = 2 (karena 6 habis dibagi 2)

a = 3, b = 3 (karena 3 habis dibagi 3)

a = 6, b = 3 (karena 6 habis dibagi 3)

a = 4, b = 4 (karena 4 habis dibagi 4)

a = 6, b = 4 (karena 6 habis dibagi 4)

a = 5, b = 5 (karena 5 habis dibagi 5)

a = 6, b = 6 (karena 6 habis dibagi 6)

Jadi, semua elemen dalam relasi R = {(1, 1), (2, 1), (3, 1), (4, 1), (5, 1), (6, 1), (2, 2), (4, 2), (6, 2), (3, 3), (6, 3), (4, 4), (6, 4), (5, 5), (6, 6)}.

Berikut adalah representasi grafis dari relasi R:
graph TD;
1 --> 1;

2 --> 1;

3 --> 1;

4 --> 1;

5 --> 1;

6 --> 1;

2 --> 2;

4 --> 2;

6 --> 2;

3 --> 3;

6 --> 3;

4 --> 4;

6 --> 4;

5 --> 5;

6 --> 6;

## Problem 5
Tentukan apakah relasi $R$ pada semua himpunan halaman web
refleksif, simetrik, dan transitif, jika diberikan $(a, b) \in R$
memenuhi aturan:  
setiap orang yang mengunjungi halaman web $a$ juga mengunjungi 
halaman web $b$.

### Answer

- Relasi refleksif

Sebuah relasi dikatakan refleksif jika setiap anggota himpunan berpasangan dengan dirinya sendiri.

Relasi R bersifat refleksif jika setiap halaman web berhubungan dengan dirinya sendiri.

Misalkan halaman web a ada di himpunan halaman web. Maka, setiap orang yang mengunjungi halaman web a juga mengunjungi halaman web a. Oleh karena itu, (a,a) ∈ R, sehingga relasi R bersifat refleksif

- Relasi simetris

Sebuah relasi dikatakan simetris jika untuk setiap pasangan (a,b) ∈ R, maka (b,a) ∈ R.

Dalam hal ini, jika setiap orang yang mengunjungi halaman web a juga mengunjungi halaman web b, maka setiap orang yang mengunjungi halaman web b juga mengunjungi halaman web a. Oleh karena itu, relasi R bersifat simetris.

- Relasi transitif

Sebuah relasi dikatakan transitif jika untuk setiap pasangan (a,b) ∈ R dan (b,c) ∈ R, maka (a,c) ∈ R.

Dalam hal ini, jika setiap orang yang mengunjungi halaman web a juga mengunjungi halaman web b, dan setiap orang yang mengunjungi halaman web b juga mengunjungi halaman web c, maka setiap orang yang mengunjungi halaman web a juga mengunjungi halaman web c. Oleh karena itu, relasi R bersifat  tidak transitif karena tidak terdapat halaman web c di dalam relasi R.

- Kesimpulan

Relasi R pada semua himpunan halaman web bersifat refleksif, simetrik, dan tidak transitif.

- Contoh

Misalkan ada dua halaman web, yaitu a dan b. Jika ada orang yang mengunjungi halaman web a, maka orang tersebut juga mengunjungi halaman web b. Maka, (a,b) ∈ R.

Karena relasi R bersifat refleksif, maka (a,a) ∈ R.

Karena relasi R bersifat simetris, maka (b,a) ∈ R.

Karena relasi R bersifat tidak transitif, maka (a,b) ∈ R dan (b,c) ∈ R implies (a,c) ∈ R. 

Jadi, relasi R bersifat refleksif, simetris, dan tidak transitif.an transitif jika untuk setiap pasangan (a,b) ∈ R dan (b,c) ∈ R, maka (a,c) ∈ R.

Dalam hal ini, jika setiap orang yang mengunjungi halaman web a juga mengunjungi halaman web b, dan setiap orang yang mengunjungi halaman web b juga mengunjungi halaman web c, maka setiap orang yang mengunjungi halaman web a juga mengunjungi halaman web c. Oleh karena itu, relasi R bersifat  tidak transitif karena tidak terdapat halaman web c di dalam relasi R.

- Kesimpulan

Relasi R pada semua himpunan halaman web bersifat refleksif, simetrik, dan tidak transitif.

- Contoh

Misalkan ada dua halaman web, yaitu a dan b. Jika ada orang yang mengunjungi halaman web a, maka orang tersebut juga mengunjungi halaman web b. Maka, (a,b) ∈ R.

Karena relasi R bersifat refleksif, maka (a,a) ∈ R.

Karena relasi R bersifat simetris, maka (b,a) ∈ R.

Karena relasi R bersifat tidak transitif, maka (a,b) ∈ R dan (b,c) ∈ R implies (a,c) ∈ R. 

Jadi, relasi R bersifat refleksif, simetris, dan tidak transitif.