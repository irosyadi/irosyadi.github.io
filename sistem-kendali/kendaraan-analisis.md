---
layout: default
author: irosyadi
title:  2.2. Analisis Sistem Kendaraan
date: 2021-03-28 10:05:55
category: sistem-kendali
tags: ["sistem kendali"]
draft: false
---

# 2.2. Analisis Sistem Kendaraan

## 2.2.1. System model and parameters
The transfer function model for the cruise control problem is given below. Please see the Cruise Control: System Modeling page for the derivation.

(1)

$$
P(s) = \frac{V(s)}{U(s)} = \frac{1}{ms+b}  \qquad  [ \frac{m/s}{N} ]
$$

The parameters used in this example are as follows:

(m)   vehicle mass            1000 kg
(b)   damping coefficient     50 N.s/m
(u)   nominal control force   500 N


## 2.2.2. Performance specifications
The next step is to come up with some design criteria that the compensated system should achieve. When the engine gives a 500 Newton force, the car will reach a maximum velocity of 10 m/s (22 mph), see open-loop step response section below. An automobile should be able to accelerate up to that speed in less than 5 seconds. In this application, a 10% overshoot and 2% steady-state error on the velocity are sufficient.

Keeping the above in mind, we have proposed the following design criteria for this problem:

Rise time < 5 s
Overshoot < 10%
Steady-state error < 2%
Open-loop step response
The open-loop response of the system, without any feedback control, to a step input force of 500 Newtons is simulated in MATLAB as follows:

```matlab
m = 1000;
b = 50;
u = 500;

s = tf('s');
P_cruise = 1/(m*s+b);

step(u*P_cruise)
```