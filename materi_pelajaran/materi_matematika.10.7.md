# Peluang

## Tujuan Pembelajaran

Setelah mempelajari materi ini, diharapkan peserta didik dapat:

1. Memahami konsep dasar peluang dan percobaan acak
2. Menentukan ruang sampel dan kejadian dalam percobaan acak
3. Menghitung peluang teoritis suatu kejadian
4. Membedakan peluang teoritis dan peluang empiris
5. Menerapkan konsep peluang dalam kehidupan sehari-hari

## Pendahuluan

Pernahkah kamu bermain ular tangga atau monopoli dan berharap mendapatkan angka tertentu saat melempar dadu? Atau mungkin bertanya-tanya berapa peluang hujan besok berdasarkan prakiraan cuaca? Selamat datang di dunia peluang, cabang matematika yang mempelajari kemungkinan terjadinya suatu kejadian.

Peluang hadir dalam berbagai aspek kehidupan kita sehari-hari—dari permainan kartu dan undian lotre hingga keputusan ekonomi, medis, dan asuransi. Saat kamu mempertimbangkan risiko sebuah investasi, menentukan kemungkinan sukses dalam bisnis, atau bahkan saat dokter menentukan diagnosis, mereka menggunakan konsep peluang.

Pada materi ini, kita akan menjelajahi bagaimana matematika membantu mengukur ketidakpastian dan memprediksi kemungkinan suatu kejadian terjadi. Mari kita mulai petualangan dalam dunia peluang yang menarik ini!

## Isi Materi

### Konsep Dasar Peluang

Peluang adalah ukuran numerik yang menunjukkan kemungkinan terjadinya suatu kejadian, dengan nilai mulai dari 0 (mustahil terjadi) hingga 1 (pasti terjadi). Peluang erat kaitannya dengan percobaan acak dan ruang sampel.

**Percobaan Acak** adalah kegiatan yang hasilnya tidak dapat diprediksi dengan pasti sebelumnya.

Contoh percobaan acak:

- Melempar sebuah dadu
- Melempar koin
- Mengambil kartu dari setumpuk kartu bridge

**Ruang Sampel** adalah himpunan semua hasil yang mungkin dari suatu percobaan acak. Dilambangkan dengan $S$.

Contoh:

- Ruang sampel dari pelemparan satu dadu adalah $S = \{1, 2, 3, 4, 5, 6\}$
- Ruang sampel dari pelemparan satu koin adalah $S = \{\text{Angka}, \text{Gambar}\}$

**Kejadian** adalah himpunan bagian dari ruang sampel. Dilambangkan dengan $A$.

Contoh:

- Kejadian munculnya angka genap pada pelemparan dadu adalah $A = \{2, 4, 6\}$

### Peluang Teoritis

Peluang teoritis suatu kejadian $A$ didefinisikan sebagai perbandingan antara banyaknya anggota kejadian $A$ dengan banyaknya anggota ruang sampel $S$.

$$P(A) = \frac{n(A)}{n(S)}$$

dimana:

- $P(A)$ = peluang kejadian $A$
- $n(A)$ = banyaknya anggota kejadian $A$
- $n(S)$ = banyaknya anggota ruang sampel $S$

Contoh:
Peluang munculnya angka genap pada pelemparan sebuah dadu.

- $S = \{1, 2, 3, 4, 5, 6\}$, maka $n(S) = 6$
- $A = \{2, 4, 6\}$, maka $n(A) = 3$
- $P(A) = \frac{n(A)}{n(S)} = \frac{3}{6} = \frac{1}{2} = 0,5$

### Peluang Empiris

Peluang empiris didasarkan pada percobaan yang dilakukan berulang kali. Peluang empiris kejadian $A$ didefinisikan sebagai perbandingan banyaknya kejadian $A$ muncul dengan banyaknya percobaan yang dilakukan.

$$P(A) = \frac{\text{frekuensi kejadian } A}{\text{banyaknya percobaan}}$$

Contoh:
Jika sebuah dadu dilempar 100 kali dan angka genap muncul 48 kali, maka peluang empiris munculnya angka genap adalah:

$$P(\text{angka genap}) = \frac{48}{100} = 0,48$$

### Aturan Penjumlahan Peluang

#### 1. Kejadian Saling Lepas (Mutually Exclusive)

Dua kejadian $A$ dan $B$ dikatakan saling lepas jika kedua kejadian tersebut tidak dapat terjadi bersamaan, artinya $A \cap B = \emptyset$.

Untuk kejadian saling lepas, berlaku:

$$P(A \cup B) = P(A) + P(B)$$

Contoh:
Pada pelemparan sebuah dadu, kejadian $A$ adalah munculnya angka ganjil, dan kejadian $B$ adalah munculnya angka genap.

- $A = \{1, 3, 5\}$, $P(A) = \frac{3}{6} = \frac{1}{2}$
- $B = \{2, 4, 6\}$, $P(B) = \frac{3}{6} = \frac{1}{2}$
- $P(A \cup B) = P(A) + P(B) = \frac{1}{2} + \frac{1}{2} = 1$

#### 2. Kejadian Tidak Saling Lepas (Not Mutually Exclusive)

Jika kejadian $A$ dan $B$ tidak saling lepas, maka:

$$P(A \cup B) = P(A) + P(B) - P(A \cap B)$$

Contoh:
Pada pengambilan satu kartu dari seperangkat kartu bridge, kejadian $A$ adalah terambilnya kartu hati, dan kejadian $B$ adalah terambilnya kartu As.

- $P(A) = \frac{13}{52} = \frac{1}{4}$ (13 kartu hati dari 52 kartu)
- $P(B) = \frac{4}{52} = \frac{1}{13}$ (4 kartu As dari 52 kartu)
- $P(A \cap B) = \frac{1}{52}$ (1 kartu As hati dari 52 kartu)
- $P(A \cup B) = P(A) + P(B) - P(A \cap B) = \frac{1}{4} + \frac{1}{13} - \frac{1}{52} = \frac{13}{52} + \frac{4}{52} - \frac{1}{52} = \frac{16}{52} = \frac{4}{13}$

### Aturan Perkalian Peluang

#### 1. Kejadian Saling Bebas (Independent Events)

Dua kejadian $A$ dan $B$ dikatakan saling bebas jika terjadinya kejadian $A$ tidak mempengaruhi peluang terjadinya kejadian $B$.

Untuk kejadian saling bebas, berlaku:

$$P(A \cap B) = P(A) \times P(B)$$

Contoh:
Pada pelemparan dua buah dadu, kejadian $A$ adalah munculnya angka 6 pada dadu pertama, dan kejadian $B$ adalah munculnya angka 5 pada dadu kedua.

- $P(A) = \frac{1}{6}$
- $P(B) = \frac{1}{6}$
- $P(A \cap B) = P(A) \times P(B) = \frac{1}{6} \times \frac{1}{6} = \frac{1}{36}$

#### 2. Kejadian Bersyarat (Conditional Probability)

Peluang bersyarat kejadian $B$ dengan syarat kejadian $A$ telah terjadi dinotasikan dengan $P(B|A)$ dan dirumuskan:

$$P(B|A) = \frac{P(A \cap B)}{P(A)}, P(A) \neq 0$$

Jika kejadian $A$ dan $B$ saling bebas, maka:

$$P(B|A) = P(B)$$

Contoh:
Dari setumpuk kartu bridge, diambil sebuah kartu secara acak. Kejadian $A$ adalah terambilnya kartu berwarna merah, dan kejadian $B$ adalah terambilnya kartu As.

- $P(A) = \frac{26}{52} = \frac{1}{2}$ (26 kartu merah dari 52 kartu)
- $P(A \cap B) = \frac{2}{52} = \frac{1}{26}$ (2 kartu As merah dari 52 kartu)
- $P(B|A) = \frac{P(A \cap B)}{P(A)} = \frac{\frac{1}{26}}{\frac{1}{2}} = \frac{1}{26} \times 2 = \frac{2}{52} = \frac{1}{26}$

### Aplikasi Peluang dalam Kehidupan Sehari-hari

#### 1. Prediksi Cuaca

Meteorolog menggunakan model peluang untuk memprediksi cuaca. Misalnya, "kemungkinan hujan besok adalah 70%" berarti berdasarkan data historis, pada kondisi atmosfer yang serupa, hujan terjadi 70% kali.

#### 2. Asuransi

Perusahaan asuransi menggunakan peluang untuk menentukan premi. Mereka menghitung peluang seseorang mengalami kecelakaan, sakit, atau kematian berdasarkan data statistik.

#### 3. Permainan dan Perjudian

Kasino menggunakan peluang untuk memastikan mereka selalu memiliki keuntungan. Peluang memenangkan lotre sangat kecil, misal peluang memenangkan jackpot lotre 6 dari 49 adalah:

$$P = \frac{1}{\binom{49}{6}} = \frac{1}{13,983,816} \approx 0.0000000715$$

#### 4. Genetika

Peluang digunakan untuk memprediksi kemungkinan anak mewarisi sifat genetik tertentu dari orangtuanya.

| Jenis Gen Orangtua | Peluang Anak Berambut Pirang |
|--------------------|------------------------------|
| Kedua orangtua berambut pirang (resesif homozigot) | 100% |
| Satu orangtua berambut pirang, satu heterozigot | 50% |
| Kedua orangtua heterozigot | 25% |

#### 5. Pengendalian Kualitas

Industri menggunakan peluang untuk memantau kualitas produk. Sampel acak diambil dan diuji untuk menentukan apakah kualitas produksi berada dalam batas yang dapat diterima.

#### 6. Judi (*EDUKASI*)

### 6. Judi dari Perspektif Matematika

Dalam konteks edukasi matematika, permainan judi menawarkan contoh nyata tentang konsep peluang dan keacakan (randomness). Penting untuk dipahami:

- **Prinsip Keacakan**: Permainan judi dirancang berdasarkan peristiwa acak (seperti kartu yang dikocok, dadu yang dilempar, atau putaran roda rolet) yang tidak dapat diprediksi dengan pasti.

- **Expected Value (Nilai Harapan)**: Secara matematis, judi memiliki nilai harapan negatif. Jika $X$ adalah keuntungan dalam permainan judi, maka $E(X) < 0$ untuk pemain.

- **House Edge**: Kasino atau penyelenggara judi merancang permainan dengan "house edge" (keunggulan rumah), yakni persentase matematika yang menjamin keuntungan jangka panjang bagi penyelenggara.

   Contoh: Dalam roulette Amerika dengan 38 angka (0, 00, dan 1-36), peluang menang saat bertaruh pada satu angka adalah $\frac{1}{38}$ ≈ 0.0263, namun pembayaran hanya 35:1. Ini memberikan house edge sekitar 5.26%.

- **Hukum Bilangan Besar**: Semakin banyak percobaan dilakukan, hasil rata-rata akan mendekati nilai harapan. Ini menjelaskan mengapa kasino selalu untung dalam jangka panjang meskipun ada pemain yang menang besar sesekali.

- **Gambler's Fallacy**: Kesalahan berpikir bahwa hasil acak sebelumnya memengaruhi hasil berikutnya. Contoh: meyakini angka 7 "akan segera muncul" pada dadu karena belum muncul dalam beberapa lemparan.

Memahami matematika di balik permainan judi memberikan wawasan penting tentang konsep peluang dan bagaimana keputusan yang bijak harus didasarkan pada pemahaman statistik, bukan pada keberuntungan.

## Rangkuman Materi

1. **Konsep Dasar Peluang**:
   - Peluang mengukur kemungkinan terjadinya suatu kejadian, dengan nilai antara 0 dan 1
   - Ruang sampel ($S$) adalah himpunan semua hasil yang mungkin
   - Kejadian ($A$) adalah himpunan bagian dari ruang sampel

2. **Jenis Peluang**:
   - Peluang teoritis: $P(A) = \frac{n(A)}{n(S)}$
   - Peluang empiris: berdasarkan percobaan berulang

3. **Aturan Penjumlahan**:
   - Kejadian saling lepas: $P(A \cup B) = P(A) + P(B)$
   - Kejadian tidak saling lepas: $P(A \cup B) = P(A) + P(B) - P(A \cap B)$

4. **Aturan Perkalian**:
   - Kejadian saling bebas: $P(A \cap B) = P(A) \times P(B)$
   - Peluang bersyarat: $P(B|A) = \frac{P(A \cap B)}{P(A)}$

5. **Aplikasi Peluang**:
   - Digunakan dalam prediksi cuaca, asuransi, perjudian, genetika, dan pengendalian kualitas
   - Membantu mengambil keputusan dalam situasi ketidakpastian
