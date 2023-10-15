# Assignment 02

**Group members**
- Alfiani Dwiyuniarti (10231010) (Problem #1)
- Muhammad Irvany Saputra (10231064) (Problem #2)
- Irwan Maulana (10231046) (Problem #3)
- Riqqah Khalda Karina (10231082) (Problem #4)
- David Ramadhani Pangestu (10231028) (Problem #5)

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
1. $`\{\,\} \in \{ \{\,\} \}`$
Benar. Ini mengatakan bahwa himpunan kosong (yang tidak berisi apa-apa) adalah salah satu elemen dari himpunan yang berisi himpunan kosong. Dengan kata lain, kita punya "sebuah kotak kosong di dalam sebuah kotak".

2. $`\{\{\,\}\} \in \{ \{\,\}\}`$
Salah. Ini menyatakan bahwa sebuah himpunan yang berisi himpunan kosong adalah elemen dari himpunan yang berisi himpunan kosong. Keduanya adalah himpunan yang sama, jadi pernyataan ini tidak benar.

3. $`\{\{\,\}\} \subset \{ \{\,\}, \{ \{\,\} \} \}`$
Benar. Himpunan yang berisi himpunan kosong adalah bagian dari (atau subset dari) himpunan yang memiliki dua elemen: himpunan kosong dan himpunan yang berisi himpunan kosong.

4. $`\{\{ \{\,\}\}\} \subset \{\{\{\,\}\}, \{\{\,\}\}\}`$
Benar. Himpunan yang berisi himpunan yang berisi himpunan kosong adalah subset dari himpunan yang memiliki dua elemen: himpunan yang berisi himpunan yang berisi himpunan kosong dan himpunan yang berisi himpunan kosong.

5. $`\{\,\} \in \{\{\,\}, \{\{\,\}\}\}`$
Benar. Himpunan kosong adalah salah satu elemen dari himpunan yang memiliki dua elemen: himpunan kosong dan himpunan yang berisi himpunan kosong.

6. $`\{\{\,\}\} \in \{\{\{\,\}\}\}`$
Salah. Himpunan yang berisi himpunan kosong bukan elemen dari himpunan yang berisi himpunan yang berisi himpunan kosong.

7. $`\{\{\{\,\}\}\} \subset \{\{\,\}, \{\{\,\}\}\}`$
Salah. Himpunan yang berisi himpunan yang berisi himpunan kosong bukan subset dari himpunan yang memiliki dua elemen: himpunan kosong dan himpunan yang berisi himpunan kosong.

## Problem 2

Diberikan dua buah himpunan $A$ dan $B$, operasi **selisih simetrik**
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

### Answer :
   1. $A$ = $\{1,3,5\}$

      $B$ = $\{1,2,3\}$

      $A$ $\oplus$ $B$ = $\{2,5\}$

   2.   $A$ = { mahasiswa SI yang mengambil 
   kelas Matematika diskrit }

        $B$ = {mahasiswa SI yang mengambil 
   kelas Kalkulus 1}

        $A$ $\oplus$ $B$ = { mahasiswa SI yang mengambil 
   kelas Matematika diskrit saja }

        $A$ $\oplus$ $B$ = { mahasiswa SI yang mengambil 
   kelas Kalkulus 1 saja }

   3. ![Diagram_venn_problem_3](<Diagram Venn problem 3.png>)
   
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
Untuk setiap fungsi di atas, perlu dipastikan bahwa kondisi ini terpenuhi. Berikut adalah batasan yang harus diterapkan untuk masing-masing fungsi:

1. Nomor telepon : Batasannya adalah setiap mahasiswa-mahasiswi harus memiliki nomor telepon yang unik dan tidak ada yang sama dengan nomor telepon orang lain. Jika ada yang memiliki nomor telepon yang sama, maka fungsi ini tidak injektif karena ada dua elemen di domain yang memiliki bayangan yang sama di kodomain.
   
2. Nomor induk mahasiswa : Batasannya adalah setiap mahasiswa-mahasiswi harus memiliki nomor induk mahasiswa yang unik dan tidak ada yang sama dengan nomor induk mahasiswa orang lain. Jika ada yang memiliki nomor induk mahasiswa yang sama, maka fungsi ini tidak injektif karena ada dua elemen di domain yang memiliki bayangan yang sama di kodomain.
   
3. Nilai akhir kelas Matematika Diskrit : Batasannya adalah setiap mahasiswa-mahasiswi harus memiliki nilai akhir kelas Matematika Diskrit yang unik dan tidak ada yang sama dengan nilai akhir kelas Matematika Diskrit orang lain. Jika ada yang memiliki nilai akhir kelas Matematika Diskrit yang sama, maka fungsi ini tidak injektif karena ada dua elemen di domain yang memiliki bayangan yang sama di kodomain.
   
4. Alamat rumah : Batasannya adalah setiap mahasiswa-mahasiswi harus memiliki alamat rumah yang unik dan tidak ada yang sama dengan alamat rumah orang lain. Jika ada yang memiliki alamat rumah yang sama, maka fungsi ini tidak injektif karena ada dua elemen di domain yang memiliki bayangan yang sama di kodomain.

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
1. $x \oplus y = (x + y)\overline{xy}$

| $x$ | $y$ | $x+y$ | $xy$ |$\overline{xy}$ | $(x + y)\overline{xy}$ |
|-----|-----|-------|------|----------------|------------------------|
| 1   | 1   | 1     | 1    | 0              | 0                      |
| 1   | 0   | 1     | 0    | 1              | 1                      |
| 0   | 1   | 1     | 0    | 1              | 1                      |
| 0   | 0   | 0     | 0    | 1              | 0                      |

jadi identitas $x \oplus y = (x + y)\overline{xy}$ berlaku

2. $x \oplus y = (x\overline{y}) + (\overline{x} y)$

| $x$ | $y$ | $\overline{x}$ | $\overline{y}$ | $(x\overline{y})$ | $(\overline{x} y)$ | $(x\overline{y}) + (\overline{x} y)$ |
|-----|-----|----------------|----------------|-------------------|--------------------|--------------------------------------|
| 1   | 1   | 0              | 0              | 0                 | 0                  | 0                                    |
| 1   | 0   | 0              | 1              | 1                 | 0                  | 1                                    |
| 0   | 1   | 1              | 0              | 0                 | 1                  | 1                                    |
| 0   | 0   | 1              | 1              | 0                 | 0                  | 0                                    |

jadi identitas $x \oplus y = (x\overline{y}) + (\overline{x} y)$ berlaku

## Problem 5
Carilah cara untuk menyatakan komplement, Boolean sum, dan Boolean product dengan hanya menggunakan NOR operator

### Answer
1). Untuk menyatakan komplement (NOT) menggunakan operator NOR,
dapat dilakukan dengan menghubungkan kedua input NOR ke dalam NAND gate,
melalui sirkuit berikut:

A → NOR gate --┐ → NOR gate --┐
                ├─────────> NOT A
B → NOR gate --┘

Dalam sirkuit di atas, output dari kedua gerbang NOR dihubungkan bersama untuk membentuk kedua input ke NOT gate,
sehingga menghasilkan keluaran yang merupakan kebalikan dari input A.

2.) Untuk menyatakan Boolean sum (OR) menggunakan operator NOR,
dapat dilakukan dengan menghubungkan dua input ke dalam gate NOR,
melalui sirkuit berikut:

A → NOR gate --┐ → OR A,B
B → NOR gate --┘

Dalam sirkuit di atas, kedua input dihubungkan ke gerbang NOR,
dan output dari gerbang tersebut adalah hasil dari operasi OR antara input A dan B.

3). Untuk menyatakan Boolean product (AND) menggunakan operator NOR,
dapat dilakukan dengan menghubungkan kedua input NOR ke dalam sirkuit berikut:

A → NOR gate --┐
                ├──→ AND A,B
B → NOR gate --┘

Dalam sirkuit di atas, kedua input dihubungkan ke gerbang NOR,
dan output dari gerbang tersebut adalah hasil dari operasi AND antara input A dan B.
