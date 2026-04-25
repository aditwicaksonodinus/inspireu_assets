Materi ini membahas eksponen dan logaritma sebagai fondasi penting untuk memahami pertumbuhan, peluruhan, skala, dan pemodelan kuantitatif. Penyajian materi disusun bertahap dari gagasan konkret menuju simbol, sehingga peserta didik dapat membangun pemahaman melalui pola, penalaran, dan refleksi.

# Eksponen dan Logaritma

## Tujuan Pembelajaran
Setelah mempelajari bab ini, peserta didik diharapkan mampu:
1. Menjelaskan makna eksponen sebagai perkalian berulang dan perluasannya.
2. Menggunakan sifat-sifat eksponen untuk menyederhanakan bentuk aljabar.
3. Menjelaskan logaritma sebagai invers dari eksponen.
4. Menggunakan sifat-sifat logaritma dalam perhitungan dan pemecahan masalah.
5. Menyelesaikan persamaan eksponen dan logaritma sederhana.
6. Mengaitkan eksponen dan logaritma dengan konteks kehidupan nyata.

## Apersepsi
Dalam kehidupan sehari-hari, kita sering menjumpai perubahan yang sangat cepat, misalnya pertumbuhan jumlah data digital, bunga tabungan majemuk, atau peluruhan zat tertentu. Situasi seperti ini tidak cukup dijelaskan dengan penjumlahan biasa, melainkan memerlukan model perpangkatan. Dari sinilah eksponen menjadi penting. Ketika kita ingin mengetahui pangkat yang menghasilkan suatu nilai, kita masuk ke konsep logaritma.

## Peta Konsep
- Eksponen: makna dasar, sifat-sifat, bentuk pecahan, bentuk negatif.
- Persamaan eksponen: menyamakan basis, substitusi sederhana.
- Logaritma: definisi, syarat, hubungan dengan eksponen.
- Sifat logaritma: perkalian, pembagian, pangkat, perubahan basis sederhana.
- Aplikasi: pertumbuhan, peluruhan, skala.

## 1.1 Konsep Dasar Eksponen
Eksponen menyatakan perkalian berulang dari bilangan yang sama. Jika $a$ adalah bilangan pokok dan $n$ bilangan bulat positif, maka:

$$a^n = \underbrace{a \times a \times a \times \cdots \times a}_{n\ \text{faktor}}$$

Contoh:
- $2^4 = 2 \times 2 \times 2 \times 2 = 16$
- $3^3 = 27$
- $10^2 = 100$

Makna ini kemudian diperluas agar aturan eksponen tetap konsisten untuk pangkat nol, negatif, dan rasional.

## 1.2 Sifat-Sifat Eksponen
Sifat eksponen membantu menyederhanakan bentuk yang panjang menjadi lebih ringkas.

| Sifat | Bentuk Umum | Contoh |
|---|---|---|
| Perkalian basis sama | $a^m \cdot a^n = a^{m+n}$ | $2^3 \cdot 2^4 = 2^7$ |
| Pembagian basis sama | $\frac{a^m}{a^n} = a^{m-n}$ | $\frac{3^5}{3^2} = 3^3$ |
| Pangkat dari pangkat | $(a^m)^n = a^{mn}$ | $(2^3)^2 = 2^6$ |
| Pangkat pada perkalian | $(ab)^n = a^n b^n$ | $(2 \cdot 3)^2 = 2^2 \cdot 3^2$ |
| Pangkat pada pembagian | $\left(\frac{a}{b}\right)^n = \frac{a^n}{b^n}$ | $\left(\frac{6}{2}\right)^3 = \frac{6^3}{2^3}$ |
| Pangkat nol | $a^0 = 1$, $a \neq 0$ | $5^0 = 1$ |
| Pangkat negatif | $a^{-n} = \frac{1}{a^n}$ | $2^{-3} = \frac{1}{8}$ |
| Pangkat rasional | $a^{\frac{m}{n}} = \sqrt[n]{a^m}$ | $16^{\frac{1}{2}} = 4$ |

### Mengapa $a^0 = 1$?
Perhatikan pola berikut:
- $2^3 = 8$
- $2^2 = 4$
- $2^1 = 2$

Setiap pangkat turun 1, nilainya dibagi 2. Maka dari $2^1 = 2$, jika turun lagi satu tingkat diperoleh $2^0 = 1$. Pola ini menjaga konsistensi aturan eksponen.

## 1.3 Bentuk Akar dan Eksponen Rasional
Eksponen pecahan berkaitan langsung dengan bentuk akar.

$$a^{\frac{1}{n}} = \sqrt[n]{a}$$
$$a^{\frac{m}{n}} = \sqrt[n]{a^m} = (\sqrt[n]{a})^m$$

Contoh:
- $27^{\frac{1}{3}} = 3$
- $16^{\frac{3}{2}} = (\sqrt{16})^3 = 4^3 = 64$

Pada tahap ini, peserta didik perlu hati-hati membedakan antara $a^{\frac{m}{n}}$ dan $\frac{a^m}{n}$. Keduanya adalah bentuk yang berbeda.

## 1.4 Persamaan Eksponen
Persamaan eksponen adalah persamaan yang memuat peubah pada pangkat. Strategi paling dasar adalah mengubah kedua ruas ke basis yang sama.

Contoh 1:

$$2^{x+1} = 8$$
$$2^{x+1} = 2^3$$
$$x+1 = 3$$
$$x = 2$$

Contoh 2:

$$3^{2x-1} = 27$$
$$3^{2x-1} = 3^3$$
$$2x - 1 = 3$$
$$2x = 4$$
$$x = 2$$

Jika basis tidak langsung sama, kadang diperlukan substitusi sederhana atau manipulasi aljabar terlebih dahulu.

## 1.5 Konsep Dasar Logaritma
Logaritma adalah invers dari eksponen. Jika:

$$a^x = b$$

maka bentuk logaritmanya adalah:

$$\log_a b = x$$

Dengan syarat:
- $a > 0$
- $a \neq 1$
- $b > 0$

Contoh:
- $2^3 = 8 \iff \log_2 8 = 3$
- $10^2 = 100 \iff \log_{10} 100 = 2$
- $5^0 = 1 \iff \log_5 1 = 0$

Logaritma pada dasarnya menjawab pertanyaan: “bilangan pokok ini harus dipangkatkan berapa agar menghasilkan nilai tertentu?”

## 1.6 Sifat-Sifat Logaritma
| Sifat | Bentuk Umum | Contoh |
|---|---|---|
| Perkalian | $\log_a (bc) = \log_a b + \log_a c$ | $\log_2 32 = \log_2 (8\cdot4)$ |
| Pembagian | $\log_a \left(\frac{b}{c}\right) = \log_a b - \log_a c$ | $\log_3 9 = \log_3 27 - \log_3 3$ |
| Pangkat | $\log_a b^n = n\log_a b$ | $\log_2 8^2 = 2\log_2 8$ |
| Log 1 | $\log_a 1 = 0$ | $\log_7 1 = 0$ |
| Log basis sendiri | $\log_a a = 1$ | $\log_5 5 = 1$ |
| Invers | $\log_a a^x = x$ | $\log_2 2^6 = 6$ |

Sifat-sifat ini penting karena bentuk perkalian yang rumit dapat diubah menjadi penjumlahan, dan perpangkatan dapat diubah menjadi perkalian. Dengan demikian, perhitungan menjadi lebih sederhana.

## 1.7 Persamaan Logaritma Sederhana
Contoh 1:

$$\log_2 x = 5$$
$$x = 2^5$$
$$x = 32$$

Contoh 2:

$$\log_3 (x+1) = 2$$
$$x+1 = 3^2$$
$$x+1 = 9$$
$$x = 8$$

Selalu periksa syarat nilai dalam logaritma harus positif. Pada contoh kedua, bentuk $x+1$ memang bernilai positif ketika $x = 8$.

## 1.8 Hubungan Grafik Fungsi Eksponen dan Logaritma
Fungsi eksponen berbentuk $y = a^x$, sedangkan fungsi logaritma berbentuk $y = \log_a x$. Keduanya saling invers, sehingga grafiknya merupakan pencerminan terhadap garis $y = x$.

Sifat grafik eksponen:
- Domain semua bilangan real.
- Range bilangan real positif.
- Melalui titik $(0,1)$.
- Naik jika $a > 1$ dan turun jika $0 < a < 1$.

Sifat grafik logaritma:
- Domain $x > 0$.
- Range semua bilangan real.
- Melalui titik $(1,0)$.
- Memiliki asimtot tegak $x = 0$.
- Naik jika $a > 1$ dan turun jika $0 < a < 1$.

## 1.9 Aplikasi Kontekstual
1. Pertumbuhan populasi dapat dimodelkan dengan $P_t = P_0(1+r)^t$.
2. Bunga majemuk tabungan mengikuti pola eksponensial.
3. Skala keasaman $pH$ menggunakan logaritma.
4. Intensitas gempa dan bunyi juga melibatkan skala logaritmik.

Aplikasi ini menunjukkan bahwa eksponen dan logaritma bukan sekadar operasi simbolik, tetapi alat untuk memahami perubahan kuantitatif di dunia nyata.

## 1.10 Aktivitas Belajar
- Amati pola $2^1, 2^2, 2^3, 2^4$, lalu prediksi nilai $2^0$ dan $2^{-1}$ beserta alasannya.
- Ubah lima bentuk eksponen menjadi logaritma, kemudian ubah kembali ke bentuk semula.
- Diskusikan mengapa syarat $b > 0$ wajib dipenuhi pada $\log_a b$.
- Carilah satu contoh fenomena nyata yang lebih cocok dimodelkan secara eksponensial daripada linear.

## 1.11 Latihan Pemahaman
1. Sederhanakan $2^5 \cdot 2^3$.
2. Sederhanakan $\frac{5^7}{5^2}$.
3. Hitung nilai $(3^2)^4$.
4. Tentukan nilai $81^{\frac{1}{2}}$.
5. Selesaikan $2^{x+3} = 32$.
6. Selesaikan $3^{2x} = 81$.
7. Tentukan nilai $\log_2 64$.
8. Tentukan nilai $\log_5 125$.
9. Selesaikan $\log_2 (x-1) = 4$.
10. Jelaskan hubungan fungsi eksponen dan logaritma dengan kalimatmu sendiri.

## Refleksi
Jika kamu masih sering tertukar antara eksponen negatif dan bilangan negatif, berarti yang perlu diperkuat adalah makna bentuk, bukan hafalan rumus. Jika kamu sudah dapat berpindah dari bentuk eksponen ke logaritma dan sebaliknya tanpa bingung, berarti pemahaman dasarmu sudah cukup kuat untuk melanjutkan ke soal yang lebih kompleks.

## Glosarium
- **Eksponen**: pangkat yang menyatakan perkalian berulang.
- **Basis**: bilangan pokok pada bentuk eksponen atau logaritma.
- **Logaritma**: operasi invers dari eksponen.
- **Invers**: hubungan dua bentuk yang saling membalikkan.
- **Eksponen rasional**: pangkat pecahan yang berkaitan dengan akar.
- **Asimtot**: garis yang didekati grafik tetapi tidak dipotong pada perilaku tertentu.
