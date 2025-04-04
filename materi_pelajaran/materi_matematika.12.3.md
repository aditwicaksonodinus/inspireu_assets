# Limit Fungsi

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta didik diharapkan mampu:

- Memahami konsep dasar limit fungsi
- Menjelaskan sifat-sifat limit fungsi
- Menentukan nilai limit fungsi aljabar
- Menyelesaikan masalah yang berkaitan dengan limit fungsi dalam kehidupan sehari-hari

## Pendahuluan

Pernahkah kamu bertanya-tanya bagaimana para ilmuwan dapat menghitung kecepatan sesaat sebuah objek? Atau bagaimana para insinyur menghitung tingkat perubahan suhu pada suatu material? Jawabannya terletak pada konsep limit. Limit adalah salah satu konsep paling mendasar dan penting dalam kalkulus, yang menjembatani aljabar dan kalkulus.

Bayangkan kamu sedang mengendarai sepeda. Ketika kamu melihat speedometer, yang kamu lihat adalah kecepatan pada saat tertentu. Namun, bagaimana cara menghitung kecepatan pada satu titik waktu yang spesifik? Di sinilah konsep limit berperan. Limit memungkinkan kita untuk memahami perilaku fungsi saat variabelnya mendekati suatu nilai tertentu, meskipun fungsi tersebut mungkin tidak terdefinisi pada nilai tersebut.

## Isi Materi

### Pengertian Limit

Limit fungsi adalah nilai yang didekati oleh output fungsi ketika inputnya mendekati suatu nilai tertentu. Secara matematis, limit fungsi $f(x)$ saat $x$ mendekati $a$ ditulis sebagai:

$$\lim_{x \to a} f(x) = L$$

Artinya, nilai $f(x)$ semakin mendekati $L$ ketika $x$ semakin mendekati $a$ (dari kiri maupun kanan).

### Limit Satu Sisi

Ada dua jenis limit satu sisi:

1. **Limit Kiri**: Nilai limit saat $x$ mendekati $a$ dari arah kiri (nilai $x < a$)
   $$\lim_{x \to a^-} f(x) = L_1$$

2. **Limit Kanan**: Nilai limit saat $x$ mendekati $a$ dari arah kanan (nilai $x > a$)
   $$\lim_{x \to a^+} f(x) = L_2$$

Limit fungsi di titik $a$ ada jika dan hanya jika $L_1 = L_2$.

### Sifat-sifat Limit

Berikut beberapa sifat limit yang perlu dipahami:

1. **Limit Konstanta**:
   $$\lim_{x \to a} k = k$$
   dimana $k$ adalah konstanta.

2. **Limit Identitas**:
   $$\lim_{x \to a} x = a$$

3. **Limit Jumlah**:
   $$\lim_{x \to a} [f(x) + g(x)] = \lim_{x \to a} f(x) + \lim_{x \to a} g(x)$$

4. **Limit Selisih**:
   $$\lim_{x \to a} [f(x) - g(x)] = \lim_{x \to a} f(x) - \lim_{x \to a} g(x)$$

5. **Limit Perkalian**:
   $$\lim_{x \to a} [f(x) \cdot g(x)] = \lim_{x \to a} f(x) \cdot \lim_{x \to a} g(x)$$

6. **Limit Pembagian**:
   $$\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)}$$
   dengan syarat $\lim_{x \to a} g(x) \neq 0$

7. **Limit Pangkat**:
   $$\lim_{x \to a} [f(x)]^n = [\lim_{x \to a} f(x)]^n$$
   dimana $n$ adalah bilangan real.

### Teknik Menghitung Limit

#### 1. Substitusi Langsung

Jika fungsi $f(x)$ kontinu di $x = a$, maka:
$$\lim_{x \to a} f(x) = f(a)$$

**Contoh:**
$$\lim_{x \to 2} (x^2 + 3x - 5) = 2^2 + 3(2) - 5 = 4 + 6 - 5 = 5$$

#### 2. Faktorisasi

Digunakan saat menghadapi bentuk $\frac{0}{0}$ (tak tentu).

**Contoh:**
$$\lim_{x \to 3} \frac{x^2 - 9}{x - 3} = \lim_{x \to 3} \frac{(x - 3)(x + 3)}{x - 3} = \lim_{x \to 3} (x + 3) = 6$$

#### 3. Perkalian dengan Sekawan

Digunakan untuk mengatasi bentuk tak tentu yang melibatkan akar.

**Contoh:**
$$\lim_{x \to 4} \frac{\sqrt{x} - 2}{x - 4} = \lim_{x \to 4} \frac{(\sqrt{x} - 2)(\sqrt{x} + 2)}{(x - 4)(\sqrt{x} + 2)} = \lim_{x \to 4} \frac{x - 4}{(x - 4)(\sqrt{x} + 2)} = \lim_{x \to 4} \frac{1}{\sqrt{x} + 2} = \frac{1}{4}$$

#### 4. Limit Fungsi Trigonometri

Beberapa limit penting dalam trigonometri:

$$\lim_{x \to 0} \frac{\sin x}{x} = 1$$

$$\lim_{x \to 0} \frac{1 - \cos x}{x} = 0$$

**Contoh:**
$$\lim_{x \to 0} \frac{\sin 3x}{x} = \lim_{x \to 0} \frac{3 \sin 3x}{3x} \cdot 3 = 3 \cdot \lim_{t \to 0} \frac{\sin t}{t} = 3 \cdot 1 = 3$$
dimana $t = 3x$

### Aplikasi Limit dalam Kehidupan Sehari-hari

1. **Kecepatan Sesaat**
   Kecepatan sesaat pada waktu $t = a$ dapat didefinisikan sebagai:
   $$v(a) = \lim_{h \to 0} \frac{s(a + h) - s(a)}{h}$$
   dimana $s(t)$ adalah fungsi posisi terhadap waktu.

2. **Laju Perubahan**
   Misalnya, laju perubahan suhu terhadap waktu:
   $$\frac{dT}{dt} = \lim_{h \to 0} \frac{T(t + h) - T(t)}{h}$$

3. **Perhitungan Luas dan Volume**
   Limit digunakan dalam integral untuk menghitung luas di bawah kurva atau volume benda putar.

## Rangkuman

- Limit fungsi adalah nilai yang didekati oleh output fungsi ketika inputnya mendekati suatu nilai tertentu.
- Limit dapat didekati dari kiri ($\lim_{x \to a^-}$) atau dari kanan ($\lim_{x \to a^+}$).
- Limit fungsi di titik $a$ ada jika limit kiri sama dengan limit kanan.
- Teknik menghitung limit meliputi: substitusi langsung, faktorisasi, perkalian dengan sekawan, dan teknik khusus untuk fungsi trigonometri.
- Sifat-sifat limit meliputi: limit konstanta, limit identitas, limit jumlah, limit selisih, limit perkalian, limit pembagian, dan limit pangkat.
- Limit menjadi dasar dalam kalkulus dan memiliki banyak aplikasi dalam kehidupan sehari-hari, seperti menghitung kecepatan sesaat, laju perubahan, dan dalam perhitungan luas serta volume.
