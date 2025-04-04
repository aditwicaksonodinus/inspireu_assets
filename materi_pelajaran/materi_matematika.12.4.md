# Fungsi Turunan

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta didik diharapkan mampu:

- Memahami konsep dasar fungsi turunan
- Menerapkan aturan-aturan turunan dalam menyelesaikan masalah
- Mengidentifikasi aplikasi turunan dalam kehidupan sehari-hari
- Menyelesaikan soal-soal yang berkaitan dengan fungsi turunan

## Pendahuluan

Pernahkah kamu memperhatikan bagaimana seorang pengemudi mobil mengatur kecepatannya? Atau bagaimana seorang insinyur merancang bentuk aerodinamis sebuah pesawat? Semua itu berkaitan erat dengan konsep yang akan kita pelajari hari ini: fungsi turunan.

Fungsi turunan merupakan salah satu konsep paling penting dalam kalkulus yang memungkinkan kita menganalisis laju perubahan suatu fungsi. Bayangkan kamu sedang mengamati ketinggian bola yang dilempar ke atas. Ketinggian bola berubah setiap waktu, dan turunan dapat memberi tahu kita seberapa cepat perubahan itu terjadi pada suatu titik tertentu.

Mari kita jelajahi dunia turunan yang menarik dan aplikasinya yang luas dalam kehidupan sehari-hari!

## Isi Materi

### Konsep Dasar Turunan

Turunan dari suatu fungsi $f(x)$ didefinisikan sebagai:

$$f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$$

Secara geometris, turunan $f'(x)$ pada suatu titik merepresentasikan kemiringan garis singgung pada grafik fungsi $f(x)$ di titik tersebut.

### Notasi Turunan

Jika $y = f(x)$, maka turunan dari $y$ terhadap $x$ dapat ditulis dengan beberapa notasi:

- $f'(x)$ (notasi Lagrange)
- $\frac{dy}{dx}$ (notasi Leibniz)
- $y'$ (notasi Newton)

### Aturan-aturan Turunan

1. **Turunan Fungsi Konstan**
   Jika $f(x) = c$, dimana $c$ adalah konstanta, maka:
   $$f'(x) = 0$$

2. **Turunan Fungsi Identitas**
   Jika $f(x) = x$, maka:
   $$f'(x) = 1$$

3. **Aturan Pangkat**
   Jika $f(x) = x^n$, dimana $n$ adalah bilangan real, maka:
   $$f'(x) = n \cdot x^{n-1}$$

4. **Aturan Penjumlahan dan Pengurangan**
   Jika $f(x) = g(x) \pm h(x)$, maka:
   $$f'(x) = g'(x) \pm h'(x)$$

5. **Aturan Perkalian**
   Jika $f(x) = g(x) \cdot h(x)$, maka:
   $$f'(x) = g'(x) \cdot h(x) + g(x) \cdot h'(x)$$

6. **Aturan Pembagian**
   Jika $f(x) = \frac{g(x)}{h(x)}$, maka:
   $$f'(x) = \frac{g'(x) \cdot h(x) - g(x) \cdot h'(x)}{[h(x)]^2}$$

7. **Aturan Rantai**
   Jika $f(x) = g(h(x))$, maka:
   $$f'(x) = g'(h(x)) \cdot h'(x)$$

### Turunan Fungsi Trigonometri

- $\frac{d}{dx}(\sin x) = \cos x$
- $\frac{d}{dx}(\cos x) = -\sin x$
- $\frac{d}{dx}(\tan x) = \sec^2 x$

### Turunan Fungsi Eksponensial dan Logaritma

- $\frac{d}{dx}(e^x) = e^x$
- $\frac{d}{dx}(\ln x) = \frac{1}{x}$
- $\frac{d}{dx}(a^x) = a^x \ln a$

### Aplikasi Turunan

1. **Menentukan Kemiringan Garis Singgung**

   Turunan $f'(x_0)$ memberikan kemiringan garis singgung pada kurva $y = f(x)$ di titik $(x_0, f(x_0))$.

2. **Laju Perubahan**

   Turunan fungsi menggambarkan laju perubahan suatu besaran terhadap besaran lain. Misalnya, jika $s(t)$ merupakan fungsi posisi, maka $s'(t)$ merupakan kecepatan dan $s''(t)$ merupakan percepatan.

3. **Nilai Maksimum dan Minimum**

   Titik-titik kritis (yaitu titik di mana $f'(x) = 0$ atau $f'(x)$ tidak terdefinisi) merupakan kandidat nilai maksimum atau minimum fungsi.

4. **Analisis Grafik**

   Turunan pertama memberikan informasi tentang interval di mana fungsi naik atau turun.
   Turunan kedua memberikan informasi tentang kecekungan grafik.

### Contoh Soal

**Contoh 1:**
Tentukan turunan dari fungsi $f(x) = 3x^4 - 2x^2 + 5x - 7$

Penyelesaian:
\begin{align}
f'(x) &= \frac{d}{dx}(3x^4 - 2x^2 + 5x - 7)\\
&= \frac{d}{dx}(3x^4) - \frac{d}{dx}(2x^2) + \frac{d}{dx}(5x) - \frac{d}{dx}(7)\\
&= 3 \cdot 4x^3 - 2 \cdot 2x^1 + 5 \cdot 1 - 0\\
&= 12x^3 - 4x + 5
\end{align}

**Contoh 2:**
Jika $f(x) = \sin x \cdot \cos x$, tentukan $f'(x)$.

Penyelesaian:
Menggunakan aturan perkalian:
\begin{align}
f'(x) &= \frac{d}{dx}(\sin x) \cdot \cos x + \sin x \cdot \frac{d}{dx}(\cos x)\\
&= \cos x \cdot \cos x + \sin x \cdot (-\sin x)\\
&= \cos^2 x - \sin^2 x\\
&= \cos 2x
\end{align}

**Contoh 3:**
Tentukan persamaan garis singgung kurva $y = x^2 - 3x + 2$ di titik $(2, 0)$.

Penyelesaian:
Pertama, kita cari $f'(x) = 2x - 3$
Pada $x = 2$, $f'(2) = 2(2) - 3 = 4 - 3 = 1$

Jadi, kemiringan garis singgung di titik $(2, 0)$ adalah 1.
Persamaan garis singgung: $y - y_0 = m(x - x_0)$
$y - 0 = 1(x - 2)$
$y = x - 2$

## Rangkuman Materi

- Turunan adalah laju perubahan suatu fungsi terhadap variabel bebasnya, didefinisikan sebagai $f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$
  
- Aturan-aturan penting turunan:
  - Turunan konstanta = 0
  - Turunan $x^n = n \cdot x^{n-1}$
  - Aturan penjumlahan: $(f \pm g)' = f' \pm g'$
  - Aturan perkalian: $(f \cdot g)' = f' \cdot g + f \cdot g'$
  - Aturan pembagian: $(\frac{f}{g})' = \frac{f' \cdot g - f \cdot g'}{g^2}$
  - Aturan rantai: $(f(g(x)))' = f'(g(x)) \cdot g'(x)$
  
- Turunan memiliki aplikasi penting dalam:
  - Menentukan kemiringan garis singgung
  - Menganalisis laju perubahan
  - Mencari nilai maksimum/minimum
  - Menganalisis karakteristik grafik fungsi
  
- Turunan menjadi dasar dalam berbagai bidang seperti fisika, ekonomi, biologi, dan teknik untuk menganalisis perubahan suatu sistem.
