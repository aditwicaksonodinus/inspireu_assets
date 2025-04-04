# Fluida Statis dan Dinamis

## Tujuan Pembelajaran

Setelah mempelajari materi ini, peserta didik diharapkan mampu:

1. Menjelaskan konsep dasar fluida statis dan dinamis
2. Menerapkan konsep tekanan hidrostatis dalam fenomena sehari-hari
3. Menganalisis penerapan hukum Pascal dan hukum Archimedes
4. Menjelaskan persamaan kontinuitas pada fluida
5. Menerapkan prinsip Bernoulli dalam pemecahan masalah fluida dinamis
6. Mengidentifikasi aplikasi fluida statis dan dinamis dalam teknologi

## Pendahuluan

Pernahkah kamu memperhatikan bagaimana kapal besar dapat mengapung di lautan, atau bagaimana pesawat terbang yang berat dapat terangkat ke udara? Atau mungkin kamu pernah bertanya-tanya mengapa aliran air di sungai kadang tenang dan kadang deras? Semua fenomena itu berkaitan erat dengan konsep fluida dalam fisika!

Fluida—baik berupa cairan seperti air atau gas seperti udara—adalah bagian tak terpisahkan dari kehidupan kita. Setiap hari, kita berinteraksi dengan berbagai jenis fluida tanpa menyadarinya. Dari mengisi gelas dengan air, menghirup udara untuk bernapas, hingga berenang di kolam, semua aktivitas tersebut melibatkan interaksi dengan fluida dan diatur oleh hukum-hukum fisika.

Dalam materi ini, kita akan menjelajahi dua aspek utama fluida: fluida statis (fluida dalam keadaan diam) dan fluida dinamis (fluida dalam keadaan bergerak). Pemahaman tentang konsep-konsep ini tidak hanya menarik secara intelektual, tetapi juga memiliki banyak aplikasi praktis dalam kehidupan modern—mulai dari desain kapal dan pesawat hingga sistem perpipaan dan teknologi hidrolik.

## Isi Materi

### Fluida Statis

#### Pengertian Fluida

Fluida adalah zat yang dapat mengalir dan mengambil bentuk sesuai dengan wadahnya. Fluida mencakup zat cair dan gas. Perbedaan utama antara zat cair dan gas adalah:

| Karakteristik | Zat Cair | Gas |
|---------------|----------|-----|
| Volume | Tetap | Tidak tetap |
| Bentuk | Mengikuti wadah | Mengisi seluruh ruang |
| Kompresibilitas | Sangat kecil | Besar |
| Jarak antar molekul | Kecil | Besar |

Fluida memiliki sifat penting yaitu massa jenis (densitas), yang didefinisikan sebagai perbandingan massa terhadap volume:

$$\rho = \frac{m}{V}$$

Dengan:

- $\rho$ = massa jenis (kg/m³)
- $m$ = massa (kg)
- $V$ = volume (m³)

#### Tekanan Hidrostatis

Tekanan hidrostatis adalah tekanan yang dihasilkan oleh fluida diam pada kedalaman tertentu. Tekanan hidrostatis dirumuskan:

$$P_h = \rho \times g \times h$$

Dengan:

- $P_h$ = tekanan hidrostatis (N/m² atau Pascal)
- $\rho$ = massa jenis fluida (kg/m³)
- $g$ = percepatan gravitasi (m/s²)
- $h$ = kedalaman dari permukaan fluida (m)

Tekanan hidrostatis menjelaskan mengapa:

- Semakin dalam kita menyelam, semakin besar tekanan air yang kita rasakan
- Bendungan dibuat lebih tebal di bagian bawah
- Kapal selam memiliki dinding yang sangat kuat untuk menahan tekanan air laut

#### Hukum Pascal

Hukum Pascal menyatakan bahwa tekanan yang diberikan pada fluida dalam ruang tertutup akan diteruskan sama besar ke segala arah. Secara matematis:

$$\frac{F_1}{A_1} = \frac{F_2}{A_2}$$

Dengan:

- $F_1$ dan $F_2$ = gaya pada penampang 1 dan 2 (N)
- $A_1$ dan $A_2$ = luas penampang 1 dan 2 (m²)

Aplikasi hukum Pascal antara lain:

- Dongkrak hidrolik
- Rem hidrolik pada kendaraan
- Lift hidrolik
- Mesin pengepres hidrolik

#### Hukum Archimedes

Hukum Archimedes menyatakan bahwa sebuah benda yang terendam sebagian atau seluruhnya dalam fluida akan mengalami gaya apung sebesar berat fluida yang dipindahkan oleh benda tersebut.

$$F_A = \rho_f \times g \times V_t$$

Dengan:

- $F_A$ = gaya apung (N)
- $\rho_f$ = massa jenis fluida (kg/m³)
- $g$ = percepatan gravitasi (m/s²)
- $V_t$ = volume benda yang tercelup (m³)

Berdasarkan hukum Archimedes, benda dalam fluida dapat:

1. Tenggelam: jika $\rho_{\text{benda}} > \rho_{\text{fluida}}$
2. Melayang: jika $\rho_{\text{benda}} = \rho_{\text{fluida}}$
3. Mengapung: jika $\rho_{\text{benda}} < \rho_{\text{fluida}}$

Aplikasi hukum Archimedes:

- Kapal laut dan perahu
- Balon udara dan kapal udara
- Hidrometer (alat ukur massa jenis cairan)
- Jaket pelampung

### Fluida Dinamis

#### Pengertian Fluida Dinamis

Fluida dinamis adalah cabang ilmu fisika yang mempelajari fluida bergerak. Fluida dinamis memiliki beberapa asumsi:

- Fluida bersifat ideal (tak termampatkan dan tak kental)
- Aliran fluida bersifat tunak (kecepatan di suatu titik konstan terhadap waktu)
- Aliran fluida bersifat laminar (teratur)

#### Persamaan Kontinuitas

Persamaan kontinuitas menyatakan bahwa pada fluida inkompresibel (tak termampatkan), hasil kali luas penampang dengan kecepatan aliran fluida selalu konstan:

$$A_1 \times v_1 = A_2 \times v_2$$

Atau dalam bentuk laju aliran massa:

$$\rho \times A_1 \times v_1 = \rho \times A_2 \times v_2$$

Dengan:

- $A_1$ dan $A_2$ = luas penampang 1 dan 2 (m²)
- $v_1$ dan $v_2$ = kecepatan aliran di penampang 1 dan 2 (m/s)
- $\rho$ = massa jenis fluida (kg/m³)

Persamaan kontinuitas menjelaskan:

- Mengapa air mengalir lebih cepat saat nozzle selang diperkecil
- Penyempitan aliran sungai menyebabkan aliran air menjadi lebih deras
- Desain pipa air di perumahan

#### Prinsip Bernoulli

Prinsip Bernoulli menyatakan bahwa pada aliran fluida yang steady, jumlah dari tekanan ($P$), energi potensial per satuan volume ($\rho gh$), dan energi kinetik per satuan volume ($\frac{1}{2}\rho v^2$) selalu konstan di setiap titik. Secara matematis:

$$P_1 + \frac{1}{2}\rho v_1^2 + \rho gh_1 = P_2 + \frac{1}{2}\rho v_2^2 + \rho gh_2$$

Dengan:

- $P$ = tekanan (N/m² atau Pascal)
- $\rho$ = massa jenis fluida (kg/m³)
- $v$ = kecepatan aliran (m/s)
- $g$ = percepatan gravitasi (m/s²)
- $h$ = ketinggian dari titik referensi (m)

Aplikasi prinsip Bernoulli:

- Gaya angkat pada sayap pesawat terbang
- Venturimeter dan tabung pitot (alat ukur kecepatan fluida)
- Karburator pada mesin kendaraan
- Aliran darah dalam pembuluh darah
- Atomizer parfum dan alat semprot
- Fenomena bola yang berputar dalam olahraga (efek Magnus)

#### Viskositas dan Aliran Turbulen

Pada kenyataannya, fluida memiliki kekentalan (viskositas) dan dapat mengalami aliran turbulen (tidak teratur). Viskositas adalah ukuran hambatan internal fluida untuk mengalir.

Hukum Stokes menyatakan gaya hambat pada benda yang bergerak dalam fluida kental:

$$F_s = 6\pi\eta rv$$

Dengan:

- $F_s$ = gaya Stokes (N)
- $\eta$ = koefisien viskositas fluida (N·s/m²)
- $r$ = jari-jari benda (m)
- $v$ = kecepatan relatif benda terhadap fluida (m/s)

Aliran fluida dapat bersifat:

1. Laminar (teratur) - terjadi pada kecepatan rendah
2. Turbulen (tidak teratur) - terjadi pada kecepatan tinggi

Jenis aliran ditentukan oleh bilangan Reynolds:

$$Re = \frac{\rho vL}{\eta}$$

Dengan:

- $Re$ = bilangan Reynolds (tak berdimensi)
- $\rho$ = massa jenis fluida (kg/m³)
- $v$ = kecepatan fluida (m/s)
- $L$ = panjang karakteristik (m)
- $\eta$ = viskositas dinamik fluida (N·s/m²)

Aliran fluida bersifat:

- Laminar jika $Re < 2000$
- Transisi jika $2000 < Re < 4000$
- Turbulen jika $Re > 4000$

## Rangkuman Materi

1. **Fluida Statis:**
   - Fluida adalah zat yang dapat mengalir dan mengambil bentuk sesuai wadahnya
   - Tekanan hidrostatis: $P_h = \rho gh$ (tekanan meningkat dengan kedalaman)
   - Hukum Pascal: tekanan pada fluida tertutup diteruskan sama besar ke segala arah
   - Hukum Archimedes: benda yang terendam dalam fluida mendapat gaya apung sebesar berat fluida yang dipindahkan

2. **Fluida Dinamis:**
   - Persamaan kontinuitas: $A_1v_1 = A_2v_2$ (laju volume aliran konstan)
   - Prinsip Bernoulli: $P + \frac{1}{2}\rho v^2 + \rho gh =$ konstan (jumlah energi per satuan volume konstan)
   - Viskositas menyebabkan hambatan internal pada fluida yang mengalir
   - Aliran fluida dapat bersifat laminar atau turbulen tergantung pada bilangan Reynolds

3. **Aplikasi dalam kehidupan:**
   - Dongkrak hidrolik, rem hidrolik (Hukum Pascal)
   - Kapal laut, balon udara (Hukum Archimedes)
   - Sistem perpipaan (Persamaan Kontinuitas)
   - Gaya angkat pesawat, atomizer, karburator (Prinsip Bernoulli)
