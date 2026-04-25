Materi ini membahas bilangan kompleks sebagai perluasan dari sistem bilangan real. Perluasan ini diperlukan karena tidak semua persamaan, terutama persamaan kuadrat tertentu, memiliki penyelesaian di himpunan bilangan real. Dengan mempelajari bilangan kompleks, peserta didik memahami bahwa matematika berkembang untuk menjawab keterbatasan sistem yang telah ada.

# Bilangan Kompleks

## Tujuan Pembelajaran
Setelah mempelajari bab ini, peserta didik diharapkan mampu:
1. Menjelaskan alasan munculnya bilangan kompleks.
2. Menyatakan bilangan kompleks dalam bentuk $a + bi$.
3. Menentukan bagian real dan bagian imajiner suatu bilangan kompleks.
4. Melakukan operasi penjumlahan, pengurangan, perkalian, dan pembagian bilangan kompleks.
5. Menentukan konjugat dan modulus bilangan kompleks.
6. Menggunakan bilangan kompleks untuk menyelesaikan persoalan sederhana.

## Apersepsi
Saat mempelajari persamaan kuadrat, kita menemukan bahwa persamaan seperti $x^2 + 1 = 0$ tidak memiliki penyelesaian real. Sebab, tidak ada bilangan real yang jika dikuadratkan menghasilkan $-1$. Dari kebutuhan inilah lahir bilangan imajiner, yang kemudian berkembang menjadi bilangan kompleks.

## Peta Konsep
- Bilangan imajiner dan satuan $i$.
- Bentuk umum bilangan kompleks.
- Operasi aljabar pada bilangan kompleks.
- Konjugat bilangan kompleks.
- Modulus dan interpretasi geometri sederhana.

## 1.1 Latar Belakang Bilangan Kompleks
Bilangan kompleks muncul dari kebutuhan menyelesaikan persamaan yang tidak dapat diselesaikan dalam bilangan real. Didefinisikan bahwa:

$$i^2 = -1$$

Dari definisi ini diperoleh:
- $i = \sqrt{-1}$
- $i^3 = i^2 \cdot i = -i$
- $i^4 = 1$

Pola pangkat $i$ berulang setiap empat langkah. Pola ini penting untuk menyederhanakan bentuk berpangkat tinggi.

## 1.2 Bentuk Umum Bilangan Kompleks
Bilangan kompleks ditulis dalam bentuk:

$$z = a + bi$$

Dengan:
- $a$ adalah bagian real
- $b$ adalah koefisien bagian imajiner
- $i$ adalah satuan imajiner dengan sifat $i^2 = -1$

Contoh:
- $3 + 2i$
- $-4 - 5i$
- $7$ dapat ditulis sebagai $7 + 0i$
- $-3i$ dapat ditulis sebagai $0 - 3i$

## 1.3 Bagian Real dan Imajiner
Jika $z = a + bi$, maka:
- bagian real $\operatorname{Re}(z) = a$
- bagian imajiner $\operatorname{Im}(z) = b$

Contoh:
Jika $z = 5 - 3i$, maka:
- $\operatorname{Re}(z) = 5$
- $\operatorname{Im}(z) = -3$

Peserta didik perlu cermat membedakan antara bagian imajiner dengan suku imajiner. Bagian imajiner adalah koefisiennya, bukan seluruh bentuk $bi$.

## 1.4 Kesamaan Bilangan Kompleks
Dua bilangan kompleks sama jika bagian real dan bagian imajinernya sama.

Jika:

$$a + bi = c + di$$

maka:

$$a = c \quad \text{dan} \quad b = d$$

Contoh:
Jika $2x + (y+1)i = 6 + 5i$, maka:
- $2x = 6 \Rightarrow x = 3$
- $y + 1 = 5 \Rightarrow y = 4$

## 1.5 Operasi Penjumlahan dan Pengurangan
Operasi dilakukan dengan mengelompokkan bagian real dan bagian imajiner.

Jika:

$$z_1 = a + bi, \quad z_2 = c + di$$

maka:

$$z_1 + z_2 = (a+c) + (b+d)i$$
$$z_1 - z_2 = (a-c) + (b-d)i$$

Contoh:

$$ (3+2i) + (1-5i) = 4-3i $$
$$ (4+7i) - (2+3i) = 2+4i $$

## 1.6 Operasi Perkalian
Perkalian dilakukan seperti aljabar biasa, lalu gunakan sifat $i^2 = -1$.

Contoh:

$$ (2+3i)(1-4i) $$
$$ = 2 - 8i + 3i - 12i^2 $$
$$ = 2 - 5i + 12 $$
$$ = 14 - 5i $$

Operasi ini menunjukkan bahwa hasil kali dua bilangan kompleks tetap berupa bilangan kompleks.

## 1.7 Operasi Pembagian
Pembagian bilangan kompleks dilakukan dengan mengalikan pembilang dan penyebut dengan konjugat penyebut.

Contoh:

$$\frac{3+2i}{1-i}$$

Kalikan dengan konjugat $1+i$:

$$\frac{3+2i}{1-i} \cdot \frac{1+i}{1+i} = \frac{(3+2i)(1+i)}{(1-i)(1+i)}$$

Pembilang:

$$ (3+2i)(1+i) = 3 + 3i + 2i + 2i^2 = 1 + 5i $$

Penyebut:

$$ (1-i)(1+i) = 1 - i^2 = 2 $$

Maka:

$$\frac{3+2i}{1-i} = \frac{1+5i}{2} = \frac{1}{2} + \frac{5}{2}i$$

## 1.8 Konjugat Bilangan Kompleks
Konjugat dari $z = a + bi$ adalah:

$$\overline{z} = a - bi$$

Contoh:
- konjugat dari $4 + 3i$ adalah $4 - 3i$
- konjugat dari $-2 - i$ adalah $-2 + i$

Konjugat berguna dalam pembagian dan dalam perhitungan modulus.

## 1.9 Modulus Bilangan Kompleks
Jika $z = a + bi$, maka modulusnya adalah:

$$|z| = \sqrt{a^2 + b^2}$$

Contoh:
Jika $z = 3 + 4i$, maka:

$$|z| = \sqrt{3^2 + 4^2} = 5$$

Secara geometri, modulus menyatakan jarak titik $(a,b)$ dari titik asal pada bidang kompleks.

## 1.10 Representasi Geometri Sederhana
Bilangan kompleks $z = a + bi$ dapat direpresentasikan sebagai titik $(a,b)$ pada bidang kompleks.
- sumbu horizontal menyatakan bagian real
- sumbu vertikal menyatakan bagian imajiner

Dengan cara ini, bilangan kompleks tidak lagi tampak abstrak semata, tetapi dapat dilihat sebagai objek geometri.

## 1.11 Aktivitas Belajar
- Hitung beberapa pangkat $i$ lalu temukan polanya.
- Nyatakan beberapa bilangan kompleks dalam bentuk titik pada bidang kompleks.
- Lakukan operasi penjumlahan dan pengurangan dua bilangan kompleks, lalu bandingkan pola hasilnya.
- Diskusikan mengapa konjugat membuat penyebut pembagian menjadi bilangan real.

## 1.12 Latihan Pemahaman
1. Sederhanakan $i^{15}$.
2. Tentukan bagian real dan imajiner dari $7 - 4i$.
3. Hitung $(2+5i) + (3-2i)$.
4. Hitung $(6-3i) - (1+4i)$.
5. Hitung $(2+i)(3-2i)$.
6. Tentukan konjugat dari $-5 + 6i$.
7. Hitung modulus dari $1 - \sqrt{3}i$.
8. Sederhanakan $\frac{2+i}{1+i}$.
9. Jika $x + 2i = 5 + yi$, tentukan $x$ dan $y$.
10. Jelaskan mengapa bilangan kompleks disebut perluasan dari bilangan real.

## Refleksi
Jika kamu sudah dapat melihat bahwa bentuk $a+bi$ memiliki struktur yang mirip dengan pasangan koordinat, maka bilangan kompleks akan terasa lebih mudah dipahami. Jika masih kesulitan, perkuat kembali makna $i^2=-1$ dan biasakan menyederhanakan hasil operasi langkah demi langkah.

## Glosarium
- **Bilangan kompleks**: bilangan berbentuk $a+bi$.
- **Bilangan imajiner**: bilangan yang melibatkan satuan $i$.
- **Bagian real**: komponen $a$ pada $a+bi$.
- **Bagian imajiner**: koefisien $b$ pada $a+bi$.
- **Konjugat**: pasangan $a-bi$ dari $a+bi$.
- **Modulus**: panjang atau jarak bilangan kompleks dari titik asal pada bidang kompleks.
