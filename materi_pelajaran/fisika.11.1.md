Materi ini membahas vektor sebagai bahasa penting dalam fisika untuk menyatakan besaran yang memiliki nilai sekaligus arah. Pemahaman vektor sangat dibutuhkan untuk mempelajari gerak, gaya, momentum, medan, dan berbagai model fisika lain. Karena itu, bab ini tidak hanya menekankan perhitungan, tetapi juga makna geometris dan fisis dari setiap operasi vektor.

# Vektor

## Tujuan Pembelajaran
Setelah mempelajari bab ini, kamu diharapkan mampu:
1. Menjelaskan perbedaan besaran skalar dan besaran vektor.
2. Menyatakan vektor dalam bentuk gambar, komponen, dan notasi satuan.
3. Menentukan resultan dua atau lebih vektor dengan metode grafik dan analitik.
4. Menguraikan vektor ke sumbu-sumbu koordinat.
5. Menentukan besar dan arah vektor dari komponennya.
6. Menerapkan operasi vektor dalam masalah fisika sederhana.

## 1.1 Konsep Dasar Vektor

Dalam fisika, tidak semua besaran cukup dinyatakan dengan angka saja. Massa, suhu, waktu, dan energi cukup dinyatakan oleh nilai, sehingga termasuk besaran skalar. Sebaliknya, perpindahan, kecepatan, percepatan, dan gaya memerlukan informasi arah, sehingga termasuk besaran vektor.

Vektor biasanya digambarkan sebagai panah. Panjang panah menyatakan besar vektor, sedangkan arah panah menyatakan arah vektor tersebut. Jika sebuah benda berpindah 5 meter ke timur, informasi “5 meter” saja belum cukup; arah “ke timur” adalah bagian esensial dari besaran itu.

## 1.2 Notasi dan Representasi Vektor

Vektor dapat dinyatakan dalam beberapa bentuk berikut.

### 1.2.1 Bentuk gambar
Panah dari titik pangkal ke titik ujung. Misalnya, perpindahan dari titik A ke titik B dinyatakan sebagai vektor dari A menuju B.

### 1.2.2 Notasi huruf
Vektor dapat ditulis sebagai $\vec{A}$, $\vec{B}$, atau huruf tebal seperti $\mathbf{A}$. Besar vektor ditulis sebagai $|\vec{A}|$ atau cukup $A$ jika konteksnya jelas.

### 1.2.3 Bentuk komponen
Pada bidang datar, vektor dapat dinyatakan sebagai:

$$
\vec{A} = A_x \hat{i} + A_y \hat{j}
$$

Pada ruang tiga dimensi:

$$
\vec{A} = A_x \hat{i} + A_y \hat{j} + A_z \hat{k}
$$

Di sini, $\hat{i}$, $\hat{j}$, dan $\hat{k}$ adalah vektor satuan pada sumbu-$x$, sumbu-$y$, dan sumbu-$z$.

## 1.3 Besar dan Arah Vektor

Jika komponen-komponen vektor diketahui, maka besar vektor pada dua dimensi ditentukan dengan teorema Pythagoras:

$$
|\vec{A}| = \sqrt{A_x^2 + A_y^2}
$$

Arah vektor terhadap sumbu-$x$ positif dapat dicari dengan:

$$
\tan \theta = \frac{A_y}{A_x}
$$

Namun, dalam praktik, kuadran harus diperhatikan. Nilai sudut tidak cukup diperoleh dari kalkulator saja; kita juga harus menafsirkan tanda komponen agar arah vektor tepat.

Contoh:
Jika $\vec{A} = 3\hat{i} + 4\hat{j}$, maka:

$$
|\vec{A}| = \sqrt{3^2 + 4^2} = 5
$$

Dan arah vektor:

$$
\theta = \tan^{-1}\left(\frac{4}{3}\right)
$$

Jadi besar vektor adalah 5 satuan, dengan arah di kuadran I.

## 1.4 Penjumlahan dan Pengurangan Vektor

Penjumlahan vektor menyatakan penggabungan pengaruh dua atau lebih vektor. Secara geometris, penjumlahan dapat dilakukan dengan metode segitiga atau jajar genjang. Secara analitik, penjumlahan dilakukan dengan menjumlahkan komponen yang sejenis.

Jika:

$$
\vec{A} = A_x \hat{i} + A_y \hat{j}
$$

$$
\vec{B} = B_x \hat{i} + B_y \hat{j}
$$

maka:

$$
\vec{A} + \vec{B} = (A_x + B_x)\hat{i} + (A_y + B_y)\hat{j}
$$

Sedangkan pengurangan vektor didefinisikan sebagai penjumlahan dengan lawan vektornya:

$$
\vec{A} - \vec{B} = \vec{A} + (-\vec{B})
$$

Secara fisika, penjumlahan vektor sangat penting karena banyak besaran bekerja secara simultan. Misalnya, resultan gaya merupakan jumlah vektor dari semua gaya yang bekerja pada benda.

## 1.5 Resultan Vektor Sejajar dan Tegak Lurus

### 1.5.1 Vektor searah atau berlawanan arah
Jika dua vektor berada pada satu garis lurus, resultannya dapat dihitung dengan penjumlahan aljabar biasa. Jika searah, nilainya dijumlahkan; jika berlawanan, nilainya dikurangkan dan arah resultan mengikuti vektor yang lebih besar.

### 1.5.2 Vektor saling tegak lurus
Jika dua vektor saling tegak lurus, besar resultannya adalah:

$$
R = \sqrt{A^2 + B^2}
$$

Arah resultan terhadap salah satu sumbu dapat ditentukan dengan perbandingan trigonometri.

Contoh:
Sebuah benda mengalami perpindahan 6 m ke timur dan 8 m ke utara. Maka besar perpindahan resultan:

$$
R = \sqrt{6^2 + 8^2} = 10 \text{ m}
$$

## 1.6 Uraian Vektor ke Komponen

Sering kali sebuah vektor diketahui besar dan arahnya, tetapi yang dibutuhkan adalah komponennya. Jika vektor $\vec{A}$ membentuk sudut $\theta$ terhadap sumbu-$x$ positif, maka:

$$
A_x = A \cos \theta
$$

$$
A_y = A \sin \theta
$$

Penguraian ini sangat penting karena hukum-hukum fisika biasanya lebih mudah diterapkan pada masing-masing sumbu. Dalam analisis gaya pada bidang miring, misalnya, gaya berat sering diuraikan menjadi komponen sejajar dan tegak lurus bidang.

Contoh:
Sebuah gaya 20 N membentuk sudut 37° terhadap horizontal. Komponennya adalah:

$$
F_x = 20 \cos 37^\circ \approx 16 \text{ N}
$$

$$
F_y = 20 \sin 37^\circ \approx 12 \text{ N}
$$

## 1.7 Vektor Satuan

Vektor satuan adalah vektor yang besarnya 1 dan hanya menunjukkan arah. Pada koordinat Kartesius digunakan:
- $\hat{i}$ untuk arah sumbu-$x$ positif,
- $\hat{j}$ untuk arah sumbu-$y$ positif,
- $\hat{k}$ untuk arah sumbu-$z$ positif.

Jika sebuah vektor $\vec{A}$ diketahui, maka vektor satuan searah $\vec{A}$ dapat ditulis sebagai:

$$
\hat{A} = \frac{\vec{A}}{|\vec{A}|}
$$

Konsep ini berguna ketika kita ingin memisahkan informasi arah dari besar vektor.

## 1.8 Tabel Ringkas Operasi Vektor

| Konsep | Bentuk | Makna |
|---|---|---|
| Besar vektor 2D | $|\vec{A}| = \sqrt{A_x^2 + A_y^2}$ | Menentukan panjang vektor dari komponennya |
| Sudut vektor | $\tan \theta = \frac{A_y}{A_x}$ | Menentukan arah vektor |
| Penjumlahan | $\vec{R} = \vec{A} + \vec{B}$ | Menggabungkan dua vektor |
| Pengurangan | $\vec{A} - \vec{B}$ | Selisih dua vektor |
| Komponen sumbu-$x$ | $A_x = A\cos\theta$ | Proyeksi mendatar |
| Komponen sumbu-$y$ | $A_y = A\sin\theta$ | Proyeksi vertikal |
| Vektor satuan | $\hat{A} = \frac{\vec{A}}{|\vec{A}|}$ | Menyatakan arah murni |

## 1.9 Penerapan dalam Fisika

Konsep vektor digunakan hampir di seluruh cabang fisika. Perpindahan, kecepatan, percepatan, gaya, momentum, medan listrik, dan medan magnet semuanya adalah besaran vektor. Tanpa pemahaman vektor, analisis gerak dan gaya akan mudah keliru karena arah tidak dapat diabaikan.

Sebagai ilustrasi, dua gaya masing-masing 10 N yang bekerja berlawanan arah tidak menghasilkan 20 N, melainkan resultan 0 N. Ini menunjukkan bahwa pada besaran vektor, arah sama pentingnya dengan nilai.

## 1.10 Latihan Pemahaman

1. Jelaskan perbedaan besaran skalar dan besaran vektor, lalu berikan masing-masing tiga contoh.
2. Tentukan besar vektor $\vec{A} = 6\hat{i} + 8\hat{j}$.
3. Tentukan arah vektor $\vec{B} = 4\hat{i} + 4\hat{j}$ terhadap sumbu-$x$ positif.
4. Jika $\vec{P} = 2\hat{i} + 3\hat{j}$ dan $\vec{Q} = 5\hat{i} - \hat{j}$, tentukan $\vec{P} + \vec{Q}$.
5. Tentukan $\vec{P} - \vec{Q}$ untuk data pada soal nomor 4.
6. Sebuah gaya 50 N membentuk sudut 53° terhadap horizontal. Tentukan komponennya pada sumbu-$x$ dan sumbu-$y$.
7. Dua perpindahan saling tegak lurus masing-masing 9 m dan 12 m. Tentukan besar resultannya.
8. Mengapa resultan gaya harus dihitung dengan aturan vektor, bukan penjumlahan bilangan biasa?

## Glosarium

- **Besaran skalar**: besaran yang hanya memiliki nilai.
- **Besaran vektor**: besaran yang memiliki nilai dan arah.
- **Resultan**: vektor pengganti dari gabungan dua atau lebih vektor.
- **Komponen vektor**: proyeksi vektor pada sumbu tertentu.
- **Vektor satuan**: vektor dengan besar satu yang menyatakan arah.
- **Kuadran**: daerah pembagian bidang koordinat yang membantu menentukan arah sudut.
