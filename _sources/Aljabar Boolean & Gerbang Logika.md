---
title: Aljabar Boolean & Gerbang Logika

---

# Aljabar Boolean & Gerbang Logika
## Pengertian
### Aljabar Boolean
Aljabar Boolean adalah kategori aljabar yang nilai variabelnya adalah nilai kebenaran, benar dan salah, yang biasanya dilambangkan dengan 1 dan 0. Aljabar ini digunakan untuk menganalisis dan menyederhanakan rangkaian digital atau gerbang digital . Aljabar ini juga disebut Aljabar Biner atau Aljabar Logika .  Aljabar ini telah menjadi dasar dalam pengembangan elektronika digital dan tersedia dalam semua bahasa pemrograman modern. Aljabar ini juga digunakan dalam teori himpunan dan statistik.

#### Operasi Aljabar Boolean
Operasi dasar aljabar Boolean adalah sebagai berikut:

* Operasi Konjungsi atau AND
* Operasi Disjungsi atau OR
* Operasi Negasi atau Tidak
 

Berikut adalah tabel yang mendefinisikan simbol untuk ketiga operasi dasar.


| Operator | Simbol | Hak Lebih Tinggi|
| -------- | -------- | -------- |
| Bukan     | ' (atau) ¬     | Paling Tinggi     |
| Dan     | . (atau) ∧     | Tengah     |
| Atau     | + (atau) ∨    | Terendah     |

Misalkan A dan B adalah dua variabel Boolean, maka kita dapat mendefinisikan ketiga operasi tersebut sebagai;

* Konjungsi B atau A DAN B, memenuhi A ∧ B = Benar, jika A = B = Benar atau A ∧ B = Salah.
* Disjungsi B atau A ATAU B, memenuhi A ∨ B = Salah, jika A = B = Salah, jika tidak A ∨ B = Benar.
* Negasi A atau ¬A memenuhi ¬A = Salah, jika A = Benar dan ¬A = Benar jika A = Salah


### Gerbang Logika
Gerbang logika atau logic gate adalah bagian dasar dari perancangan sistem elektronika digital untuk mengubah masukan (input) menjadi sinyal keluaran (output) yang logis sebagai hasil dari voltase atau arus.

#### Jenis Gerbang Logika
Mengutip Universitas Sains dan Teknologi Komputer, ada sejumlah jenis logic gate yang digunakan secara umum. Berikut adalah tujuh jenis gerbang logika:

1. Gerbang AND
Gerbang AND merupakan jenis gerbang logika yang memerlukan dua input atau lebih untuk menghasilkan satu output. Hasil output akan berupa 0 bila semua atau salah satu inputnya merupakan bilangan biner 0. Sebaliknya, jika semua input adalah bilangan biner 1, outputnya pun juga 1.

1. **Gerbang OR**
Jenis kedua adalah gerbang OR, yaitu jenis gerbang logika yang sama seperti gerbang AND, memerlukan dua input untuk menghasilkan satu output. Gerbang OR menghasilkan input 1 bila semua atau salah satu input adalah bilangan biner 1. Sementara itu, output menghasilkan 0 bila inputnya bilangan biner 0.

1. **Gerbang NOT**
Gerbang NOT merupakan jenis gerbang yang berfungsi sebagai pembalik keadaan. Bila input bernilai 1, outputnya bernilai 0. Begitupun sebaliknya, output bernilai 1 bila inputnya bernilai 0.

1. **Gerbang NAND**
Jenis gerbang ini merupakan gabungan gerbang AND dan NOT. Artinya, nilai output gerbang NAND adalah kebalikan dari gerbang AND.

1. **Gerbang NOR**
Gerbang ini menjadi gabungan dari gerbang OR dan NOT. Output yang dihasilkan NOR adalah kebalikan dari gerbang OR.

1. **Gerbang XOR**
Jenis gerbang logika berikutnya adalah XOR yang membutuhkan dua input juga untuk menghasilkan satu output. Dalam jenis gerbang ini, output yang dihasilkan adalah bilangan biner 1 jika kedua inputnya memiliki bilangan yang berbeda. Sementara itu, bila kedua inputnya merupakan bilangan yang sama, hasil outputnya adalah bilangan biner 0.

1. **Gerbang XNOR**
Gerbang terakhir adalah XNOR. Gerbang ini adalah kebalikan dari XNOR. Bila kedua input yang dimasukkan berbeda, outputnya yang dihasilkan bilangan biner 0. Outputnya akan berupa bilangan biner 1 bila kedua input yang dimasukkan sama.

**Operator Biner:**
Aljabar Boolean memiliki dua operator biner:
Penjumlahan (+): Digunakan untuk operasi disjungsi (OR).
Perkalian (⋅): Digunakan untuk operasi konjungsi (AND).

**Operator Uner:**
Komplemen (’): Digunakan untuk menghasilkan nilai yang berlawanan dari suatu elemen. Misalnya, jika a = 1, maka a’ = 0, dan sebaliknya.

## Manfaat Dalam Pemrograman
Aljabar Boolean sering digunakan dalam pemrograman untuk mengevaluasi ekspresi logika.

### Contoh Dalam Pemrograman Python
![Picture1](https://hackmd.io/_uploads/ryXs-Mby1l.png)

**1. Aksioma-Aksioma:**
Untuk setiap a, b, c ∈ B, berlaku aksioma-aksioma berikut:
* Closure: a + b ∈ B dan a ⋅ b ∈ B.
* Identitas: a + 0 = a dan a ⋅ 1 = a.
* Komutatif: a + b = b + a dan a ⋅ b = b ⋅ a.
* Distributif: a ⋅ (b + c) = (a ⋅ b) + (a ⋅ c) dan a + (b ⋅ c) = (a + b) ⋅ (a + c).
* Komplemen: Untuk setiap a ∈ B, terdapat elemen unik a’ ∈ B sehingga a + a’ = 1 dan a ⋅ a’ = 0

---

* Aljabar Boolean adalah sistem matematika untuk manipulasi variabel yang dapat memiliki salah satu dari dua nilai.  
* Dalam logika formal, nilai-nilai ini adalah "benar" dan "salah."  
* Dalam sistem digital, nilai-nilai ini adalah "nyala" dan "mati," 1 dan 0, atau "tinggi" dan "rendah."  
* Ekspresi Boolean dibuat dengan melakukan operasi pada variabel Boolean.  
* Operator Boolean yang umum termasuk AND (AND), (OR), dan (NOT).

## Aljabar Boolean
* Sebuah operator Boolean dapat dijelaskan sepenuhnya menggunakan tabel kebenaran.  
* Tabel kebenaran untuk operator Boolean D (AND) dan (OR) ditunjukkan di sebelah kanan.  
* Operator AND  juga dikenal sebagai produk Boolean. Operator OR adalah jumlah Boolean..
![x and y](https://hackmd.io/_uploads/rk0nZp_ykg.png)

## Boolean Algebra
* Tabel kebenaran untuk operator Boolean (NOT) ditunjukkan di sebelah kanan.  
* Operasi NOT paling sering dilambangkan dengan garis atas. 
![Picture1](https://hackmd.io/_uploads/rJcVMTuy1e.png)
* Sebuah fungsi Boolean memiliki:  
  * Setidaknya satu variabel Boolean,  
  * Setidaknya satu operator Boolean, dan  
  * Setidaknya satu input dari himpunan {0,1}.  
* Fungsi ini menghasilkan output yang juga merupakan anggota dari himpunan {0,1}.
* Tabel kebenaran untuk fungsi Boolean. : 
![Picture2](https://hackmd.io/_uploads/rJveQa_1Jg.png)
* Untuk mempermudah evaluasi fungsi Boolean, tabel kebenaran berisi kolom tambahan (diarsir) untuk menyimpan evaluasi dari bagian-bagian subfungsi.
![Picture3](https://hackmd.io/_uploads/ryTQQT_1Jx.png)
![Picture4](https://hackmd.io/_uploads/r1U4mpuk1g.png)
* Sebagian besar identitas Boolean memiliki bentuk AND (perkallian) serta bentuk OR (jumlah). Kami menyajikan identitas kami menggunakan kedua bentuk tersebut. 
![Picture5](https://hackmd.io/_uploads/HkjFXaOk1l.png)
* Kelompok kedua
![Picture6](https://hackmd.io/_uploads/rkfk4T_JJg.png)
* Kelompok Ketiga
![Picture7](https://hackmd.io/_uploads/By21NTu1yl.png)
* Terkadang, lebih ekonomis membangun sirkuit dengan menggunakan komplemen fungsi dan mengkomplementasi hasilnya dibandingkan mengimplementasikan fungsi secara langsung. Hukum DeMorgan memudahkan penemuan komplemen dari fungsi Boolean, yang menyatakan: :
![Picture8](https://hackmd.io/_uploads/By17Epd1yx.png)

## Logic Gates
* Fungsi Boolean diimplementasikan dalam sirkuit komputer digital yang disebut gerbang (gates).  
* Gerbang adalah perangkat elektronik yang menghasilkan hasil berdasarkan dua atau lebih nilai input.  
* Dalam kenyataannya, gerbang terdiri dari satu hingga enam transistor, tetapi desainer digital menganggapnya sebagai satu kesatuan.  
* Sirkuit terintegrasi mengandung kumpulan gerbang yang sesuai untuk tujuan tertentu..
* Tiga gerbang AND, OR, dan  NOT.
![Picture9](https://hackmd.io/_uploads/BJQoNTOk1x.png)
* Gerbang yang sangat berguna lainnya adalah gerbang eksklusif OR (XOR).  
* Output dari operasi XOR adalah benar hanya ketika nilai-nilai input berbeda.
![Picture10](https://hackmd.io/_uploads/H1kBSa_1kl.png)
Note the special symbol  for the XOR operation.
* NAND dan NOR dua gerbang yang sangat penting. Simbol dan tabel kebenarannya ditunjukkan di sebelah kanan. 
![Picture11](https://hackmd.io/_uploads/BJftHp_Jke.png)


## Gerbang Logika
* NAND dan NOR dikenal dengan gerbang universal  karena mereka murah untuk diproduksi dan setiap fungsi Boolean dapat dibangun menggunakan gerbang ini. NAND atau hanya gerbang NOR .  
![Picture12](https://hackmd.io/_uploads/SyrpB6_y1g.png)

## Logic Gates
* Gerbang dapat memiliki beberapa  inputs dan dan lebih dari satu output.
  * Output kedua dapat disediakan untuk komplemen dari operasi. 
  ![Picture17](https://hackmd.io/_uploads/H1WnPpOJyx.png)


## Komponen Digital
* Hal utama yang perlu diingat adalah bahwa kombinasi gerbang menerapkan fungsi Boolean.
* Rangkaian di bawah ini mengimplementasikan fungsi Boolean :
![Picture18](https://hackmd.io/_uploads/BkQJ_6Okyg.png)
![Picture19](https://hackmd.io/_uploads/r121ua_J1g.png)
Kami menyederhanakan ekspresi Boolean sehingga kami dapat membuat rangkaian yang lebih sederhana.


## Combinational Circuits
* Kami telah merancang rangkaian yang mengimplementasikan fungsi Boolean :
![Picture13](https://hackmd.io/_uploads/SymjLpuy1e.png)
* Rangkaian ini merupakan contoh rangkaian logika kombinasional.
* Rangkaian logika kombinasional menghasilkan output tertentu
* Rangkaian logika kombinasional memberi kita banyak perangkat yang berguna.
* Salah satu yang paling sederhana adalah setengah penambah, yang menemukan jumlah dua bit.
* Kita dapat memperoleh gambaran tentang konstruksi setengah penambah dengan melihat tabel kebenarannya, yang ditunjukkan di sebelah kanan.
![Picture14](https://hackmd.io/_uploads/By1ZPpO11e.png)
* Seperti kita lihat, jumlahnya dapat ditemukan menggunakan operasi XOR dan sisanya menggunakan operasi AND.
![Picture15](https://hackmd.io/_uploads/S1QIPp_JJl.png)
![Picture16](https://hackmd.io/_uploads/B1sID6OJ1l.png)

## Refrensi
* Byju's, Aljabar Boolean, https://byjus.com/maths/boolean-algebra/
* Adelaide Wreta, 26 Agustus 2022, Gerbang Logika Adalah: Jenis, Fungsi, dan Simbol https://www.detik.com/jabar/berita/d-6256628/gerbang-logika-adalah-jenis-fungsi-dan-simbol
