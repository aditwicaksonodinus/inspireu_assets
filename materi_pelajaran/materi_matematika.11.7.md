# Transformasi Geometri

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta didik diharapkan mampu:

- Memahami konsep dasar transformasi geometri
- Mengidentifikasi jenis-jenis transformasi geometri (translasi, refleksi, rotasi, dan dilatasi)
- Menentukan hasil transformasi suatu titik atau bangun datar
- Menerapkan konsep transformasi geometri dalam pemecahan masalah sehari-hari

## Pendahuluan

Pernahkah kamu memperhatikan bayangan dirimu di cermin? Atau mungkin melihat pola-pola menarik pada ubin lantai atau desain batik? Semua itu merupakan contoh transformasi geometri yang ada di sekitar kita. Transformasi geometri adalah perubahan posisi, ukuran, atau bentuk suatu objek geometri berdasarkan aturan tertentu. Bahkan dalam permainan video, animasi film, atau desain grafis, transformasi geometri menjadi dasar untuk menciptakan gerakan dan efek visual yang menarik. Mari kita jelajahi dunia transformasi geometri yang menakjubkan ini dan temukan bagaimana matematika dapat menjelaskan begitu banyak keindahan di sekitar kita.

## Isi Materi

### Pengertian Transformasi Geometri

Transformasi geometri adalah perubahan posisi (koordinat) suatu titik atau bangun geometri menjadi posisi yang baru berdasarkan aturan tertentu. Dalam sistem koordinat Kartesius, transformasi dapat dinyatakan sebagai pemetaan suatu titik $P(x,y)$ menjadi titik $P'(x',y')$.

Secara umum, transformasi geometri memiliki sifat:

1. Dapat dibalik (invertible)
2. Dapat digabungkan (komposisi transformasi)
3. Beberapa transformasi mempertahankan ukuran dan bentuk (isometri)

### Jenis-jenis Transformasi Geometri

#### 1. Translasi (Pergeseran)

Translasi adalah transformasi yang memindahkan setiap titik pada bidang dengan jarak dan arah yang sama. Jika suatu titik $P(x,y)$ ditranslasikan sejauh $a$ satuan ke arah sumbu-$x$ dan $b$ satuan ke arah sumbu-$y$, maka:

$P(x,y) \rightarrow P'(x',y')$ dengan $x' = x + a$ dan $y' = y + b$

Secara matematis, translasi oleh vektor $\begin{pmatrix} a \\ b \end{pmatrix}$ dapat ditulis:

$$\begin{pmatrix} x' \\ y' \end{pmatrix} = \begin{pmatrix} x \\ y \end{pmatrix} + \begin{pmatrix} a \\ b \end{pmatrix} = \begin{pmatrix} x + a \\ y + b \end{pmatrix}$$

**Contoh:**
Titik $A(3,4)$ ditranslasikan dengan vektor translasi $\begin{pmatrix} 2 \\ -5 \end{pmatrix}$. Tentukan koordinat titik hasil translasi.

**Penyelesaian:**
$A'(x',y') = (3+2, 4+(-5)) = (5, -1)$

#### 2. Refleksi (Pencerminan)

Refleksi adalah transformasi yang memindahkan setiap titik pada bidang dengan menggunakan sumbu pencerminan tertentu. Bayangan suatu titik terletak pada garis yang tegak lurus dengan sumbu pencerminan, dan jarak antara titik asal ke sumbu sama dengan jarak bayangan ke sumbu.

Berikut adalah beberapa refleksi umum:

| Sumbu Refleksi | Transformasi Titik $(x,y)$ menjadi $(x',y')$ |
|----------------|----------------------------------------------|
| Sumbu-$x$ | $(x, y) \rightarrow (x, -y)$ |
| Sumbu-$y$ | $(x, y) \rightarrow (-x, y)$ |
| Garis $y = x$ | $(x, y) \rightarrow (y, x)$ |
| Garis $y = -x$ | $(x, y) \rightarrow (-y, -x)$ |
| Titik asal (0,0) | $(x, y) \rightarrow (-x, -y)$ |

**Contoh:**
Titik $B(4,-3)$ direfleksikan terhadap sumbu-$y$. Tentukan koordinat bayangannya.

**Penyelesaian:**
$B'(x',y') = (-4, -3)$

#### 3. Rotasi (Perputaran)

Rotasi adalah transformasi yang memindahkan setiap titik pada bidang dengan cara memutar titik tersebut dengan sudut dan pusat rotasi tertentu. Jika suatu titik $P(x,y)$ dirotasikan sebesar sudut $\theta$ (positif berlawanan arah jarum jam) dengan pusat rotasi di titik asal $(0,0)$, maka:

$$\begin{pmatrix} x' \\ y' \end{pmatrix} = \begin{pmatrix} \cos\theta & -\sin\theta \\ \sin\theta & \cos\theta \end{pmatrix} \begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} x\cos\theta - y\sin\theta \\ x\sin\theta + y\cos\theta \end{pmatrix}$$

Untuk sudut-sudut istimewa:

| Sudut Rotasi | Transformasi Titik $(x,y)$ menjadi $(x',y')$ |
|--------------|----------------------------------------------|
| $90°$ | $(x, y) \rightarrow (-y, x)$ |
| $180°$ | $(x, y) \rightarrow (-x, -y)$ |
| $270°$ | $(x, y) \rightarrow (y, -x)$ |
| $360°$ | $(x, y) \rightarrow (x, y)$ |

**Contoh:**
Titik $C(3,5)$ dirotasikan $90°$ berlawanan arah jarum jam dengan pusat rotasi di titik asal. Tentukan koordinat bayangannya.

**Penyelesaian:**
$C'(x',y') = (-5, 3)$

#### 4. Dilatasi (Perbesaran/Perkecilan)

Dilatasi adalah transformasi yang mengubah ukuran suatu bangun geometri dengan faktor skala tertentu terhadap suatu titik pusat dilatasi. Jika suatu titik $P(x,y)$ didilatasikan dengan faktor skala $k$ dan pusat dilatasi di titik asal $(0,0)$, maka:

$$\begin{pmatrix} x' \\ y' \end{pmatrix} = k \begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} kx \\ ky \end{pmatrix}$$

Jika $k > 1$, maka terjadi perbesaran.
Jika $0 < k < 1$, maka terjadi perkecilan.
Jika $k < 0$, maka terjadi perbesaran/perkecilan disertai pencerminan terhadap pusat dilatasi.

**Contoh:**
Titik $D(4,6)$ didilatasikan dengan faktor skala $2$ dan pusat dilatasi di titik asal. Tentukan koordinat bayangannya.

**Penyelesaian:**
$D'(x',y') = (2 \cdot 4, 2 \cdot 6) = (8, 12)$

### Komposisi Transformasi

Komposisi transformasi adalah gabungan dari dua atau lebih transformasi yang dilakukan secara berurutan. Hasil akhir dari komposisi transformasi bergantung pada urutan transformasi yang dilakukan.

**Contoh:**
Titik $P(3,4)$ ditranslasikan dengan vektor $\begin{pmatrix} 2 \\ 1 \end{pmatrix}$ kemudian direfleksikan terhadap sumbu-$x$. Tentukan koordinat akhir titik tersebut.

**Penyelesaian:**

- Translasi: $P(3,4) \rightarrow P'(3+2, 4+1) = P'(5,5)$
- Refleksi terhadap sumbu-$x$: $P'(5,5) \rightarrow P''(5,-5)$

Jadi, koordinat akhir titik tersebut adalah $(5,-5)$.

### Aplikasi Transformasi Geometri

Transformasi geometri memiliki banyak aplikasi dalam kehidupan sehari-hari, seperti:

1. **Seni dan Desain**: Pola batik, ornamen, dan seni grafis sering menggunakan konsep transformasi geometri.
2. **Komputer Grafis**: Animasi, game, dan desain grafis komputer menggunakan transformasi untuk menggerakkan objek.
3. **Arsitektur**: Perencanaan bangunan dan struktur menggunakan prinsip transformasi geometri.
4. **Teknologi Navigasi**: Sistem GPS menggunakan transformasi koordinat untuk menentukan posisi.
5. **Robotika**: Gerakan robot diprogram menggunakan konsep transformasi.

## Rangkuman

- **Transformasi Geometri** adalah perubahan posisi, ukuran, atau bentuk suatu objek geometri berdasarkan aturan tertentu.
- **Translasi** adalah pergeseran objek dengan jarak dan arah yang sama $(x,y) \rightarrow (x+a, y+b)$.
- **Refleksi** adalah pencerminan objek terhadap suatu sumbu atau titik tertentu.
- **Rotasi** adalah perputaran objek dengan sudut dan pusat rotasi tertentu.
- **Dilatasi** adalah perbesaran atau perkecilan objek dengan faktor skala tertentu $(x,y) \rightarrow (kx, ky)$.
- **Komposisi Transformasi** adalah gabungan dari dua atau lebih transformasi yang dilakukan secara berurutan.
- Transformasi geometri memiliki banyak aplikasi dalam kehidupan sehari-hari, seperti seni, desain, teknologi, dan arsitektur.
