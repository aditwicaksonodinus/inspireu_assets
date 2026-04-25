Materi ini membahas fluida, yaitu zat yang dapat mengalir, mencakup cairan dan gas. Dalam fisika SMA, fluida dipelajari melalui sifat dasar seperti massa jenis, tekanan, hukum-hukum pada fluida statis, dan prinsip aliran pada fluida dinamis. Konsep ini sangat dekat dengan kehidupan sehari-hari, mulai dari kapal, pipa air, semprotan, dongkrak hidrolik, hingga gaya angkat pesawat.

# Fluida

## Tujuan Pembelajaran
Setelah mempelajari bab ini, kamu diharapkan mampu:
1. Menjelaskan pengertian fluida dan massa jenis.
2. Menentukan tekanan pada zat cair dan gas secara sederhana.
3. Menjelaskan Hukum Pascal dan Hukum Archimedes.
4. Menganalisis kondisi benda terapung, melayang, dan tenggelam.
5. Menjelaskan konsep debit, persamaan kontinuitas, dan asas Bernoulli.
6. Menerapkan konsep fluida pada berbagai peristiwa dan alat sehari-hari.

## 4.1 Pengertian Fluida dan Massa Jenis

Fluida adalah zat yang dapat mengalir dan bentuknya mengikuti wadah. Cairan memiliki volume tetap tetapi bentuk berubah mengikuti wadah, sedangkan gas memiliki bentuk dan volume yang mudah berubah.

Salah satu sifat penting fluida adalah massa jenis, yaitu massa per satuan volume:

$$
\rho = \frac{m}{V}
$$

Dengan:
- $\rho$ = massa jenis,
- $m$ = massa,
- $V$ = volume.

Massa jenis membantu menjelaskan mengapa beberapa benda tenggelam dan yang lain terapung. Benda yang massa jenis rata-ratanya lebih kecil daripada massa jenis fluida cenderung terapung.

## 4.2 Tekanan

Tekanan adalah gaya per satuan luas yang bekerja tegak lurus permukaan. Secara umum dirumuskan sebagai:

$$
P = \frac{F}{A}
$$

Dari rumus ini terlihat bahwa gaya yang sama akan menghasilkan tekanan lebih besar jika luas bidang sentuh lebih kecil. Itulah sebabnya ujung paku dibuat runcing, sedangkan ban kendaraan dibuat lebar untuk memperkecil tekanan pada permukaan jalan tertentu.

## 4.3 Tekanan Hidrostatis

Pada fluida diam, tekanan bertambah seiring bertambahnya kedalaman. Tekanan hidrostatis pada kedalaman $h$ dinyatakan dengan:

$$
P_h = \rho gh
$$

Jika memperhitungkan tekanan di permukaan, tekanan total dapat ditulis sebagai:

$$
P = P_0 + \rho gh
$$

Konsep ini menjelaskan mengapa dinding bendungan dibuat lebih tebal di bagian bawah dan mengapa telinga terasa lebih sakit saat menyelam lebih dalam.

## 4.4 Hukum Pascal

Hukum Pascal menyatakan bahwa tekanan yang diberikan pada fluida dalam ruang tertutup diteruskan sama besar ke segala arah. Prinsip ini menjadi dasar kerja berbagai alat hidrolik.

Secara matematis:

$$
P_1 = P_2
$$

atau:

$$
\frac{F_1}{A_1} = \frac{F_2}{A_2}
$$

Jika luas penampang keluaran lebih besar, gaya keluaran dapat menjadi jauh lebih besar daripada gaya masukan. Inilah prinsip kerja dongkrak hidrolik dan rem hidrolik.

Contoh:
Jika gaya 50 N diberikan pada penampang kecil 5 cm² dan penampang besar 100 cm², maka gaya keluaran:

$$
F_2 = F_1 \frac{A_2}{A_1} = 50 \times \frac{100}{5} = 1000 \text{ N}
$$

## 4.5 Hukum Archimedes

Hukum Archimedes menyatakan bahwa benda yang dicelupkan sebagian atau seluruhnya ke dalam fluida akan mengalami gaya ke atas yang besarnya sama dengan berat fluida yang dipindahkan.

Rumus gaya angkat ke atas adalah:

$$
F_A = \rho_f g V_{tercelup}
$$

Dengan:
- $F_A$ = gaya Archimedes,
- $\rho_f$ = massa jenis fluida,
- $V_{tercelup}$ = volume benda yang tercelup.

### 4.5.1 Terapung, melayang, tenggelam
- Terapung: $F_A = w$ dan hanya sebagian volume benda tercelup.
- Melayang: $F_A = w$ dan seluruh volume tercelup tanpa menyentuh dasar.
- Tenggelam: $F_A < w$ sehingga benda turun ke dasar.

Hubungan massa jenis yang umum digunakan:
- Jika $\rho_{benda} < \rho_{fluida}$, benda terapung.
- Jika $\rho_{benda} = \rho_{fluida}$, benda melayang.
- Jika $\rho_{benda} > \rho_{fluida}$, benda tenggelam.

## 4.6 Tegangan Permukaan dan Kapilaritas

Pada skala kecil, fluida menunjukkan gejala permukaan yang menarik. Tegangan permukaan membuat permukaan zat cair cenderung meminimalkan luasnya, sehingga tetesan air cenderung berbentuk mendekati bola.

Kapilaritas adalah gejala naik atau turunnya permukaan zat cair dalam pipa sempit akibat adhesi dan kohesi. Peristiwa ini menjelaskan naiknya air pada pembuluh kapiler tumbuhan dan meresapnya minyak pada sumbu lampu.

## 4.7 Fluida Dinamis dan Debit

Fluida dinamis membahas fluida yang mengalir. Salah satu besaran penting adalah debit, yaitu volume fluida yang mengalir tiap satuan waktu:

$$
Q = \frac{V}{t}
$$

Jika penampang pipa dilalui aliran dengan laju $v$ dan luas penampang $A$, maka:

$$
Q = Av
$$

Debit berguna dalam perancangan saluran air, pompa, infus, irigasi, dan sistem distribusi cairan lainnya.

## 4.8 Persamaan Kontinuitas

Untuk fluida ideal tak termampatkan yang mengalir tunak, debit di setiap penampang pipa sama. Maka berlaku persamaan kontinuitas:

$$
A_1 v_1 = A_2 v_2
$$

Persamaan ini menunjukkan bahwa pada penampang yang lebih kecil, laju aliran lebih besar. Karena itu, air dari ujung selang yang disempitkan akan keluar lebih cepat.

## 4.9 Asas Bernoulli

Asas Bernoulli menyatakan bahwa pada aliran fluida ideal, jumlah tekanan, energi kinetik per satuan volume, dan energi potensial per satuan volume adalah konstan sepanjang garis arus.

Persamaannya adalah:

$$
P + \frac{1}{2}\rho v^2 + \rho gh = \text{konstan}
$$

Jika ketinggian sama, maka bagian aliran yang lebih cepat memiliki tekanan lebih kecil. Prinsip ini menjelaskan gaya angkat pada sayap pesawat, semprotan parfum, karburator, dan atap rumah yang dapat terangkat saat angin sangat kencang.

## 4.10 Tabel Ringkas Konsep Fluida

| Konsep | Persamaan | Makna |
|---|---|---|
| Massa jenis | $\rho = \frac{m}{V}$ | Kerapatan materi dalam volume tertentu |
| Tekanan | $P = \frac{F}{A}$ | Gaya per satuan luas |
| Tekanan hidrostatis | $P_h = \rho gh$ | Tekanan akibat kedalaman |
| Hukum Pascal | $\frac{F_1}{A_1} = \frac{F_2}{A_2}$ | Tekanan diteruskan sama besar |
| Gaya Archimedes | $F_A = \rho_f g V_{tercelup}$ | Gaya ke atas pada benda tercelup |
| Debit | $Q = \frac{V}{t} = Av$ | Laju aliran volumetrik |
| Kontinuitas | $A_1 v_1 = A_2 v_2$ | Kekekalan aliran |
| Bernoulli | $P + \frac{1}{2}\rho v^2 + \rho gh = \text{konstan}$ | Hubungan tekanan, laju, dan ketinggian |

## 4.11 Penerapan dalam Kehidupan

Konsep fluida digunakan pada kapal laut, kapal selam, hidrometer, pipa venturi, alat semprot, infus, sistem hidrolik, dan aerodinamika pesawat. Pada level rumah tangga, prinsip yang sama muncul pada toren air, pompa, sedotan, semprotan cairan, dan aliran air dari keran.

Bab ini menunjukkan bahwa konsep yang tampak sederhana seperti tekanan dan massa jenis sebenarnya menjelaskan banyak teknologi penting. Fluida menjadi contoh bagus bagaimana fisika menghubungkan model matematis dengan fenomena nyata secara langsung.

## 4.12 Latihan Pemahaman

1. Jelaskan perbedaan cairan dan gas sebagai fluida.
2. Sebuah benda bermassa 500 g memiliki volume 250 cm³. Tentukan massa jenisnya.
3. Gaya 200 N bekerja pada luas 0,5 m². Tentukan tekanannya.
4. Hitung tekanan hidrostatis pada kedalaman 2 m dalam air jika $\rho = 1000$ kg/m³ dan $g = 10$ m/s².
5. Sebuah dongkrak hidrolik memiliki luas penampang kecil 4 cm² dan penampang besar 80 cm². Jika gaya masukan 60 N, tentukan gaya keluarannya.
6. Sebuah benda tercelup memindahkan air sebanyak 0,02 m³. Tentukan gaya Archimedes yang dialami jika $\rho_{air} = 1000$ kg/m³ dan $g = 10$ m/s².
7. Mengapa kapal baja dapat terapung padahal baja lebih rapat daripada air?
8. Air mengalir dalam pipa dengan luas penampang mula-mula 10 cm² dan laju 2 m/s, lalu memasuki penampang 4 cm². Tentukan laju aliran pada penampang kedua.
9. Jelaskan makna asas Bernoulli pada sayap pesawat.
10. Mengapa tekanan pada bagian bawah bendungan lebih besar daripada di bagian atas?

## Glosarium

- **Fluida**: zat yang dapat mengalir.
- **Massa jenis**: massa per satuan volume.
- **Tekanan**: gaya per satuan luas.
- **Tekanan hidrostatis**: tekanan dalam fluida diam akibat kedalaman.
- **Gaya Archimedes**: gaya ke atas pada benda yang berada dalam fluida.
- **Debit**: volume aliran per satuan waktu.
- **Kontinuitas**: kekekalan aliran pada fluida ideal.
- **Asas Bernoulli**: hubungan antara tekanan, laju, dan ketinggian aliran fluida.
