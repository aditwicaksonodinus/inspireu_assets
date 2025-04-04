# Bilangan Kompleks

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta didik diharapkan mampu:

- Memahami konsep dasar bilangan kompleks
- Menjelaskan bentuk-bentuk bilangan kompleks
- Melakukan operasi aritmatika pada bilangan kompleks
- Menerapkan konsep bilangan kompleks dalam pemecahan masalah
- Mengidentifikasi aplikasi bilangan kompleks dalam kehidupan sehari-hari

## Pendahuluan

Pernahkah kamu bertanya-tanya, apa yang terjadi ketika kita mencoba mencari akar kuadrat dari bilangan negatif? Misalnya, berapakah nilai dari $\sqrt{-1}$? Dalam matematika yang kita pelajari sebelumnya, pertanyaan ini tampak mustahil untuk dijawab karena tidak ada bilangan real yang jika dikuadratkan menghasilkan nilai negatif.

Namun, matematika adalah ilmu yang terus berkembang. Para matematikawan menciptakan sistem bilangan baru untuk mengatasi keterbatasan ini. Inilah yang melahirkan konsep bilangan kompleks, sebuah perluasan dari bilangan real yang membuka dimensi baru dalam matematika.

Bilangan kompleks bukan sekadar konsep abstrak. Tanpa kita sadari, bilangan kompleks memainkan peran penting dalam kehidupan modern kita. Dari teknologi komunikasi yang kita gunakan sehari-hari, desain rangkaian listrik, hingga pengolahan sinyal digital dalam smartphone yang kita genggam saat ini, semuanya memanfaatkan prinsip bilangan kompleks.

Mari kita jelajahi dunia bilangan kompleks ini bersama-sama!

## Isi Materi

### Pengertian Bilangan Kompleks

Bilangan kompleks adalah bilangan yang dapat dinyatakan dalam bentuk $a + bi$, dimana:

- $a$ dan $b$ adalah bilangan real
- $i$ adalah unit imajiner, didefinisikan sebagai $i = \sqrt{-1}$ atau $i^2 = -1$

Dalam bilangan kompleks $z = a + bi$:

- $a$ disebut bagian real, dinotasikan sebagai $\text{Re}(z)$
- $b$ disebut bagian imajiner, dinotasikan sebagai $\text{Im}(z)$

### Jenis-Jenis Bilangan Kompleks

1. **Bilangan Kompleks Murni**

   Jika $a = 0$ dan $b \neq 0$, maka $z = bi$ disebut bilangan kompleks murni.

   Contoh: $3i$, $-5i$, $\frac{1}{2}i$

2. **Bilangan Real**

   Jika $b = 0$, maka $z = a$ merupakan bilangan real.

   Contoh: $5$, $-7$, $\frac{3}{4}$

3. **Bilangan Kompleks Konjugat**

   Untuk bilangan kompleks $z = a + bi$, kompleks konjugatnya adalah $\overline{z} = a - bi$

   Contoh: Jika $z = 2 + 3i$, maka $\overline{z} = 2 - 3i$

### Representasi Bilangan Kompleks

Bilangan kompleks dapat direpresentasikan dalam beberapa bentuk:

1. **Bentuk Aljabar**: $$z = a + bi$$

2. **Bentuk Polar**:
  $$z = r(\cos\theta + i\sin\theta)$$
  
dimana:

- $r = |z| = \sqrt{a^2 + b^2}$ (modulus/nilai mutlak)
- $\theta = \arg(z) = \arctan\left(\frac{b}{a}\right)$ (argumen)

3. **Bentuk Eksponensial**:  

$$z = re^{i\theta}$$

### Operasi Pada Bilangan Kompleks

#### 1. Penjumlahan dan Pengurangan

$$z_1 = a + bi$$ dan $$z_2 = c + di$$

- Penjumlahan: $z_1 + z_2 = (a + c) + (b + d)i$
- Pengurangan: $z_1 - z_2 = (a - c) + (b - d)i$

Contoh:
$(3 + 2i) + (4 - 5i) = (3 + 4) + (2 - 5)i = 7 - 3i$

#### 2. Perkalian

$$z_1 \times z_2 = (a + bi)(c + di) = ac + adi + bci + bdi^2
= (ac - bd) + (ad + bc)i$$

Contoh:
$(2 + 3i) \times (1 - i) = 2 \times 1 - 2 \times i + 3i \times 1 - 3i \times i$
$= 2 - 2i + 3i - 3i^2 = 2 - 2i + 3i - 3(-1) = 2 - 2i + 3i + 3 = 5 + i$

#### 3. Pembagian

Untuk membagi bilangan kompleks $\frac{z_1}{z_2}$, kalikan pembilang dan penyebut dengan konjugat dari penyebut:

$$\frac{z_1}{z_2} = \frac{a + bi}{c + di} = \frac{(a + bi)(c - di)}{(c + di)(c - di)} = \frac{ac + bd + (bc - ad)i}{c^2 + d^2}$$

Contoh:
$\frac{5 + 2i}{3 - 4i} = \frac{(5 + 2i)(3 + 4i)}{(3 - 4i)(3 + 4i)} = \frac{15 + 20i + 6i + 8i^2}{9 + 16} = \frac{15 - 8 + (20 + 6)i}{25} = \frac{7 + 26i}{25} = \frac{7}{25} + \frac{26}{25}i$

### Aplikasi Bilangan Kompleks

1. **Teknik Elektro**

   Bilangan kompleks digunakan untuk menganalisis rangkaian AC (arus bolak-balik), impedansi, dan resonansi.

2. **Pengolahan Sinyal**

   Transformasi Fourier, yang menggunakan bilangan kompleks, menjadi dasar dalam pemrosesan sinyal digital seperti pemampatan audio (MP3) dan gambar (JPEG).

3. **Mekanika Kuantum**

   Fungsi gelombang dalam mekanika kuantum digambarkan menggunakan bilangan kompleks.

4. **Aerodinamika**

   Aliran fluida dan analisis dinamika pesawat terbang sering menggunakan bilangan kompleks.

### Sifat-Sifat Penting Bilangan Kompleks

| Sifat | Rumus | Contoh |
|-------|-------|--------|
| Konjugat dari Penjumlahan | $\overline{z_1 + z_2} = \overline{z_1} + \overline{z_2}$ | $\overline{(3+2i)+(4+5i)} = \overline{(7+7i)} = 7-7i = \overline{(3+2i)}+\overline{(4+5i)} = (3-2i)+(4-5i) = 7-7i$ |
| Konjugat dari Perkalian | $\overline{z_1 \times z_2} = \overline{z_1} \times \overline{z_2}$ | $\overline{(2+i)(3+4i)} = \overline{(2+i)(3+4i)} = \overline{6+8i+3i+4i^2} = \overline{6+11i-4} = \overline{2+11i} = 2-11i$ |
| Modulus Perkalian | $\|z_1 \times z_2\| = \|z_1\| \times \|z_2\|$ | $\|(3+4i)(2+i)\| = 5\sqrt{5}$ |
| Modulus Pembagian | $\left\|\frac{z_1}{z_2}\right\| = \frac{\|z_1\|}{\|z_2\|}$ | $\left\|\frac{3+4i}{1+i}\right\| = \frac{5\sqrt{2}}{2}$ |

## Rangkuman Materi

- **Bilangan Kompleks**: Bentuk $z = a + bi$ dimana $i^2 = -1$
- **Bagian Bilangan Kompleks**:
  - Bagian real: $\text{Re}(z) = a$
  - Bagian imajiner: $\text{Im}(z) = b$
- **Representasi**:
  - Aljabar: $z = a + bi$
  - Polar: $z = r(\cos\theta + i\sin\theta)$
  - Eksponensial: $z = re^{i\theta}$
- **Operasi Dasar**:
  - Penjumlahan: $(a + bi) + (c + di) = (a + c) + (b + d)i$
  - Pengurangan: $(a + bi) - (c + di) = (a - c) + (b - d)i$
  - Perkalian: $(a + bi)(c + di) = (ac - bd) + (ad + bc)i$
  - Pembagian: $\frac{a + bi}{c + di} = \frac{ac + bd}{c^2 + d^2} + \frac{bc - ad}{c^2 + d^2}i$
- **Sifat Penting**:
  - Konjugat: $\overline{z} = a - bi$
  - Modulus: $|z| = \sqrt{a^2 + b^2}$
- **Aplikasi**: Teknik elektro, pengolahan sinyal, mekanika kuantum, dan aerodinamika
