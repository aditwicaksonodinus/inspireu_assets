# Integral

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta didik diharapkan dapat:

- Memahami konsep dasar integral sebagai antiturunan
- Mengenal integral tentu dan integral tak tentu
- Mengaplikasikan rumus-rumus dasar integral
- Menyelesaikan permasalahan luas daerah menggunakan integral
- Mengaitkan konsep integral dalam pemecahan masalah kehidupan sehari-hari

## Pendahuluan

Pernahkah kamu mengamati air yang mengisi bak mandi? Kecepatan aliran air menentukan berapa cepat bak tersebut terisi. Jika kita tahu kecepatan aliran setiap saat, bagaimana cara menghitung total volume air yang masuk? Atau pernahkah kamu bertanya-tanya bagaimana cara menghitung luas bidang dengan bentuk yang tidak beraturan seperti daun?

Pertanyaan-pertanyaan tersebut dapat dijawab dengan konsep integral! Integral merupakan salah satu konsep penting dalam kalkulus yang memungkinkan kita menghitung luas, volume, panjang kurva, dan banyak aplikasi menarik lainnya. Integral adalah "kebalikan" dari turunan yang telah kita pelajari sebelumnya. Jika turunan membantu kita menganalisis perubahan, integral membantu kita menjumlahkan atau mengakumulasi perubahan tersebut.

Mari kita jelajahi dunia integral yang menarik ini!

## Isi Materi

### Konsep Dasar Integral

Integral merupakan antiturunan (anti-derivative) dari suatu fungsi. Jika turunan dari fungsi $F(x)$ adalah $f(x)$, maka kita dapat menuliskan:

$$\int f(x) \, dx = F(x) + C$$

dimana:

- $\int$ adalah simbol integral
- $f(x)$ adalah fungsi yang diintegralkan (integrand)
- $dx$ menunjukkan variabel integrasi
- $F(x)$ adalah antiturunan dari $f(x)$
- $C$ adalah konstanta integrasi

### Integral Tak Tentu

Integral tak tentu adalah integral yang tidak memiliki batas atas dan batas bawah. Hasilnya berupa sebuah fungsi dan konstanta integrasi.

Beberapa rumus dasar integral tak tentu:

1. $\int k \, dx = kx + C$, dimana $k$ adalah konstanta
2. $\int x^n \, dx = \frac{x^{n+1}}{n+1} + C$, untuk $n \neq -1$
3. $\int \frac{1}{x} \, dx = \ln|x| + C$
4. $\int e^x \, dx = e^x + C$
5. $\int \sin x \, dx = -\cos x + C$
6. $\int \cos x \, dx = \sin x + C$

**Contoh 1:**
Tentukan $\int (3x^2 + 2x - 5) \, dx$

Penyelesaian:
$$\begin{align*}
\int (3x^2 + 2x - 5) \, dx &= \int 3x^2 \, dx + \int 2x \, dx - \int 5 \, dx \\
&= 3 \int x^2 \, dx + 2 \int x \, dx - 5 \int dx \\
&= 3 \cdot \frac{x^3}{3} + 2 \cdot \frac{x^2}{2} - 5x + C \\
&= x^3 + x^2 - 5x + C
\end{align*}$$

### Integral Tentu

Integral tentu memiliki batas atas ($b$) dan batas bawah ($a$), dan hasilnya berupa nilai numerik. Rumus integral tentu:

$$\int_{a}^{b} f(x) \, dx = F(b) - F(a)$$

dimana $F(x)$ adalah antiturunan dari $f(x)$.

**Contoh 2:**
Tentukan nilai $\int_{0}^{2} (x^2 + 3x) \, dx$

Penyelesaian:
$$\begin{align*}
\int_{0}^{2} (x^2 + 3x) \, dx &= \left[ \frac{x^3}{3} + \frac{3x^2}{2} \right]_{0}^{2} \\
&= \left( \frac{2^3}{3} + \frac{3 \cdot 2^2}{2} \right) - \left( \frac{0^3}{3} + \frac{3 \cdot 0^2}{2} \right) \\
&= \left( \frac{8}{3} + 6 \right) - 0 \\
&= \frac{8}{3} + 6 \\
&= \frac{8}{3} + \frac{18}{3} \\
&= \frac{26}{3} \approx 8,67
\end{align*}$$

### Aplikasi Integral: Luas Daerah

Salah satu aplikasi penting integral adalah menghitung luas daerah di bawah kurva. Luas daerah yang dibatasi oleh kurva $y = f(x)$, sumbu-$x$, dan garis $x = a$ dan $x = b$ adalah:

$$\text{Luas} = \int_{a}^{b} f(x) \, dx$$

**Contoh 3:**
Tentukan luas daerah yang dibatasi oleh kurva $y = x^2$ dan sumbu-$x$ dari $x = 0$ hingga $x = 3$.

Penyelesaian:
$$\begin{align*}
\text{Luas} &= \int_{0}^{3} x^2 \, dx \\
&= \left[ \frac{x^3}{3} \right]_{0}^{3} \\
&= \frac{3^3}{3} - \frac{0^3}{3} \\
&= 9 - 0 \\
&= 9 \text{ satuan luas}
\end{align*}$$

### Luas Daerah antara Dua Kurva

Luas daerah yang dibatasi oleh kurva $y = f(x)$, $y = g(x)$, dan garis $x = a$ dan $x = b$ adalah:

$$\text{Luas} = \int_{a}^{b} |f(x) - g(x)| \, dx$$

Jika $f(x) \geq g(x)$ untuk semua $x$ dalam interval $[a,b]$, maka:

$$\text{Luas} = \int_{a}^{b} [f(x) - g(x)] \, dx$$

**Contoh 4:**
Tentukan luas daerah yang dibatasi oleh kurva $y = x^2$ dan $y = x$ dari $x = 0$ hingga $x = 1$.

Penyelesaian:
Pertama, perhatikan bahwa $y = x \geq y = x^2$ untuk $0 \leq x \leq 1$, sehingga:

$$\begin{align*}
\text{Luas} &= \int_{0}^{1} (x - x^2) \, dx \\
&= \int_{0}^{1} x \, dx - \int_{0}^{1} x^2 \, dx \\
&= \left[ \frac{x^2}{2} \right]_{0}^{1} - \left[ \frac{x^3}{3} \right]_{0}^{1} \\
&= \left( \frac{1^2}{2} - \frac{0^2}{2} \right) - \left( \frac{1^3}{3} - \frac{0^3}{3} \right) \\
&= \frac{1}{2} - \frac{1}{3} \\
&= \frac{3-2}{6} \\
&= \frac{1}{6} \text{ satuan luas}
\end{align*}$$

### Aplikasi Integral dalam Kehidupan Sehari-hari

1. **Perhitungan Jarak dan Kecepatan**

   Jika $v(t)$ adalah fungsi kecepatan terhadap waktu, maka jarak yang ditempuh dari waktu $t = a$ hingga $t = b$ adalah:

   $$s = \int_{a}^{b} v(t) \, dt$$

   **Contoh 5:**
   Sebuah mobil bergerak dengan kecepatan $v(t) = 2t + 5$ m/s, dimana $t$ dalam detik. Tentukan jarak yang ditempuh mobil dari $t = 0$ hingga $t = 10$ detik.

   Penyelesaian:
   $$\begin{align*}
   s &= \int_{0}^{10} (2t + 5) \, dt \\
   &= \left[ t^2 + 5t \right]_{0}^{10} \\
   &= (10^2 + 5 \cdot 10) - (0^2 + 5 \cdot 0) \\
   &= 100 + 50 - 0 \\
   &= 150 \text{ meter}
   \end{align*}$$

2. **Perhitungan Volume Benda Putar**

   Volume benda putar yang terbentuk dari perputaran daerah di bawah kurva $y = f(x)$ dari $x = a$ hingga $x = b$ terhadap sumbu-$x$ adalah:

   $$V = \pi \int_{a}^{b} [f(x)]^2 \, dx$$

   **Contoh 6:**
   Tentukan volume benda putar yang terbentuk dari perputaran daerah di bawah kurva $y = \sqrt{x}$ dari $x = 0$ hingga $x = 4$ terhadap sumbu-$x$.

   Penyelesaian:
   $$\begin{align*}
   V &= \pi \int_{0}^{4} (\sqrt{x})^2 \, dx \\
   &= \pi \int_{0}^{4} x \, dx \\
   &= \pi \left[ \frac{x^2}{2} \right]_{0}^{4} \\
   &= \pi \left( \frac{4^2}{2} - \frac{0^2}{2} \right) \\
   &= \pi \cdot \frac{16}{2} \\
   &= 8\pi \text{ satuan volume}
   \end{align*}$$

## Rangkuman

- **Integral** adalah antiturunan dari suatu fungsi, merupakan operasi kebalikan dari turunan.
- **Integral tak tentu** ditulis sebagai $\int f(x) \, dx = F(x) + C$, dimana $F'(x) = f(x)$.
- **Integral tentu** ditulis sebagai $\int_{a}^{b} f(x) \, dx = F(b) - F(a)$, memberikan nilai numerik.
- **Rumus dasar integral**:
  - $\int x^n \, dx = \frac{x^{n+1}}{n+1} + C$, untuk $n \neq -1$
  - $\int \frac{1}{x} \, dx = \ln|x| + C$
  - $\int e^x \, dx = e^x + C$
  - $\int \sin x \, dx = -\cos x + C$
  - $\int \cos x \, dx = \sin x + C$
- **Aplikasi integral** mencakup:
  - Menghitung luas daerah di bawah kurva
  - Menghitung luas daerah antara dua kurva
  - Menghitung jarak dari fungsi kecepatan
  - Menghitung volume benda putar
  - Menyelesaikan berbagai masalah fisika dan teknik
