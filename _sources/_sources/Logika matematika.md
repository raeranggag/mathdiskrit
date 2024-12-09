---
title: Logika matematika

---

# Logika matematika

## Negasi
Negasi didefinisikan sebagai sebuah pernyataan yang memiliki nilai kebenaran yang berlawanan dengan pernyataan semula. Berikut adalah simbol dan tabel kebenaran ingkaran/negasi.
Sumber : https://www.ruangguru.com/blog/logika-matematika


| p     | $\neg p$ |
| ----- | -------- |
| Benar | Salah    |
| Salah | Benar    |

Artinya, jika suatu pertanyaan p benar, maka ingkaran q akan bernilai salah. Begitu pula sebaliknya

## Konjungsi
Konjungsi adalah pernyataan majemuk dengan kata hubung “dan”. Sehingga, notasi “p $\cap$ q” dibaca “p dan q”. Berikut adalah tabel nilai kebenaran konjungsi.
Sumber : https://www.ruangguru.com/blog/logika-matematika


| p     | q     | p $\wedge$ q |
| ----- | ----- | ------------ |
| Benar | Benar | Benar        |
| Benar | Salah | Salah        |
| Salah | Benar | Salah        |
| Salah | Salah | Salah        |

Dari tabel di atas, kita dapat melihat bahwa konjungsi hanya akan benar jika kedua pernyataan (p dan q) benar

## Disjungsi
Disjungsi adalah pernyataan majemuk dengan kata hubung “atau”. Sehingga notasi “p $\cup$ q” dibaca “p atau q”. Berikut adalah tabel nilai kebenaran disjungsi.
Sumber : https://www.ruangguru.com/blog/logika-matematika


| p | q | p $\vee$ q |
| -------- | -------- | -------- |
| Benar        | Salah        | Benar        |
| Benar        | Benar        | Benar        |
| Salah        | Benar        | Salah        |
| Salah        | Salah        | Salah        |

Jika kita lihat pada tabel kebenaran, disjungsi hanya salah jika kedua pernyataan (p dan q) salah.

## Implikasi
Implikasi adalah pernyataan majemuk dengan kata hubung “jika… maka…” Sehingga notasi dari “p $\implies$ q” dibaca “Jika p, maka q”
Sumber : https://www.ruangguru.com/blog/logika-matematika


| p     | q     | p$\implies$q |
| ----- | ----- | ------------ |
| Benar | Benar | Benar        |
| Benar | Salah | Salah        |
| Salah | Benar | Benar        |
| Salah | Salah | Salah        |

Dari tabel terlihat bahwa implikasi hanya bernilai salah jika anteseden p benar, dan konsekuen q salah.


## Bimplikasi
Biimplikasi adalah pernyataan majemuk dengan kata hubung “… jika dan hanya jika”. Sehingga, notasi dari “p $\iff$ q” akan dibaca “p jika dan hanya jika q”.
Sumber : https://www.ruangguru.com/blog/logika-matematika


| P     | Q     | p$\iff$q |
| ----- | ----- | -------- |
| Benar | Benar | Benar    |
| Benar | Salah | Salah    |
| Salah | Benar | Salah    |
| Salah | Salah | Benar    |

Dari tabel kebenaran tersebut, dapat kita amati bahwa biimplikasi akan bernilai benar jika sebab dan akibatnya (pernyataan p dan q) bernilai sama. Baik itu sama-sama benar, atau sama-sama salah.

 Soal :
Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{T}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{F}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{F}&\text{F}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{F}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{F}&\text{F}&\text{F}&\text{}\end{array}$$
