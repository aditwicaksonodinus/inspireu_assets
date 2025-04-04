# Sistem Persamaan dan Pertidaksamaan Linier

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta didik diharapkan mampu:

- Memahami konsep dasar sistem persamaan linier
- Menyelesaikan sistem persamaan linier dua variabel
- Menyelesaikan sistem persamaan linier tiga variabel
- Memahami konsep dasar sistem pertidaksamaan linier
- Menyelesaikan masalah sehari-hari menggunakan sistem persamaan dan pertidaksamaan linier

## Pendahuluan

Pernahkah kamu membeli beberapa barang di kantin sekolah dan bertanya-tanya berapa harga setiap barangnya? Misalnya, kamu membeli 2 roti dan 1 minuman seharga Rp15.000, sementara temanmu membeli 1 roti dan 2 minuman seharga Rp17.000. Bagaimana cara mengetahui harga masing-masing roti dan minuman tersebut?

Di sinilah sistem persamaan linier menjadi penyelamat! Sistem persamaan linier merupakan alat matematika yang sangat berguna dalam kehidupan sehari-hari untuk memecahkan berbagai masalah, mulai dari menentukan harga barang, merencanakan anggaran, hingga digunakan oleh insinyur dalam merancang bangunan atau ekonom dalam menganalisis pasar.

## Sistem Persamaan Linier

### Pengertian Sistem Persamaan Linier

Sistem persamaan linier adalah sekumpulan persamaan linier yang memiliki variabel-variabel yang sama. Solusi dari sistem persamaan linier adalah nilai-nilai variabel yang memenuhi semua persamaan dalam sistem tersebut.

Bentuk umum sistem persamaan linier dua variabel (SPLDV):

$$\begin{cases}
a_1x + b_1y = c_1 \\
a_2x + b_2y = c_2
\end{cases}$$

dengan $a_1$, $a_2$, $b_1$, $b_2$, $c_1$, dan $c_2$ adalah konstanta real.

### Metode Penyelesaian Sistem Persamaan Linier Dua Variabel

#### 1. Metode Substitusi

Langkah-langkah:
1. Nyatakan salah satu variabel dalam bentuk variabel lainnya dari salah satu persamaan
2. Substitusikan (gantikan) bentuk variabel tersebut ke persamaan lainnya
3. Selesaikan persamaan yang diperoleh untuk mendapatkan nilai salah satu variabel
4. Substitusikan kembali nilai yang diperoleh untuk mendapatkan nilai variabel lainnya

**Contoh:**
Selesaikan sistem persamaan:
$$\begin{cases}
x + y = 5 \\
2x - y = 4
\end{cases}$$

Penyelesaian:
Dari persamaan pertama: $x + y = 5$, sehingga $y = 5 - x$

Substitusikan $y = 5 - x$ ke persamaan kedua:
$2x - (5 - x) = 4$
$2x - 5 + x = 4$
$3x - 5 = 4$
$3x = 9$
$x = 3$

Substitusikan $x = 3$ ke persamaan $y = 5 - x$:
$y = 5 - 3 = 2$

Jadi, solusinya adalah $x = 3$ dan $y = 2$.

#### 2. Metode Eliminasi

Langkah-langkah:
1. Samakan koefisien salah satu variabel dari kedua persamaan
2. Eliminasi variabel tersebut dengan cara menambah atau mengurangi kedua persamaan
3. Selesaikan persamaan yang diperoleh untuk mendapatkan nilai salah satu variabel
4. Ulangi langkah 1-3 untuk variabel lainnya atau gunakan substitusi

**Contoh:**

Menggunakan sistem persamaan yang sama:
$$\begin{cases}
x + y = 5 \\
2x - y = 4
\end{cases}$$

Penyelesaian:
Eliminasi variabel $y$:

$x + y = 5$
$2x - y = 4$
```----------- +```
$3x = 9$
$x = 3$

Substitusikan $x = 3$ ke persamaan pertama:
$3 + y = 5$
$y = 2$

Jadi, solusinya adalah $x = 3$ dan $y = 2$.

#### 3. Metode Determinan (Cramer)

Untuk sistem:
$$\begin{cases}
a_1x + b_1y = c_1 \\
a_2x + b_2y = c_2
\end{cases}$$

Nilai $x$ dan $y$ dapat dihitung dengan:

$$x = \frac{\begin{vmatrix} c_1 & b_1 \\ c_2 & b_2 \end{vmatrix}}{\begin{vmatrix} a_1 & b_1 \\ a_2 & b_2 \end{vmatrix}} = \frac{c_1b_2 - c_2b_1}{a_1b_2 - a_2b_1}$$

$$y = \frac{\begin{vmatrix} a_1 & c_1 \\ a_2 & c_2 \end{vmatrix}}{\begin{vmatrix} a_1 & b_1 \\ a_2 & b_2 \end{vmatrix}} = \frac{a_1c_2 - a_2c_1}{a_1b_2 - a_2b_1}$$

### Sistem Persamaan Linier Tiga Variabel

Bentuk umum:
$$\begin{cases}
a_1x + b_1y + c_1z = d_1 \\
a_2x + b_2y + c_2z = d_2 \\
a_3x + b_3y + c_3z = d_3
\end{cases}$$

Dapat diselesaikan dengan metode eliminasi dan substitusi. Prinsipnya sama dengan SPLDV, namun lebih kompleks karena melibatkan tiga variabel.

### Aplikasi Sistem Persamaan dan Pertidaksamaan Linier dalam Pemrograman Linier

Sistem persamaan dan pertidaksamaan linier sering digunakan dalam pemrograman linier untuk mengoptimalkan sumber daya. Contohnya, sebuah perusahaan yang ingin memaksimalkan keuntungan atau meminimalkan biaya produksi dengan mempertimbangkan berbagai kendala seperti bahan baku, tenaga kerja, dan waktu produksi.

**Contoh:**
Sebuah pabrik memproduksi kursi dan meja. Setiap kursi membutuhkan 2 jam pengerjaan dan 3 unit kayu, sementara setiap meja membutuhkan 3 jam pengerjaan dan 5 unit kayu. Tersedia 100 jam waktu pengerjaan dan 150 unit kayu per minggu. Jika keuntungan untuk setiap kursi adalah Rp200.000 dan setiap meja Rp300.000, berapa banyak kursi dan meja yang harus diproduksi untuk memaksimalkan keuntungan?

Model matematikanya:
Misalkan $x$ = jumlah kursi dan $y$ = jumlah meja

Fungsi tujuan: Maksimumkan $Z = 200.000x + 300.000y$

Kendala:
$$\begin{cases}
2x + 3y \leq 100 \text{ (waktu pengerjaan)} \\
3x + 5y \leq 150 \text{ (unit kayu)} \\
x \geq 0 \\
y \geq 0
\end{cases}$$

Penyelesaian masalah ini memerlukan metode pemrograman linier seperti metode grafik atau metode simpleks.

## Rangkuman Materi

- **Sistem Persamaan Linier**: Sekumpulan persamaan linier yang memiliki variabel-variabel yang sama.
  - SPLDV dapat diselesaikan dengan metode substitusi, eliminasi, atau determinan (Cramer).
  - SPLTV dapat diselesaikan dengan kombinasi metode eliminasi dan substitusi.

- **Sistem Pertidaksamaan Linier**: Sekumpulan pertidaksamaan linier yang harus dipenuhi secara bersamaan.
  - Penyelesaian dapat ditentukan dengan metode grafik.
  - Daerah penyelesaian adalah irisan dari daerah penyelesaian tiap pertidaksamaan.

- **Aplikasi**: Sistem persamaan dan pertidaksamaan linier memiliki banyak aplikasi dalam kehidupan sehari-hari seperti:
  - Masalah ekonomi dan bisnis
  - Optimasi penggunaan sumber daya
  - Analisis pasar
  - Perencanaan produksi
  - Penentuan harga barang
