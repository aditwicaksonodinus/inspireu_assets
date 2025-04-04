# Kinetik Gas dan Termodinamika

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta didik diharapkan mampu:

1. Menjelaskan konsep dasar teori kinetik gas dan termodinamika
2. Menganalisis sifat-sifat gas ideal berdasarkan teori kinetik gas
3. Menerapkan persamaan keadaan gas ideal dalam pemecahan masalah
4. Mengidentifikasi proses-proses termodinamika dan hukum-hukumnya
5. Menghitung usaha, kalor, dan perubahan energi dalam dalam proses termodinamika
6. Menganalisis efisiensi mesin kalor berdasarkan hukum termodinamika kedua

## Pendahuluan

Pernahkah kamu memperhatikan uap yang keluar dari cerek yang mendidih? Atau bagaimana ban sepeda mengembang saat dipompa? Fenomena sehari-hari ini berhubungan erat dengan konsep kinetik gas dan termodinamika. Bayangkan saja, setiap kali kamu memasak dengan panci presto atau menyalakan mesin kendaraan, kamu sedang menyaksikan prinsip-prinsip termodinamika dalam aksi!

Kinetik gas dan termodinamika adalah cabang fisika yang mempelajari hubungan antara panas, energi, dan kerja. Ilmu ini menjadi landasan dari berbagai teknologi modern—dari mesin pembangkit listrik hingga sistem pendingin di lemari es. Bahkan tubuh kita sendiri beroperasi mengikuti hukum-hukum termodinamika, mengubah energi dari makanan menjadi gerakan dan panas.

Dalam materi ini, kita akan menjelajahi dunia mikroskopis gas—bagaimana partikel-partikel kecil yang tak terlihat bergerak dan berinteraksi—hingga dampak makroskopisnya yang dapat kita amati dan manfaatkan dalam kehidupan sehari-hari.

## Teori Kinetik Gas

### Asumsi Dasar Teori Kinetik Gas

Teori kinetik gas didasarkan pada beberapa asumsi berikut:

1. Gas terdiri dari partikel-partikel yang sangat kecil (molekul-molekul)
2. Molekul gas bergerak secara acak dengan kecepatan tinggi
3. Jarak antar molekul jauh lebih besar dibandingkan ukuran molekul
4. Tumbukan antar molekul dan dengan dinding wadah bersifat elastik sempurna
5. Tidak ada gaya tarik menarik antar molekul kecuali saat tumbukan
6. Energi total gas hanya bergantung pada suhu

### Gas Ideal

Gas ideal adalah model teoritis gas yang memenuhi semua asumsi teori kinetik gas. Persamaan keadaan gas ideal dinyatakan dalam:

$$PV = nRT$$

Dengan:

- $P$ = tekanan gas (Pa)
- $V$ = volume gas ($\text{m}^3$)
- $n$ = jumlah mol gas (mol)
- $R$ = konstanta gas universal ($8,314$ J/mol·K)
- $T$ = suhu mutlak (K)

Persamaan ini juga dapat ditulis dalam bentuk:

$$PV = NkT$$

Dengan:

- $N$ = jumlah partikel gas
- $k$ = konstanta Boltzmann ($1,38 \times 10^{-23}$ J/K)

### Energi Kinetik Molekul Gas

Energi kinetik rata-rata molekul gas ideal berhubungan langsung dengan suhu gas:

$$\bar{E_k} = \frac{3}{2}kT$$

Untuk gas yang terdiri dari $N$ molekul, energi kinetik totalnya adalah:

$$E_k = \frac{3}{2}NkT = \frac{3}{2}nRT$$

### Kecepatan Molekul Gas

Dalam teori kinetik gas, terdapat tiga jenis kecepatan yang sering digunakan:

1. Kecepatan rata-rata ($\bar{v}$):

   $$\bar{v} = \sqrt{\frac{8RT}{\pi M}}$$

2. Kecepatan efektif/akar rata-rata kuadrat ($v_{rms}$):

   $$v_{rms} = \sqrt{\frac{3RT}{M}} = \sqrt{\frac{3kT}{m}}$$

3. Kecepatan paling mungkin ($v_p$):

   $$v_p = \sqrt{\frac{2RT}{M}}$$

Dengan:

- $M$ = massa molar gas (kg/mol)
- $m$ = massa molekul gas (kg)

## Termodinamika

### Sistem Termodinamika

Sistem termodinamika adalah bagian dari alam semesta yang menjadi objek penelitian. Sistem termodinamika dapat dibedakan menjadi:

1. Sistem tertutup: dapat bertukar energi tetapi tidak dapat bertukar materi dengan lingkungan
2. Sistem terbuka: dapat bertukar energi dan materi dengan lingkungan
3. Sistem terisolasi: tidak dapat bertukar energi maupun materi dengan lingkungan

### Usaha dalam Termodinamika

Usaha yang dilakukan oleh gas saat mengalami perubahan volume dinyatakan oleh:

$$W = \int_{V_1}^{V_2} P \, dV$$

Untuk proses dengan tekanan tetap (isobarik):

$$W = P(V_2 - V_1) = P\Delta V$$

### Hukum Pertama Termodinamika

Hukum pertama termodinamika adalah bentuk dari hukum kekekalan energi:

$$\Delta U = Q - W$$

Dengan:

- $\Delta U$ = perubahan energi dalam sistem
- $Q$ = kalor yang diterima sistem
- $W$ = usaha yang dilakukan oleh sistem

Untuk gas ideal, perubahan energi dalam hanya bergantung pada perubahan suhu:

$$\Delta U = nC_V\Delta T$$

Dengan $C_V$ adalah kapasitas kalor pada volume tetap.

### Proses Termodinamika

#### 1. Proses Isotermal (T konstan)

Pada proses isotermal, suhu gas tetap sehingga $\Delta U = 0$. Berdasarkan hukum pertama termodinamika:

$$Q = W = nRT \ln\frac{V_2}{V_1} = nRT \ln\frac{P_1}{P_2}$$

#### 2. Proses Isobarik (P konstan)

Pada proses isobarik, tekanan tetap sehingga:

$$W = P\Delta V = nR\Delta T$$
$$Q = nC_P\Delta T$$
$$\Delta U = nC_V\Delta T$$

Dengan $C_P$ adalah kapasitas kalor pada tekanan tetap.

#### 3. Proses Isokhorik (V konstan)

Pada proses isokhorik, volume tetap sehingga $W = 0$. Maka:

$$Q = \Delta U = nC_V\Delta T$$

#### 4. Proses Adiabatik (Q = 0)

Pada proses adiabatik, tidak ada pertukaran kalor sehingga:

$$\Delta U = -W$$
$$PV^{\gamma} = \text{konstan}$$
$$TV^{\gamma-1} = \text{konstan}$$

Dengan $\gamma = \frac{C_P}{C_V}$ adalah rasio kapasitas kalor.

### Siklus Termodinamika

Siklus termodinamika adalah serangkaian proses yang membawa sistem kembali ke keadaan awal. Contoh siklus termodinamika yang penting:

#### Siklus Carnot

Siklus Carnot terdiri dari dua proses isotermal dan dua proses adiabatik. Efisiensi siklus Carnot adalah:

$$\eta_C = 1 - \frac{T_C}{T_H}$$

Dengan:

- $T_H$ = suhu reservoir panas (K)
- $T_C$ = suhu reservoir dingin (K)

Siklus Carnot merupakan siklus termodinamika paling efisien yang dapat beroperasi antara dua suhu.

| Mesin Kalor | Proses | Efisiensi Maksimum |
|-------------|--------|-------------------|
| Carnot | 2 isotermal, 2 adiabatik | $\eta_C = 1 - \frac{T_C}{T_H}$ |
| Otto (mesin bensin) | 2 adiabatik, 2 isokhorik | $\eta_O = 1 - \frac{1}{r^{\gamma-1}}$ |
| Diesel | 2 adiabatik, 1 isobarik, 1 isokhorik | $\eta_D = 1 - \frac{1}{r^{\gamma}} \left(\frac{r_c^{\gamma} - 1}{\gamma(r_c - 1)}\right)$ |

Dengan $r$ adalah rasio kompresi dan $r_c$ adalah rasio cut-off.

### Hukum Kedua Termodinamika

Hukum kedua termodinamika berhubungan dengan arah aliran kalor dan entropi. Beberapa pernyataan hukum kedua termodinamika:

1. Pernyataan Kelvin-Planck: Tidak mungkin membuat mesin kalor yang bekerja dalam siklus yang hanya menyerap kalor dari reservoir dan mengubahnya seluruhnya menjadi usaha.

2. Pernyataan Clausius: Tidak mungkin membuat mesin kalor yang bekerja dalam siklus yang memindahkan kalor dari benda bersuhu rendah ke benda bersuhu tinggi tanpa memerlukan usaha dari luar.

### Entropi

Entropi ($S$) adalah ukuran ketidakteraturan atau ketidakpastian sistem. Perubahan entropi didefinisikan sebagai:

$$\Delta S = \int \frac{dQ_{rev}}{T}$$

Untuk proses reversibel. Untuk gas ideal:

$$\Delta S = nC_V \ln\frac{T_2}{T_1} + nR \ln\frac{V_2}{V_1}$$

atau

$$\Delta S = nC_P \ln\frac{T_2}{T_1} - nR \ln\frac{P_2}{P_1}$$

Hukum kedua termodinamika juga dapat dinyatakan dalam bentuk entropi: entropi total alam semesta selalu meningkat dalam proses irreversibel dan tetap dalam proses reversibel.

## Rangkuman Materi

1. **Teori Kinetik Gas**
   - Gas terdiri dari partikel-partikel kecil yang bergerak acak
   - Gas ideal memenuhi persamaan $PV = nRT$
   - Energi kinetik rata-rata molekul gas: $\bar{E_k} = \frac{3}{2}kT$
   - Kecepatan efektif (rms) molekul gas: $v_{rms} = \sqrt{\frac{3RT}{M}}$

2. **Hukum Pertama Termodinamika**
   - Bentuk dari hukum kekekalan energi: $\Delta U = Q - W$
   - Untuk gas ideal: $\Delta U = nC_V\Delta T$
   - Usaha oleh gas pada tekanan tetap: $W = P\Delta V$

3. **Proses Termodinamika**
   - Isotermal (T konstan): $PV = \text{konstan}$, $\Delta U = 0$
   - Isobarik (P konstan): $\frac{V}{T} = \text{konstan}$
   - Isokhorik (V konstan): $\frac{P}{T} = \text{konstan}$, $W = 0$
   - Adiabatik (Q = 0): $PV^{\gamma} = \text{konstan}$

4. **Hukum Kedua Termodinamika**
   - Menentukan arah proses alami
   - Kalor mengalir secara spontan dari suhu tinggi ke suhu rendah
   - Entropi alam semesta selalu meningkat dalam proses irreversibel
   - Efisiensi mesin kalor tidak pernah 100%
   - Efisiensi maksimum mesin Carnot: $\eta_C = 1 - \frac{T_C}{T_H}$

5. **Entropi**
   - Ukuran ketidakteraturan sistem
   - Perubahan entropi: $\Delta S = \int \frac{dQ_{rev}}{T}$
   - Untuk gas ideal: $\Delta S = nC_V \ln\frac{T_2}{T_1} + nR \ln\frac{V_2}{V_1}$
