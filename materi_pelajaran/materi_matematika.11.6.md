# Matriks

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta didik diharapkan mampu:

- Memahami konsep dasar matriks dan notasinya
- Mengidentifikasi jenis-jenis matriks
- Melakukan operasi penjumlahan, pengurangan, dan perkalian matriks
- Menentukan determinan dan invers matriks
- Mengaplikasikan konsep matriks dalam penyelesaian masalah sehari-hari

## Pendahuluan

Pernahkah kamu bermain game komputer atau menonton film animasi 3D? Dibalik teknologi tersebut, terdapat konsep matematika yang sangat penting bernama matriks. Matriks adalah susunan bilangan, simbol, atau ekspresi yang disusun dalam bentuk persegi panjang dan diatur dalam baris dan kolom.

Bayangkan kamu sedang membuat jadwal kegiatan harian di mana setiap hari memiliki beberapa aktivitas dengan durasi tertentu. Informasi tersebut dapat diorganisir dengan rapi menggunakan matriks. Tidak hanya itu, matriks juga digunakan dalam berbagai aplikasi seperti transformasi gambar digital, analisis jaringan sosial, sistem persamaan linear, pengolahan sinyal, dan bahkan dalam algoritma mesin pencari seperti Google.

Matriks mungkin terlihat sederhana, namun memiliki kekuatan luar biasa dalam menyelesaikan berbagai permasalahan kompleks. Mari kita jelajahi dunia matriks yang menakjubkan ini!

## Isi Materi

### Pengertian dan Notasi Matriks

Matriks adalah susunan bilangan, simbol, atau ekspresi yang disusun dalam bentuk persegi panjang dan diatur dalam baris dan kolom. Setiap bilangan dalam matriks disebut sebagai elemen atau entri matriks.

Notasi umum matriks:

$$A = \begin{pmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{m1} & a_{m2} & \cdots & a_{mn}
\end{pmatrix}$$

Matriks $A$ di atas memiliki ukuran $m \times n$ (dibaca: m kali n), di mana $m$ menyatakan banyaknya baris dan $n$ menyatakan banyaknya kolom.

### Jenis-jenis Matriks

1. **Matriks Persegi**

   Matriks persegi adalah matriks yang memiliki jumlah baris sama dengan jumlah kolom, misalnya matriks berukuran $2 \times 2$, $3 \times 3$, dan seterusnya.

   Contoh matriks persegi ordo $2 \times 2$:
   $$P = \begin{pmatrix}
   5 & 7 \\
   2 & 9
   \end{pmatrix}$$

2. **Matriks Diagonal**

   Matriks diagonal adalah matriks persegi dengan elemen-elemen di luar diagonal utama bernilai nol.

   Contoh:
   $$D = \begin{pmatrix}
   4 & 0 & 0 \\
   0 & 7 & 0 \\
   0 & 0 & 2
   \end{pmatrix}$$

3. **Matriks Identitas**

   Matriks identitas adalah matriks diagonal dengan elemen-elemen pada diagonal utama bernilai 1.

   Contoh matriks identitas ordo $3 \times 3$:
   $$I_3 = \begin{pmatrix}
   1 & 0 & 0 \\
   0 & 1 & 0 \\
   0 & 0 & 1
   \end{pmatrix}$$

4. **Matriks Nol**

   Matriks nol adalah matriks yang semua elemennya bernilai 0.

   Contoh:
   $$O = \begin{pmatrix}
   0 & 0 \\
   0 & 0
   \end{pmatrix}$$

5. **Matriks Segitiga**

   - Matriks segitiga atas: Semua elemen di bawah diagonal utama bernilai 0.
   - Matriks segitiga bawah: Semua elemen di atas diagonal utama bernilai 0.

   Contoh matriks segitiga atas:
   $$U = \begin{pmatrix}
   3 & 6 & 1 \\
   0 & 8 & 4 \\
   0 & 0 & 5
   \end{pmatrix}$$

   Contoh matriks segitiga bawah:
   $$L = \begin{pmatrix}
   2 & 0 & 0 \\
   7 & 9 & 0 \\
   6 & 4 & 1
   \end{pmatrix}$$

### Operasi Matriks

1. **Penjumlahan dan Pengurangan Matriks**

   Dua matriks dapat dijumlahkan atau dikurangkan jika keduanya memiliki ukuran yang sama. Operasi dilakukan dengan menjumlahkan atau mengurangkan elemen-elemen yang bersesuaian.

   Misalkan:
   $$A = \begin{pmatrix}
   3 & 2 \\
   1 & 4
   \end{pmatrix} \text{ dan }
   B = \begin{pmatrix}
   1 & 5 \\
   6 & 2
   \end{pmatrix}$$

   Penjumlahan:
   $$A + B = \begin{pmatrix}
   3+1 & 2+5 \\
   1+6 & 4+2
   \end{pmatrix} = \begin{pmatrix}
   4 & 7 \\
   7 & 6
   \end{pmatrix}$$

   Pengurangan:
   $$A - B = \begin{pmatrix}
   3-1 & 2-5 \\
   1-6 & 4-2
   \end{pmatrix} = \begin{pmatrix}
   2 & -3 \\
   -5 & 2
   \end{pmatrix}$$

2. **Perkalian Matriks dengan Skalar**

   Perkalian matriks dengan skalar (bilangan) dilakukan dengan mengalikan setiap elemen matriks dengan skalar tersebut.

   Contoh:
   $$3 \times \begin{pmatrix}
   2 & 5 \\
   1 & 7
   \end{pmatrix} = \begin{pmatrix}
   3 \times 2 & 3 \times 5 \\
   3 \times 1 & 3 \times 7
   \end{pmatrix} = \begin{pmatrix}
   6 & 15 \\
   3 & 21
   \end{pmatrix}$$

3. **Perkalian Antar Matriks**

   Dua matriks $A$ dan $B$ dapat dikalikan jika jumlah kolom pada matriks $A$ sama dengan jumlah baris pada matriks $B$.

   Jika $A$ berukuran $m \times n$ dan $B$ berukuran $n \times p$, maka hasil perkalian $A \times B$ akan berukuran $m \times p$.

   Contoh:
   $$A = \begin{pmatrix}
   2 & 3 \\
   4 & 1
   \end{pmatrix} \text{ dan }
   B = \begin{pmatrix}
   5 & 6 \\
   7 & 8
   \end{pmatrix}$$

   $$A \times B = \begin{pmatrix}
   (2 \times 5 + 3 \times 7) & (2 \times 6 + 3 \times 8) \\
   (4 \times 5 + 1 \times 7) & (4 \times 6 + 1 \times 8)
   \end{pmatrix} = \begin{pmatrix}
   31 & 36 \\
   27 & 32
   \end{pmatrix}$$

### Determinan Matriks

Determinan adalah nilai skalar yang dihitung dari elemen-elemen matriks persegi. Determinan dinotasikan dengan $\det(A)$ atau $|A|$.

1. **Determinan Matriks Ordo $2 \times 2$**

   Untuk matriks $A = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$

   $$\det(A) = |A| = \begin{vmatrix} a & b \\ c & d \end{vmatrix} = ad - bc$$

   Contoh:
   $$\det\begin{pmatrix}
   3 & 5 \\
   2 & 7
   \end{pmatrix} = (3 \times 7) - (5 \times 2) = 21 - 10 = 11$$

2. **Determinan Matriks Ordo $3 \times 3$**

   Salah satu metode menghitung determinan matriks $3 \times 3$ adalah dengan ekspansi kofaktor.

   Untuk matriks $A = \begin{pmatrix} a & b & c \\ d & e & f \\ g & h & i \end{pmatrix}$

   $$\det(A) = a(ei - fh) - b(di - fg) + c(dh - eg)$$

### Invers Matriks

Invers dari matriks $A$ dinotasikan dengan $A^{-1}$, di mana $A \times A^{-1} = A^{-1} \times A = I$ (matriks identitas).

Syarat suatu matriks memiliki invers adalah determinannya tidak sama dengan nol $(\det(A) \neq 0)$.

1. **Invers Matriks Ordo $2 \times 2$**

   Untuk matriks $A = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$

   $$A^{-1} = \frac{1}{\det(A)} \begin{pmatrix} d & -b \\ -c & a \end{pmatrix} = \frac{1}{ad-bc} \begin{pmatrix} d & -b \\ -c & a \end{pmatrix}$$

   Contoh:
   Misalkan $A = \begin{pmatrix} 3 & 2 \\ 4 & 3 \end{pmatrix}$

   $\det(A) = (3 \times 3) - (2 \times 4) = 9 - 8 = 1$

   $$A^{-1} = \frac{1}{1} \begin{pmatrix} 3 & -2 \\ -4 & 3 \end{pmatrix} = \begin{pmatrix} 3 & -2 \\ -4 & 3 \end{pmatrix}$$

### Aplikasi Matriks dalam Kehidupan Sehari-hari

1. **Sistem Persamaan Linear**

   Matriks dapat digunakan untuk menyelesaikan sistem persamaan linear.

   Contoh:
   Sistem persamaan linear:
   $2x + 3y = 8$
   $4x + y = 6$

   Dapat ditulis dalam bentuk matriks:
   $$\begin{pmatrix}
   2 & 3 \\
   4 & 1
   \end{pmatrix} \begin{pmatrix}
   x \\
   y
   \end{pmatrix} = \begin{pmatrix}
   8 \\
   6
   \end{pmatrix}$$

2. **Transformasi Geometri**

   Matriks dapat digunakan untuk merepresentasikan transformasi geometri seperti rotasi, refleksi, dan dilatasi.

   Contoh matriks rotasi 90° berlawanan arah jarum jam:
   $$R_{90°} = \begin{pmatrix}
   0 & -1 \\
   1 & 0
   \end{pmatrix}$$

3. **Grafik Komputer**

   Dalam grafik komputer, matriks digunakan untuk memanipulasi objek 3D, seperti translasi, rotasi, dan penskalaan.

4. **Analisis Data**

   Matriks digunakan dalam analisis data multivariabel, seperti analisis komponen utama (PCA) dan analisis faktor.

5. **Teori Jaringan**

   Matriks ketetanggaan digunakan untuk merepresentasikan jaringan atau graf, yang penting dalam analisis jaringan sosial dan World Wide Web.

## Rangkuman Materi

- **Matriks** adalah susunan bilangan yang diatur dalam baris dan kolom.
- **Jenis-jenis Matriks**:
  - Matriks Persegi: jumlah baris sama dengan jumlah kolom
  - Matriks Diagonal: elemen di luar diagonal utama bernilai nol
  - Matriks Identitas: matriks diagonal dengan diagonal utama bernilai 1
  - Matriks Nol: semua elemen bernilai 0
  - Matriks Segitiga: segitiga atas atau segitiga bawah

- **Operasi Matriks**:
  - Penjumlahan/Pengurangan: dilakukan pada matriks dengan ukuran sama
  - Perkalian dengan Skalar: mengalikan setiap elemen matriks dengan skalar
  - Perkalian Antar Matriks: syarat jumlah kolom matriks pertama = jumlah baris matriks kedua

- **Determinan** adalah nilai skalar yang dihitung dari elemen-elemen matriks persegi.

- **Invers Matriks** ($A^{-1}$) memenuhi $A \times A^{-1} = A^{-1} \times A = I$, dengan syarat $\det(A) \neq 0$.

- **Aplikasi Matriks** meliputi sistem persamaan linear, transformasi geometri, grafik komputer, analisis data, dan teori jaringan.
