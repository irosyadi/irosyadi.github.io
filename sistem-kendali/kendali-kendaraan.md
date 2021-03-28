---
layout: default
author: irosyadi
title:  Kendali Kendaraan
date: 2021-03-28 10:04:55
category: sistem-kendali
tags: ["sistem kendali"]
draft: false
---

# 2. Kendali Kendaraan

## 2.1. Sistem Kendali Kendaraan

Sistem kendali kendaraan adalah contoh sistem kendali umpan balik yang banyak digunakan dalam kendaraan otonom. Salah satu tujuan dari kendali kendaraan adalah untuk mempertahankan kecepatan kendaraan secara konstan dan mengatasi berbagai gangguan, seperti angin atau keadaan jalan. Hal ini bisa diperoleh dengan mengukur kecepatan kendaraan, membandingkannya dengan kecepatan yang diinginkan atau kecepatan referensi, dan secara otomatis mengatur gas sesuai dengan hukum kendali yang diberikan.

![](https://raw.githubusercontent.com/irosyadi/vnote.image/master/1616900791_20210328100507201_19989.png)

Dinamika dari kendaraan We consider here a simple model of the vehicle dynamics, shown in the free-body diagram (FBD) above. The vehicle, of mass m, is acted on by a control force, u. The force u represents the force generated at the road/tire interface. For this simplified model we will assume that we can control this force directly and will neglect the dynamics of the powertrain, tires, etc., that go into generating the force. The resistive forces, bv, due to rolling resistance and wind drag, are assumed to vary linearly with the vehicle velocity, v, and act in the direction opposite the vehicle's motion.

## 2.2. Persamaan Sistem

Berdasar asumsi di atas, sistem kendaraan dinyatakan sebagai sebuah sistem orde satu dalam bentuk sistem massa dengan peredam (_mass-damper_). Melalui penjumlahan gaya dalam arah-x dan menerapkan hukum Newton ke-2 , kita mendapatkan persamaan sistem:

$$
m \dot{v} + b v = u
$$

Karena kita tertarik dengan pengendalian kecepatan kendaraan, maka luaran dari sistem adalah:

$$
y = v
$$

## 2.3. System parameters