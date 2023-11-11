# Assignment 03

**Group members**
- Muhammad Ayash Az Dzikri (10231060) (Problem 1)
- Aditya Laksamana P Butar Butar (10231006) (Problem 2)
- Cantika Ade Qutnindra Maharani (10231024) (Problem 3)
- Ranaya chintya Mahitsa (10231078) (Problem 4) 
- Ilham Ahmad Fahriji (10231042) (Problem 5)

## Problem 1
Gambarkan K-maps untuk _sum-of-products_ berikut:
- $\overline{x}yz + \overline{x}\,\overline{y}\,\overline{z}$
- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$

Petunjuk: Gunakan tabel di markdown untuk menggambar K-maps.

### Answer
- $\overline{x}yz + \overline{x}\, \overline{y}\, \overline{z}$

|   | 00 | 01 | 11 | 10 |
|---|----|----|----|----|
|00 |  0 |  1 |  0 |  0 |
|01 |  0 |  0 |  0 |  0 |
|11 |  0 |  0 |  1 |  0 |
|10 |  0 |  0 |  0 |  0 |

- $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\, \overline{y}z$

|   | 00 | 01 | 11 | 10 |
|---|----|----|----|----|
|00 |  0 |  0 |  0 |  0 |
|01 |  0 |  1 |  0 |  1 |
|11 |  0 |  1 |  1 |  1 |
|10 |  0 |  0 |  0 |  0 |
## Problem 2

Sederhanakan K-maps yang ada di Problem 1 dengan aturan 
yang telah di bahas di pertemuan minggu ke-9.


### Answer
- K-maps untuk _sum-of-product_ $\overline{x}yz$ + $\overline{x}$ $\overline{y}$ $\overline{z}$ jika disederhanakan menjadi $xx$ + $xy$ +$xz$ + $yz$ dengan nilai :

  x = 0, y = 1, z = 1 untuk $\overline{x}yz$

  x = 0, y = 0, z = 0 untuk $\overline{x}$ $\overline{y}$ $\overline{z}$

- K-maps untuk _sum-of-product_ $xyz + xy\overline{z} + \overline{x}y\overline{z} + \overline{x}\,\overline{y}z$ jika disederhanakan menjadi $xy$ + $xz$ +$yz$ + $zz$ dengan nilai :

  x = 1, y = 1, z = 1 untuk $xyz$

  x = 1, y = 1, z = 0 untuk $xy\overline{z}$

  x = 0, y = 1, z = 0 untuk $\overline{x}y\overline{z}$

  x = 0, y = 0, z = 1 untuk $\overline{x}\overline{y}z$

## Problem 3

Tentukan relasi $R$ dari himpunan $A = \{0, 1, 2, 3, 4\}$
ke himpunan $B = \{0, 1, 2, 3\}$ dengan aturan $(a, b) \in R$
sebagai berikut:
- $a = b$
- $a > b$

### Answer
Untuk dapat menentukan relasi _R_ antara himpunan _A_ dan _B_ dengan aturan (a, b) ∈ _R_ jika a = b atau a > b. 


+  Ketika a = b, maka pasangan memenuhi aturan (a, b) ∈ _R_. Jadi, bisa ditambahkan pasangan (0, 0), (1, 1) (2, 2), dan (3, 3) ke dalam relasi _R_.

+ Ketika a > b, maka pasangan juga memenuhi aturan (a, b) ∈ _R_. Ini dapat terjadi karena kita harus mempertimbangkan semua pasangan di mana a > b. Pasangan-pasangan ini adalah:
   - (1, 0)
   - (2, 0), (2, 1)
   - (3, 0), (3, 1), (3, 2)
   - (4, 0), (4, 1), (4, 2), (4, 3)

Jadi, relasi _R_ yang ada antara _A_ dan _B_ adalah sebagai berikut:
R = {(0, 0), (1, 1), (2, 2), (3, 3), (1, 0), (2, 0), (2, 1), (3, 0), (3, 1), (3, 2), (4, 0), (4, 1), (4, 2), (4, 3)}

jadi dapat disimpulkan, himpunan merupakan himpunan pasangan terurut yang memenuhi aturan (a, b) ∈ _R_ sesuai dengan a = b atau a > b antara himpunan _A_ dan _B_.
## Problem 4

Sebutkan semua elemen di dalam relasi 
$R = \{(a, b) \mid a \text{ habis dibagi } b\}$ pada 
himpunan $\{1, 2, 3, 4, 5, 6\}$. Gambarkan juga
relasi $R$ secara grafik (gambar titik untuk masing-masing
domain dan range dan panah berarah).


### Answer
- (1, 1) - 1 habis dibagi 1
- (2, 1) - 2 habis dibagi 1
- (2, 2) - 2 habis dibagi 2
- (3, 1) - 3 habis dibagi 1
- (3, 3) - 3 habis dibagi 3
- (4, 1) - 4 habis dibagi 1
- (4, 2) - 4 habis dibagi 2
- (4, 4) - 4 habis dibagi 4
- (5, 1) - 5 habis dibagi 1
- (5, 5) - 5 habis dibagi 5
- (6, 1) - 6 habis dibagi 1
- (6, 2) - 6 habis dibagi 2
- (6, 3) - 6 habis dibagi 3
- (6, 6) - 6 habis dibagi 6

Gambar grafiknya relasi R seperti ini:

Domain: {1, 2, 3, 4, 5, 6}

Range: {1, 2, 3, 4, 5, 6}

![gambar_grafik_relasi_R](image.png)
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

Jadi, relasi R bersifat refleksif, simetris, dan tidak transitif.