---
layout: default
author: irosyadi
title:  8.1. Pemodelan Sistem Bola Balok
date: 2021-03-28 16:45:42
category: sistem-kendali
tags: ["sistem kendali"]
draft: false
---

# 8.1. Pemodelan Sistem Bola Balok

## 8.1.1. Sistem Bola Balok

A ball is placed on a beam, see figure below, where it is allowed to roll with 1 degree of freedom along the length of the beam. A lever arm is attached to the beam at one end and a servo gear at the other. As the servo gear turns by an angle $\theta$, the lever changes the angle of the beam by $\alpha$. When the angle is changed from the horizontal position, gravity causes the ball to roll along the beam. A controller will be designed for this system so that the ball's position can be manipulated.

![Bola Balok](_v_images/20210330171214832_5957.png)

## 8.1.2. Persamaan Sistem

The second derivative of the input angle $\alpha$ actually affects the second derivative of $r$. However, we will ignore this contribution. The Lagrangian equation of motion for the ball is then given by the following:

(1)$$ 0 = \left(\frac{J}{R^2}+m\right) \ddot{r} + m g \sin{\alpha} - m r
\dot{\alpha}^2 $$

Linearization of this equation about the beam angle, $\alpha = 0$, gives us the following linear approximation of the system:

(2)$$ \left(\frac{J}{R^2}+m\right) \ddot{r} = - m g \alpha $$

The equation which relates the beam angle to the angle of the gear can be approximated as linear by the equation below:

(3)$$ \alpha = \frac{d}{L}\theta $$

Substituting this into the previous equation, we get:

(4)$$ \left(\frac{J}{R^2}+m\right) \ddot{r} = - m g \frac{d}{L} \theta $$

### Parameter Sistem

- For this problem, we will assume that the ball rolls without slipping and friction between the beam and ball is negligible. The constants and variables for this example are defined as follows:

- (m) massa bola: 0.11 kg
- (R) radius bola: 0.015 m
- (d) offset lengan tuas: 0.03 m
- (g) percepatan gravitasi: 9.8 m/s^2
- (L) panjang balok: 1.0 m
- (J) momen inersia bola: 9.99e-6 kg.m^2
- (r) koordinat posisi bola
- (alpha) koordinat sudut bola
- (theta)  sudut gir servo

## 8.1.3. Fungsi Alih dan State Space Sistem

Fungsi alih sistem kendaraan dengan masukan sudut gir $\Theta(s)$ dan keluaran posisi bola $R(s)$  adalah ...

State space system dengan *state vector* $\left[{\begin{array}{c} r \\ \dot{r} \\ \alpha \\ \dot{\alpha} \end{array}}\right]$,  input $\theta$ dan output $r$ adalah ...

The linearized system equations can also be represented in state-space form. This can be done by selecting the ball's position ($r$) and velocity ($\dot{r}$) as the state variable and the gear angle ($\theta$) as the input.

$$ \left[{\begin{array}{c} \dot{r} \\ \ddot{r} \end{array}}\right] =
\left[{\begin{array}{cc} 0 & 1 \\ 0 & 0 \end{array}}\right]
\left[{\begin{array}{c} r \\ \dot{r} \end{array}}\right] +
\left[{\begin{array}{c} 0 \\ -\frac{m g d}{L
\left(\frac{J}{R^2}+m\right)}\end{array}}\right] \theta$$

