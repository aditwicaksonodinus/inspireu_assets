# Listrik Bolak Balik (Alternating Current)

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta didik diharapkan mampu:

- Menjelaskan konsep dasar arus listrik bolak-balik (AC)
- Menganalisis karakteristik rangkaian yang mengandung resistor, induktor, dan kapasitor
- Menghitung impedansi dan resonansi dalam rangkaian RLC
- Menganalisis daya pada rangkaian AC
- Menjelaskan prinsip kerja dan aplikasi transformator
- Menerapkan konsep listrik AC untuk menyelesaikan permasalahan sehari-hari

## Pendahuluan

Pernahkah kamu memperhatikan stopkontak di rumahmu? Atau mungkin bertanya-tanya mengapa lampu di rumah bisa menyala tanpa berkedip meskipun listrik yang mengalirinya selalu berubah-ubah? Jawabannya ada pada sistem listrik yang kita gunakan sehari-hari: Listrik Bolak-Balik atau Alternating Current (AC).

Berbeda dengan listrik searah (DC) yang mengalir dalam satu arah konstan, listrik AC memiliki arus yang terus berubah arah secara periodik. Bayangkan seperti gelombang laut yang naik-turun dengan teratur. Sistem ini menjadi tulang punggung infrastruktur listrik modern karena kemampuannya untuk ditransmisikan jarak jauh dengan kehilangan energi minimal.

Saat kamu menyalakan televisi, mengisi daya ponsel, atau menyalakan AC di hari yang panas, kamu memanfaatkan keajaiban listrik bolak-balik. Mari kita jelajahi dunia listrik AC yang menakjubkan ini, mengungkap konsep-konsep fisika yang memungkinkan teknologi modern berfungsi dengan mulus.

## Isi Materi

### Konsep Dasar Listrik Bolak Balik

Listrik bolak-balik (AC) adalah arus listrik yang mengubah arah aliran secara periodik. Pada listrik AC, besar dan arah arus berubah membentuk pola sinusoidal. Secara matematis, arus sebagai fungsi waktu dapat dinyatakan sebagai:

$$i = I_m \sin(\omega t)$$

di mana:

- $i$ = arus sesaat (A)
- $I_m$ = arus maksimum (A)
- $\omega$ = frekuensi sudut ($\omega = 2\pi f$)
- $t$ = waktu (s)

Tegangan AC juga membentuk pola sinusoidal, dinyatakan sebagai:

$$v = V_m \sin(\omega t)$$

di mana:

- $v$ = tegangan sesaat (V)
- $V_m$ = tegangan maksimum (V)

Frekuensi listrik AC di Indonesia adalah 50 Hz, artinya dalam satu detik terjadi 50 siklus lengkap perubahan arah arus.

### Komponen Dalam Rangkaian AC

#### 1. Resistor dalam Rangkaian AC

Resistor bersifat sama pada rangkaian AC maupun DC. Hubungan tegangan dan arus pada resistor mengikuti Hukum Ohm:

$$v_R = R \cdot i$$

Dalam rangkaian AC, tegangan dan arus pada resistor sefase.

#### 2. Induktor dalam Rangkaian AC

Induktor menyimpan energi dalam bentuk medan magnet. Ketika dialiri arus AC, induktor menghasilkan GGL induksi yang melawan perubahan arus. Hubungan tegangan dan arus pada induktor adalah:

$$v_L = L \cdot \frac{di}{dt}$$

Untuk arus sinusoidal, tegangan pada induktor adalah:

$$v_L = L \omega I_m \sin(\omega t + 90°)$$

Ini menunjukkan bahwa tegangan mendahului arus sebesar 90° pada induktor.

Reaktansi induktif didefinisikan sebagai:

$$X_L = \omega L = 2\pi f L$$

di mana $X_L$ adalah reaktansi induktif dalam ohm (Ω).

#### 3. Kapasitor dalam Rangkaian AC

Kapasitor menyimpan energi dalam bentuk medan listrik. Hubungan tegangan dan arus pada kapasitor adalah:

$$i = C \cdot \frac{dv}{dt}$$

Untuk tegangan sinusoidal, arus pada kapasitor adalah:

$$i = C \omega V_m \sin(\omega t + 90°)$$

Ini menunjukkan bahwa arus mendahului tegangan sebesar 90° pada kapasitor.

Reaktansi kapasitif didefinisikan sebagai:

$$X_C = \frac{1}{\omega C} = \frac{1}{2\pi f C}$$

di mana $X_C$ adalah reaktansi kapasitif dalam ohm (Ω).

### Rangkaian RLC Seri

Rangkaian RLC seri terdiri dari resistor, induktor, dan kapasitor yang tersusun secara seri. Impedansi total rangkaian adalah:

$$Z = \sqrt{R^2 + (X_L - X_C)^2}$$

Sudut fase antara tegangan dan arus:

$$\phi = \tan^{-1}\left(\frac{X_L - X_C}{R}\right)$$

Jika $X_L > X_C$, rangkaian bersifat induktif dan arus tertinggal dari tegangan.
Jika $X_L < X_C$, rangkaian bersifat kapasitif dan arus mendahului tegangan.
Jika $X_L = X_C$, terjadi resonansi dan rangkaian bersifat resistif murni.

### Resonansi

Resonansi terjadi ketika $X_L = X_C$, sehingga:

$$\omega L = \frac{1}{\omega C}$$

Frekuensi resonansi dapat dihitung dengan:

$$f_r = \frac{1}{2\pi\sqrt{LC}}$$

Pada saat resonansi:

- Impedansi rangkaian minimum (sama dengan R)
- Arus maksimum
- Tegangan dan arus sefase

### Daya pada Rangkaian AC

Terdapat tiga jenis daya dalam rangkaian AC:

1. Daya nyata (real power) - diukur dalam watt (W):
   $$P = V_{rms} \cdot I_{rms} \cdot \cos\phi$$

2. Daya reaktif - diukur dalam volt-ampere reaktif (VAR):
   $$Q = V_{rms} \cdot I_{rms} \cdot \sin\phi$$

3. Daya semu (apparent power) - diukur dalam volt-ampere (VA):
   $$S = V_{rms} \cdot I_{rms}$$

Hubungan ketiganya dinyatakan dalam segitiga daya:

$$S^2 = P^2 + Q^2$$

Faktor daya didefinisikan sebagai:

$$\text{Faktor daya} = \cos\phi = \frac{P}{S}$$

Faktor daya bernilai 1 untuk rangkaian resistif murni, dan makin kecil ketika komponen reaktif (induktif atau kapasitif) makin dominan.

### Transformator

Transformator adalah perangkat yang menggunakan prinsip induksi elektromagnetik untuk mengubah tegangan AC dari satu nilai ke nilai lain.

#### Prinsip Kerja Transformator

Transformator terdiri dari dua kumparan (primer dan sekunder) yang dililitkan pada inti besi. Ketika kumparan primer dialiri arus AC, timbul medan magnet yang berubah-ubah pada inti besi. Perubahan medan magnet ini menginduksi tegangan pada kumparan sekunder.

Perbandingan tegangan primer dan sekunder bergantung pada jumlah lilitan:

$$\frac{V_s}{V_p} = \frac{N_s}{N_p}$$

di mana:

- $V_s$ = tegangan sekunder (V)
- $V_p$ = tegangan primer (V)
- $N_s$ = jumlah lilitan sekunder
- $N_p$ = jumlah lilitan primer

Untuk transformator ideal (tanpa rugi-rugi):

$$V_p \cdot I_p = V_s \cdot I_s$$

Sehingga:

$$\frac{I_s}{I_p} = \frac{N_p}{N_s}$$

#### Jenis Transformator

| Jenis Transformator | Perbandingan Lilitan | Fungsi |
|---------------------|----------------------|--------|
| Step-up | $N_s > N_p$ | Menaikkan tegangan, menurunkan arus |
| Step-down | $N_s < N_p$ | Menurunkan tegangan, menaikkan arus |
| Isolasi | $N_s = N_p$ | Memisahkan rangkaian secara elektrik tanpa mengubah tegangan |

#### Efisiensi Transformator

Efisiensi transformator dinyatakan sebagai:

$$\eta = \frac{P_{out}}{P_{in}} \times 100\%$$

Rugi-rugi pada transformator meliputi:

- Rugi inti (hysteresis dan arus eddy)
- Rugi tembaga (hambatan kawat)
- Rugi fluks bocor

### Aplikasi Listrik AC dalam Kehidupan

1. **Distribusi Listrik**: Sistem transmisi daya listrik jarak jauh menggunakan AC karena tegangan dapat dinaikkan/diturunkan dengan transformator.

2. **Peralatan Rumah Tangga**: Hampir semua perangkat elektronik rumah tangga menggunakan listrik AC (kulkas, AC, mesin cuci).

3. **Industri**: Motor AC digunakan luas di industri karena efisiensi dan kehandalannya.

4. **Sistem Komunikasi**: Pemancar radio menggunakan prinsip resonansi rangkaian RLC.

## Rangkuman

- **Listrik Bolak-Balik (AC)** adalah arus listrik yang berubah arah secara periodik dengan pola sinusoidal.

- **Komponen dalam rangkaian AC**:
  - **Resistor**: Tegangan dan arus sefase
  - **Induktor**: Tegangan mendahului arus sebesar 90°, $X_L = \omega L$
  - **Kapasitor**: Arus mendahului tegangan sebesar 90°, $X_C = \frac{1}{\omega C}$

- **Impedansi** adalah hambatan total dalam rangkaian AC, bergantung pada resistansi dan reaktansi: $Z = \sqrt{R^2 + (X_L - X_C)^2}$

- **Resonansi** terjadi ketika $X_L = X_C$, menghasilkan impedansi minimum dan arus maksimum pada frekuensi $f_r = \frac{1}{2\pi\sqrt{LC}}$

- **Daya AC** terdiri dari tiga jenis:
  - Daya nyata (P) dalam watt
  - Daya reaktif (Q) dalam VAR
  - Daya semu (S) dalam VA
  - Faktor daya = $\cos\phi = \frac{P}{S}$

- **Transformator** bekerja berdasarkan prinsip induksi elektromagnetik untuk mengubah level tegangan AC:
  - $\frac{V_s}{V_p} = \frac{N_s}{N_p}$
  - Tipe: step-up, step-down, dan isolasi

Listrik AC menjadi dasar sistem kelistrikan modern karena kemampuannya untuk ditransmisikan jarak jauh dengan efisiensi tinggi melalui penggunaan transformator.
