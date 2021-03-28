---
layout: default
author: irosyadi
title:  3.1. Pemodelan Kecepatan Motor
date: 2021-03-28 13:45:42
category: sistem-kendali
tags: ["sistem kendali"]
draft: false
---

# 3.1. Pemodelan Kecepatan Motor

A common actuator in control systems is the DC motor. It directly provides rotary motion and, coupled with wheels or drums and cables, can provide translational motion. The electric equivalent circuit of the armature and the free-body diagram of the rotor are shown in the following figure.

![](https://raw.githubusercontent.com/irosyadi/vnote.image/master/1616914091_20210328134756212_12378.png)
For this example, we will assume that the input of the system is the voltage source ($V$) applied to the motor's armature, while the output is the rotational speed of the shaft $\dot{\theta}$. The rotor and shaft are assumed to be rigid. We further assume a viscous friction model, that is, the friction torque is proportional to shaft angular velocity.