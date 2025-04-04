# Barisan dan Deret

## Tujuan Pembelajaran

Setelah mempelajari materi ini, siswa diharapkan mampu:

- Memahami konsep barisan dan deret
- Mengidentifikasi jenis-jenis barisan dan deret
- Menentukan rumus suku ke-n dari barisan
- Menghitung jumlah deret dengan berbagai teknik
- Mengaplikasikan konsep barisan dan deret dalam pemecahan masalah sehari-hari

## Pendahuluan

Pernahkah kamu memperhatikan susunan kursi di bioskop? Baris pertama mungkin berisi 10 kursi, baris kedua 12 kursi, baris ketiga 14 kursi, dan seterusnya. Atau mungkin kamu pernah menabung dengan jumlah tetap setiap bulan dan ingin tahu berapa total tabunganmu setelah beberapa tahun. Kedua situasi tersebut adalah contoh penerapan konsep barisan dan deret dalam kehidupan sehari-hari.

Barisan dan deret adalah salah satu topik matematika yang memiliki banyak aplikasi praktis, mulai dari menghitung bunga tabungan, pertumbuhan populasi, hingga pola-pola dalam seni dan arsitektur. Mari kita jelajahi konsep menakjubkan ini yang menghubungkan angka-angka dalam pola yang teratur dan dapat diprediksi.

## Isi Materi

### Pengertian Barisan dan Deret

**Barisan (Sequence)** adalah susunan bilangan yang memiliki aturan tertentu. Setiap bilangan dalam barisan disebut sebagai suku. Suku ke-n dinotasikan dengan

$U_n$ atau $a_n$.

**Deret (Series)** adalah jumlah dari suku-suku dalam suatu barisan. Jika barisan dilambangkan dengan $a_1, a_2, a_3, ..., a_n$, maka deret dilambangkan dengan $a_1 + a_2 + a_3 + ... + a_n$ dan dinotasikan sebagai

$$\sum_{i=1}^{n} a_i$$.

### Barisan Aritmatika

Barisan aritmatika adalah barisan dengan selisih antara dua suku yang berurutan selalu tetap. Selisih tersebut dinamakan beda (dilambangkan dengan $b$).

**Rumus Umum:**

- Suku ke-n:
  
  $$U_n = a + (n-1)b$$
  
  - $a$ = suku pertama
  - $b$ = beda
  - $n$ = nomor suku

**Contoh:**
Barisan aritmatika $2, 5, 8, 11, 14, ...$

- Suku pertama ($a$) = $2$
- Beda ($b$) = $5 - 2 = 3$
- Suku ke-10 ($U_{10}$) = $2 + (10-1) \times 3 = 2 + 27 = 29$

### Deret Aritmatika

Jumlah $n$ suku pertama dari barisan aritmatika disebut deret aritmatika dan dilambangkan dengan $S_n$.

**Rumus:**

$$S_n = \frac{n}{2}[2a + (n-1)b] \text{ atau } S_n = \frac{n}{2}(a + U_n)$$

**Keterangan:**

- $S_n$ = jumlah $n$ suku
- $a$ = suku pertama
- $b$ = beda
- $n$ = nomor suku
- $U_n$ = suku ke-n
- $S_n$ = jumlah $n$ suku

### Barisan Geometri

Barisan geometri adalah barisan dengan perbandingan dua suku berurutan selalu tetap. Perbandingan ini disebut rasio (dilambangkan dengan $r$).

**Rumus Umum:**

- Suku ke-n:

$$U_n = a \times r^{n-1}$$

- $a$ = suku pertama
- $r$ = rasio
- $n$ = nomor suku

**Contoh:**
Barisan geometri $3, 6, 12, 24, ...$

- Suku pertama ($a$) = $3$
- Rasio ($r$) = $\frac{6}{3} = 2$
- Suku ke-6 ($U_6$) = $3 \times 2^{5} = 3 \times 32 = 96$

### Deret Geometri

Jumlah $n$ suku pertama dari barisan geometri disebut deret geometri.

**Rumus:**

- Untuk $r \neq 1$: $S_n = \frac{a(1-r^n)}{1-r}$
- Untuk $r = 1$: $S_n = n \times a$
- Untuk $|r| < 1$ dan $n \to \infty$: $S_{\infty} = \frac{a}{1-r}$

**Keterangan:**

- $a$ = suku pertama
- $r$ = rasio
- $n$ = nomor suku
- $S_n$ = jumlah $n$ suku
- $S_{\infty}$ = jumlah deret tak hingga

### Barisan dan Deret Tak Hingga

Jika suatu barisan diteruskan tanpa batas, maka kita memiliki barisan tak hingga. Begitu pula deret tak hingga adalah jumlah suku-suku dari barisan tak hingga.

Deret geometri tak hingga dengan $|r| < 1$ akan konvergen dengan jumlah

$$S_{\infty} = \frac{a}{1-r}$$

**Contoh:**
Deret $1 + \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + ...$

- $a = 1$, $r = \frac{1}{2}$
- $S_{\infty} = \frac{1}{1-\frac{1}{2}} = \frac{1}{\frac{1}{2}} = 2$

### Aplikasi Barisan dan Deret

#### 1. Perhitungan Bunga Majemuk

Jika kita menabung sejumlah $P$ (pokok) dengan bunga $i$ per periode, maka setelah $n$ periode jumlah tabungan menjadi:

$$A = P(1+i)^n$$

**Keterangan:**

- $A$ = jumlah akhir
- $P$ = pokok
- $i$ = suku bunga per periode
- $n$ = jumlah periode

Ini merupakan contoh penerapan barisan geometri dengan $a = P$ dan $r = (1+i)$.

#### 2. Pertumbuhan Populasi

Jika populasi awal sebesar $P_0$ dan tingkat pertumbuhan per tahun adalah $r$, maka populasi setelah $n$ tahun adalah:

$P_n = P_0(1+r)^n$

**Keterangan:**

- $P_n$ = populasi setelah $n$ tahun
- $P_0$ = populasi awal
- $r$ = tingkat pertumbuhan
- $n$ = jumlah tahun
  
#### 3. Pola dalam Arsitektur

Barisan Fibonacci ($1, 1, 2, 3, 5, 8, 13, ...$) sering ditemukan dalam pola arsitektur dan alam. Setiap suku adalah jumlah dari dua suku sebelumnya: $F_n = F_{n-1} + F_{n-2}$.

| Jenis Barisan | Definisi | Rumus Suku ke-n | Rumus Jumlah n Suku |
|---------------|----------|-----------------|---------------------|
| Aritmatika | Beda tetap | $U_n = a + (n-1)b$ | $S_n = \frac{n}{2}(a + U_n)$ |
| Geometri | Rasio tetap | $U_n = a \times r^{n-1}$ | $S_n = \frac{a(1-r^n)}{1-r}$ |
| Fibonacci | Jumlah dua suku sebelumnya | $F_n = F_{n-1} + F_{n-2}$ | - |

## Rangkuman Materi

- **Barisan** adalah susunan bilangan dengan pola tertentu, setiap bilangan disebut suku.
- **Deret** adalah jumlah suku-suku dari suatu barisan.
- **Barisan Aritmatika**:
  - Memiliki beda ($b$) yang tetap antar suku berurutan
  - Rumus suku ke-n: $U_n = a + (n-1)b$
  - Rumus jumlah $n$ suku: $S_n = \frac{n}{2}(a + U_n)$ atau $S_n = \frac{n}{2}[2a + (n-1)b]$
- **Barisan Geometri**:
  - Memiliki rasio ($r$) yang tetap antar suku berurutan
  - Rumus suku ke-n: $U_n = a \times r^{n-1}$
  - Rumus jumlah $n$ suku: $S_n = \frac{a(1-r^n)}{1-r}$ (untuk $r \neq 1$)
  - Jumlah deret tak hingga: $S_{\infty} = \frac{a}{1-r}$ (untuk $|r| < 1$)
- Barisan dan deret memiliki banyak aplikasi praktis dalam kehidupan sehari-hari seperti dalam perhitungan keuangan, pertumbuhan populasi, dan pola-pola di alam.
