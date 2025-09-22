# BAB 1: Vektor - Membaca Peta Dunia Fisika

**Tujuan Pembelajaran:**
Setelah mempelajari bab ini, diharapkan kamu mampu untuk:

1. Menjelaskan perbedaan mendasar antara besaran skalar dan besaran vektor.
2. Menggambarkan dan menuliskan notasi sebuah vektor dengan benar.
3. Menerapkan operasi penjumlahan dan pengurangan vektor menggunakan metode grafis (poligon & jajargenjang) dan analitis untuk menyelesaikan masalah.
4. Menguraikan sebuah vektor menjadi komponen-komponennya.

**Pemahaman Bermakna:**
Bayangkan kamu sedang memberikan petunjuk arah kepada temanmu. Apakah cukup dengan mengatakan, "Jalan saja 500 meter"? Tentu tidak. Temanmu akan bingung, "500 meter ke mana?". Kamu harus menambahkan informasi **arah**, misalnya, "Jalan 500 meter ke arah timur, lalu belok 200 meter ke arah utara." Informasi lengkap inilah (nilai dan arah) yang menjadi inti dari vektor. Mempelajari vektor ibarat belajar membaca "peta" dan "bahasa" yang digunakan dalam Fisika untuk menjelaskan gerak, gaya, dan banyak fenomena lainnya secara presisi. Kemampuan ini tidak hanya berguna di Fisika, tapi juga melatih cara berpikir logis dan terstruktur.

**Pembukaan: Kisah Perjalanan Budi ke Pasar**
Setiap hari Minggu, Budi pergi ke pasar untuk membantu ibunya. Rumah Budi tidak berada di jalan utama, jadi ia harus melewati jalan-jalan kecil di pematang sawah. Dari rumahnya, ia berjalan lurus ke arah Timur sejauh 400 meter hingga tiba di sebuah jembatan bambu. Setelah menyeberangi jembatan, ia berbelok ke Utara dan berjalan lagi sejauh 300 meter, barulah ia sampai di gerbang pasar.

Suatu hari, seorang temannya bertanya, "Budi, seberapa jauh sebenarnya rumahmu dari pasar jika ditarik garis lurus?" Budi pun terdiam sejenak. Ia tahu total jarak yang ia tempuh adalah 400 m + 300 m = 700 meter. Tapi itu adalah jarak tempuh perjalanannya yang berbelok. Jarak lurus dari rumahnya ke pasar, seolah-olah ia bisa terbang seperti burung, tentu lebih pendek.

`#sisipkan gambar peta sederhana perjalanan Budi dari rumah ke pasar, menunjukkan jalur 400 m ke Timur dan 300 m ke Utara`

Pertanyaan teman Budi inilah yang akan membawa kita pada sebuah konsep penting dalam Fisika. Jarak 700 meter yang ditempuh Budi adalah **besaran skalar**, yang hanya peduli pada total nilainya. Sedangkan "jarak lurus" yang ditanyakan temannya, yang memiliki nilai **dan** arah tertentu (arah Tenggara dari pasar, atau Timur Laut dari rumah), adalah **besaran vektor**. Kisah Budi ini menunjukkan bahwa untuk mendeskripsikan sesuatu secara lengkap, terkadang nilai saja tidak cukup. Kita butuh arah!

**Materi Pembelajaran**  

## Skalar dan Vektor: Nilai Saja atau Perlu Arah?

Dalam Fisika, tidak semua besaran diperlakukan sama. Kita membaginya menjadi dua "keluarga" besar:

1. **Besaran Skalar:** Ini adalah besaran yang "sederhana". Ia sudah cukup dijelaskan hanya dengan **nilainya** saja (dan satuan, tentu saja). Ia tidak peduli dengan arah.
    * *Contoh dalam cerita Budi:* Total jarak tempuh Budi (700 m).
    * *Contoh lain:* Massa beras (5 kg), suhu air (30°C), waktu yang dibutuhkan untuk menggiling padi (2 jam), volume bak penampungan air (1000 liter).

2. **Besaran Vektor:** Ini adalah besaran yang lebih "informatif". Ia baru bisa dijelaskan secara lengkap jika memiliki **nilai** dan juga **arah**.
    * *Contoh dalam cerita Budi:* Perpindahan Budi dari rumah ke pasar (memiliki nilai jarak lurus dan arah yang spesifik).
    * *Contoh lain:* Kecepatan angin (misalnya 20 km/jam ke arah Barat), gaya seorang pekerja mendorong gerobak (misalnya 100 Newton ke depan), percepatan motor (misalnya 2 m/s² ke arah Timur).

Vektor biasanya digambarkan dengan sebuah **anak panah**. Panjang anak panah mewakili **nilai** vektor, dan arah ujung panah menunjukkan **arah** vektor.

## Penjumlahan Vektor: Mencari Rute Terpendek

Kembali ke masalah Budi tadi. Bagaimana cara kita mengetahui perpindahannya (jarak lurus dari rumah ke pasar)? Kita perlu menjumlahkan dua perjalanan vektornya: **Vektor A** (400 m ke Timur) dan **Vektor B** (300 m ke Utara). Hasil penjumlahan vektor disebut **Resultan Vektor (R)**. Ada beberapa cara untuk melakukannya:

### 1. Metode Poligon (Metode Grafis)

Ini adalah cara paling intuitif, seperti mengikuti jejak perjalanan.

* Gambarkan vektor pertama (Vektor A).
* Gambarkan vektor kedua (Vektor B) dengan pangkalnya berada di ujung vektor pertama.
* Resultannya (R) adalah vektor yang ditarik dari pangkal vektor pertama ke ujung vektor kedua.

`#sisipkan gambar metode poligon untuk perjalanan Budi, membentuk segitiga siku-siku`

### 2. Metode Jajargenjang (Metode Grafis)

Metode ini berguna jika dua vektor bekerja dari titik yang sama (misalnya dua orang menarik satu benda).

* Gambarkan kedua vektor (A dan B) dari titik pangkal yang sama.
* Buat garis bayangan yang sejajar dengan masing-masing vektor dari ujung vektor lainnya, sehingga membentuk sebuah jajargenjang.
* Resultannya (R) adalah diagonal jajargenjang yang ditarik dari titik pangkal kedua vektor.

### 3. Metode Analitis (Metode Matematis)

Jika kedua vektor membentuk sudut tertentu $\theta$, kita dapat menggunakan **rumus kosinus** untuk menghitung resultan vektor:

$R = \sqrt{A^2 + B^2 + 2AB\cos\theta}$

Misalnya, jika sudut antara vektor perjalanan Budi adalah $90^\circ$, maka $\cos 90^\circ = 0$, sehingga rumusnya kembali menjadi:

$R = \sqrt{A^2 + B^2}$

Namun, jika sudutnya berbeda, misalnya $60^\circ$, maka:

$R = \sqrt{400^2 + 300^2 + 2(400)(300)\cos 60^\circ}$  
$R = \sqrt{160000 + 90000 + 240000 \cdot 0.5}$  
$R = \sqrt{160000 + 90000 + 120000}$  
$R = \sqrt{370000} \approx 608.28$ m.

Jadi, perpindahan atau jarak lurus rumah Budi dari pasar bergantung pada sudut antara vektor perjalanan.

## Mengurai Vektor: Melihat dari Sudut Pandang Berbeda

Bayangkan seorang petani menarik gerobak dengan tali yang membentuk sudut dengan tanah. Gaya tarik yang ia berikan sebenarnya memiliki dua efek sekaligus: efek mendatar yang membuat gerobak maju (sumbu x) dan efek vertikal yang sedikit mengangkat gerobak (sumbu y). Proses memecah satu vektor menjadi dua komponen pada sumbu x dan y inilah yang disebut **menguraikan vektor**. Ini sangat berguna untuk menganalisis masalah yang lebih kompleks.

`#sisipkan gambar sebuah vektor gaya F yang diuraikan menjadi komponen Fx dan Fy`

**Refleksi**  

Pilih jawaban yang paling tepat untuk menguji pemahamanmu!

1. Dari kelompok besaran berikut, yang seluruhnya merupakan besaran vektor adalah...
    a. Jarak, kecepatan, gaya
    b. Perpindahan, kelajuan, massa
    c. Gaya, percepatan, perpindahan
    d. Waktu, suhu, percepatan
    e. Volume, gaya, kecepatan

2. Dua buah vektor gaya, F1 = 10 N dan F2 = 15 N, bekerja pada satu titik dan saling tegak lurus. Resultan kedua vektor tersebut adalah...
    a. 5 N
    b. 18 N
    c. 20 N
    d. 25 N
    e. 30 N

3. Sebuah perahu menyeberangi sungai yang arusnya deras. Kecepatan perahu dan kecepatan arus sungai merupakan contoh besaran...
    a. Skalar
    b. Pokok
    c. Vektor
    d. Turunan
    e. Absolut

4. Jika sebuah vektor digambarkan dengan anak panah, maka panjang anak panah tersebut melambangkan...
    a. Arah vektor
    b. Nilai/Besar vektor
    c. Satuan vektor
    d. Komponen vektor
    e. Titik pangkal vektor

5. Budi berjalan 4 meter ke Barat, kemudian 3 meter ke Selatan. Perpindahan total Budi dari titik awal adalah...
    a. 7 meter arah Tenggara
    b. 7 meter arah Barat Daya
    c. 5 meter arah Tenggara
    d. 5 meter arah Barat Daya
    e. 1 meter arah Barat Daya

**Asesmen Formatif**  

Jawablah pertanyaan berikut dengan singkat dan jelas!

1. Sebutkan perbedaan paling mendasar antara **jarak tempuh** dan **perpindahan** menggunakan contoh perjalananmu dari rumah ke sekolah!
2. Dua orang anak, Ali dan Budi, mencoba menggeser sebuah lemari. Ali mendorong dengan gaya 300 N ke arah kanan, sementara Budi mendorong dengan gaya 400 N ke arah yang sama. Berapakah resultan gaya yang bekerja pada lemari tersebut?
3. Sebuah pesawat terbang dengan kecepatan 200 km/jam ke arah Timur. Pada saat yang sama, angin bertiup ke arah Utara dengan kecepatan 150 km/jam. Gambarkan penjumlahan vektor kecepatan tersebut menggunakan metode poligon!

**Glosarium**  

* **Besaran Skalar:** Besaran fisika yang hanya memiliki nilai dan tidak memiliki arah.
* **Besaran Vektor:** Besaran fisika yang memiliki nilai dan arah.
* **Resultan Vektor:** Hasil penjumlahan dari dua atau lebih vektor.
* **Komponen Vektor:** Uraian sebuah vektor terhadap sumbu-sumbu koordinat (biasanya sumbu x dan y).

**Daftar Pustaka**  

* Giancoli, Douglas C. (2005). *Physics: Principles with Applications*. Pearson Education.
* Halliday, D., Resnick, R., & Walker, J. (2010). *Fundamentals of Physics*. John Wiley & Sons.
* Pusat Kurikulum dan Perbukuan. (2024). *Capaian Pembelajaran dan Alur Tujuan Pembelajaran Mata Pelajaran Fisika Fase F*. Kemendikbudristek.
