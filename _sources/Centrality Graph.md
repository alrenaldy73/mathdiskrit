---
title: Centrality Graph

---

# Analisa Graph
### Social Network Analysis 
merupakan bidang kajian yang mengekplorasitentang hubungan manusia dengan menggunakan teori graf. Implementasi Social Network Analysis dapat menjelaskan relasi atau hubungan antar aktor melalui visualisasi berbentuk graf. Relasi dalam analisis jaringan sosial dapat diproses dalam bentuk perhitungan yang disebut centrality dalam sebuah jaringan sosial sesuai dengan posisi masing-masing aktor di dalam struktur jaringan tersebut
![Picture1](https://hackmd.io/_uploads/B1P0rbIzJg.png)

![Picture2](https://hackmd.io/_uploads/B1ikI-Ifye.png)

### Social network 
terdapat node yang mewakili orang atau individu atau aktor. Relasi  antar objek  dapat dinyatakan dengan link atau edges yang terjadi antara aktor tersebut Social network terdiri dari banyak aktor yang mempunyai relasi satu sama lain hingga membentuk peta jaringan sosial yang dinyatakan dengan 
graph
* Tidak semua node dalam jaringan adalah penting  (aktor)
* Mencari node yang paling penting dalam suatu jaringan
* Centrality adalah penentuan aktor menggunakan ukuran pada Social Network Centrality dalam teori graf dan social network .Dibagi menjadi empat jenis, 
  * degree centrality, 
  * betweeness centrality, 
  * closeness centrality 
  * eigenvector centrality

## Degree Centrality
* Degree centrality adalah jumlah edge yang terkoneksi pada suatu node yang mewakili interaksi.
* Pentingnya node ditentukan oleh jumlah node yang berdekatan dengan node tersebut
    *  Degree Centrality!  ![Picture3](https://hackmd.io/_uploads/S1_QDZUGye.png)
    * Normalisasi  Degree Centrality:  ![Picture4](https://hackmd.io/_uploads/ByeMDbLMJe.png)

  ![Picture6](https://hackmd.io/_uploads/rJzwwb8zJl.png)
Untuk  node 1, degree centrality adalah 3;
Normalisasi degree centrality adalah  
3/(9-1)=3/8.

## Closeness Centrality
* Closenes centrality adalah nilai kedekatan antara satu node dengan node lain dalam jaringan dengan menghitung rata-rata dari jarak relasi node-node tersebut. Skor closeness centrality mewakili kecepatan dalam penyebaran informasi.
* Average Distance: ![Picture7](https://hackmd.io/_uploads/Hyyv_ZLGkl.png)
* Closeness Centrality  ![Picture8](https://hackmd.io/_uploads/ryWt_ZLz1l.png)

## Contoh Closeness Centrality 
![Picture9](https://hackmd.io/_uploads/SyiAtWLfJg.png)
![Picture10](https://hackmd.io/_uploads/SyoyqbUfye.png)
![Picture11](https://hackmd.io/_uploads/HyKx9ZLGyg.png)
Node 4  lebih central  dari node 3
## Betweenness Centrality
* Skor betweeness Centrality mewakili seberapa besar informasi yang tersebar dari suatu aktor. Semakin besar skor, artinya aktor tersebut semakin berperan dalam penyebaran informasi 
* Semakin banyak lintasan yang harus melewati persimpangan itu (misal tidak ada jalan alternatif), maka semakin penting arti persimpangan tersebut. Hal ini menandakan seberapa besar suatu node diperlukan sebagai penghubung dalam penyebaran informasi di dalam jaringan
* Ukuran ini juga dapat digunakan untuk mengidentifikasi **boundary spanners**, yaitu orang atau node yang berperan sebagai penghubung (jembatan) antara dua komunitas
* Menghitung jumlah lintasan terpendek yang melewati suatu node
* Node dengan  betweenness  tinggi  adalah  penting dalam komunikasi dan penyebaran informasi
* Betweenness Centrality
![Picture12](https://hackmd.io/_uploads/ByGyi-Izkl.png)
![Picture15](https://hackmd.io/_uploads/SJ44j-8M1x.png)  Jumlah lintasan terpendek antara  s dan t
![Picture16](https://hackmd.io/_uploads/H1gHibUzJg.png) Jumlah lintasan terpendek antara s dan t yang melewati vi
# Betweenness Centrality
![Picture17](https://hackmd.io/_uploads/HJBy2bIfJg.png)![Picture18](https://hackmd.io/_uploads/S1YJ3WLfke.png)
![Picture19](https://hackmd.io/_uploads/HkVl2ZUM1g.png)
**betweenness centrality  untuk node 5?**
![Picture20](https://hackmd.io/_uploads/r1y5h-Lfkx.png)   Jumlah path terpendek antara  s dan t
![Picture21](https://hackmd.io/_uploads/rJL9nbUMyl.png)  Jumlah path terpendek antara s dan t yang melewati  vi
![Picture22](https://hackmd.io/_uploads/SJ1i2ZLfkx.png)
# Normalisasi Betweenness Centrality
![Picture23](https://hackmd.io/_uploads/HyUt6Z8fJg.png)

