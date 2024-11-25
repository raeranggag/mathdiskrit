---
title: Matematika diskret

---

# 1. HUKUM DE MORGAN'S

Hukum De Morgan adalah dua aturan dalam logika yang menghubungkan operasi konjungsi (AND) dan disjungsi (OR) dengan negasi. Hukum ini dinyatakan sebagai berikut:

1. Negasi dari konjungsi:
   $\overline(A\cap B)= \bar A \cup \bar B$
   Artinya, negasi dari "A dan B" sama dengan "tidak A atau tidak B".

2. Negasi dari disjungsi:
   $\overline(A\cup B)= \bar A \cap \bar B$
   Artinya, negasi dari "A atau B" sama dengan "tidak A dan tidak B".

Hukum ini sering digunakan dalam pengembangan logika dan juga dalam berbagai aplikasi seperti matematika, komputer, dan ilmu statistik. Hukum De Morgan membantu dalam menyederhanakan ekspresi logika dan memfasilitasi proses pembuktian.

### Pembuktian : $\overline(A\cap B)= \bar A \cup \bar B$
Misal :
A = [1,4,3,5]
B = [1,6,7,9]
U = [2,8,10]
Maka $A\cup B=$ [1,3,4,5,6,7,9]
Dan jika yang ditanyakan $\overline(A\cup B)=$[2,8,10]/U
###### $\bar{A}\cap\bar{B}$
Di baca bukan A irisan bukan B.
Yang dimana hasilnya tidak akan ada di
Dalam Himpunan A Dan B.
Jadi hasilnya = U
# 2. HUKUM ABSORPTION
Hukum penyerapan atau absorption law adalah identitas yang menghubungkan dua operasi biner dalam aljabar. Hukum ini muncul dalam definisi aljabar Boolean dan kisi. 
Hukum penyerapan menyatakan bahwa p ∨ ( p ∧ q ) sama dengan p, tidak peduli apa pun q. 

Dalam hukum penyerapan, variabel-variabel yang serupa dapat diserap, misalnya X. (X + Y) = X. X + XY = X. 
#### PEMBUKTIAN : 
$A\cup(A\cap B)=A$
Misal:
A=[1,4,3,5]
B=[1,6,7,9]

Kerjakan / Eliminasi yang di dalam tanda kurung terlebih dahulu
$(A\cap B)=$[1]

Kemudian kerjakan / Eliminasi yang di luar tanda kurung
Kita misalkan hasil dari $(A\cap B)=$ C
Maka $A\cup C=$[1,4,3,5] Dimana Himpunan tersebut = Himpunan A
### 3. HUKUM COMPLEMENT LAWS
Hukum komplemen adalah salah satu sifat dari komplemen himpunan, yaitu:
##### a. Gabungan himpunan A dan komplemennya A' akan menghasilkan himpunan semesta U.
##### b. Irisan himpunan A dan komplemennya A' akan menghasilkan himpunan kosong ∅. 
Komplemen suatu himpunan adalah himpunan yang berisi semua elemen himpunan semesta, tetapi tidak ada dalam himpunan yang diberikan. 

Selain hukum komplemen, ada juga hukum De Morgan yang merupakan sepasang aturan transformasi dalam aljabar boolean dan teori himpunan. Hukum De Morgan digunakan untuk menghubungkan irisan dan gabungan himpunan melalui komplemen.
#### PEMBUKTIAN : 
$A\cup\bar A = U$
Misal:
A=[1,4,3,5]
U=[2,6,7]
[1,4,3,5] $\cup$ not[1,4,3,5] = [2,6,7]