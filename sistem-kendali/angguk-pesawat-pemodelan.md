---
layout: default
author: irosyadi
title:  7.1. Pemodelan Sistem Angguk Pesawat (Aircraft Pitch)
date: 2021-03-28 15:45:42
category: sistem-kendali
tags: ["sistem kendali"]
draft: false
---

# 7.1. Pemodelan Sistem Angguk Pesawat (Aircraft Pitch)

## 7.1.1. Sistem Angguk Pesawat

Persamaan yang mengatur pergerakan pesawat adalah sangat kompleks yang meliputi enam pasang persamaan diferensial non linear. Akan tetapi dalam keadaan tertentu, persamaan tersebut dapat dipisahkan dan dilinearkan menjadi persamaan longitudinal dan persamaan lateral. Mekanisme anggukan pesawat (*aircraft pitch*) diatur dengan dinamika longitudinal. Pada contoh berikut, kita akan merancangsebuah autopilot yang mengatur anggukan sebuah pesawat.

Koordinat dasar sumbu dan gaya yang bekerja pada sebuah pesawat ditunjukkan pada gambar berikut.

![Sistem Pesawat](https://raw.githubusercontent.com/irosyadi/vnote.image/master/1617095342_20210330160853818_7698.png)

Kita mengasumsikan bahwa pesawat dalam keadaan meluncur secara tetap pada kecepatan dan ketinggian yang konstan; sehingga daya dorong, daya tarik, berat, dan daya angkat bersifat saling mengimbangi satu sama lain dalam arah x dan y. Kita juga mengasumsikan bahwa perubahan pada sudut angguk tidak akan mengubah kecepatan pesawat (meskipun pada aslinya tidak seperti itu). 

Dengan asumsi-asumsi tersebut, persamaan longitudinal gerak pesawat dapat ditulis sebagai berikutequations.

$$ \dot{\alpha} = \mu\Omega\sigma [-(C_L+C_D)\alpha+\frac{1}{(\mu-C_L)}q-(C_W \sin\gamma)\theta+C_L] $$ (1)
![pitch_equation](_v_images/20210330165652657_18683.png)
$$ \dot\theta = \Omega q $$ (2)

Lebih lanjut, bagaimana persamaan di atas diperoleh dapat dipelajari pada berbagai buku teks terkait pesawat terbang.
Untuk sistem ini, masukan sistem adalah sudut defleksi elevator $\delta$ dan keluarannya adalah sudut angguk $\theta$ dari pesawat.

### Parameter Sistem

Dalam sistem angguk pesawat, berikut adalah parameter-parameter tarkait.
$\alpha$ = Sudut serang (*Angle of attack*).
$q$ = Tingkat angguk (*Pitch rate*).
$\theta$ = Sudut angguk (*Pitch angle*).
$\delta$ = Sudut defleksi elevator (*Elevator deflection angle*).
$\mu = \frac{\rho S \bar{c}}{4 m}$.
$\rho$ = Massa jenis udara (*Density of air*).
$S$ = Area platform sayap (*Platform area of the wing*).
$\bar{c}$ = Rerata bentang lebar sayap (*Average chord length*).
$m$ = Massa pesawat (*Mass of the aircraft*).
$\Omega = \frac{2 U}{\bar{c}}$.
$U$ = Kecepatan terbang setimbang (*Equilibrium flight speed*).
$C_T$ = Koefisien dorong (*Coefficient of thrust*).
$C_D$ = Koefisien tarik (*Coefficient of drag*).
$C_L$ = Koefisien angkat (*Coefficient of lift*).
$C_W$ = Koefisien berat (*Coefficient of weight*).
$C_M$ = Koefisien momen angguk (*Coefficient of pitch moment*).
$\gamma$ = Sudut arah terbang (*Flight path angle*).
$\sigma=\frac{1}{1+\mu C_L}$ = Konstanta.
$i_{yy}$ = Momen inersia ternormalisasi (*Normalized moment of inertia*).
$\eta=\mu \sigma C_M$ = Konstanta.


Persamaan sudut angguk pesawat di atas kemudian dapat disederhanakan menjadi

$$\dot\alpha = K_1\alpha+K_2q+K_3\delta $$

$$\dot q = L_1\alpha+L_2q+L_3\delta $$

$$\dot\theta = \Omega q $$

Berdasarkan data dari salah satu jenis pesawat komersial Boeing, nilai numerikal dari persamaan model angguk pesawat adalah sebagai berikut:

$$\dot\alpha = -0.313\alpha+56.7q+0.232\delta $$ (3)

$$\dot q = -0.0139\alpha-0.426q+0.0203\delta $$ (4)

$$\dot\theta = 56.7q $$ (5)

## 7.1.3. Fungsi Alih dan State Space Sistem

Fungsi alih sistem kendaraan dengan masukan sudut defleksi elevator  $\Delta(s)$ dan keluaran sudut angguk ${\Theta}(s)$  adalah ...
State space system dengan *state vector*  $\left [\begin{array}{c} {\alpha} \\ \ \\ {q} \\ \ \\ {\theta}\end{array}\right]$,  input $V$ dan output $\theta$ adalah ...