Materi ini membahas transformasi fungsi sebagai cara memahami perubahan bentuk grafik melalui translasi, refleksi, peregangan, penyusutan, dan komposisi transformasi. Topik ini penting karena membantu siswa melihat hubungan antara bentuk aljabar fungsi dan perubahan geometris grafik secara sistematis.

# Transformasi Fungsi

## Tujuan Pembelajaran
Setelah mempelajari bab ini, kamu diharapkan mampu:
1. Memahami makna transformasi fungsi sebagai perubahan grafik dari fungsi asal.
2. Menjelaskan translasi vertikal dan horizontal pada grafik fungsi.
3. Menjelaskan refleksi grafik terhadap sumbu-X, sumbu-Y, dan garis tertentu.
4. Menjelaskan dilatasi atau skala vertikal dan horizontal pada fungsi.
5. Menentukan hasil komposisi beberapa transformasi fungsi.
6. Menggunakan transformasi fungsi untuk menganalisis grafik fungsi sederhana.

## 1.1 Konsep Dasar Transformasi Fungsi

Suatu fungsi dapat dipandang sebagai aturan yang memasangkan setiap nilai masukan dengan suatu nilai keluaran. Ketika bentuk fungsi diubah, grafiknya juga mengalami perubahan. Perubahan inilah yang disebut transformasi fungsi.

Jika fungsi asal dinyatakan dengan $y=f(x)$, maka bentuk-bentuk seperti $y=f(x)+k$, $y=f(x-h)$, atau $y=af(x)$ menunjukkan adanya transformasi tertentu terhadap grafik asal. Dengan demikian, transformasi fungsi adalah jembatan antara representasi aljabar dan representasi geometri.

Sebagai fungsi acuan, sering digunakan fungsi sederhana seperti:
- $f(x)=x^2$
- $f(x)=|x|$
- $f(x)=\sqrt{x}$
- $f(x)=\sin x$

Melalui fungsi acuan ini, perubahan grafik dapat diamati dengan lebih jelas.

## 1.2 Translasi Grafik

Translasi adalah pergeseran grafik tanpa mengubah bentuk dasarnya. Translasi dapat terjadi secara vertikal maupun horizontal.

### 1.2.1 Translasi Vertikal

Bentuk umum translasi vertikal adalah:
$$
y=f(x)+k
$$

- Jika $k>0$, grafik bergeser ke atas sejauh $k$ satuan.
- Jika $k<0$, grafik bergeser ke bawah sejauh $|k|$ satuan.

Contoh:
Jika $f(x)=x^2$, maka fungsi $y=x^2+3$ adalah grafik parabola $y=x^2$ yang bergeser 3 satuan ke atas.

Misalnya titik puncak parabola semula di $(0,0)$, maka setelah transformasi menjadi $(0,3)$.

### 1.2.2 Translasi Horizontal

Bentuk umum translasi horizontal adalah:
$$
y=f(x-h)
$$

- Jika $h>0$, grafik bergeser ke kanan sejauh $h$ satuan.
- Jika $h<0$, grafik bergeser ke kiri sejauh $|h|$ satuan.

Perlu diperhatikan bahwa tanda pada variabel sering terasa “berlawanan” dengan arah geser. Bentuk $f(x-2)$ justru menggeser grafik ke kanan 2 satuan.

Contoh:
Jika $f(x)=x^2$, maka $y=(x-2)^2$ adalah parabola yang bergeser ke kanan 2 satuan. Titik puncaknya berubah dari $(0,0)$ menjadi $(2,0)$.

## 1.3 Refleksi Grafik

Refleksi adalah pencerminan grafik terhadap garis tertentu. Transformasi ini mengubah orientasi grafik, tetapi tidak mengubah ukuran dasar grafik.

### 1.3.1 Refleksi terhadap Sumbu-X

Bentuk umumnya:
$$
y=-f(x)
$$

Setiap nilai keluaran fungsi berubah tanda, sehingga titik $(x,y)$ menjadi $(x,-y)$.

Contoh:
Jika $f(x)=x^2$, maka $y=-x^2$ adalah hasil pencerminan parabola $y=x^2$ terhadap sumbu-X.

### 1.3.2 Refleksi terhadap Sumbu-Y

Bentuk umumnya:
$$
y=f(-x)
$$

Setiap titik $(x,y)$ berubah menjadi $(-x,y)$. Transformasi ini sering digunakan untuk memeriksa kesimetrian fungsi.

Contoh:
Jika $f(x)=x^3+1$, maka fungsi hasil refleksi terhadap sumbu-Y adalah:
$$
y=f(-x)=(-x)^3+1=-x^3+1
$$

### 1.3.3 Refleksi terhadap Garis $y=x$

Refleksi terhadap garis $y=x$ menghasilkan pertukaran posisi koordinat, yaitu dari $(x,y)$ menjadi $(y,x)$. Dalam konteks fungsi, refleksi ini berkaitan dengan fungsi invers, jika inversnya ada.

Contoh sederhana:
Jika $y=2x+1$, maka setelah ditukar diperoleh:
$$
x=2y+1
$$
Sehingga:
$$
y=\frac{x-1}{2}
$$

Hasil tersebut merupakan invers dari fungsi semula.

## 1.4 Dilatasi Grafik

Dilatasi adalah transformasi yang mengubah skala grafik. Grafik dapat menjadi lebih “tinggi”, lebih “rendah”, lebih “sempit”, atau lebih “lebar”.

### 1.4.1 Dilatasi Vertikal

Bentuk umumnya:
$$
y=af(x)
$$

- Jika $a>1$, grafik mengalami peregangan vertikal.
- Jika $0<a<1$, grafik mengalami penyusutan vertikal.
- Jika $a<0$, selain terjadi skala juga terjadi refleksi terhadap sumbu-X.

Contoh:
Jika $f(x)=x^2$, maka $y=2x^2$ lebih sempit daripada $y=x^2$ karena semua nilai $y$ menjadi dua kali lipat.

### 1.4.2 Dilatasi Horizontal

Bentuk umum yang sering digunakan adalah:
$$
y=f(bx)
$$

- Jika $b>1$, grafik mengalami penyusutan horizontal.
- Jika $0<b<1$, grafik mengalami peregangan horizontal.

Contoh:
Jika $f(x)=\sin x$, maka $y=\sin 2x$ memiliki periode yang lebih pendek daripada $y=\sin x$. Artinya grafik menjadi lebih rapat secara horizontal.

## 1.5 Transformasi pada Fungsi Nilai Mutlak

Fungsi nilai mutlak sering dipakai karena bentuk grafiknya mudah diamati. Fungsi dasar $y=|x|$ memiliki titik puncak di $(0,0)$ dan simetri terhadap sumbu-Y.

Perhatikan fungsi:
$$
y=2|x-3|-4
$$

Analisis transformasinya:
- Bentuk $x-3$ berarti geser ke kanan 3 satuan.
- Faktor 2 di depan berarti peregangan vertikal dengan skala 2.
- Angka $-4$ di luar berarti geser ke bawah 4 satuan.

Dengan demikian, titik puncak grafik berubah dari $(0,0)$ menjadi $(3,-4)$.

## 1.6 Transformasi pada Fungsi Kuadrat

Fungsi kuadrat sangat penting dalam transformasi karena bentuk puncaknya mudah ditelusuri. Bentuk umum transformasi fungsi kuadrat adalah:
$$
y=a(x-h)^2+k
$$

Dari bentuk tersebut dapat dibaca bahwa:
- titik puncak berada di $(h,k)$,
- grafik membuka ke atas jika $a>0$,
- grafik membuka ke bawah jika $a<0$,
- grafik lebih sempit jika $|a|>1$,
- grafik lebih lebar jika $0<|a|<1$.

Contoh:
$$
y=-3(x+1)^2+2
$$

Interpretasinya:
- Geser ke kiri 1 satuan.
- Geser ke atas 2 satuan.
- Refleksi terhadap sumbu-X karena $a<0$.
- Peregangan vertikal faktor 3.

Maka titik puncaknya adalah $(-1,2)$.

## 1.7 Komposisi Transformasi

Dalam banyak soal, sebuah grafik mengalami lebih dari satu transformasi. Karena itu, siswa perlu membaca transformasi secara bertahap dari bentuk aljabarnya.

Misalkan:
$$
y=-2f(x-1)+5
$$

Urutan pembacaan yang aman adalah:
1. Grafik $f(x)$ digeser ke kanan 1 satuan.
2. Hasilnya diregangkan vertikal dengan faktor 2.
3. Karena bertanda negatif, grafik direfleksikan terhadap sumbu-X.
4. Terakhir, grafik digeser ke atas 5 satuan.

Membaca transformasi secara bertahap membantu mengurangi beban kognitif ketika bentuk fungsi tampak rumit.

## 1.8 Strategi Menganalisis Transformasi

Agar tidak keliru, analisis transformasi dapat dilakukan dengan langkah berikut:
1. Tentukan fungsi dasar yang dikenali.
2. Perhatikan perubahan pada bagian dalam fungsi, misalnya $x-h$ atau $bx$.
3. Perhatikan perubahan pada bagian luar fungsi, misalnya $af(x)+k$.
4. Tentukan titik-titik penting seperti puncak, titik potong, atau simetri.
5. Gambarkan perubahan secara bertahap.

Sebagai ilustrasi, pada fungsi $y=-(x-2)^2+1$, kita mulai dari $y=x^2$, lalu geser ke kanan 2 satuan, refleksi terhadap sumbu-X, dan akhirnya geser ke atas 1 satuan.

## 1.9 Penerapan dalam Pemodelan

Transformasi fungsi tidak hanya digunakan dalam menggambar grafik, tetapi juga dalam pemodelan. Dalam fisika, pergeseran grafik dapat menggambarkan perubahan posisi awal. Dalam ekonomi, transformasi dapat mewakili perubahan skala biaya atau pendapatan. Dalam komputasi dan pemrosesan sinyal, transformasi membantu membaca perubahan amplitudo dan fase.

Dengan demikian, transformasi fungsi adalah alat untuk memahami bagaimana suatu model berubah tanpa harus membangun model baru dari nol.

## 1.10 Latihan Pemahaman

1. Tentukan arah dan besar translasi dari fungsi $y=(x-4)^2+5$ terhadap $y=x^2$.
2. Jelaskan perubahan grafik dari $y=-x^2$ terhadap $y=x^2$.
3. Tentukan hasil refleksi fungsi $y=2x-3$ terhadap garis $y=x$.
4. Bandingkan grafik $y=x^2$ dan $y=3x^2$.
5. Tentukan titik puncak fungsi $y=(x+2)^2-7$.
6. Uraikan transformasi pada fungsi $y=-2|x-1|+4$.
7. Tentukan pengaruh bentuk $y=f(x+3)$ terhadap grafik $y=f(x)$.
8. Tentukan pengaruh bentuk $y=f(\tfrac{1}{2}x)$ terhadap lebar grafik.
9. Gambarkan secara deskriptif transformasi pada $y=-(x-3)^2-2$.
10. Mengapa urutan membaca transformasi penting dalam analisis grafik?

## Glosarium

- **Transformasi fungsi**: perubahan grafik fungsi dari bentuk asal ke bentuk baru.
- **Translasi**: pergeseran grafik tanpa mengubah bentuk dasar.
- **Refleksi**: pencerminan grafik terhadap garis tertentu.
- **Dilatasi**: perubahan skala grafik secara vertikal atau horizontal.
- **Fungsi dasar**: fungsi acuan yang digunakan untuk membaca transformasi.
- **Komposisi transformasi**: gabungan dua atau lebih transformasi pada satu grafik.
- **Fungsi invers**: fungsi yang membalik proses fungsi asal, sering terkait refleksi terhadap garis $y=x$.
