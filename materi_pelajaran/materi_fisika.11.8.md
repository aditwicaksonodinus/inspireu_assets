# BAB 8: Termodinamika - Mengubah Panas Menjadi Kerja

**Tujuan Pembelajaran:**
Setelah mempelajari bab ini, diharapkan kamu mampu untuk:

1. Menerapkan teori kinetik gas untuk menganalisis sifat-sifat gas dalam ruang tertutup.
2. Menganalisis hubungan antara usaha, kalor, dan energi dalam berdasarkan Hukum I Termodinamika.
3. Membedakan pernyataan tentang Hukum II Termodinamika dan menjelaskan konsep entropi.
4. Menjelaskan prinsip kerja dan efisiensi mesin kalor sebagai penerapan konsep termodinamika.

**Pemahaman Bermakna:**
Pernahkah kamu bertanya-tanya bagaimana mesin motor atau traktor bisa memiliki tenaga begitu besar hanya dengan membakar sedikit bahan bakar? Bagaimana bisa panas dari pembakaran solar diubah menjadi gerakan kuat yang mampu membajak sawah? Jawabannya terletak pada **termodinamika**, yaitu ilmu yang mempelajari hubungan antara panas (kalor), kerja (usaha), dan energi. Memahami termodinamika berarti kita memahami cara kerja hampir semua mesin yang menggerakkan dunia modern, mulai dari mesin kendaraan, pembangkit listrik, hingga kulkas di rumah. Ilmu ini adalah kunci untuk menciptakan teknologi yang efisien dan mengubah energi panas menjadi sesuatu yang berguna.

**Pembukaan: Jantung Mekanis di Tengah Sawah**
Perhatikan sebuah traktor yang sedang bekerja di sawah. Dari knalpotnya keluar asap panas, dan dari badannya terpancar hawa hangat. Di dalam "jantung" traktor itu, yaitu mesin dieselnya, terjadi sebuah keajaiban fisika. Sejumlah kecil solar disemprotkan ke dalam silinder, lalu dibakar. Ledakan kecil dari pembakaran itu menghasilkan panas yang luar biasa. Panas inilah yang mendorong piston untuk bergerak turun-naik dengan sangat cepat. Gerakan naik-turun ini kemudian diubah menjadi gerak putar yang menggerakkan roda-roda besar traktor.

Asap panas yang terbuang, hawa hangat dari badan mesin, dan tenaga besar yang dihasilkan adalah tiga komponen utama dalam cerita termodinamika. Ada **panas yang masuk** (dari pembakaran), ada **kerja yang dihasilkan** (menggerakkan roda), dan ada **panas yang dibuang**. Proses mengubah panas menjadi kerja inilah yang akan kita bedah dalam bab ini, seolah-olah kita sedang menjadi montir yang mengintip ke dalam cara kerja sebuah mesin.

`#sisipkan gambar skema sederhana mesin diesel pada traktor`

## Teori Kinetik Gas dan Gas Ideal

Untuk memahami mesin, kita perlu memahami "fluida kerja" di dalamnya, yaitu gas. **Teori Kinetik Gas** membayangkan gas sebagai kumpulan partikel (atom atau molekul) yang sangat banyak dan bergerak acak dengan kecepatan tinggi. Partikel-partikel ini terus-menerus bertumbukan satu sama lain dan dengan dinding wadahnya. Tumbukan partikel ke dinding inilah yang kita rasakan sebagai **tekanan gas**.

Untuk menyederhanakan analisis, para ilmuwan menggunakan model **Gas Ideal**, yaitu gas hipotetis dengan sifat-sifat:

* Partikelnya bergerak acak dan merata.
* Tidak ada gaya tarik-menarik antarpartikel.
* Tumbukan antarpartikel bersifat lenting sempurna.

Perilaku gas ideal ini dirangkum dalam satu persamaan elegan:

**Persamaan Gas Ideal:**

$$PV = nRT$$

Dimana:

* P = Tekanan (Pascal, Pa)
* V = Volume ($m^3$)
* n = Jumlah mol gas (mol)
* R = Konstanta gas ideal (8,314 J/mol·K)
* T = Suhu (Kelvin, K)

## Hukum-Hukum Fundamental Termodinamika

**1. Hukum Awal (Ke-Nol) Termodinamika**
Hukum ini terdengar sederhana tapi sangat mendasar. Jika benda A berada dalam kesetimbangan termal dengan benda B, dan benda B juga setimbang dengan benda C, maka A pasti setimbang dengan C. Artinya, mereka semua memiliki **suhu yang sama**. Hukum inilah yang menjadi dasar validitas pengukuran suhu menggunakan termometer.

**2. Hukum I Termodinamika (Kekekalan Energi)**
Hukum ini adalah penerapan Hukum Kekekalan Energi pada sistem termodinamika. Hukum ini menghubungkan tiga besaran penting:

* **Energi Dalam ($\Delta U$):** Total energi kinetik dari seluruh partikel gas dalam sistem.
* **Kalor (Q):** Energi panas yang masuk atau keluar dari sistem.
* **Usaha (W):** Kerja yang dilakukan oleh sistem (misalnya gas mendorong piston) atau pada sistem.

> **Hukum I Termodinamika berbunyi:** *"Perubahan energi dalam dari suatu sistem termodinamika tertutup sama dengan total dari kalor yang ditambahkan ke dalam sistem dikurangi usaha yang dilakukan oleh sistem terhadap lingkungannya."*

dituliskan menjadi:

$$\Delta U = Q - W$$

**Aturan Tanda:**

* Q (+): Sistem menerima kalor.
* Q (-): Sistem melepaskan kalor.
* W (+): Sistem melakukan usaha (misal: gas memuai).
* W (-): Sistem dikenai usaha (misal: gas dimampatkan).

**3. Hukum II Termodinamika (Arah Aliran dan Entropi)**
Jika Hukum I menyatakan energi itu kekal, Hukum II memberikan "aturan main"-nya. Hukum ini menjelaskan arah proses alami.

* **Pernyataan Aliran Kalor:** Kalor mengalir secara spontan dari benda bersuhu tinggi ke benda bersuhu rendah, dan tidak sebaliknya.
* **Pernyataan Mesin Kalor:** Tidak ada mesin yang dapat mengubah seluruh kalor yang diterimanya menjadi usaha. Pasti ada sebagian kalor yang "terbuang" ke reservoir suhu rendah.

Hukum II juga melahirkan konsep **Entropi (S)**, yaitu ukuran **ketidakteraturan** atau **keacakan** suatu sistem.
> Hukum II Termodinamika dalam konsep entropi menyatakan bahwa total entropi alam semesta cenderung meningkat seiring waktu. Proses alami selalu bergerak menuju keadaan yang lebih tidak teratur.

**4. Hukum III Termodinamika**
Hukum ini menyatakan bahwa entropi suatu sistem akan mendekati nilai minimum (mendekati nol) ketika suhunya mendekati **nol mutlak (0 Kelvin)**. Artinya, tidak mungkin mendinginkan suatu sistem hingga mencapai suhu nol mutlak.

## Penerapan: Mesin Kalor

**Mesin Kalor** adalah perangkat apa pun yang mengubah energi panas menjadi usaha mekanis secara terus-menerus. Mesin pada traktor atau motor adalah contohnya.
Sebuah mesin kalor bekerja dengan cara:

1. Menyerap kalor ($Q_1$) dari reservoir suhu tinggi (T1), misalnya dari ruang pembakaran.
2. Mengubah sebagian kalor tersebut menjadi usaha mekanis (W).
3. Membuang sisa kalor ($Q_2$) ke reservoir suhu rendah (T2), misalnya melalui knalpot ke lingkungan.

Efisiensi ($\eta$) sebuah mesin kalor adalah perbandingan antara usaha yang dihasilkan dengan kalor yang diserap.

$$\eta = \frac{W}{Q_1} = \frac{Q_1 - Q_2}{Q_1} = 1 - \frac{Q_2}{Q_1}$$

Menurut Hukum II Termodinamika, efisiensi mesin tidak akan pernah bisa 100% karena $Q_2$ tidak mungkin bernilai nol.

**Refleksi**  

Pilih jawaban yang paling tepat untuk menguji pemahamanmu!

1. Hukum Termodinamika yang menjadi dasar ilmiah bagi cara kerja termometer adalah...
    a. Hukum I Termodinamika
    b. Hukum II Termodinamika
    c. Hukum III Termodinamika
    d. Hukum Awal (Ke-Nol) Termodinamika
    e. Hukum Kekekalan Energi

2. Sebuah sistem gas menerima kalor sebesar 2000 J dan melakukan usaha sebesar 1200 J. Perubahan energi dalam sistem tersebut adalah...
    a. Bertambah 3200 J
    b. Berkurang 3200 J
    c. Bertambah 800 J
    d. Berkurang 800 J
    e. Tetap

3. Pernyataan bahwa "kalor tidak mungkin diubah seluruhnya menjadi usaha" adalah inti dari...
    a. Hukum I Termodinamika
    b. Hukum II Termodinamika
    c. Persamaan Gas Ideal
    d. Teori Kinetik Gas
    e. Asas Black

4. Ukuran tingkat ketidakteraturan atau keacakan dalam suatu sistem termodinamika disebut...
    a. Entalpi
    b. Energi dalam
    c. Usaha
    d. Kalor
    e. Entropi

5. Sebuah mesin kalor memiliki efisiensi 30%. Jika mesin tersebut menyerap kalor sebesar 10.000 Joule, maka usaha yang dihasilkan adalah...
    a. 300 J
    b. 700 J
    c. 3.000 J
    d. 7.000 J
    e. 10.000 J

**Asesmen Formatif**  

Jawablah pertanyaan berikut dengan singkat dan jelas!

1. Saat kamu memompa ban sepeda, tabung pompa akan terasa panas. Jelaskan fenomena ini menggunakan konsep Hukum I Termodinamika!
2. Mengapa knalpot pada mesin motor atau traktor selalu panas? Hubungkan jawabanmu dengan prinsip kerja mesin kalor dan Hukum II Termodinamika!
3. Gas di dalam sebuah tabung baja dipanaskan sehingga suhunya naik, namun volumenya tetap. Apakah gas tersebut melakukan usaha? Jelaskan mengapa!

**Glosarium**  

* **Termodinamika:** Cabang fisika yang mempelajari hubungan antara panas, kerja, dan energi.
* **Gas Ideal:** Model gas teoretis yang digunakan untuk menyederhanakan perhitungan termodinamika.
* **Energi Dalam (U):** Jumlah total energi kinetik dan potensial dari seluruh partikel dalam sistem.
* **Usaha (W):** Energi yang ditransfer ketika sebuah gaya menyebabkan perpindahan. Dalam termodinamika, seringkali berupa gas yang memuai atau dimampatkan.
* **Kalor (Q):** Energi yang berpindah karena adanya perbedaan suhu.
* **Entropi (S):** Ukuran kuantitatif dari ketidakteraturan atau keacakan suatu sistem.
* **Mesin Kalor:** Perangkat yang mengubah energi panas menjadi kerja mekanis.

**Daftar Pustaka**  

* Giancoli, Douglas C. (2005). *Physics: Principles with Applications*. Pearson Education.
* Halliday, D., Resnick, R., & Walker, J. (*2010*). *Fundamentals of Physics*. John Wiley & Sons.
* Pusat Kurikulum dan Perbukuan. (2024). *Capaian Pembelajaran dan Alur Tujuan Pembelajaran Mata Pelajaran Fisika Fase F*. Kemendikbudristek.
