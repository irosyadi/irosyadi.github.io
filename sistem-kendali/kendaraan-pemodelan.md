---
layout: default
author: irosyadi
title:  2.1. Pemodelan Sistem Kendaraan
date: 2021-03-29 10:04:55
category: sistem-kendali
tags: ["sistem kendali"]
draft: false
---

# 2.1. Pemodelan Sistem Kendaraan

## 2.1.1. Sistem Kendaraan

Sistem kendali kendaraan adalah contoh sistem kendali umpan balik yang banyak digunakan dalam kendaraan otonom. Salah satu tujuan dari kendali kendaraan adalah untuk mempertahankan kecepatan kendaraan secara konstan dan mengatasi berbagai gangguan, seperti angin atau keadaan jalan. Hal ini bisa diperoleh dengan mengukur kecepatan kendaraan, membandingkannya dengan kecepatan yang diinginkan atau kecepatan referensi, dan secara otomatis mengatur gas sesuai dengan hukum kendali yang diberikan.

![](https://raw.githubusercontent.com/irosyadi/vnote.image/master/1616900791_20210328100507201_19989.png)

Dinamika dari kendaraan dinyatakan dengan *free-body diagram* (FBD) seperti pada gambar atas. Kendaraan, dengan massa m, mendapatkan gaya, u. Gaya u menyatakan gaya yang diberikan antara ban mobil dan permukaan jalan. Model ini disederhanakan dengan mengasumsikan bahwa kita bisa langsung memberikan gaya pada roda dan mengabaikan dinamika dari rangkaian tenaga pada mobil, karakteristik ban dll. Gaya hambat pada model tersebut, bv, disebabkan karena hambatan angin dan gesekan perputaran roda. Gaya hambat tersebut diasumsikan berubah secara linear sesuai dengan kecepatan kendaraan, v, dan memiliki arah berkebalikan dengan gerakan mobil.

## 2.1.2. Persamaan Sistem

Berdasar asumsi di atas, sistem kendaraan dinyatakan sebagai sebuah sistem orde satu dalam bentuk sistem massa dengan peredam (_mass-damper_). Melalui penjumlahan gaya dalam arah-x dan menerapkan hukum Newton ke-2 , kita mendapatkan persamaan sistem:

$$
m \dot{v} + b v = u
$$ (1)  

Karena kita tertarik dengan pengendalian kecepatan kendaraan, maka luaran dari sistem adalah:

$$
y = v
$$ (2)  

### Parameter Sistem

Untuk contoh ini, asumsikan bahwa parameter sistem adalah:

- (m) massa kendaraan: 1000 kg
- (b) koefisien redaman: 50 N.s/m


## 2.1.3. Fungsi Alih dan State Space Sistem

Fungsi alih sistem kendaraan dengan masukan $u(s)$ dan keluaran $V(s)$ adalah ...  


State space system dengan *state vector* $[v]$ , input $u$ dan output $v$ adalah ...  

