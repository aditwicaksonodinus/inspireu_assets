Materi ini membahas turunan fungsi aljabar sebagai alat untuk mempelajari laju perubahan dan kecenderungan suatu fungsi. Turunan sangat penting karena digunakan untuk menganalisis kemiringan garis singgung, menentukan titik naik atau turun, serta menyelesaikan berbagai persoalan optimasi.

# Turunan Fungsi Aljabar

## Tujuan Pembelajaran
Setelah mempelajari bab ini, peserta didik diharapkan mampu:
1. Menjelaskan makna turunan sebagai laju perubahan.
2. Memahami hubungan turunan dengan gradien garis singgung.
3. Menentukan turunan fungsi aljabar sederhana.
4. Menggunakan aturan turunan dasar.
5. Menafsirkan turunan untuk menentukan interval naik dan turun secara sederhana.
6. Menggunakan turunan pada masalah kontekstual dasar.

## Apersepsi
Saat sebuah mobil bergerak, kita tidak hanya tertarik pada posisi, tetapi juga perubahan posisinya terhadap waktu, yaitu kecepatan. Gagasan perubahan seperti inilah yang menjadi inti turunan. Dalam matematika, turunan membantu kita mengukur seberapa cepat suatu fungsi berubah pada titik tertentu.

## Peta Konsep
- Makna turunan.
- Turunan sebagai gradien garis singgung.
- Aturan turunan dasar.
- Turunan fungsi polinomial.
- Aplikasi sederhana turunan.

## 7.1 Makna Turunan
Turunan fungsi di suatu titik menyatakan laju perubahan sesaat fungsi tersebut. Secara geometri, turunan dapat dipahami sebagai kemiringan garis singgung kurva di titik itu.

Jika suatu fungsi berubah cepat, nilai turunannya besar. Jika fungsi mendatar, nilai turunannya mendekati nol.

## 7.2 Hubungan dengan Limit
Secara konseptual, turunan didefinisikan melalui limit:

$$f'(x)=\lim_{h \to 0}\frac{f(x+h)-f(x)}{h}$$

Rumus ini menunjukkan bahwa turunan berasal dari perubahan rata-rata yang diamati pada selang sangat kecil, lalu dibawa menuju perubahan sesaat.

## 7.3 Aturan Turunan Dasar
Beberapa aturan dasar turunan:
- turunan konstanta: jika $f(x)=c$, maka $f'(x)=0$
- turunan $x$: jika $f(x)=x$, maka $f'(x)=1$
- turunan pangkat: jika $f(x)=x^n$, maka $f'(x)=nx^{n-1}$

Contoh:
- jika $f(x)=x^3$, maka $f'(x)=3x^2$
- jika $f(x)=5x^4$, maka $f'(x)=20x^3$

## 7.4 Turunan Jumlah dan Selisih
Jika:

$$f(x)=u(x) \pm v(x)$$

maka:

$$f'(x)=u'(x) \pm v'(x)$$

Contoh:
Jika $f(x)=x^3+2x^2-5x+7$, maka:

$$f'(x)=3x^2+4x-5$$

Aturan ini memudahkan penurunan fungsi polinomial yang tersusun dari beberapa suku.

## 7.5 Turunan Fungsi Polinomial
Untuk fungsi polinomial, turunan dapat dicari dengan menurunkan setiap suku sesuai aturan pangkat.

Contoh:

$$f(x)=4x^3-3x^2+2x-8$$

Maka:

$$f'(x)=12x^2-6x+2$$

Pada tahap ini, fokus utama peserta didik adalah ketelitian membaca pangkat dan koefisien.

## 7.6 Interpretasi Gradien
Jika $f'(a)>0$, maka di sekitar $x=a$ fungsi cenderung naik. Jika $f'(a)<0$, fungsi cenderung turun. Jika $f'(a)=0$, titik tersebut dapat menjadi titik stasioner yang perlu dianalisis lebih lanjut.

Contoh:
Jika $f'(2)=5$, maka kurva di sekitar $x=2$ memiliki kemiringan positif. Artinya fungsi sedang meningkat pada sekitar titik itu.

## 7.7 Aplikasi Sederhana
Turunan dapat digunakan untuk:
- menentukan kecepatan sesaat
- menentukan kemiringan kurva
- membantu mencari nilai maksimum atau minimum
- menganalisis kecenderungan naik dan turun fungsi

Contoh sederhana:
Jika tinggi benda dinyatakan oleh fungsi kuadrat terhadap waktu, maka turunannya dapat menafsirkan kecepatan vertikal benda tersebut.

## 7.8 Menentukan Interval Naik dan Turun
Untuk analisis sederhana, kita dapat melihat tanda turunan.
- jika $f'(x)>0$, fungsi naik
- jika $f'(x)<0$, fungsi turun

Contoh:
Jika:

$$f(x)=x^2-4x+1$$

maka:

$$f'(x)=2x-4$$

Turunan bernilai nol saat $x=2$. Maka:
- untuk $x<2$, turunan negatif, fungsi turun
- untuk $x>2$, turunan positif, fungsi naik

Dengan demikian, titik $x=2$ berkaitan dengan titik minimum.

## 7.9 Aktivitas Belajar
- Bandingkan gradien beberapa garis lurus dan hubungkan dengan gagasan laju perubahan.
- Turunkan beberapa fungsi polinomial sederhana.
- Tentukan tanda turunan pada beberapa interval.
- Diskusikan hubungan antara turunan nol dan titik belok perubahan arah kecenderungan fungsi.

## 7.10 Latihan Pemahaman
1. Tentukan turunan dari $f(x)=x^5$.
2. Tentukan turunan dari $f(x)=3x^4-2x+7$.
3. Tentukan turunan dari $f(x)=6x^2-5x+1$.
4. Jika $f(x)=x^2+3x$, hitung $f'(2)$.
5. Jelaskan makna turunan sebagai laju perubahan.
6. Mengapa turunan konstanta bernilai nol?
7. Jika $f'(x)$ positif pada suatu interval, apa artinya?
8. Tentukan titik stasioner dari $f(x)=x^2-6x+5$ melalui turunannya.
9. Mengapa turunan berkaitan dengan garis singgung?
10. Apa manfaat turunan dalam masalah optimasi?

## Refleksi
Jika kamu sudah dapat menghubungkan turunan dengan perubahan dan kemiringan, maka topik ini tidak lagi tampak hanya sebagai aturan simbolik. Jika masih kesulitan, perkuat dulu intuisi melalui grafik dan makna gerak sebelum memperbanyak latihan prosedural.

## Glosarium
- **Turunan**: ukuran laju perubahan sesaat suatu fungsi.
- **Garis singgung**: garis yang menyentuh kurva pada satu titik dengan arah kemiringan yang sama.
- **Gradien**: ukuran kemiringan garis.
- **Titik stasioner**: titik saat turunan bernilai nol.
- **Fungsi naik**: fungsi yang nilainya cenderung bertambah.
- **Fungsi turun**: fungsi yang nilainya cenderung berkurang.
