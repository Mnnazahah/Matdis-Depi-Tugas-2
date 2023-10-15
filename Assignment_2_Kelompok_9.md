# Assignment 02

*Group members*
- Ariel Itsbat Nurhaq (10231018) (Problem #2)
- Noviansyah (10231072) (Problem #3)
- Muchlis Wahyu Saputra (10231054) (Problem #4)
- Eka Kusuma Yanti (10231036) (Problem #5)
- Verina Rahma Dinah (10231090) (Problem #1)

## Problem 1
Tentukan pernyataan berikut apakah bernilai benar atau salah, dan jelaskan 
mengapa bernilai benar atau bernilai salah
1. $`\{\,\} \in \{ \{\,\} \}`$   
2. $`\{\{\,\}\} \in \{ \{\,\}\}`$
3. $`\{\{\,\}\} \subset \{ \{\,\}, \{ \{\,\} \} \}`$
4. $`\{\{ \{\,\}\}\} \subset \{\{\{\,\}\}, \{\{\,\}\}\}`$
5. $`\{\,\} \in \{\{\,\}, \{\{\,\}\}\}`$
6. $`\{\{\,\}\} \in \{\{\{\,\}\}\}`$
7. $`\{\{\{\,\}\}\} \subset \{\{\,\}, \{\{\,\}\}\}`$

### Answer
1. $`\{\,\} \in \{ \{\,\} \}`$   bernilai benar karena himpunan kosong $`\{\,\}`$ merupakan elemen dari himpunan yang berisi himpunan kosong  $`\{ \{\,\} \}`$
2. $`\{\{\,\}\} \in \{ \{\,\}\}`$ bernilai salah karena memiliki elemen yang sama sehingga tidak bisa dikatakan bahwa himpunan yang berisi himpunan kosong ialah elemen dari himpunan yang beri himpunan kosong
3. $`\{\{\,\}\} \subset \{ \{\,\}, \{ \{\,\} \} \}`$ bernilai benar karena himpunan pertama $`\{\{\,\}\}`$ yang elemennya adalah himpunan kosong dan himpunan kosong juga ada pada himpunan kedua sehingga himpunan pertama merupakan sub himpunan kedua
4. $`\{\{ \{\,\}\}\} \subset \{\{\{\,\}\}, \{\{\,\}\}\}`$ bernilai benar karena pada himpunan pertama berisikan himpunan yang berisi himpunan kosong dan himpunan yang berisi himpunan kosong ini juga ada pada himpunan kedua sehingga himpunan pertama adalah sub himpunan kedua
5. $`\{\,\} \in \{\{\,\}, \{\{\,\}\}\}`$ bernilai benar karena pada himpunan kosong pada himpunan pertama juga ada di himpunan kedua $`\{\{\,\}, \{\{\,\}\}\}`$ sehingga himpunan kosong merupakan sub himpunan kedua
6. $`\{\{\,\}\} \in \{\{\{\,\}\}\}`$ bernilai benar karena himpunan yang berisikan himpunan kosong merupakan elemen dari himpunan yang berisikan himpunan yang berisi himpunan kosong 
7. $`\{\{\{\,\}\}\} \subset \{\{\,\}, \{\{\,\}\}\}`$ bernilai benar karena pada himpunan pertama berisikan himpunan yang berisi himpunan kosong dan himpunan yang berisi himpunan kosong ini juga ada pada himpunan kedua yaitu pada elemen kedua $`\{\{\,\}, \{\{\,\}\}\}`$  sehingga himpunan pertama adalah sub himpunan kedua

## Problem 2
Diberikan dua buah himpunan $A$ dan $B$, operasi *selisih simetrik*
yang dinotasikan $A \oplus B$ adalah himpunan yang memuat elemen-elemen
yang berada di $A$ atau di $B$ namun yang tidak berada bersamaan di 
$A$ dan $B$.
1. Carilah selisih simetrik dari dua himpunan berikut: $\{1, 3, 5\}$
   dan $\{1, 2, 3\}$
2. Carilah selisih simetrik dari himpunan mahasiswa SI yang mengambil 
   kelas Matematika diskrit dan himpunan mahasiswa SI yang mengambil 
   kelas Kalkulus 1
3. Gambarkan diagram Venn untuk operasi selisih simetrik dari dua 
   himpunan $A$ dan $B$.

### Answer
1. Himpunan $A$: {1, 3, 5}

    Himpunan $B$: {1, 2, 3}

    Operasi selisih simetris ($A \oplus B$) antara $A$ dan $B$ adalah himpunan yang berisi elemen-elemen yang ada di $A$ atau di $B$, tetapi tidak ada di kedua himpunan tersebut.

    $A \oplus B$ = ($A$ ∪ $B$) - ($A$ ∩ $B$)

    A &cup; B = {1, 2, 3, 5} (menggabungkan semua elemen dari $A$ dan $B$)

    A &cap; B = {1, 3} (elemen yang ada di kedua himpunan $A$ dan $B$)

    $A \oplus B$ = ({1, 2, 3, 5} - {1, 3}) = {2, 5}    

    Jadi, hasil dari operasi selisih simetris antara {1, 3, 5} dan {1, 2, 3} adalah *{2, 5}*.
2. Permisalan 1:

    Himpunan $A$ adalah mahasiswa SI yang mengambil kelas *Matematika Diskrit*.

    Himpunan $B$ adalah mahasiswa SI yang mengambil kelas *Kalkulus 1*.

    Permisalan 2: 

    $A$ = {Ariel, Novi, Muchlis}

    $B$ = {Novi, Muchlis, Bella}

    Selisih simetrisnya adalah:

    $A \oplus B$ = ($A$ - $B$) &cup; ($B$ - $A$)

    $A$ - $B$ adalah himpunan elemen yang ada di $A$ tetapi tidak ada di $B$:
    $A$ - $B$ = {Ariel}

    $B$ - $A$ adalah himpunan elemen yang ada di $B$ tetapi tidak ada di $A$:
    $B$ - $A$ = {Bella}

    Lalu, gabungkan kedua himpunan dengan operator gabungan (&cup;):

    $A \oplus B$ = {Ariel} &cup; {Bella}

    Yang akan menghasilkan: 

    $A \oplus B$ = {Ariel, Bella}

3. https://drive.google.com/file/d/1wIy8ueE1f4SWFzI7-oum5VYPAlkjJJVZ/view?usp=sharing

## Problem 3
Diberikan empat buah fungsi yang memetakan dari himpunan mahasiswa-mahasiswi
yang mengambil kelas Matematika Diskrit ke:
1. nomor telepon
2. nomor induk mahasiswa
3. nilai akhir kelas Matematika Diskrit
4. alamat rumah

Untuk setiap fungsi di atas, batasan apakah yang harus diterapkan supaya 
masing-masing ke-empat fungsi di atas adalah fungsi injektif (fungsi 
satu-satu)?

### Answer
1. Masing-masing mahasiswa harus memiliki nomor telepon yang berbeda agar tidak salah menghubungi mahasisiswa dengan nomor telepon yang sama. Jika tidak, fungsi tersebut tidak akan menjadi satu-satu.
2. Setiap mahasiswa harus memiliki nomor induk mahasiswa agar tidak tertukar dengan mahasiswa lainnya. Jika tidak, fungsi tersebut tidak akan menjadi satu-satu
3. Setiap mahasiswa pasti memiliki nilai akhir yang berbeda dalam mata kuliah Matematika Diskrit karena adanya perbedaan penilaian dengan mahasiswa lainnya. Jika tidak, fungsi tersebut tidak akan menjadi satu-satu
4. Setiap mahasiswa pasti memiliki alamat rumah yang berbeda beda agar tidak membingungkan. Jika tidak, fungsi tersebut tidak akan menjadi satu-satu.

## Problem 4
Diberikan operator Boolean $\oplus$ yang disebut XOR operator dengan 
tabel perhitungan berikut
| $x$ | $y$ | $x \oplus y$ |
|-----|-----|--------------|
| 1   | 1   | 0            |
| 1   | 0   | 1            |
| 0   | 1   | 1            |
| 0   | 0   | 0            |

Tunjukkan bahwa dua identitas berikut berlaku
1. $x \oplus y = (x + y)\overline{xy}$
2. $x \oplus y = (x\overline{y}) + (\overline{x} y)$

### Answer
1. Dibawah ini adalah tabel untuk menunjukkan identitas yang berlaku dari $x \oplus y = (x + y)\overline{xy}$ menggunakan Hukum De Morgan

| $x$ | $y$ | $x \oplus y$ | $x + y$ | $xy$ | $\overline{xy}$ | $(x + y)\overline{xy}$ |
| --- | --- | ------------ | ------- | ---- | --------------- | ---------------------- |
| 1   | 1   | 0            | 1       | 1    | 0               | 0                      |
| 1   | 0   | 1            | 1       | 0    | 1               | 1                      |
| 0   | 1   | 1            | 1       | 0    | 1               | 1                      |
| 0   | 0   | 0            | 0       | 0    | 1               | 0                      |

2. Dibawah ini adalah tabel untuk menunjukkan identitas yang berlaku dari $x \oplus y = (x\overline{y}) + (\overline{x} y)$ menggunakan Hukum De Morgan

| $x$ | $y$ | $x \oplus y$ | $\overline{x}$ | $\overline{y}$ | $x\overline{y}$ | $\overline{x}y$ | $(x\overline{y}) + (\overline{x} y)$ |
| --- | --- | ------------ | -------------- | -------------- | --------------- | --------------- | ------------------------------------ |
| 1   | 1   | 0            | 0              | 0              | 0               | 0               | 0                                    |
| 1   | 0   | 1            | 0              | 1              | 1               | 0               | 1                                    |
| 0   | 1   | 1            | 1              | 0              | 0               | 1               | 1                                    |
| 0   | 0   | 0            | 1              | 1              | 0               | 0               | 0                                    |

Berdasarkan tabel kebenaran di atas, dapat dilihat bahwa kedua identitas tersebut benar untuk setiap kombinasi $x$ dan $y$.\overline{y}) + (\overline{x} y)$ menggunakan Hukum De Morgan

| $x$ | $y$ | $x \oplus y$ | $\overline{x}$ | $\overline{y}$ | $x\overline{y}$ | $\overline{x}y$ | $(x\overline{y}) + (\overline{x} y)$ |
| --- | --- | ------------ | -------------- | -------------- | --------------- | --------------- | ------------------------------------ |
| 1   | 1   | 0            | 0              | 0              | 0               | 0               | 0                                    |
| 1   | 0   | 1            | 0              | 1              | 1               | 0               | 1                                    |
| 0   | 1   | 1            | 1              | 0              | 0               | 1               | 1                                    |
| 0   | 0   | 0            | 1

## Problem 5   
Carilah cara untuk menyatakan komplement, Boolean sum, 
dan Boolean product dengan hanya menggunakan NOR operator

### Answer
Kita akan menggunakan NOR operator

1. Eliminasi komplemen (NOT gate)
   
   $\overline{x}$ = $x$ | $x$

   | $x$ | $\overline{x}$ | $x \| x$ |
   |-----|----------------|----------|
   | 0   | 1              | 1        |
   | 1   | 0              | 0        |

2. Eliminasi perkalian boolean (AND gate)
   
   Menggunakan De Morgan's Law
   
   $(\overline{x+y})$ = $\overline{x}$ $\overline{y}$

   $x$ $y$ = $(x|x)$ | $(y|y)$  

3. Eliminasi penjumlahan boolean (OR gate)

   $x + y$ = $(\overline{x+y})$ = $\overline{x}$ $\overline{y}$
   
   = $\overline{(x|x).(y|y)}$
   
   = [($x|x$)$|$($y|y$)] | [($x|x$)$|$($y|y$)]

   = [($x|x$)$|$($y|y$)] | [($x|x$)$|$($y|y$)] *|* [($x|x$)$|$($y|y$)] | [($x|x$)$|$($y|y$)] 