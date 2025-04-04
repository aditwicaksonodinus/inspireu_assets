# Listrik Dinamis (Arus Searah)

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta didik diharapkan mampu:

- Menjelaskan konsep dasar arus listrik dan beda potensial
- Menganalisis hukum Ohm dan faktor-faktor yang mempengaruhi hambatan listrik
- Menghitung kuat arus, tegangan, dan hambatan pada rangkaian listrik sederhana
- Menerapkan hukum Kirchhoff pada rangkaian listrik
- Menganalisis rangkaian seri, paralel, dan kombinasi
- Menghitung energi dan daya listrik dalam kehidupan sehari-hari

## Pendahuluan

Pernahkah kamu bertanya-tanya bagaimana lampu di rumahmu menyala saat saklar ditekan? Atau mengapa ponselmu perlu diisi daya setiap hari? Semua ini berkaitan dengan fenomena listrik dinamis yang menjadi tulang punggung teknologi modern.

Listrik dinamis adalah cabang fisika yang mempelajari muatan listrik yang bergerak (arus listrik). Berbeda dengan listrik statis yang mempelajari muatan diam, listrik dinamis membahas tentang pergerakan elektron yang mengalir melalui konduktor, menciptakan arus yang dapat melakukan berbagai pekerjaan mulai dari menyalakan lampu hingga menggerakkan motor.

Dalam kehidupan sehari-hari, kita sangat bergantung pada listrik dinamis. Hampir seluruh perangkat elektronik yang kita gunakan—dari smartphone hingga kulkas—bekerja berdasarkan prinsip listrik dinamis. Dengan memahami konsep ini, kita dapat menjelaskan mengapa baterai ponsel habis, bagaimana listrik dapat mengalir dalam rangkaian, dan bahkan bagaimana tubuh kita mengirimkan sinyal listrik ke otak!

## Arus Listrik dan Muatan Listrik

Arus listrik adalah aliran muatan listrik yang melewati suatu penghantar dalam selang waktu tertentu. Secara matematis, arus listrik dapat ditulis sebagai:

$$I = \frac{Q}{t}$$

dimana:

- $I$ = kuat arus listrik (ampere, A)
- $Q$ = muatan listrik (coulomb, C)
- $t$ = waktu (sekon, s)

Dalam konduktor logam, arus listrik terjadi karena pergerakan elektron-elektron bebas. Arah arus listrik konvensional mengalir dari potensial tinggi ke potensial rendah (dari kutub positif ke kutub negatif), sedangkan elektron sebenarnya bergerak dari potensial rendah ke potensial tinggi.

## Beda Potensial dan Gaya Gerak Listrik

Beda potensial (tegangan) adalah energi yang diperlukan untuk memindahkan satu satuan muatan listrik dari satu titik ke titik lain. Secara matematis:

$$V = \frac{W}{Q}$$

dimana:

- $V$ = beda potensial (volt, V)
- $W$ = usaha/energi (joule, J)
- $Q$ = muatan listrik (coulomb, C)

Gaya gerak listrik (GGL) adalah beda potensial yang dihasilkan oleh sumber tegangan (seperti baterai) dalam keadaan terbuka (tanpa beban). Sedangkan tegangan jepit adalah beda potensial pada kutub-kutub sumber tegangan saat diberi beban.

## Hukum Ohm

Hukum Ohm menyatakan bahwa kuat arus listrik yang mengalir melalui sebuah penghantar sebanding dengan beda potensial antara ujung-ujung penghantar tersebut. Secara matematis:

$$V = I \times R$$

dimana:

- $V$ = beda potensial (volt, V)
- $I$ = kuat arus listrik (ampere, A)
- $R$ = hambatan listrik (ohm, Ω)

Hambatan suatu konduktor dipengaruhi oleh beberapa faktor yang dapat dinyatakan dengan rumus:

$$R = \rho \frac{L}{A}$$

dimana:

- $R$ = hambatan (ohm, Ω)
- $\rho$ = hambat jenis bahan (ohm.m)
- $L$ = panjang penghantar (m)
- $A$ = luas penampang penghantar ($m^2$)

Hambatan juga dipengaruhi oleh suhu dengan persamaan:

$$R_t = R_0(1 + \alpha \Delta T)$$

dimana:

- $R_t$ = hambatan pada suhu $t$ (ohm, Ω)
- $R_0$ = hambatan pada suhu awal (ohm, Ω)
- $\alpha$ = koefisien suhu hambatan jenis bahan (/°C)
- $\Delta T$ = perubahan suhu (°C)

## Rangkaian Listrik

### Rangkaian Seri

Dalam rangkaian seri, komponen-komponen listrik dihubungkan secara berurutan sehingga arus yang mengalir pada setiap komponen sama besar. Karakteristik rangkaian seri:

- Kuat arus sama di semua titik: $I = I_1 = I_2 = I_3 = ... = I_n$
- Tegangan total adalah jumlah tegangan pada setiap komponen: $V = V_1 + V_2 + V_3 + ... + V_n$
- Hambatan total (ekivalen) adalah jumlah hambatan semua komponen: $R_{total} = R_1 + R_2 + R_3 + ... + R_n$

### Rangkaian Paralel

Dalam rangkaian paralel, komponen-komponen listrik dihubungkan secara bercabang sehingga tegangan pada setiap komponen sama besar. Karakteristik rangkaian paralel:

- Tegangan sama di semua cabang: $V = V_1 = V_2 = V_3 + ... + V_n$
- Arus total adalah jumlah arus pada setiap cabang: $I = I_1 + I_2 + I_3 + ... + I_n$
- Hambatan total (ekivalen) dapat dihitung dengan: $\frac{1}{R_{total}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3} + ... + \frac{1}{R_n}$

### Rangkaian Campuran

Rangkaian campuran adalah kombinasi dari rangkaian seri dan paralel. Untuk menyelesaikan rangkaian campuran, kita perlu menganalisis bagian-bagian rangkaian seri dan paralel secara terpisah, kemudian menggabungkannya.

## Hukum Kirchhoff

### Hukum I Kirchhoff (Hukum Arus)

Hukum I Kirchhoff menyatakan bahwa jumlah kuat arus yang masuk ke suatu titik percabangan sama dengan jumlah kuat arus yang keluar dari titik percabangan tersebut.

$$\sum I_{masuk} = \sum I_{keluar}$$

Atau secara umum:

$$\sum I = 0$$

### Hukum II Kirchhoff (Hukum Tegangan)

Hukum II Kirchhoff menyatakan bahwa dalam suatu rangkaian tertutup, jumlah aljabar dari gaya gerak listrik (GGL) sama dengan jumlah aljabar dari hasil kali kuat arus dan hambatan.

$$\sum \varepsilon = \sum IR$$

Dengan konvensi tanda:

- GGL bertanda positif jika saat melintasi sumber tegangan, arah loop dari kutub negatif ke kutub positif
- Penurunan tegangan $(IR)$ bertanda positif jika arah arus searah dengan arah loop

## Energi dan Daya Listrik

Energi listrik adalah energi yang dihasilkan dari pergerakan elektron. Secara matematis:

$$W = V \times I \times t = I^2 \times R \times t = \frac{V^2}{R} \times t$$

dimana:

- $W$ = energi listrik (joule, J)
- $V$ = beda potensial (volt, V)
- $I$ = kuat arus listrik (ampere, A)
- $R$ = hambatan (ohm, Ω)
- $t$ = waktu (sekon, s)

Daya listrik adalah laju perubahan energi listrik terhadap waktu. Secara matematis:

$$P = \frac{W}{t} = V \times I = I^2 \times R = \frac{V^2}{R}$$

dimana:

- $P$ = daya listrik (watt, W)
- $W$ = energi listrik (joule, J)
- $t$ = waktu (sekon, s)
- $V$ = beda potensial (volt, V)
- $I$ = kuat arus listrik (ampere, A)
- $R$ = hambatan (ohm, Ω)

Dalam kehidupan sehari-hari, energi listrik sering dinyatakan dalam kilowatt-jam (kWh):

$$W_{kWh} = P_{kW} \times t_{jam}$$

## Alat Ukur Listrik

| Alat Ukur | Fungsi | Cara Penggunaan |
|-----------|--------|----------------|
| Amperemeter | Mengukur kuat arus listrik | Dipasang secara seri pada rangkaian |
| Voltmeter | Mengukur beda potensial | Dipasang secara paralel pada komponen yang diukur |
| Ohmmeter | Mengukur hambatan listrik | Dipasang pada komponen yang terlepas dari rangkaian |
| Wattmeter | Mengukur daya listrik | Kumparan arus dipasang seri, kumparan tegangan dipasang paralel |
| Multimeter | Mengukur arus, tegangan, dan hambatan | Sesuaikan selektor dengan besaran yang akan diukur |

## Rangkuman

- Arus listrik adalah aliran muatan listrik yang melewati konduktor, dirumuskan sebagai $I = \frac{Q}{t}$
- Beda potensial adalah energi per satuan muatan, dirumuskan sebagai $V = \frac{W}{Q}$
- Hukum Ohm: beda potensial sebanding dengan kuat arus, $V = I \times R$
- Hambatan dipengaruhi oleh panjang penghantar, luas penampang, jenis bahan, dan suhu
- Rangkaian seri: arus sama, hambatan total adalah jumlah hambatan, $R_{total} = R_1 + R_2 + ... + R_n$
- Rangkaian paralel: tegangan sama, $\frac{1}{R_{total}} = \frac{1}{R_1} + \frac{1}{R_2} + ... + \frac{1}{R_n}$
- Hukum I Kirchhoff: jumlah arus masuk sama dengan jumlah arus keluar, $\sum I = 0$
- Hukum II Kirchhoff: jumlah GGL sama dengan jumlah penurunan tegangan, $\sum \varepsilon = \sum IR$
- Daya listrik: $P = V \times I = I^2 \times R = \frac{V^2}{R}$
- Energi listrik: $W = P \times t = V \times I \times t$
