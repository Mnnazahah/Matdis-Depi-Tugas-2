# Assignment 02

**Group members**
- Muhammad Alif Setiawan (10231056) (Problem 1)
- Putri Rahmawati (10231074) (Problem 2)
- Arya Wijaya S (10231020) (Problem 3)
- Achmad Zaki Zaidan (10231002) (Problem 4)
- Firni Fauziah Ramadhini (10231038) (Problem 5)

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
    Benar, karena himpunan kosong $\{\,\}$ adalah anggota dari himpunan yang juga berisi himpunan kosong.

2. $`\{\{\,\}\} \in \{ \{\,\}\}`$
   Benar, karena himpunan yang berisi himpunan kosong $\{\{\,\}\}$ adalah anggota dari himpunan yang berisi satu himpunan kosong $\{\{\,\}\}$

3. $`\{\{\,\}\} \subset \{ \{\,\}, \{ \{\,\} \} \}`$
   Benar, karena himpunan yang berisi himpunan kosong $\{\{\,\}\}$ adalah himpunan bagian dari himpunan yang berisi dua elemen: satu himpunan kosong $\{\,\}$ dan satu himpunan yang berisi himpunan kosong $\{\{\,\}\}$

4. $`\{\{ \{\,\}\}\} \subset \{\{\{\,\}\}, \{\{\,\}\}\}`$
   Benar, karena himpunan yang berisi himpunan yang berisi himpunan kosong $\{\{ \{\,\}\}\}$ adalah himpunan bagian dari himpunan yang berisi dua elemen: satu himpunan yang berisi himpunan kosong $\{\{ \{\,\}\}\}$ dan satu himpunan yang berisi himpunan kosong $\{\{\,\}\}$

5. $`\{\,\} \in \{\{\,\}, \{\{\,\}\}\}`$
   Benar, karena himpunan kosong $\{\,\}$ adalah salah satu elemen dalam himpunan yang berisi dua elemen: satu himpunan kosong $\{\,\}$ dan satu himpunan yang berisi himpunan kosong $\{\{\,\}\}$

6. $`\{\{\,\}\} \in \{\{\{\,\}\}\}`$
   Benar, karena himpunan yang berisi himpunan kosong $\{\{\,\}\}$ adalah satu-satunya elemen dalam himpunan yang berisi hanya satu elemen, yaitu himpunan tersebut sendiri $\{\{ \{\,\}\}\}$ 
    
7. $`\{\{\{\,\}\}\} \subset \{\{\,\}, \{\{\,\}\}\}`$
   Benar, karena himpunan yang berisi himpunan yang berisi himpunan kosong $\{\{ \{\,\}\}\}$ adalah himpunan bagian dari himpunan yang berisi dua elemen: satu himpunan kosong $\{\,\}$ dan satu himpunan yang berisi himpunan kosong $\{\{\,\}\}$

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

### Answer
1. Carilah selisih simetrik dari dua himpunan berikut: $\{1, 3, 5\}$
   dan $\{1, 2, 3\}$

   A = $\{1, 3, 5\}$

   B = $\{1, 2, 3\}$

   Jawaban : 

   A $\oplus$ B = ( A - B) $\cup$ ( A  - B )
   
   A $\oplus$ B = {5} $\cup$ {2}

   A $\oplus$ B = {5, 2}

 2. Carilah selisih simetrik dari himpunan mahasiswa SI yang mengambil 
    kelas Matematika Diskrit dan himpunan mahasiswa SI yang mengambil 
    kelas Kalkulus 1

    A = {Mahasiswa SI yang mengambil kelas Matematika Diskrit}
    
    B = {Mahasiswa SI yang mengambil kelas Kalkulus 1}

    A - B = {Mahasiswa SI yang hanya mengambil kelas Matematika Diskrit}

    B - A = {Mahasiswa SI yang hanya mengambil kelas Kalkulus 1}

    A $\oplus$ B = ( A - B) $\cup$ ( A  - B )

    A $\oplus$ B = {Mahasiswa SI yang hanya mengambil kelas Matematika Diskrit} $\cup$ {Mahasiswa SI yang hanya mengambil kelas Kalkulus 1}

    A $\oplus$ B = {Mahasiswa SI yang hanya mengambil kelas Matematika Diskrit dan Mahasiswa SI yang hanya mengambil kelas Kalkulus 1}

3.  Gambarkan diagram Venn untuk operasi selisih simetrik dari dua 
   himpunan $A$ dan $B$.
  ![Alt text](05261f36-2cec-458a-9f67-653f163ddad5-2.jpg)

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

Nomor Telepon:

Batasan: Nomor telepon harus unik untuk setiap mahasiswa. Maka tidak boleh ada dua mahasiswa dengan nomor telepon yang sama.

Nomor Induk Mahasiswa:

Batasan: Nomor induk mahasiswa harus unik untuk setiap mahasiswa. Maka tidak boleh ada dua mahasiswa dengan nomor induk yang sama.

Nilai Akhir Kelas Matematika Diskrit:

Batasan: Jika setiap mahasiswa hanya mengambil kelas Matematika Diskrit sekali, maka nilai akhir akan unik untuk setiap mahasiswa. Namun, jika ada mahasiswa yang bisa mengambil kelas ini lebih dari sekali, maka diperlukan batasan tambahan 

Alamat Rumah:

Batasan: Jika setiap mahasiswa memiliki alamat rumah yang berbeda, maka tidak diperlukan batasan tambahan. Namun, jika beberapa mahasiswa tinggal di alamat yang sama, maka fungsi ini tidak akan bisa menjadi injektif.

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

| $x$ | $y$ | $x \oplus y$ | $(x+y)$ | $\overline{xy}$ | $(x+y)\overline{xy}$ |
|-----|-----|--------------|---------|-----------------|----------------------|
| 1   | 1   | 0            | 1       | 1               | 1                    |
| 1   | 0   | 1            | 1       | 0               | 0                    |
| 0   | 1   | 1            | 1       | 0               | 0                    |
| 0   | 0   | 0            | 0       | 0               | 0                    |

2. $x \oplus y = (x\overline{y}) + (\overline{x} y)$

| $x$ | $y$ | $x \oplus y$ | $(\overline y)$ | $(\overline x)$ | $(x+y)\overline{xy}$ | $(x\overline{y}) + (\overline{x} y)$ |
|-----|-----|--------------|-----------------|-----------------|----------------------|--------------------------------------|
| 1   | 1   | 0            | 1               | 1               | 1                    | 1                                    |
| 1   | 0   | 1            | 1               | 0               | 0                    | 1                                    |
| 0   | 1   | 1            | 1               | 0               | 0                    | 1                                    |
| 0   | 0   | 0            | 0               | 0               | 0                    | 0                                    |

## Problem 5   
Carilah cara untuk menyatakan komplement, Boolean sum, 
dan Boolean product dengan hanya menggunakan NOR operator

### Answer
1. Komplement $($$NOT$$)$:
Gunakan operator $NOR$ dengan kedua input yang sama. Ini akan menghasilkan keluaran yang selalu berlawanan dengan input. Misalnya:

    $NOT$ $A$ = $A$ $NOR$ $A$

2. Boolean Sum $($$OR$$)$:
Anda dapat menyusun operasi $OR$ dengan menggunakan operator $NOR$ dan $NOT$. Misalnya, untuk $A$ $OR$ $B$:

    $A$ $OR$ $B$ = $($$A$ $NOR$ $A$$)$ $NOR$ $($$B$ $NOR$ $B$$)$

3. Boolean Product $($$AND$$)$:
    Anda dapat menyusun operasi $AND$ dengan menggunakan operator $NOR$, $NOT$, dan $OR$. Misalnya, untuk $A$ $AND$ $B$:

    $A$ $AND$ $B$ = $($$A$ $NOR$ $A$$)$ $NOR$ $($$B$ $NOR$ $B$$)$ $NOR$ $($$A$ $OR$ $B$$)$