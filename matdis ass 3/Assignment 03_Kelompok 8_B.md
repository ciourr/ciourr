# Assignment 03

**Anggota kelompok**
- Anjas Geofany Diamare_10231016  (Soal 1)
- Dzakwan Fatih Fadhilah_10231034  (Soal 2)
- Meiske Handayani_10231052  (Soal 3)
- Nilam Ayu NandaStari Romdoni_10231070  (Soal 4)
- Tiya Mitra Ayu Purwanti_10231088  (Soal 5)

## Soal 1
Gambarkan K-maps untuk _sum-of-products_ berikut:
- $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$
- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$

Petunjuk: Gunakan tabel di markdown untuk menggambar K-maps.

### Jawaban
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


## Soal 2
Sederhanakan K-maps yang ada di Problem 1 dengan aturan 
yang telah di bahas di pertemuan minggu ke-9.

### Jawaban 
- K-maps untuk _sum-of-product_ $\overline{x}yz$ + $\overline{x}$ $\overline{y}$ $\overline{z}$ jika disederhanakan menjadi $xx$ + $xy$ + $xz$ + $yz$ dengan nilai :

  x = 0, y = 1, z = 1 untuk $\overline{x}yz$
  
  x = 0, y = 0, z = 0 untuk $\overline{x}$ $\overline{y}$ $\overline{z}$

- K-maps untuk _sum-of-product_ $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$ jika disederhanakan menjadi $xy$ + $xz$ +$yz$ + $zz$ dengan nilai :

  x = 1, y = 1, z = 1 untuk $xyz$

  x = 1, y = 1, z = 0 untuk $xy\overline{z}$

  x = 0, y = 1, z = 0 untuk $\overline{x}y\overline{z}$

  x = 0, y = 0, z = 1 untuk $\overline{x}\overline{y}z$

## Soal 3
Tentukan relasi $R$ dari himpunan $A = \{0, 1, 2, 3, 4\}$
ke himpunan $B = \{0, 1, 2, 3\}$ dengan aturan $(a, b) \in R$
sebagai berikut:
- $a = b$
- $a > b$

### Jawaban
pasangan terurut yang memenuhi aturan  $a = b$ adalah
 
- $a = b$ = $\{(0, 0), (1, 1), (2, 2), (3, 3), dan (4, 4)\}$. 

pasangan terurut yang memenuhi aturan $a > b$ adalah


-  $a > b$ = $\{(3, 2), (4, 3), dan (4, 2)\}$.

 Oleh karena itu, relasi $R$ dari himpunan $A$ ke himpunan $B$ adalah sebagai berikut 

 $R$ = ${(0, 0), (1, 1), (2, 2), (3, 3), (4, 4), (3, 2), (4, 3), (4, 2)}$


## Soal 4
Sebutkan semua elemen di dalam relasi 
$R = \{(a, b) \mid a \text{ habis dibagi } b\}$ pada 
himpunan $\{1, 2, 3, 4, 5, 6\}$. Gambarkan juga
relasi $R$ secara grafik (gambar titik untuk masing-masing
domain dan range dan panah berarah).
    
### Jawaban
$A = \{1, 2, 3, 4, 5, 6\}$
$R = \{(1,1), (2,1), (2,2), (3,1), (3,3), (4,1), (4,2), (4,4), (5,1), (5,5), (6,1), (6,2), (6,3), (6,6)\}$

Berikut adalah elemen-elemen dalam relasi $R$ untuk himpunan $\{1,2,3,4,5,6\}$ :
1. $(1,1)$ : 1 habis dibagi oleh 1
2. $(2,1)$ : 2 habis dibagi oleh 1
3. $(2,2)$ : 2 habis dibagi oleh 2
4. $(3,1)$ : 3 habis dibagi oleh 1
5. $(3,3)$ : 3 habis dibagi oleh 3
6. $(4,1)$ : 4 habis dibagi oleh 1
7. $(4,2)$ : 4 habis dibagi oleh 2
8. $(4,4)$ : 4 habis dibagi oleh 4
9. $(5,1)$ : 5 habis dibagi oleh 1
10. $(5,5)$ : 5 habis dibagi oleh 5
11. $(6,1)$ : 6 habis dibagi oleh 1
12. $(6,2)$ : 6 habis dibagi oleh 2
13. $(6,3)$ : 6 habis dibagi oleh 3
14. $(6,6)$ : 6 habis dibagi oleh 6

Grafik relasi $R$ adalah sebagai berikut :

<img src="../Markdown/grafik.jpeg" width=300>

1 $\dashrightarrow$ 1

2 $\dashrightarrow$ 1, 2

3 $\dashrightarrow$ 1, 3

4 $\dashrightarrow$ 1, 2, 4

5 $\dashrightarrow$ 1, 5

6 $\dashrightarrow$ 1, 2, 3, 6


## Soal 5
Tentukan apakah relasi $R$ pada semua himpunan halaman web
refleksif, simetrik, dan transitif, jika diberikan $(a, b) \in R$
memenuhi aturan:  
setiap orang yang mengunjungi halaman web $a$ juga mengunjungi 
halaman web $b$.

### Jawaban
$R$ = \{ Pengunjung halaman web }
 
 dari relasi $R = \{(a,b), | a, b \in R$ dugaan orng yang mengunjungin web a juga mengunjungi web b }

 Tentukan apakah $R$ refleksif, simetrik,dan transitif?

 $R = \{(a,b), | a, b \in R$ orng yang mengunjungin web a juga mengunjungi web b }
 
 - Apakan $R$ refleksif ? Tidak

   a > b $\dashrightarrow$ a =! b 

   $R \in R$ = (r, r ) $\dashrightarrow$ r = r $ \in R$ 

   r > r 
   
- Apakah $ R$ simetrik ? Tidak

  ambil 1 pengunjung di web a dan 1 pengungunjung di web b 

  r1 , r2  $\dashrightarrow$ (r1, r2) $ \in R$

   $\dashrightarrow$ r1 > r2 (ini salah)

  (r1, r2) $ \in R$ $\dashrightarrow$ (r1, r2) $ \in R$ ?

  r2 > r1

 - Apakah $ R$ Transitif ? Iya

   kita ambil r1, r2 $ \in R$ dan (r1, r2) $ \in R$ ambil lagi pasangan kedua dari salah satu penggunjung web, r2,r3 $ \in R$ dan (r2, r3) $ \in R$

   (r1, r2) $ \in R$ $ \in R$ $\dashrightarrow$ r1, r2

   (r2, r3) $ \in R$ $ \in R$ $\dashrightarrow$ r2, r3

   r2 > r3

   (r2, r3) $ \in R$
  <!--  --> 


  