---
title: aljabar boolean dan gerbang logika

---

# Aljabar Boolean dan gerbang logika
##Aljabar Boolean
Aljabar Boolean adalah sistem matematika untuk manipulasi variabel yang dapat memiliki salah satu dari dua nilai.  

Dalam logika formal, nilai-nilai ini adalah "benar" dan "salah."  

Dalam sistem digital, nilai-nilai ini adalah "nyala" dan "mati," 1 dan 0, atau "tinggi" dan "rendah."  
Ekspresi Boolean dibuat dengan melakukan operasi pada variabel Boolean.  
Operator Boolean yang umum termasuk AND (AND), (OR), dan (NOT).
![image](https://hackmd.io/_uploads/r1Yof4cJke.png)

Sebuah operator Boolean dapat dijelaskan sepenuhnya menggunakan tabel kebenaran.  
Tabel kebenaran untuk operator Boolean D (AND) dan (OR) ditunjukkan di sebelah kanan.  
Operator AND  juga dikenal sebagai produk Boolean. Operator OR adalah jumlah Boolean..

Aljabar Boolean sering digunakan dalam pemrograman untuk mengevaluasi ekspresi logika.
![image](https://hackmd.io/_uploads/BJmhb45J1l.png)


## Operator Biner:
Aljabar Boolean memiliki dua operator biner:
Penjumlahan (+): Digunakan untuk operasi disjungsi (OR).
Perkalian (⋅): Digunakan untuk operasi konjungsi (AND).

## Operator Uner:
Komplemen (’): Digunakan untuk menghasilkan nilai yang berlawanan dari suatu elemen. Misalnya, jika a = 1, maka a’ = 0, dan sebaliknya.


![image](https://hackmd.io/_uploads/Hy4g-Vq1ke.png)

## Aksioma-Aksioma:
Untuk setiap a, b, c ∈ B, berlaku aksioma-aksioma berikut:
Closure: a + b ∈ B dan a ⋅ b ∈ B.
Identitas: a + 0 = a dan a ⋅ 1 = a.
Komutatif: a + b = b + a dan a ⋅ b = b ⋅ a.
Distributif: a ⋅ (b + c) = (a ⋅ b) + (a ⋅ c) dan a + (b ⋅ c) = (a + b) ⋅ (a + c).
Komplemen: Untuk setiap a ∈ B, terdapat elemen unik a’ ∈ B sehingga a + a’ = 1 dan a ⋅ a’ = 0

# Gerban Logika

Fungsi Boolean diimplementasikan dalam sirkuit komputer digital yang disebut gerbang (gates).  

Gerbang adalah perangkat elektronik yang menghasilkan hasil berdasarkan dua atau lebih nilai input.  

Dalam kenyataannya, gerbang terdiri dari satu hingga enam transistor, tetapi desainer digital menganggapnya sebagai satu kesatuan.  

Sirkuit terintegrasi mengandung kumpulan gerbang yang sesuai untuk tujuan tertentu..

Tiga gerbang AND, OR, dan  NOT.
![image](https://hackmd.io/_uploads/B1NamEqJJg.png)
Gerbang yang sangat berguna lainnya adalah gerbang eksklusif OR (XOR).  
Output dari operasi XOR adalah benar hanya ketika nilai-nilai input berbeda.
![image](https://hackmd.io/_uploads/SylM4N9yyl.png)
NAND dan NOR dua gerbang yang sangat penting. Simbol dan tabel kebenarannya ditunjukkan di sebelah kanan. 
![image](https://hackmd.io/_uploads/rJxBV4cJyl.png)
NAND dan NOR dikenal dengan gerbang universal  karena mereka murah untuk diproduksi dan setiap fungsi Boolean dapat dibangun menggunakan gerbang ini. NAND atau hanya gerbang NOR .  
![image](https://hackmd.io/_uploads/SyrOEV5JJe.png)


