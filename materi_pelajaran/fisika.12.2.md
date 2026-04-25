Materi ini membahas rangkaian arus searah sebagai dasar analisis aliran muatan listrik pada penghantar. Pada bab ini kamu akan mempelajari arus, tegangan, hambatan, Hukum Ohm, susunan resistor, hukum Kirchhoff, serta energi dan daya listrik yang sangat penting dalam kehidupan sehari-hari maupun teknologi.

# Rangkaian Arus Searah

## Tujuan Pembelajaran
Setelah mempelajari bab ini, kamu diharapkan mampu:
1. Menjelaskan pengertian arus listrik, beda potensial, dan hambatan.
2. Menggunakan Hukum Ohm untuk menganalisis rangkaian sederhana.
3. Menentukan hambatan pengganti pada rangkaian seri dan paralel.
4. Menerapkan hukum Kirchhoff pada rangkaian yang lebih kompleks.
5. Menghitung energi listrik dan daya listrik.
6. Menafsirkan penerapan rangkaian arus searah pada peralatan sehari-hari.

## 2.1 Arus, Tegangan, dan Hambatan

Arus listrik adalah laju aliran muatan listrik melalui suatu penghantar. Jika sejumlah muatan $Q$ mengalir dalam waktu $t$, maka arus listrik dinyatakan dengan:

$$
I = \frac{Q}{t}
$$

Satuan arus adalah ampere $(A)$. Beda potensial atau tegangan menyatakan energi per satuan muatan yang mendorong muatan bergerak dalam rangkaian. Hambatan listrik menyatakan ukuran kesulitan arus mengalir melalui bahan.

Pada penghantar homogen, hambatan dipengaruhi oleh panjang, luas penampang, dan jenis bahan.

$$
R = \rho \frac{L}{A}
$$

Dengan demikian, kawat yang lebih panjang memiliki hambatan lebih besar, sedangkan kawat dengan luas penampang lebih besar memiliki hambatan lebih kecil.

## 2.2 Hukum Ohm

Hukum Ohm menyatakan bahwa kuat arus yang mengalir pada penghantar sebanding dengan beda potensial di ujung-ujung penghantar dan berbanding terbalik dengan hambatannya.

$$
V = IR
$$

Rumus ini adalah dasar utama dalam analisis rangkaian listrik sederhana. Jika dua dari tiga besaran diketahui, besaran ketiga dapat ditentukan.

### 2.2.1 Contoh Soal

Sebuah resistor $6\ \Omega$ dipasang pada sumber tegangan $12\ V$. Tentukan arus yang mengalir.

Penyelesaian:
$$
I = \frac{V}{R} = \frac{12}{6} = 2\ A
$$

Jadi arus yang mengalir adalah $2\ A$.

## 2.3 Rangkaian Seri dan Paralel

Dalam rangkaian seri, komponen disusun berurutan pada satu jalur arus. Akibatnya, arus yang mengalir pada setiap resistor sama, tetapi beda potensial dapat berbeda-beda.

Hambatan pengganti pada rangkaian seri adalah jumlah seluruh hambatan:

$$
R_s = R_1 + R_2 + R_3 + \cdots
$$

Dalam rangkaian paralel, komponen dihubungkan pada cabang-cabang yang memiliki dua titik ujung sama. Pada susunan ini, beda potensial pada setiap cabang sama, tetapi arus dapat berbeda.

Hambatan pengganti pada rangkaian paralel memenuhi:

$$
\frac{1}{R_p} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3} + \cdots
$$

### 2.3.1 Ringkasan Perbandingan

| Besaran | Rangkaian Seri | Rangkaian Paralel |
|---|---|---|
| Arus | Sama di setiap komponen | Terbagi pada tiap cabang |
| Tegangan | Terbagi pada tiap komponen | Sama di setiap cabang |
| Hambatan pengganti | Lebih besar dari hambatan tunggal terbesar | Lebih kecil dari hambatan tunggal terkecil |

## 2.4 Hukum Kirchhoff

Untuk rangkaian yang lebih kompleks, Hukum Ohm saja belum cukup. Diperlukan hukum Kirchhoff untuk menganalisis titik cabang dan lintasan tertutup.

### 2.4.1 Hukum Kirchhoff I

Jumlah arus yang masuk ke suatu titik cabang sama dengan jumlah arus yang keluar dari titik tersebut.

$$
\sum I_{masuk} = \sum I_{keluar}
$$

Hukum ini merupakan bentuk kekekalan muatan listrik.

### 2.4.2 Hukum Kirchhoff II

Jumlah aljabar perubahan potensial dalam satu lintasan tertutup sama dengan nol.

$$
\sum \Delta V = 0
$$

Hukum ini menyatakan kekekalan energi dalam rangkaian tertutup.

## 2.5 GGL dan Hambatan Dalam

Sumber tegangan nyata seperti baterai memiliki gaya gerak listrik $(\mathcal{E})$ dan hambatan dalam $r$. Tegangan terminal yang terukur pada baterai saat arus mengalir diberikan oleh:

$$
V = \mathcal{E} - Ir
$$

Akibat adanya hambatan dalam, tegangan pada terminal baterai lebih kecil daripada GGL-nya ketika baterai digunakan.

## 2.6 Energi dan Daya Listrik

Energi listrik yang digunakan alat listrik dalam selang waktu tertentu dinyatakan oleh:

$$
W = VIt
$$

Daya listrik menyatakan laju penggunaan energi listrik.

$$
P = \frac{W}{t} = VI
$$

Dengan menggabungkan Hukum Ohm, daya juga dapat ditulis sebagai:

$$
P = I^2R
$$

atau

$$
P = \frac{V^2}{R}
$$

Rumus-rumus ini sangat berguna dalam menghitung konsumsi energi peralatan rumah tangga.

## 2.7 Langkah Analisis Rangkaian

Saat menghadapi soal rangkaian arus searah, lakukan langkah berikut:
1. Identifikasi jenis susunan komponen, apakah seri, paralel, atau campuran.
2. Tentukan hambatan pengganti bila memungkinkan.
3. Gunakan Hukum Ohm untuk mencari arus atau tegangan.
4. Untuk rangkaian bercabang atau memiliki lebih dari satu sumber, gunakan hukum Kirchhoff.
5. Setelah itu, hitung daya atau energi jika diminta.

Pendekatan bertahap ini membantu membangun pemahaman dari struktur rangkaian ke analisis kuantitatif.

## 2.8 Penerapan dalam Kehidupan

Lampu rumah, senter, rangkaian baterai, adaptor, dan sistem kelistrikan kendaraan merupakan contoh penerapan rangkaian arus searah. Instalasi rumah umumnya dirancang menyerupai paralel agar tiap alat dapat bekerja independen. Pemahaman tentang arus dan daya juga penting agar penggunaan peralatan listrik aman dan efisien.

## 2.9 Latihan Pemahaman

1. Jelaskan perbedaan arus listrik dan beda potensial.
2. Sebuah penghantar memiliki hambatan $10\ \Omega$ dan diberi tegangan $20\ V$. Hitung arusnya.
3. Tiga resistor masing-masing $2\ \Omega$, $3\ \Omega$, dan $5\ \Omega$ disusun seri. Hitung hambatan penggantinya.
4. Dua resistor $6\ \Omega$ dan $3\ \Omega$ disusun paralel. Hitung hambatan penggantinya.
5. Sebuah alat bekerja pada tegangan $12\ V$ dan arus $2\ A$. Hitung dayanya.
6. Jelaskan makna fisik Hukum Kirchhoff I.
7. Tuliskan persamaan tegangan terminal pada sumber yang memiliki hambatan dalam.
8. Mengapa instalasi listrik rumah lebih sesuai disusun paralel daripada seri?

## Glosarium

- **Arus listrik**: aliran muatan listrik per satuan waktu.
- **Tegangan**: energi per satuan muatan yang mendorong arus.
- **Hambatan**: ukuran penghalang terhadap aliran arus listrik.
- **Hukum Ohm**: hubungan antara tegangan, arus, dan hambatan.
- **Hukum Kirchhoff**: hukum kekekalan muatan dan energi pada rangkaian listrik.
- **Daya listrik**: laju penggunaan energi listrik.
- **GGL**: energi per satuan muatan yang disediakan sumber listrik.
