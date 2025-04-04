# Vektor

## Tujuan Pembelajaran

- Memahami konsep dasar vektor dan perbedaannya dengan besaran skalar
- Menguasai cara menuliskan dan menggambarkan vektor dalam berbagai bentuk
- Melakukan operasi penjumlahan dan pengurangan vektor dengan metode yang berbeda
- Menghitung hasil kali skalar (dot product) dan hasil kali silang (cross product) dari vektor
- Mengaplikasikan konsep vektor dalam pemecahan masalah fisika sehari-hari

## Pendahuluan

Pernahkah kamu memperhatikan pilot pesawat yang harus mempertimbangkan arah angin saat menerbangkan pesawat? Atau pernahkah kamu bermain biliar dan harus memperhitungkan arah pukulan agar bola masuk ke lubang dengan tepat? Kedua contoh tersebut melibatkan besaran yang tidak hanya memiliki nilai tetapi juga arah. Besaran semacam ini disebut dengan **vektor**.

Dalam kehidupan kita, banyak besaran fisika yang ternyata adalah vektor: gaya, kecepatan, percepatan, momentum, medan listrik, dan medan magnet. Inilah mengapa vektor menjadi konsep fundamental dalam fisika yang akan kita eksplorasi secara mendalam pada materi ini.

## Konsep Dasar Vektor

### Definisi Vektor dan Besaran Skalar

**Vektor** adalah besaran fisika yang memiliki nilai (besar) dan arah. Contohnya adalah perpindahan, kecepatan, percepatan, dan gaya.

**Skalar** adalah besaran fisika yang hanya memiliki nilai (besar) tanpa arah. Contohnya adalah jarak, kelajuan, massa, suhu, dan energi.

Untuk membedakan notasi vektor dari skalar, vektor biasanya ditulis dengan huruf yang diberi tanda panah di atasnya $(\vec{A})$ atau huruf tebal (**A**) atau huruf miring (*A*).

### Penulisan Vektor

Vektor dapat dinyatakan dalam beberapa cara:

1. **Notasi Geometri**:
   Dilambangkan dengan anak panah yang memiliki panjang sesuai dengan besar vektor dan arah sesuai dengan arah vektor.

2. **Notasi Aljabar**:
   Dituliskan sebagai kombinasi linear dari vektor satuan. Misalnya, dalam ruang dua dimensi:
   $\vec{A} = A_x \hat{i} + A_y \hat{j}$

   Dalam ruang tiga dimensi:
   $\vec{A} = A_x \hat{i} + A_y \hat{j} + A_z \hat{k}$
   Di mana $\hat{i}$, $\hat{j}$, dan $\hat{k}$ adalah vektor satuan dalam arah sumbu $x$, $y$, dan $z$.

3. **Notasi Komponen**:
Ditulis sebagai pasangan atau tripel bilangan yang menyatakan komponen vektor pada masing-masing sumbu.
 $\vec{A} = (A_x, A_y)$ atau $\vec{A} = (A_x, A_y, A_z)$

### Besar (Magnitudo) Vektor

Besar vektor atau magnitudo vektor dinotasikan dengan $|\vec{A}|$ atau $A$. Dalam ruang dua dimensi:

$$|\vec{A}| = \sqrt{A_x^2 + A_y^2}$$

Dalam ruang tiga dimensi:

$$|\vec{A}| = \sqrt{A_x^2 + A_y^2 + A_z^2}$$

## Operasi Vektor

### Penjumlahan dan Pengurangan Vektor

Penjumlahan dan pengurangan vektor dapat dilakukan dengan beberapa metode:

1. **Metode Segitiga**: Letakkan pangkal vektor kedua pada ujung vektor pertama, lalu hasil penjumlahannya adalah vektor yang menghubungkan pangkal vektor pertama dengan ujung vektor kedua.

2. **Metode Jajargenjang**: Letakkan pangkal kedua vektor pada titik yang sama, lalu bentuk jajargenjang. Hasil penjumlahannya adalah diagonal dari jajargenjang tersebut yang titik pangkalnya sama dengan kedua vektor.

3. **Metode Analitik**: Penjumlahan dan pengurangan vektor dilakukan dengan menjumlahkan atau mengurangkan komponen-komponennya.

   $$\vec{A} + \vec{B} = (A_x + B_x)\hat{i} + (A_y + B_y)\hat{j} + (A_z + B_z)\hat{k}$$

   $$\vec{A} - \vec{B} = (A_x - B_x)\hat{i} + (A_y - B_y)\hat{j} + (A_z - B_z)\hat{k}$$

### Perkalian Vektor dengan Skalar

Perkalian vektor dengan bilangan skalar akan mengubah besar vektor sebanyak nilai skalar tersebut. Jika skalar bernilai negatif, arah vektor akan berkebalikan.

$$c\vec{A} = (cA_x)\hat{i} + (cA_y)\hat{j} + (cA_z)\hat{k}$$

### Hasil Kali Skalar (Dot Product)

Hasil kali skalar antara dua vektor menghasilkan besaran skalar dan didefinisikan sebagai:

$$\vec{A} \cdot \vec{B} = |\vec{A}||\vec{B}|\cos\theta$$

Di mana $\theta$ adalah sudut antara dua vektor tersebut.

Dalam bentuk komponen:
$$\vec{A} \cdot \vec{B} = A_x B_x + A_y B_y + A_z B_z$$

Dot product memiliki sifat komutatif:

$$\vec{A} \cdot \vec{B} = \vec{B} \cdot \vec{A}$$

Dot product sering digunakan untuk menghitung kerja yang dilakukan oleh gaya dan dalam konsep proyeksi vektor.

### Hasil Kali Silang (Cross Product)

Hasil kali silang antara dua vektor menghasilkan vektor baru yang tegak lurus terhadap kedua vektor tersebut. Didefinisikan sebagai:

$$\vec{A} \times \vec{B} = |\vec{A}||\vec{B}|\sin\theta\ \hat{n}$$

Di mana $\hat{n}$ adalah vektor satuan yang tegak lurus terhadap bidang yang dibentuk oleh $\vec{A}$ dan $\vec{B}$ (sesuai kaidah tangan kanan).

Dalam bentuk determinan:

$$\vec{A} \times \vec{B} =
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
A_x & A_y & A_z \\
B_x & B_y & B_z
\end{vmatrix}$$

Yang dapat dihitung sebagai:

$$\vec{A} \times \vec{B} = (A_y B_z - A_z B_y)\hat{i} + (A_z B_x - A_x B_z)\hat{j} + (A_x B_y - A_y B_x)\hat{k}$$

Cross product memiliki sifat anti-komutatif: $$\vec{A} \times \vec{B} = -(\vec{B} \times \vec{A})$$

Cross product digunakan dalam banyak konsep fisika seperti momen gaya (torsi), momen inersia, dan medan magnet.

## Aplikasi Vektor dalam Fisika

### Kinematika

Dalam kinematika, vektor digunakan untuk menggambarkan perpindahan, kecepatan, dan percepatan:

$\vec{v} = \frac{d\vec{r}}{dt}$ dan $\vec{a} = \frac{d\vec{v}}{dt}$

### Dinamika

Dalam dinamika, gaya adalah besaran vektor dan persamaan Hukum II Newton memiliki bentuk:

$\vec{F} = m\vec{a}$

### Usaha dan Energi

Usaha yang dilakukan oleh gaya konstan $\vec{F}$ terhadap perpindahan $\vec{s}$ adalah:

$W = \vec{F} \cdot \vec{s} = |\vec{F}||\vec{s}|\cos\theta = F s \cos\theta$

### Momentum Linear dan Impuls

Momentum linear adalah vektor yang didefinisikan sebagai:

$\vec{p} = m\vec{v}$

Impuls adalah perubahan momentum:

$\vec{I} = \int \vec{F} dt = \Delta\vec{p}$

## Kesimpulan

Vektor merupakan besaran fundamental dalam fisika yang memiliki karakteristik nilai dan arah. Pemahaman tentang vektor menjadi kunci untuk mempelajari banyak konsep fisika lanjutan.

Beberapa poin penting yang perlu diingat:

1. Vektor berbeda dari skalar karena memiliki arah dan besar, sementara skalar hanya memiliki besar.
2. Vektor dapat dijumlahkan, dikurangkan, dan dikalikan dengan cara yang berbeda dari skalar.
3. Operasi vektor seperti hasil kali skalar dan hasil kali silang memiliki makna fisik yang penting dalam berbagai aplikasi.
4. Vektor dapat direpresentasikan dalam berbagai cara: geometri, aljabar, dan komponen.
5. Aplikasi vektor dalam fisika sangat luas, mulai dari mekanika, elektromagnetik, hingga mekanika kuantum.

Pemahaman yang baik tentang vektor akan memudahkan kita dalam mempelajari konsep-konsep fisika yang lebih kompleks dan menerapkannya dalam pemecahan masalah sehari-hari.
