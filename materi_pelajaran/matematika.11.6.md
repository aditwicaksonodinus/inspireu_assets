Materi ini membahas limit fungsi aljabar sebagai gagasan tentang nilai yang didekati suatu fungsi ketika peubah mendekati nilai tertentu. Limit menjadi konsep kunci karena menjadi landasan untuk memahami kekontinuan, turunan, dan analisis perubahan secara lebih mendalam.

# Limit Fungsi Aljabar

## Tujuan Pembelajaran
Setelah mempelajari bab ini, peserta didik diharapkan mampu:
1. Menjelaskan makna limit secara intuitif.
2. Menentukan limit fungsi aljabar dengan substitusi langsung pada kasus sederhana.
3. Menentukan limit pada bentuk tak tentu sederhana melalui pemfaktoran.
4. Menentukan limit satu sisi secara dasar.
5. Menafsirkan makna limit dalam tabel, grafik, dan konteks fungsi.

## Apersepsi
Sering kali kita ingin mengetahui kecenderungan nilai suatu fungsi di sekitar titik tertentu, bahkan ketika nilai fungsi tepat di titik itu belum tentu mudah dihitung. Di sinilah limit berperan. Limit tidak selalu bertanya “berapa nilai fungsi di titik itu”, melainkan “mendekati nilai berapa fungsi tersebut saat input mendekati titik itu”.

## Peta Konsep
- Makna intuitif limit.
- Notasi limit.
- Substitusi langsung.
- Bentuk tak tentu dan pemfaktoran.
- Limit satu sisi.
- Hubungan limit dengan grafik.

## 6.1 Pengertian Intuitif Limit
Jika nilai $f(x)$ mendekati suatu bilangan tertentu saat $x$ mendekati $a$, maka dikatakan limit $f(x)$ saat $x$ mendekati $a$ adalah bilangan itu.

Ditulis:

$$\lim_{x \to a} f(x) = L$$

Artinya, ketika $x$ semakin dekat ke $a$, maka $f(x)$ semakin dekat ke $L$.

## 6.2 Limit melalui Tabel Nilai
Contoh:
Perhatikan fungsi $f(x)=2x+1$ saat $x$ mendekati 3.

Jika $x=2.9$, maka $f(x)=6.8$
Jika $x=2.99$, maka $f(x)=6.98$
Jika $x=3.01$, maka $f(x)=7.02$

Terlihat bahwa nilai $f(x)$ mendekati 7. Maka:

$$\lim_{x \to 3} (2x+1) = 7$$

Pendekatan tabel membantu peserta didik memahami limit sebagai kecenderungan, bukan semata prosedur simbolik.

## 6.3 Substitusi Langsung
Untuk banyak fungsi aljabar yang sederhana, limit dapat ditentukan langsung dengan mensubstitusi nilai yang didekati.

Contoh:

$$\lim_{x \to 2} (x^2+3x-1) = 2^2+3(2)-1 = 9$$

Metode ini berlaku jika fungsi terdefinisi dengan baik di titik tersebut dan tidak menghasilkan bentuk tak tentu.

## 6.4 Bentuk Tak Tentu
Kadang substitusi langsung menghasilkan bentuk seperti:

$$\frac{0}{0}$$

Bentuk ini disebut tak tentu. Dalam kasus seperti ini, kita perlu menyederhanakan fungsi lebih dahulu, misalnya dengan pemfaktoran.

Contoh:

$$\lim_{x \to 2} \frac{x^2-4}{x-2}$$

Jika langsung disubstitusi, diperoleh $\frac{0}{0}$. Faktorkan pembilang:

$$x^2-4=(x-2)(x+2)$$

Sehingga:

$$\frac{x^2-4}{x-2} = x+2 \quad \text{untuk} \quad x \neq 2$$

Maka:

$$\lim_{x \to 2} \frac{x^2-4}{x-2} = \lim_{x \to 2} (x+2)=4$$

## 6.5 Limit Fungsi Pecahan Aljabar
Contoh lain:

$$\lim_{x \to 1} \frac{x^2-1}{x-1}$$

Faktorkan:

$$x^2-1=(x-1)(x+1)$$

Sehingga:

$$\lim_{x \to 1} \frac{x^2-1}{x-1} = \lim_{x \to 1}(x+1)=2$$

Peserta didik perlu melihat bahwa penyederhanaan dilakukan bukan untuk mengganti nilai fungsi di titik itu, melainkan untuk menentukan kecenderungan nilainya saat mendekati titik tersebut.

## 6.6 Limit Satu Sisi
Kadang kita memperhatikan perilaku fungsi dari kiri atau dari kanan.

- limit kiri ditulis $\lim_{x \to a^-} f(x)$
- limit kanan ditulis $\lim_{x \to a^+} f(x)$

Limit dua sisi ada jika limit kiri dan limit kanan sama.

Contoh konseptual:
Jika suatu fungsi bernilai berbeda saat didekati dari kiri dan dari kanan, maka limit di titik itu tidak ada.

## 6.7 Hubungan dengan Grafik
Secara grafik, limit adalah nilai ordinat yang didekati kurva ketika absis mendekati suatu titik tertentu. Karena itu, limit dapat ada meskipun nilai fungsi di titik tersebut tidak didefinisikan atau berbeda.

Pemahaman ini sangat penting agar peserta didik tidak selalu menyamakan limit dengan nilai fungsi.

## 6.8 Strategi Menentukan Limit
1. Coba substitusi langsung terlebih dahulu.
2. Jika hasilnya bukan bentuk tak tentu, selesai.
3. Jika muncul bentuk tak tentu, sederhanakan, misalnya dengan pemfaktoran.
4. Periksa kembali nilai limit dari bentuk yang sudah disederhanakan.
5. Bila perlu, perhatikan limit kiri dan limit kanan.

## 6.9 Aktivitas Belajar
- Buat tabel nilai untuk suatu fungsi saat $x$ mendekati bilangan tertentu.
- Bandingkan nilai fungsi dan nilai limit pada contoh yang menghasilkan bentuk tak tentu.
- Latih pemfaktoran untuk menyederhanakan bentuk limit.
- Gambarkan sketsa sederhana untuk menjelaskan limit kiri dan limit kanan.

## 6.10 Latihan Pemahaman
1. Tentukan $\lim_{x \to 4}(3x-5)$.
2. Tentukan $\lim_{x \to 2}(x^2+1)$.
3. Tentukan $\lim_{x \to 3}\frac{x^2-9}{x-3}$.
4. Tentukan $\lim_{x \to 1}\frac{x^2+x-2}{x-1}$.
5. Mengapa bentuk $\frac{0}{0}$ disebut tak tentu?
6. Jelaskan perbedaan nilai fungsi dan nilai limit.
7. Kapan limit dua sisi dikatakan ada?
8. Mengapa pemfaktoran membantu pada limit fungsi aljabar?
9. Apa makna simbol $x \to a$?
10. Mengapa limit menjadi penting sebelum mempelajari turunan?

## Refleksi
Jika kamu sudah memahami limit sebagai kecenderungan nilai, maka prosedur hitungnya akan terasa lebih masuk akal. Jika masih kesulitan, jangan langsung fokus pada simbol, tetapi mulai dari tabel nilai dan grafik sederhana agar ide mendekati menjadi lebih konkret.

## Glosarium
- **Limit**: nilai yang didekati fungsi ketika peubah mendekati nilai tertentu.
- **Bentuk tak tentu**: bentuk yang belum langsung menentukan limit, seperti $\frac{0}{0}$.
- **Limit kiri**: limit saat mendekati dari sisi kiri.
- **Limit kanan**: limit saat mendekati dari sisi kanan.
- **Substitusi langsung**: mengganti peubah dengan nilai yang didekati.
- **Pemfaktoran**: penyederhanaan bentuk aljabar dengan menguraikan faktor-faktornya.
