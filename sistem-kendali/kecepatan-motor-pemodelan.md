---
layout: default
author: irosyadi
title:  3.1. Pemodelan Kecepatan Motor
date: 2021-03-29 11:45:42
category: sistem-kendali
tags: ["sistem kendali"]
draft: false
---

# 3.1. Pemodelan Kecepatan Motor

## 3.1.1. Sistem Kecepatan Motor

Motor DC adalah salah satu aktuator yang paling umum digunakan di sistem kendali. Motor DC berfungsi menyediakan luaran berupa gerakan berputar, dan apabila dikopling dengan tabung dan kabel/karet dapat menyediakan luaran berupa gerakan translasi. Rangkaian listrik ekivalen dari armatur dan *free-body diagram*  dari rotor sebuah motor ditunjukkan pada gambar berikut.

![](https://raw.githubusercontent.com/irosyadi/vnote.image/master/1616914091_20210328134756212_12378.png)

Pada contoh ini, kita mengasumsikan bahwa masukan sistem adalah sumber tegangan ($V$) yang diberikan kepada armatur motor, sedangkan luarnnya adalah kecepatan rotasi batang motor $\dot{\theta}$. Rotor dan batang motor diasumsikan kaku. Selain itu, kita juga mengasumsikan ada model gesekan *viscous*  yaitu berupa torsi gesekan yang proporsional dengan kecepatan angular batang.

## 3.1.2. Persamaan Sistem

Secara umum, torsi yang dibangkitkan oleh motor DC proporsional dengan arus armatur dan kekuatan medan magnet permanen. Pada contoh ini, kita mengasumsikan bahwa medan magnetnya bersifat konstan, sehingga torsi motor hanya proporsional dengan arus armatur $i$ dengan faktor konstanta $K_t$ sebagaimana pada persamaan di bawah ini. Model motor DC semacam itu disebut sebagai motor dengan kendali armatur (*armature-controlled motor*).

$$  T = K_{t} i$$ (1)  

Gaya gerak listrik (ggl) balik, $e$, bersifat proporsional dengan kecepatan angular batang dengan faktor konstanta $K_e$.  

$$  e = K_{e} \dot{\theta}$$ (2)  

Konstanta motor torsi dan konstanta gaya gerak listrik adalah sama, $K_t = K_e$; sehingga, kita akan menggunakan $K$ untuk menyatakan kedua konstanta tersebut.  

Berdasarkan gambar di atas, kita dapat memperoleh persamaan yang mengatur motor DC berdasarkan hukum ke-2 Newton dan hukum tegangan Kirchhoff.

$$ J\ddot{\theta} + b \dot{\theta} = K i $$ (3)  

$$ L \frac{di}{dt} + Ri = V - K\dot{\theta}$$ (4)  

### Parameter Sistem

- (J) momen inersia rotor: 0.01 kg.m^2
- (b) konstanta friksi viscous motor: 0.1 N.m.s
- (Ke) konstanta gaya gerak listrik: 0.01 V/rad/sec
- (Kt) konstanta torsi motor: 0.01 N.m/Amp
- (K) = (Ke) = (Kt)
- (R) resistansi: 1 Ohm
- (L) induktansi: 0.5 H

## 3.1.3. Fungsi Alih dan State Space Sistem

Fungsi alih sistem kendaraan dengan masukan $V(s)$ dan keluaran $\dot{\Theta}(s)$  adalah ...  


State space system dengan *state vector* $\left [ \begin{array}{c} \dot{\theta} \\ \ \\ i \end{array} \right]$,  input $V$ dan output $\dot{\theta}$ adalah ...  



