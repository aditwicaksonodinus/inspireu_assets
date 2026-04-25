# Bab 1: Eksponen dan Logaritma

Materi ini membahas konsep eksponen (pangkat) dan logaritma sebagai dua operasi yang saling berkebalikan (invers). Pemahaman tentang eksponen sangat krusial karena menjadi fondasi dalam memodelkan berbagai fenomena alam, seperti pertumbuhan penduduk, peluruhan zat radioaktif, hingga bunga majemuk dalam ekonomi.

Dalam modul ini, pembelajaran dirancang mengikuti alur **Zone of Proximal Development (ZPD)**. Kamu akan memulai dari pembangunan struktur pemikiran (scaffolding), penguatan konsep (consolidation), tantangan mandiri (exploration), hingga penerapan pada masalah nyata (engagement).

## Tujuan Pembelajaran

Setelah mempelajari bab ini, kamu diharapkan mampu:
1. Mengidentifikasi sifat-sifat eksponen dengan tepat.
2. Menyederhanakan ekspresi matematika yang melibatkan pangkat bulat dan rasional.
3. Memahami konsep logaritma sebagai invers dari eksponen.
4. Menerapkan sifat-sifat logaritma dalam penyelesaian masalah numerik.
5. Menyelesaikan persamaan eksponen dan logaritma sederhana.
6. Memodelkan fenomena pertumbuhan dan peluruhan menggunakan fungsi eksponensial.

---

## 1.1 Eksponen (Bilangan Berpangkat)

### 1.1.1 Hakikat Eksponen (Scaffolding - ZPD 0)
Eksponen adalah perkalian berulang dari suatu bilangan yang sama. Jika $a$ adalah bilangan real dan $n$ adalah bilangan bulat positif, maka:

$$a^n = \underbrace{a \times a \times a \times \dots \times a}_{n \text{ faktor}}$$

Di mana:
- $a$ disebut sebagai **bilangan pokok (basis)**.
- $n$ disebut sebagai **pangkat (eksponen)**.

### 1.1.2 Sifat-Sifat Eksponen (Consolidation - ZPD 1)
Untuk meminimalkan beban kognitif (*extraneous load*), gunakan tabel berikut sebagai acuan operasional:

| Sifat Eksponen | Rumus | Deskripsi |
| :--- | :--- | :--- |
| Perkalian | $a^m \cdot a^n = a^{m+n}$ | Pangkat dijumlahkan jika basis sama |
| Pembagian | $\frac{a^m}{a^n} = a^{m-n}$ | Pangkat dikurangi jika basis sama |
| Perpangkatan | $(a^m)^n = a^{m \cdot n}$ | Pangkat dikalikan |
| Pangkat Perkalian | $(a \cdot b)^n = a^n \cdot b^n$ | Pangkat didistribusikan ke setiap basis |
| Pangkat Nol | $a^0 = 1, a \neq 0$ | Setiap bilangan (bukan nol) pangkat nol adalah satu |
| Pangkat Negatif | $a^{-n} = \frac{1}{a^n}$ | Menjadi penyebut untuk pangkat positif |

---

## 1.2 Logaritma

### 1.2.1 Logaritma sebagai Invers (Exploration - ZPD 2)
Logaritma adalah operasi kebalikan dari eksponen. Jika eksponen mencari hasil pangkat, logaritma mencari **besar pangkat** itu sendiri.

Bentuk Umum:
$${}^a\log b = c \iff a^c = b$$

**Syarat:** $a > 0, a \neq 1,$ dan $b > 0$.
- $a$: Basis atau bilangan pokok logaritma.
- $b$: Numerus (bilangan yang dicari logaritmanya).
- $c$: Hasil logaritma (nilai pangkat).

### 1.2.2 Sifat-Sifat Logaritma
Gunakan sifat-sifat ini untuk menyederhanakan perhitungan kompleks:

1. **Sifat Penjumlahan:** ${}^a\log b + {}^a\log d = {}^a\log (b \cdot d)$
2. **Sifat Pengurangan:** ${}^a\log b - {}^a\log d = {}^a\log (\frac{b}{d})$
3. **Sifat Pangkat:** ${}^a\log b^n = n \cdot {}^a\log b$
4. **Perubahan Basis:** ${}^a\log b = \frac{{}^c\log b}{{}^c\log a}$

---

## 1.3 Penerapan dalam Kehidupan (Engagement - ZPD 3)

Eksponen dan logaritma diaplikasikan secara luas melalui konsep **Pertumbuhan** dan **Peluruhan**.

### 1.3.1 Pertumbuhan Eksponensial
Digunakan dalam perhitungan bunga majemuk atau pertumbuhan bakteri.
$$M_n = M_0(1 + i)^n$$
*Keterangan: $M_n$ (jumlah akhir), $M_0$ (jumlah awal), $i$ (laju pertumbuhan), $n$ (periode).*

### 1.3.2 Peluruhan Eksponensial
Digunakan dalam penyusutan harga barang atau peluruhan zat radioaktif.
$$M_n = M_0(1 - i)^n$$

---

## 1.4 Strategi Belajar: Cognitive Load Management

Untuk menguasai materi ini tanpa kelelahan kognitif, ikuti langkah berikut:
1. **Otomatisasi Skema:** Jangan menghafal rumus secara terisolasi. Latihlah manipulasi aljabar sederhana pada sifat eksponen sebelum masuk ke logaritma.
2. **Scaffolding Removal:** Gunakan tabel sifat saat mengerjakan soal awal, namun cobalah untuk tidak melihat tabel saat memasuki tahap latihan mandiri.
3. **Productive Struggle:** Saat menemui soal logaritma yang sulit, kembalikan bentuknya ke dalam bentuk eksponen untuk melihat hubungan logisnya.

---

## Latihan Pemahaman

1. Sederhanakan bentuk berikut: $\frac{(2^3 \cdot 2^2)^2}{2^8}$.
2. Ubahlah bentuk eksponen $5^3 = 125$ ke dalam bentuk logaritma.
3. Tentukan nilai dari ${}^2\log 16 + {}^2\log 4 - {}^2\log 8$.
4. Sebuah koloni bakteri membelah diri menjadi dua setiap satu jam. Jika awalnya terdapat 100 bakteri, berapakah jumlah bakteri setelah 5 jam?
5. Gunakan sifat logaritma untuk menghitung nilai $x$ dari persamaan: ${}^3\log x = 4$.

---

## Glosarium

- **Eksponen:** Bilangan pangkat yang menunjukkan kekerapan perkalian berulang.
- **Logaritma:** Operasi matematika yang merupakan kebalikan dari eksponensial.
- **Basis:** Bilangan pokok dalam operasi pangkat atau logaritma.
- **Numerus:** Bilangan yang dicari nilai logaritmanya.
- **ZPD (Zone of Proximal Development):** Jarak antara apa yang dapat dilakukan pembelajar secara mandiri dan apa yang dapat mereka lakukan dengan bantuan.
- **Scaffolding:** Pemberian dukungan belajar yang disesuaikan, yang akan dikurangi seiring meningkatnya kemahiran siswa.
