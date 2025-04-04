# Vektor

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta didik diharapkan mampu:

1. Memahami konsep dasar vektor dan perbedaannya dengan skalar
2. Menjelaskan representasi vektor dalam berbagai bentuk
3. Melakukan operasi penjumlahan, pengurangan, dan perkalian vektor
4. Menghitung besar (magnitudo) dan arah vektor
5. Menerapkan konsep vektor dalam pemecahan masalah kehidupan sehari-hari

## Pendahuluan

Pernahkah kamu berjalan melawan angin kencang? Atau berenang melawan arus sungai? Jika pernah, kamu telah mengalami langsung interaksi dengan vektor! Tidak seperti skalar yang hanya memiliki nilai, vektor memiliki nilai dan arah. Bayangkan saat kamu mendorong mobil yang mogok - penting untuk tahu seberapa kuat (nilai) dan ke arah mana (arah) kamu mendorong. Inilah vektor dalam kehidupan kita.

Dari pergerakan pesawat yang dipengaruhi angin, navigasi kapal di lautan, hingga desain bangunan tahan gempa - semua melibatkan vektor. Vektor bahkan menjadi dasar dalam pengembangan game dan animasi 3D yang kamu nikmati. Mari kita jelajahi dunia vektor yang menakjubkan dan menemukan bagaimana konsep matematika ini membentuk dunia di sekitar kita!

## Isi Materi

### Pengertian Vektor

Vektor adalah besaran yang memiliki nilai (magnitudo) dan arah. Ini berbeda dengan skalar yang hanya memiliki nilai. Contoh besaran vektor adalah kecepatan, percepatan, gaya, dan perpindahan. Sedangkan contoh besaran skalar adalah jarak, massa, waktu, dan suhu.

Secara matematis, vektor dapat dinotasikan dengan huruf yang diberi tanda panah di atasnya, seperti $\vec{a}$, atau huruf yang dicetak tebal, seperti **a**.

### Representasi Vektor

Vektor dapat direpresentasikan dalam beberapa cara:

1. **Representasi Geometris**: Vektor digambarkan sebagai ruas garis berarah. Panjang ruas garis menunjukkan nilai (magnitudo) vektor dan arah panah menunjukkan arah vektor.

2. **Representasi Aljabar**:
   - Dalam dimensi dua, vektor dinyatakan sebagai $\vec{a} = (a_1, a_2)$ atau $\vec{a} = a_1\vec{i} + a_2\vec{j}$
   - Dalam dimensi tiga, vektor dinyatakan sebagai $\vec{a} = (a_1, a_2, a_3)$ atau $\vec{a} = a_1\vec{i} + a_2\vec{j} + a_3\vec{k}$

Di mana $\vec{i}$, $\vec{j}$, dan $\vec{k}$ adalah vektor satuan dalam arah sumbu x, y, dan z.

### Magnitudo (Besar) Vektor

Magnitudo atau besar vektor adalah panjang dari vektor tersebut. Dinotasikan dengan $|\vec{a}|$ atau $\|\vec{a}\|$.

Untuk vektor $\vec{a} = (a_1, a_2)$ di bidang:
$$|\vec{a}| = \sqrt{a_1^2 + a_2^2}$$

Untuk vektor $\vec{a} = (a_1, a_2, a_3)$ di ruang:
$$|\vec{a}| = \sqrt{a_1^2 + a_2^2 + a_3^2}$$

### Operasi pada Vektor

#### 1. Penjumlahan dan Pengurangan Vektor

Jika $\vec{a} = (a_1, a_2, a_3)$ dan $\vec{b} = (b_1, b_2, b_3)$, maka:

Penjumlahan: $\vec{a} + \vec{b} = (a_1 + b_1, a_2 + b_2, a_3 + b_3)$
Pengurangan: $\vec{a} - \vec{b} = (a_1 - b_1, a_2 - b_2, a_3 - b_3)$

Secara geometris, penjumlahan vektor dapat dilakukan dengan metode segitiga atau metode jajargenjang.

#### 2. Perkalian Vektor dengan Skalar

Jika $\vec{a} = (a_1, a_2, a_3)$ dan $k$ adalah skalar, maka:
$$k\vec{a} = (ka_1, ka_2, ka_3)$$

Perkalian vektor dengan skalar memengaruhi magnitudo vektor, dan juga arahnya jika skalar bernilai negatif.

#### 3. Perkalian Titik (Dot Product)

Perkalian titik antara $\vec{a}$ dan $\vec{b}$ dinotasikan sebagai $\vec{a} \cdot \vec{b}$ dan hasilnya adalah skalar:
$$\vec{a} \cdot \vec{b} = a_1b_1 + a_2b_2 + a_3b_3 = |\vec{a}||\vec{b}|\cos\theta$$

Di mana $\theta$ adalah sudut antara kedua vektor.

#### 4. Perkalian Silang (Cross Product)

Perkalian silang antara $\vec{a}$ dan $\vec{b}$ dinotasikan sebagai $\vec{a} \times \vec{b}$ dan hasilnya adalah vektor yang tegak lurus pada kedua vektor tersebut:

$$\vec{a} \times \vec{b} =
\begin{vmatrix}
\vec{i} & \vec{j} & \vec{k} \\
a_1 & a_2 & a_3 \\
b_1 & b_2 & b_3
\end{vmatrix}
= (a_2b_3 - a_3b_2)\vec{i} + (a_3b_1 - a_1b_3)\vec{j} + (a_1b_2 - a_2b_1)\vec{k}$$

Magnitudo perkalian silang: $|\vec{a} \times \vec{b}| = |\vec{a}||\vec{b}|\sin\theta$

### Aplikasi Vektor dalam Kehidupan Sehari-hari

| Bidang | Aplikasi Vektor |
|--------|-----------------|
| Fisika | Gaya, kecepatan, percepatan, momentum |
| Navigasi | Penentuan arah dan kecepatan pesawat/kapal |
| Teknik Sipil | Analisis struktur, gaya pada bangunan |
| Meteorologi | Arah dan kecepatan angin |
| Komputer Grafis | Animasi 3D, game, simulasi |
| Robotika | Kontrol pergerakan robot |

### Contoh Penerapan Vektor

#### Contoh 1: Penerbangan Pesawat

Sebuah pesawat terbang dengan kecepatan 800 km/jam ke arah timur, tetapi angin bertiup dengan kecepatan 100 km/jam ke arah tenggara (sudut $45^\circ$ dari timur). Kecepatan resultan pesawat dapat dihitung dengan:

$$\vec{v}_{resultan} = \vec{v}_{pesawat} + \vec{v}_{angin}$$

Komponen angin:
$v_{angin,x} = 100 \cos 45^\circ = 100 \times \frac{\sqrt{2}}{2} = 70,7$ km/jam
$v_{angin,y} = 100 \sin 45^\circ = 100 \times \frac{\sqrt{2}}{2} = 70,7$ km/jam

Kecepatan resultan:
$v_{resultan,x} = 800 + 70,7 = 870,7$ km/jam
$v_{resultan,y} = -70,7$ km/jam

Magnitudo kecepatan resultan:
$$|\vec{v}_{resultan}| = \sqrt{870,7^2 + (-70,7)^2} \approx 873,6 \text{ km/jam}$$

Sudut terhadap arah timur:
$$\theta = \tan^{-1}\left(\frac{-70,7}{870,7}\right) \approx -4,6^\circ$$

Jadi, pesawat bergerak dengan kecepatan sekitar 873,6 km/jam pada sudut 4,6° ke arah selatan dari timur.

## Rangkuman

- **Vektor** adalah besaran yang memiliki magnitudo dan arah, berbeda dengan skalar yang hanya memiliki nilai.
- **Representasi vektor** dapat dalam bentuk geometris (ruas garis berarah) atau aljabar $(a_1, a_2, a_3)$.
- **Magnitudo vektor** adalah panjang vektor, dihitung dengan $|\vec{a}| = \sqrt{a_1^2 + a_2^2 + a_3^2}$.
- **Operasi pada vektor** meliputi:
  - Penjumlahan dan pengurangan
  - Perkalian dengan skalar
  - Perkalian titik (dot product) yang menghasilkan skalar
  - Perkalian silang (cross product) yang menghasilkan vektor
- **Aplikasi vektor** sangat luas, mulai dari fisika, navigasi, meteorologi, teknik sipil, komputer grafis, hingga robotika.
- Vektor membantu menyelesaikan masalah di dunia nyata yang melibatkan besaran yang memiliki arah.
