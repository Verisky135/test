---
layout:     post
title:      Kelas Kompleksitas Pada Permainan
date:       2016-06-03
summary:    Membandingkan kelas kompleksitas.
categories: tugas
---
<br>
## Pendahuluan
Teori kompleksitas komputasi adalah teori yang mengklasifikasikan permasalahan komputasi berdasarkan tingkat kesulitannya dan hubungan dari kelas-kelas tersebut. Permasalahan komputasi dipahami sebagai sebuah masalah yang dapat diselesaikan dengan computer. Permasalahan dapat diselesaikan dengan aplikasi mekanik dari tahap-tahap matematika seperti algoritma.

<br>

## Kelas-Kelas Kompleksitas

### Kompleksitas Waktu
Kompleksitas waktu menunjukan jumlah waktu atau jumlah tahapan yang dibutuhkan suatu komputer untuk menyelesaikan masalah komputasi dengan menggunakan algoritma tertentu.
Deterministik :
| Kelas         | Batasan             |
| ------------- | ------------------- |
| DTIME         | Waktu f(n)          |
| P             | Waktu poly(n)       |
| EXPTIME       | Waktu 2^(poly(n))   |

Non-deterministik :
| Kelas         | Batasan             |
| ------------- | ------------------- |
| NTIME         | Waktu f(n)          |
| NP            | Waktu poly(n)       |
| NEXPTIME      | Waktu 2^(poly(n))   |

<br>

### Kompleksitas Ruang
Kompleksitas ruang menunjukan jumlah total memori yang dibutuhkan suatu komputer untuk menyelesaikan masalah komputasi dengan menggunakan algoritma tertentu.
Deterministik :
| Kelas         | Batasan             |
| ------------- | ------------------- |
| DSPACE        | Ruang f(n)          |
| L             | Ruang O(log n)      |
| PSPACE        | Ruang poly(n)       |
| EXPTIME       | Ruang 2^(poly(n))   |

Non-deterministik :
| Kelas         | Batasan             |
| ------------- | ------------------- |
| NSPACE        | Ruang f(n)          |
| NL            | Ruang O(log n)      |
| NPSPACE       | Ruang poly(n)       |
| NEXPSPACE     | Ruang 2^(poly(n))   |

##
