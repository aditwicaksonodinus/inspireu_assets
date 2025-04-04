# Gerak Harmoni Sederhana

## Tujuan Pembelajaran

- Menjelaskan konsep dasar gerak harmoni sederhana
- Mengidentifikasi karakteristik gerak harmoni sederhana
- Menganalisis persamaan matematis gerak harmoni sederhana
- Menghitung besaran-besaran fisis pada gerak harmoni sederhana
- Menerapkan konsep gerak harmoni sederhana dalam penyelesaian masalah
- Mengaitkan gerak harmoni sederhana dengan fenomena dalam kehidupan sehari-hari

## Pendahuluan

Pernahkah kamu memperhatikan gerakan ayunan jam dinding? Atau mungkin mengamati gerakan pegas ketika ditarik dan dilepaskan? Kedua gerakan tersebut merupakan contoh dari **Gerak Harmoni Sederhana (GHS)**, suatu fenomena fisika yang sangat umum ditemukan dalam kehidupan sehari-hari.

Gerak Harmoni Sederhana adalah gerak bolak-balik benda melalui suatu titik kesetimbangan dengan besar dan arah gaya yang sebanding dengan simpangan benda tersebut. GHS merupakan dasar untuk memahami berbagai jenis getaran dan gelombang dalam fisika, mulai dari gelombang bunyi hingga gelombang elektromagnetik. Mari kita eksplorasi konsep menarik ini lebih dalam!

## Konsep Dasar Gerak Harmoni Sederhana

### Pengertian GHS

Gerak Harmoni Sederhana adalah gerak osilasi atau gerak bolak-balik suatu benda di mana gaya pemulih sebanding dengan simpangan dan selalu mengarah ke posisi kesetimbangan. Secara matematis, hubungan ini dinyatakan dengan Hukum Hooke:

$$F = -k \cdot x$$

Dimana:

- $F$ = gaya pemulih (N)
- $k$ = konstanta pegas (N/m)
- $x$ = simpangan dari posisi setimbang (m)
- Tanda negatif menunjukkan arah gaya berlawanan dengan arah simpangan

### Karakteristik GHS

Beberapa besaran fisis yang menandai GHS:

1. **Amplitudo ($A$)**: Simpangan maksimum dari posisi setimbang
2. **Periode ($T$)**: Waktu yang diperlukan untuk melakukan satu getaran lengkap
3. **Frekuensi ($f$)**: Jumlah getaran yang terjadi dalam satu satuan waktu
   $$f = \frac{1}{T}$$
4. **Frekuensi sudut ($\omega$)**: Kecepatan sudut benda
   $$\omega = 2\pi f = \frac{2\pi}{T}$$

### Persamaan GHS

Persamaan posisi benda yang bergerak harmonis sederhana:

$$x(t) = A \sin(\omega t + \phi)$$

dengan $\phi$ adalah sudut fase awal.

Persamaan kecepatan benda:

$$v(t) = \frac{dx}{dt} = \omega A \cos(\omega t + \phi)$$

Persamaan percepatan benda:

$$a(t) = \frac{d^2x}{dt^2} = -\omega^2 A \sin(\omega t + \phi) = -\omega^2 x(t)$$

## Contoh Sistem GHS

### Sistem Pegas-Massa

Ketika sebuah benda bermassa $m$ digantungkan pada pegas dengan konstanta $k$, frekuensi natural sistem adalah:

$$f = \frac{1}{2\pi} \sqrt{\frac{k}{m}}$$

atau periode:

$$T = 2\pi \sqrt{\frac{m}{k}}$$

### Susunan Pegas

Dalam banyak aplikasi praktis, pegas sering disusun dalam konfigurasi tertentu untuk mendapatkan karakteristik elastisitas yang diinginkan.

#### Pegas Seri

Ketika dua atau lebih pegas disusun secara seri (berurutan), konstanta pegas gabungan ($k_{eq}$) dapat dihitung dengan:

$$\frac{1}{k_{eq}} = \frac{1}{k_1} + \frac{1}{k_2} + \frac{1}{k_3} + ... + \frac{1}{k_n}$$

Pada susunan seri, konstanta pegas gabungan selalu lebih kecil dari konstanta pegas terkecil dalam susunan. Ini berarti pegas gabungan menjadi lebih "lunak" dibandingkan pegas-pegas penyusunnya.

#### Pegas Paralel

Ketika pegas disusun secara paralel (berdampingan), konstanta pegas gabungan adalah jumlah dari konstanta masing-masing pegas:

$$k_{eq} = k_1 + k_2 + k_3 + ... + k_n$$

Pada susunan paralel, pegas gabungan menjadi lebih "kaku" dibandingkan pegas-pegas penyusunnya karena nilai konstanta gabungannya lebih besar.

#### Contoh Aplikasi Susunan Pegas

Susunan pegas seri dan paralel banyak diterapkan dalam:

- Sistem suspensi kendaraan
- Desain kasur dan sofa
- Peredam getaran mesin
- Peralatan olahraga seperti trampolin

### Modulus Young dan Pegas

Modulus Young adalah ukuran kekakuan material yang menggambarkan hubungan antara tegangan (stress) dan regangan (strain) dalam batas elastis material. Untuk kawat atau batang, konstanta pegas $k$ dapat dihubungkan dengan Modulus Young ($E$) melalui persamaan:

$$k = \frac{EA}{L}$$

Dimana:

- $E$ = Modulus Young (N/m$^2$)
- $A$ = Luas penampang kawat/batang (m$^2$)
- $L$ = Panjang kawat/batang (m)

Dengan mengetahui hubungan ini, kita dapat:

1. Memilih material yang tepat untuk membuat pegas dengan karakteristik tertentu
2. Menentukan dimensi pegas (panjang dan luas penampang) untuk mendapatkan konstanta pegas yang diinginkan
3. Memprediksi perubahan konstanta pegas akibat perubahan suhu atau faktor lingkungan lain

Beberapa nilai modulus Young untuk material umum:

| Material  | Modulus Young (N/m$^2$)     |
|-----------|----------------------------|
| Baja      | 200 × 10$^9$                |
| Aluminium | 70 × 10$^9$                 |
| Tembaga   | 110 × 10$^9$                |
| Karet     | 0,01-0,1 × 10$^9$           |
| Kayu      | 10-20 × 10$^9$              |
| Kaca      | 70 × 10$^9$                 |
| Plastik   | 1-3 × 10$^9$                 |
| Beton     | 20-30 × 10$^9$               |
| Keramik   | 70-100 × 10$^9$              |
| Kaca keramik | 70-100 × 10$^9$              |

### Bandul Sederhana

Untuk bandul sederhana dengan panjang tali $L$, periode getaran:

$$T = 2\pi \sqrt{\frac{L}{g}}$$

dimana $g$ adalah percepatan gravitasi (9,8 m/s$^2$). Persamaan ini berlaku untuk sudut simpangan yang kecil (< 15°).

## Energi dalam GHS

Dalam GHS terjadi perubahan energi potensial dan energi kinetik secara berkala. Total energi mekanik sistem adalah:

$$E = E_p + E_k = \frac{1}{2}kA^2$$

dengan:

- Energi potensial: $E_p = \frac{1}{2}kx^2$
- Energi kinetik: $E_k = \frac{1}{2}mv^2$

Pada posisi setimbang ($x = 0$), energi potensial minimum (nol) dan energi kinetik maksimum. Pada simpangan maksimum ($x = A$), energi potensial maksimum dan energi kinetik minimum (nol). Energi total tetap konstan selama gerakan.

## Aplikasi GHS dalam Kehidupan

1. **Jam Bandul**: Menggunakan prinsip periode bandul untuk mengukur waktu
2. **Sistem Suspensi Kendaraan**: Menggunakan pegas dan peredam untuk menyerap getaran
3. **Seismograf**: Alat pengukur gempa yang bekerja berdasarkan prinsip GHS
4. **Instrumen Musik**: Getaran senar gitar, biola, atau piano menghasilkan nada yang berbeda
5. **Rangkaian LC**: Dalam elektronika, rangkaian induktor-kapasitor menghasilkan getaran listrik

## Rangkuman Materi

- **Gerak Harmoni Sederhana (GHS)** adalah gerak osilasi dengan gaya pemulih sebanding dengan simpangan ($F = -kx$)
- **Besaran-besaran penting dalam GHS**:
  - Amplitudo ($A$): simpangan maksimum
  - Periode ($T$): waktu untuk satu getaran lengkap
  - Frekuensi ($f = 1/T$): jumlah getaran per satuan waktu
  - Frekuensi sudut ($\omega = 2\pi f$): kecepatan sudut gerak
- **Persamaan GHS**: $x(t) = A \sin(\omega t + \phi)$
- **Periode sistem pegas-massa**: $T = 2\pi \sqrt{\frac{m}{k}}$
- **Periode bandul sederhana**: $T = 2\pi \sqrt{\frac{L}{g}}$
- **Susunan pegas**:
  - Seri: $\frac{1}{k_{eq}} = \frac{1}{k_1} + \frac{1}{k_2} + ... + \frac{1}{k_n}$
  - Paralel: $k_{eq} = k_1 + k_2 + ... + k_n$
- **Energi dalam GHS**: $E = \frac{1}{2}kA^2 = E_p + E_k$
- **Aplikasi GHS** meliputi jam bandul, sistem suspensi, seismograf, instrumen musik, dan rangkaian elektronik
