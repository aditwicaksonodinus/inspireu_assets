# Polinomial

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta didik diharapkan mampu:

- Memahami konsep dasar polinomial dan bentuk umumnya
- Mengidentifikasi jenis-jenis polinomial berdasarkan derajatnya
- Melakukan operasi matematika pada polinomial (penjumlahan, pengurangan, perkalian, dan pembagian)
- Menentukan akar-akar polinomial
- Mengaplikasikan konsep polinomial dalam pemecahan masalah kehidupan sehari-hari

## Pendahuluan

Pernahkah kamu melihat lintasan peluru yang diluncurkan ke udara? Atau mungkin membayangkan bagaimana pergerakan harga saham dari waktu ke waktu? Kedua fenomena tersebut sebenarnya dapat dimodelkan menggunakan sebuah bentuk matematika yang disebut polinomial.

Polinomial adalah salah satu bentuk ekspresi matematika yang sangat kuat dan hadir di hampir semua aspek kehidupan kita. Dari perhitungan luas lahan pertanian, estimasi pertumbuhan populasi, hingga algoritma yang menggerakkan aplikasi di smartphone kita—semua dapat direpresentasikan dengan polinomial.

Bayangkan polinomial sebagai "kalimat matematika" yang terdiri dari berbagai "kata" berupa variabel dan konstanta. Sama seperti kita dapat menyusun kalimat untuk menyampaikan berbagai makna, polinomial juga dapat disusun untuk menggambarkan berbagai fenomena di sekitar kita.

Mari kita jelajahi dunia polinomial dan temukan keindahan bentuk matematika yang ternyata sangat dekat dengan kehidupan sehari-hari kita!

## Pengertian Polinomial

Polinomial adalah bentuk ekspresi matematika yang terdiri dari satu atau lebih suku di mana variabelnya memiliki eksponen non-negatif. Bentuk umum polinomial satu variabel adalah:

$$P(x) = a_nx^n + a_{n-1}x^{n-1} + a_{n-2}x^{n-2} + ... + a_1x + a_0$$

Dimana:

- $a_n, a_{n-1}, ..., a_1, a_0$ adalah koefisien
- $x$ adalah variabel
- $n$ adalah derajat tertinggi dari polinomial tersebut

### Jenis-jenis Polinomial Berdasarkan Derajat

| Derajat | Nama | Contoh |
|---------|------|--------|
| 0 | Polinomial Konstan | $P(x) = 5$ |
| 1 | Polinomial Linear | $P(x) = 2x + 3$ |
| 2 | Polinomial Kuadratik | $P(x) = x^2 - 4x + 4$ |
| 3 | Polinomial Kubik | $P(x) = x^3 + 2x^2 - 5x + 1$ |
| $\geq 4$ | Polinomial Derajat-n | $P(x) = 2x^4 - 3x^3 + x - 7$ |

## Operasi pada Polinomial

### Penjumlahan dan Pengurangan

Untuk menjumlahkan atau mengurangkan polinomial, kita perlu menggabungkan suku-suku sejenis.

Contoh:

- $(3x^2 + 2x - 5) + (2x^2 - x + 3) = 5x^2 + x - 2$
- $(4x^3 - 2x + 7) - (x^3 + x^2 - 3) = 3x^3 - x^2 - 2x + 10$

### Perkalian

#### Perkalian dengan Konstanta

$$k \cdot P(x) = k \cdot (a_nx^n + a_{n-1}x^{n-1} + ... + a_0) = ka_nx^n + ka_{n-1}x^{n-1} + ... + ka_0$$

Contoh: $3 \cdot (2x^2 - 4x + 1) = 6x^2 - 12x + 3$

#### Perkalian Dua Polinomial

Menggunakan sifat distributif, setiap suku dari polinomial pertama dikalikan dengan setiap suku dari polinomial kedua.

Contoh:
$(x + 2)(x^2 - 3x + 4)$
$= x \cdot (x^2 - 3x + 4) + 2 \cdot (x^2 - 3x + 4)$
$= x^3 - 3x^2 + 4x + 2x^2 - 6x + 8$
$= x^3 - x^2 - 2x + 8$

### Pembagian

Pembagian polinomial dapat dilakukan dengan metode pembagian bersusun atau metode Horner.

Contoh pembagian bersusun:

Untuk menghitung $(x^3 - 2x^2 + 4x - 8) \div (x - 2)$:

$$\begin{array}{r}
x^2 + 0x + 4 \\
x - 2\overline{\smash{\begin{array}{r}
x^3 - 2x^2 + 4x - 8 \\
\underline{x^3 - 2x^2\phantom{{}+4x-8}} \\
0x^2 + 4x - 8 \\
\underline{\phantom{0x^2{}}+0x^2 - 0x\phantom{{}-8}} \\
\phantom{0x^2 + {}}4x - 8 \\
\underline{\phantom{0x^2 + {}}4x - 8\phantom{{}-8}} \\
0
\end{array}}}
\end{array}$$

Jadi, hasil baginya adalah $x^2 + 0x + 4$ dengan sisa 0.

## Akar-akar Polinomial

Akar polinomial $P(x)$ adalah nilai $x$ yang memenuhi $P(x) = 0$.

### Teorema Faktor

Jika $x = c$ adalah akar dari polinomial $P(x)$, maka $(x - c)$ adalah faktor dari $P(x)$.

### Menentukan Akar-akar Polinomial

1. **Untuk Polinomial Linear**: $ax + b = 0$, akarnya adalah $x = -\frac{b}{a}$

2. **Untuk Polinomial Kuadratik**: $ax^2 + bx + c = 0$, akarnya dapat ditemukan dengan rumus:
   $$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

3. **Untuk Polinomial Derajat Lebih Tinggi**:
   - Teorema Sisa dan Teorema Faktor
   - Metode Horner
   - Teorema Akar Rasional

### Contoh Menentukan Akar Polinomial

Untuk $P(x) = x^2 - 5x + 6$:

$$x = \frac{5 \pm \sqrt{25 - 24}}{2} = \frac{5 \pm \sqrt{1}}{2} = \frac{5 \pm 1}{2}$$

Sehingga $x = 3$ atau $x = 2$

## Aplikasi Polinomial

### 1. Pemodelan Fenomena Fisik

Misalnya, gerakan peluru dapat dimodelkan dengan:
$$h(t) = -\frac{1}{2}gt^2 + v_0t + h_0$$

Dimana:
- $h(t)$ adalah ketinggian pada waktu $t$
- $g$ adalah percepatan gravitasi
- $v_0$ adalah kecepatan awal
- $h_0$ adalah ketinggian awal

### 2. Optimasi

Menentukan nilai maksimum atau minimum dari suatu fungsi polinomial untuk menyelesaikan masalah optimasi.

### 3. Interpolasi

Mencari polinomial yang melalui sejumlah titik data tertentu.

### 4. Ekspansi Deret Taylor

Menggunakan polinomial untuk mengaproksimasi fungsi kompleks.

## Rangkuman

- **Polinomial** adalah ekspresi aljabar dengan bentuk $P(x) = a_nx^n + a_{n-1}x^{n-1} + ... + a_1x + a_0$
- **Derajat polinomial** adalah eksponen tertinggi dari variabel dalam polinomial
- **Operasi pada polinomial** meliputi penjumlahan, pengurangan, perkalian, dan pembagian
- **Akar polinomial** adalah nilai $x$ yang membuat $P(x) = 0$
- **Teorema Faktor** menyatakan bahwa jika $c$ adalah akar dari $P(x)$, maka $(x-c)$ adalah faktor dari $P(x)$
- **Aplikasi polinomial** sangat luas meliputi pemodelan fenomena fisik, optimasi, interpolasi, dan ekspansi deret Taylor
- **Polinomial derajat-1 (linear)** memiliki satu akar
- **Polinomial derajat-2 (kuadratik)** memiliki dua akar yang dapat ditemukan dengan rumus kuadratik
- **Polinomial derajat lebih tinggi** memerlukan metode khusus seperti Teorema Sisa dan metode Horner untuk menentukan akarnya
