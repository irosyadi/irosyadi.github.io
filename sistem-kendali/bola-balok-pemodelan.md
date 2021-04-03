---
layout: default
author: irosyadi
title:  8.1. Pemodelan Sistem Bola Balok
date: 2021-03-29 14:45:42
category: sistem-kendali
tags: ["sistem kendali"]
draft: false
---

# 8.1. Pemodelan Sistem Bola Balok

## 8.1.1. Sistem Bola Balok

Sebagaimana pada gambar di bawah, sebuah bola ditempatkan pada balok yang mana bola dapat menggelinding sepanjang balok. Sebuah batang tuas (*lever arm*) dipasangkan pada balok dan dihubungkan dengan sebuah gir servo. Saat gir servo berputar dengan sudut  $\theta$, tuas akan mengubah sudut balok sebesar $\alpha$. Saat sudut berubah lebih miring dari posisi horisontal awal, maka bola akan menggelinding sepanjang balok. Sebuah pengendali akand irancang untuk sistem ini untuk mengatur posisi bola di sepanjang balok.

![ball-beam](https://raw.githubusercontent.com/irosyadi/vnote.image/master/1617179902_20210331153812010_2569.jpg)

## 8.1.2. Persamaan Sistem

Persamaan Lagrange untuk gerakan bola pada balok dinyatakan dengan:

$$ 0 = \left(\frac{J}{R^2}+m\right) \ddot{r} + m g \sin{\alpha} - m r \dot{\alpha}^2 $$ (1)  

dengan $r$ adalah koordinat posisi bola pada balok, $R$ adalah radius bola, $J$ adalah momen inersia bola, $m$ adalah massa bola, dan $g$ adalah percepatan gravitasi.

Dengan melakukan linearisasi pada persamaan tersebut pada sudut balok $\alpha = 0$, aproksimasi persamaan linear sistem adalah:

$$ \left(\frac{J}{R^2}+m\right) \ddot{r} = - m g \alpha $$ (2)  

Persamaan yang menghubungkan dengan sudut balok dengan sudut gir dapat didekati dengan persamaan linear sebagai berikut:


$$ \alpha = \frac{d}{L}\theta $$ (3)  

dengan $d$ adalah offset lengan tuas, $L$ adalah panjang balok dan $\theta$ adalah sudut gir servo.

Dengan melakukan subtitusi ke persamaan sebelumnya, kita mendapatkan:

$$ \left(\frac{J}{R^2}+m\right) \ddot{r} = - m g \frac{d}{L} \theta $$ (4)  

Pada persamaan di atas, sebenarnya turunan kedua dari  $\alpha$ berkait dengan turunan kedua dari $r$. Akan tetapi untuk menyederhanakan persamaan sistem, hal tersebut diabaikan. Demikian pula kita mengasumsikan bahwa bola menggelinding tanpa mengalami selip (tergelincir) dan tanpa mengalami friksi dengan balok.  

### Parameter Sistem

- (m) massa bola: 0.11 kg
- (R) radius bola: 0.015 m
- (d) offset lengan tuas: 0.03 m
- (g) percepatan gravitasi: 9.8 m/s^2
- (L) panjang balok: 1.0 m
- (J) momen inersia bola: 9.99e-6 kg.m^2
- (r) koordinat posisi bola
- (α) koordinat sudut bola
- (θ) sudut gir servo

## 8.1.3. Fungsi Alih dan State Space Sistem

Fungsi alih sistem kendaraan dengan masukan sudut gir $\Theta(s)$ dan keluaran posisi bola $R(s)$  adalah ...  


State space system dengan *state vector* $\left[{\begin{array}{c} r \\ \dot{r} \end{array}}\right]$,  input $\theta$ dan output $r$ adalah ...


