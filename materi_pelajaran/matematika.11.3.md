Materi ini membahas matriks sebagai susunan bilangan dalam baris dan kolom yang sangat berguna untuk merepresentasikan data, transformasi, dan sistem persamaan. Matriks menjadi penting karena banyak persoalan matematika dapat ditata ulang menjadi bentuk yang lebih ringkas dan terstruktur melalui representasi ini.

# Matriks

## Tujuan Pembelajaran
Setelah mempelajari bab ini, peserta didik diharapkan mampu:
1. Menjelaskan pengertian matriks serta ordo matriks.
2. Menentukan elemen pada posisi tertentu.
3. Melakukan penjumlahan, pengurangan, dan perkalian skalar pada matriks.
4. Melakukan perkalian dua matriks pada kasus sederhana.
5. Menentukan transpose matriks.
6. Menggunakan matriks untuk merepresentasikan masalah sederhana.

## Apersepsi
Saat data siswa disusun dalam tabel nilai, sebenarnya kita sedang melihat bentuk yang sangat dekat dengan matriks. Dalam matematika, susunan seperti ini tidak hanya dipakai untuk menata data, tetapi juga untuk menghitung transformasi, menyelesaikan sistem, dan memodelkan hubungan antarkomponen secara efisien.

## Peta Konsep
- Definisi matriks dan ordo.
- Elemen matriks.
- Operasi matriks.
- Transpose matriks.
- Perkalian matriks.
- Aplikasi sederhana.

## 3.1 Pengertian Matriks
Matriks adalah susunan bilangan berbentuk persegi panjang yang disusun dalam baris dan kolom.

Contoh:

$$A = \begin{bmatrix}1 & 2 \\ 3 & 4\end{bmatrix}$$

Matriks di atas memiliki 2 baris dan 2 kolom.

## 3.2 Ordo Matriks
Ordo matriks menyatakan banyak baris dan kolom, ditulis dalam bentuk:

$$m \times n$$

Artinya matriks memiliki $m$ baris dan $n$ kolom.

Contoh:
- matriks $2 \times 3$ memiliki 2 baris dan 3 kolom
- matriks $3 \times 1$ memiliki 3 baris dan 1 kolom

Pengetahuan tentang ordo penting karena menentukan apakah dua matriks dapat dijumlahkan atau dikalikan.

## 3.3 Elemen Matriks
Elemen pada baris ke-$i$ dan kolom ke-$j$ ditulis sebagai $a_{ij}$.

Jika:

$$A = \begin{bmatrix}2 & 5 & 1 \\ 0 & -3 & 4\end{bmatrix}$$

maka:
- $a_{11}=2$
- $a_{12}=5$
- $a_{23}=4$

Peserta didik perlu membiasakan membaca posisi elemen dengan urutan baris lalu kolom.

## 3.4 Kesamaan Matriks
Dua matriks dikatakan sama jika ordonya sama dan setiap elemen yang bersesuaian juga sama.

Jika:

$$A = \begin{bmatrix}x & 2 \\ 3 & y\end{bmatrix}, \quad B = \begin{bmatrix}1 & 2 \\ 3 & 4\end{bmatrix}$$

maka $A=B$ jika:
- $x=1$
- $y=4$

## 3.5 Penjumlahan dan Pengurangan Matriks
Dua matriks dapat dijumlahkan atau dikurangkan jika ordonya sama.

Contoh:

$$A = \begin{bmatrix}1 & 2 \\ 3 & 4\end{bmatrix}, \quad B = \begin{bmatrix}5 & 6 \\ 7 & 8\end{bmatrix}$$

Maka:

$$A+B = \begin{bmatrix}6 & 8 \\ 10 & 12\end{bmatrix}$$

Dan:

$$A-B = \begin{bmatrix}-4 & -4 \\ -4 & -4\end{bmatrix}$$

## 3.6 Perkalian Matriks dengan Skalar
Jika $k$ adalah bilangan real dan $A$ matriks, maka $kA$ diperoleh dengan mengalikan setiap elemen matriks dengan $k$.

Contoh:

$$2\begin{bmatrix}1 & -1 \\ 3 & 0\end{bmatrix} = \begin{bmatrix}2 & -2 \\ 6 & 0\end{bmatrix}$$

Operasi ini serupa dengan perkalian skalar pada vektor.

## 3.7 Perkalian Dua Matriks
Jika $A$ berordo $m \times n$ dan $B$ berordo $n \times p$, maka hasil kali $AB$ berordo $m \times p$.

Contoh:

$$A = \begin{bmatrix}1 & 2 \\ 3 & 4\end{bmatrix}, \quad B = \begin{bmatrix}2 & 0 \\ 1 & 5\end{bmatrix}$$

Maka:

$$AB = \begin{bmatrix}(1)(2)+(2)(1) & (1)(0)+(2)(5) \\ (3)(2)+(4)(1) & (3)(0)+(4)(5)\end{bmatrix}$$

$$AB = \begin{bmatrix}4 & 10 \\ 10 & 20\end{bmatrix}$$

Pada tahap ini, peserta didik perlu memahami bahwa perkalian matriks tidak dilakukan per elemen secara langsung, melainkan melalui hasil kali baris dan kolom.

## 3.8 Transpose Matriks
Transpose matriks $A$, ditulis $A^T$, diperoleh dengan menukar baris menjadi kolom.

Contoh:

$$A = \begin{bmatrix}1 & 3 & 5 \\ 2 & 4 & 6\end{bmatrix}$$

Maka:

$$A^T = \begin{bmatrix}1 & 2 \\ 3 & 4 \\ 5 & 6\end{bmatrix}$$

Transpose penting dalam berbagai pembahasan lanjutan, termasuk sistem linear dan transformasi.

## 3.9 Matriks Identitas Sederhana
Matriks identitas adalah matriks persegi yang elemen diagonal utamanya 1 dan elemen lainnya 0.

Contoh matriks identitas ordo 2:

$$I = \begin{bmatrix}1 & 0 \\ 0 & 1\end{bmatrix}$$

Matriks ini berperan seperti angka 1 pada perkalian bilangan, karena untuk ordo yang sesuai berlaku $AI = IA = A$.

## 3.10 Aplikasi Sederhana
Matriks dapat digunakan untuk menyusun data penjualan, nilai siswa, atau koefisien sistem persamaan. Dengan matriks, informasi menjadi lebih teratur dan operasi dapat dilakukan secara lebih efisien.

Sebagai contoh, data nilai dua siswa pada tiga mata pelajaran dapat ditulis sebagai matriks $2 \times 3$, sehingga lebih mudah dibandingkan dan diolah.

## 3.11 Aktivitas Belajar
- Tentukan ordo beberapa matriks yang berbeda.
- Latih pembacaan elemen dengan notasi $a_{ij}$.
- Lakukan penjumlahan dan pengurangan dua matriks berordo sama.
- Coba kalikan dua matriks kecil dan periksa kesesuaian ordonya terlebih dahulu.

## 3.12 Latihan Pemahaman
1. Tentukan ordo dari $\begin{bmatrix}1 & 2 & 3 \\ 4 & 5 & 6\end{bmatrix}$.
2. Jika $A=\begin{bmatrix}2 & 1 \\ -1 & 3\end{bmatrix}$, tentukan $a_{21}$.
3. Hitung $A+B$ untuk $A=\begin{bmatrix}1 & 0 \\ 2 & 3\end{bmatrix}$ dan $B=\begin{bmatrix}4 & 5 \\ 6 & 7\end{bmatrix}$.
4. Hitung $3\begin{bmatrix}2 & -1 \\ 0 & 4\end{bmatrix}$.
5. Tentukan transpose dari $\begin{bmatrix}1 & 2 & 3\end{bmatrix}$.
6. Hitung hasil kali $\begin{bmatrix}1 & 2\end{bmatrix}\begin{bmatrix}3 \\ 4\end{bmatrix}$.
7. Mengapa dua matriks dengan ordo berbeda tidak dapat dijumlahkan?
8. Jelaskan perbedaan penjumlahan matriks dan perkalian matriks.
9. Tuliskan matriks identitas ordo 3.
10. Mengapa pengecekan ordo penting sebelum mengalikan dua matriks?

## Refleksi
Jika kamu sudah dapat membaca struktur baris dan kolom dengan baik, maka matriks akan terasa sebagai bahasa yang rapi untuk menulis data dan hubungan aljabar. Jika masih sering keliru saat mengalikan matriks, biasakan memeriksa ordo dan melatih pola baris-kolom secara perlahan.

## Glosarium
- **Matriks**: susunan bilangan dalam baris dan kolom.
- **Ordo**: ukuran matriks yang menyatakan banyak baris dan kolom.
- **Elemen matriks**: anggota atau isi matriks pada posisi tertentu.
- **Transpose**: hasil penukaran baris dan kolom.
- **Matriks identitas**: matriks persegi dengan diagonal utama 1 dan elemen lainnya 0.
- **Matriks persegi**: matriks dengan jumlah baris sama dengan jumlah kolom.
