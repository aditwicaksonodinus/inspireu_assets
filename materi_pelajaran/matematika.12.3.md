Materi ini membahas kombinatorik dan peluang sebagai dua topik yang saling berkaitan dalam menghitung banyak kemungkinan dan menaksir peluang suatu kejadian. Penguasaan materi ini penting untuk pengambilan keputusan, analisis data, pemodelan, dan pemecahan masalah diskret.

# Kombinatorik dan Peluang

## Tujuan Pembelajaran
Setelah mempelajari bab ini, kamu diharapkan mampu:
1. Memahami kaidah pencacahan dasar.
2. Menentukan banyak susunan dan pilihan dengan permutasi serta kombinasi.
3. Membedakan situasi yang memperhatikan urutan dan yang tidak.
4. Menggunakan faktorial dalam perhitungan kombinatorik.
5. Menentukan peluang kejadian sederhana dan majemuk.
6. Menyelesaikan masalah kontekstual yang melibatkan kombinatorik dan peluang.

## 3.1 Konsep Dasar Kombinatorik

Kombinatorik adalah cabang matematika yang mempelajari cara menghitung banyak kemungkinan penyusunan atau pemilihan objek tanpa harus mendaftar semuanya satu per satu. Ide dasarnya adalah efisiensi berpikir.

Dalam banyak situasi, jumlah kemungkinan sangat besar. Karena itu, diperlukan aturan sistematis agar perhitungan tetap akurat dan tidak berulang.

Contoh sederhana:
Jika seseorang memiliki 3 baju dan 2 celana, maka banyak pasangan pakaian yang dapat dipilih adalah 3 kali 2, yaitu 6. Contoh ini menunjukkan kaidah perkalian.

## 3.2 Kaidah Pencacahan

### 3.2.1 Kaidah Penjumlahan

Kaidah penjumlahan digunakan ketika beberapa pilihan tidak dapat terjadi secara bersamaan dalam satu langkah. Jika suatu pekerjaan dapat dilakukan dengan $m$ cara atau $n$ cara, maka total cara adalah:
$$
m+n
$$

Contoh:
Seorang siswa dapat memilih 4 buku matematika atau 3 buku fisika untuk dipinjam satu buku. Banyak pilihan yang tersedia adalah 7.

### 3.2.2 Kaidah Perkalian

Kaidah perkalian digunakan ketika suatu proses terdiri dari beberapa tahap yang dilakukan berurutan. Jika tahap pertama dapat dilakukan dengan $m$ cara dan tahap kedua dengan $n$ cara, maka total cara adalah:
$$
m\times n
$$

Contoh:
Tersedia 4 pilihan makanan dan 3 pilihan minuman. Banyak paket yang dapat dibentuk adalah $4\times 3=12$.

Kaidah ini dapat diperluas ke banyak tahap. Jika ada tiga tahap dengan banyak pilihan berturut-turut $a$, $b$, dan $c$, maka total kemungkinan adalah $abc$.

## 3.3 Faktorial

Faktorial sangat penting dalam kombinatorik. Untuk bilangan bulat positif $n$, didefinisikan:
$$
n!=n(n-1)(n-2)\cdots 2\cdot 1
$$

Selain itu, didefinisikan pula:
$$
0!=1
$$

Contoh:
- $5!=5\cdot 4\cdot 3\cdot 2\cdot 1=120$
- $3!=6$
- $1!=1$

Faktorial muncul ketika kita menghitung banyak cara menyusun objek yang berbeda.

## 3.4 Permutasi

Permutasi adalah penyusunan objek dengan memperhatikan urutan. Jika urutan berubah, maka susunan dianggap berbeda.

### 3.4.1 Permutasi $n$ Objek Berbeda

Banyak susunan dari $n$ objek berbeda adalah:
$$
P(n)=n!
$$

Contoh:
Tiga huruf A, B, dan C dapat disusun menjadi:
- ABC
- ACB
- BAC
- BCA
- CAB
- CBA

Totalnya ada $3!=6$ susunan.

### 3.4.2 Permutasi $r$ dari $n$ Objek

Jika dari $n$ objek berbeda dipilih dan disusun sebanyak $r$ objek, banyak susunannya adalah:
$$
{}_nP_r=\frac{n!}{(n-r)!}
$$

Contoh:
Dari 5 siswa akan dipilih ketua, sekretaris, dan bendahara. Karena jabatan berbeda, urutan penempatan penting. Banyak cara:
$$
{}_5P_3=\frac{5!}{2!}=5\cdot 4\cdot 3=60
$$

### 3.4.3 Permutasi dengan Unsur Sama

Jika ada unsur yang sama, maka banyak susunan berbeda berkurang. Untuk $n$ objek dengan beberapa objek identik, rumusnya:
$$
\frac{n!}{k_1!k_2!\cdots k_m!}
$$

Contoh:
Banyak susunan berbeda dari kata “MATA” adalah:
$$
\frac{4!}{2!}=12
$$
karena huruf A muncul dua kali.

## 3.5 Kombinasi

Kombinasi adalah pemilihan objek tanpa memperhatikan urutan. Jika urutan tidak penting, maka banyak hasil lebih sedikit dibanding permutasi.

Rumus kombinasi $r$ dari $n$ objek adalah:
$$
{}_nC_r=\frac{n!}{r!(n-r)!}
$$

Contoh:
Dari 5 siswa akan dipilih 2 orang untuk menjadi delegasi. Banyak cara memilih adalah:
$$
{}_5C_2=\frac{5!}{2!3!}=10
$$

Perhatikan bedanya dengan permutasi. Memilih Ani lalu Budi sama dengan memilih Budi lalu Ani jika yang diperhatikan hanya kelompoknya.

## 3.6 Membedakan Permutasi dan Kombinasi

Kesalahan yang sering terjadi adalah salah memilih rumus. Cara membedakannya adalah dengan melihat apakah posisi atau urutan memengaruhi hasil.

Gunakan permutasi jika:
- ada jabatan atau posisi berbeda,
- susunan kode, nomor, atau tempat duduk diperhatikan,
- urutan kejadian menghasilkan hasil berbeda.

Gunakan kombinasi jika:
- hanya memilih anggota kelompok,
- urutan tidak berpengaruh,
- hasil dipandang sebagai himpunan, bukan susunan.

Sebagai contoh, memilih 3 juara dari 10 peserta adalah permutasi jika juara 1, 2, dan 3 dibedakan. Namun memilih 3 wakil kelas dari 10 siswa adalah kombinasi jika tidak ada peran berbeda.

## 3.7 Konsep Dasar Peluang

Peluang adalah ukuran kemungkinan terjadinya suatu kejadian. Jika ruang sampel memiliki hasil yang sama peluangnya, maka peluang kejadian $A$ didefinisikan sebagai:
$$
P(A)=\frac{n(A)}{n(S)}
$$

di mana:
- $n(A)$ adalah banyak anggota kejadian $A$,
- $n(S)$ adalah banyak anggota ruang sampel.

Nilai peluang selalu memenuhi:
$$
0\leq P(A)\leq 1
$$

Jika peluang mendekati 0, kejadian sangat kecil kemungkinannya. Jika mendekati 1, kejadian sangat besar kemungkinannya.

## 3.8 Ruang Sampel dan Titik Sampel

Ruang sampel adalah himpunan semua hasil yang mungkin dari suatu percobaan. Anggota ruang sampel disebut titik sampel.

Contoh:
Pada pelemparan sebuah dadu, ruang sampelnya adalah:
$$
S=\{1,2,3,4,5,6\}
$$

Jika kejadian $A$ adalah muncul bilangan genap, maka:
$$
A=\{2,4,6\}
$$
Sehingga:
$$
P(A)=\frac{3}{6}=\frac{1}{2}
$$

## 3.9 Peluang Kejadian Komplemen

Jika $A$ adalah suatu kejadian, maka komplemennya, ditulis $A^c$, adalah kejadian bahwa $A$ tidak terjadi. Hubungan pentingnya:
$$
P(A^c)=1-P(A)
$$

Contoh:
Peluang muncul bilangan lebih dari 4 pada sebuah dadu adalah $\frac{2}{6}=\frac{1}{3}$. Maka peluang tidak muncul bilangan lebih dari 4 adalah:
$$
1-\frac{1}{3}=\frac{2}{3}
$$

Konsep komplemen sangat berguna ketika peluang kejadian yang diminta lebih mudah dihitung melalui lawannya.

## 3.10 Peluang Kejadian Majemuk

### 3.10.1 Kejadian Saling Lepas

Dua kejadian disebut saling lepas jika tidak dapat terjadi bersamaan. Untuk kejadian $A$ dan $B$ yang saling lepas:
$$
P(A\cup B)=P(A)+P(B)
$$

Contoh:
Pada pelemparan dadu, peluang muncul 1 atau 6 adalah:
$$
\frac{1}{6}+\frac{1}{6}=\frac{2}{6}=\frac{1}{3}
$$

### 3.10.2 Kejadian Independen

Dua kejadian disebut independen jika terjadinya salah satu kejadian tidak memengaruhi yang lain. Untuk kejadian independen berlaku:
$$
P(A\cap B)=P(A)\cdot P(B)
$$

Contoh:
Peluang memperoleh angka pada sebuah koin dan bilangan genap pada sebuah dadu adalah:
$$
\frac{1}{2}\cdot \frac{1}{2}=\frac{1}{4}
$$

## 3.11 Kombinatorik dalam Peluang

Banyak soal peluang lebih efisien diselesaikan dengan kombinatorik. Ketika ruang sampel sangat banyak, kita dapat menghitung banyak kejadian yang diinginkan dan membaginya dengan banyak semua kemungkinan.

Contoh:
Dari 5 bola merah dan 3 bola biru dipilih 2 bola sekaligus. Peluang terambil 2 bola merah adalah:
$$
P=\frac{{}_5C_2}{{}_8C_2}=\frac{10}{28}=\frac{5}{14}
$$

Di sini kombinasi digunakan karena urutan pengambilan tidak diperhatikan.

## 3.12 Strategi Menyelesaikan Soal

Untuk mengurangi kesalahan, gunakan langkah berikut:
1. Pahami konteks masalah dan tentukan apakah yang dicari adalah banyak cara atau peluang.
2. Tentukan apakah urutan penting.
3. Pilih kaidah penjumlahan, perkalian, permutasi, atau kombinasi.
4. Jika peluang diminta, tentukan ruang sampel dan kejadian yang sesuai.
5. Sederhanakan hasil akhir dan periksa kewajarannya.

Sebagai pemeriksaan, hasil peluang tidak boleh negatif dan tidak boleh lebih dari 1. Jika ini terjadi, biasanya ada kesalahan dalam ruang sampel atau pemilihan rumus.

## 3.13 Latihan Pemahaman

1. Berapa banyak susunan 4 huruf berbeda dapat dibuat dari huruf A, B, C, dan D?
2. Dari 7 siswa akan dipilih ketua dan wakil. Berapa banyak cara?
3. Dari 8 siswa dipilih 3 orang untuk tim lomba. Berapa banyak cara?
4. Hitung nilai $6!$.
5. Tentukan banyak susunan berbeda dari kata “DATA”.
6. Sebuah dadu dilempar sekali. Berapa peluang muncul bilangan prima?
7. Sebuah koin dan sebuah dadu dilempar bersamaan. Berapa peluang muncul gambar dan bilangan genap?
8. Dalam kotak terdapat 4 bola putih dan 6 bola hitam. Jika diambil 2 bola sekaligus, berapa peluang terambil 2 bola putih?
9. Jelaskan perbedaan permutasi dan kombinasi dengan satu contoh masing-masing.
10. Mengapa kombinatorik sangat membantu dalam penyelesaian soal peluang?

## Glosarium

- **Kombinatorik**: cabang matematika yang mempelajari pencacahan kemungkinan.
- **Kaidah penjumlahan**: aturan menghitung total pilihan yang saling terpisah.
- **Kaidah perkalian**: aturan menghitung total kemungkinan dari proses bertahap.
- **Faktorial**: hasil perkalian berurutan bilangan bulat positif hingga 1.
- **Permutasi**: penyusunan objek dengan memperhatikan urutan.
- **Kombinasi**: pemilihan objek tanpa memperhatikan urutan.
- **Ruang sampel**: himpunan semua hasil yang mungkin.
- **Kejadian**: himpunan bagian dari ruang sampel.
- **Peluang**: ukuran kemungkinan terjadinya suatu kejadian.
- **Komplemen**: kejadian bahwa suatu peristiwa tidak terjadi.
