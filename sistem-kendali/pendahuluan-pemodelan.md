---
layout: default
author: irosyadi
title:  1. Pendahuluan
date: 2021-03-28 09:58:58
category: sistem-kendali
tags: ["sistem kendali"]
draft: false
---

# 1. Pendahuluan: Pemodelan Sistem

## 1.1. Sistem Dinamik

Sistem dinamik adalah sistem yang berubah seiring waktu berdasarkan sebuah hukum yang tetap. Pada sebagian besar sistem fisika, hukum tersebut dapat dinyatakan sebagai persamaan diferensial orde-satu:

$$
\dot{\mathbf{x}} = \frac{d\mathbf{x}}{dt} = \mathbf{f}\left( \mathbf{x}(t), \mathbf{u}(t), t \right)
$$

Pada persamaan tersebut, $\mathbf{x}(t)$ adalah vektor keadaan, sebuah himpunan variabel yang menyatakan konfigurasi sistem pada waktu $t$. For instance, in a simple mechanical mass-spring-damper system, the two state variables could be the position and velocity of the mass. $\mathbf{u}(t)$ is the vector of external inputs to the system at time $t$, and $\mathbf{f}$ is a (possibly nonlinear) function producing the time derivative (rate of change) of the state vector, $d\mathbf{x}/dt$, for a particular instant of time.

The state at any future time, $\mathbf{x}(t_1)$, may be determined exactly given knowledge of the initial state, $\mathbf{x}(t_0)$, and the time history of the inputs, $\mathbf{u}(t)$, between $t_0$ and $t_1$ by integrating Equation (1). Though the state variables themselves are not unique, there is a minimum number of state variables, $n$, required in order to capture the "state" of a given system and to be able to predict the system's future behavior (solve the state equations). $n$ is referred to as the system order and determines the dimensionality of the state-space. The system order usually corresponds to the number of independent energy storage elements in the system.

The relationship given in Equation (1) is very general and can be used to describe a wide variety of different systems; unfortunately, it may be very difficult to analyze. There are two common simplifications which make the problem more tractable. First, if the function $\mathbf{f}$ does not depend explicitly on time, i.e. $\dot{\mathbf{x}} = \mathbf{f}(\mathbf{x},\mathbf{u})$, then the system is said to be time invariant. This is often a very reasonable assumption because the underlying physical laws themselves do not typically depend on time. For time-invariant systems, the parameters or coefficients of the function $\mathbf{f}$ are constant. The state variables, $\mathbf{x}(t)$, and control inputs, $\mathbf{u}(t)$, however, may still be time dependent.

The second common assumption concerns the linearity of the system. In reality, nearly every physical system is nonlinear. In other words, $\mathbf{f}$ is typically some complicated function of the state and inputs. These nonlinearities arise in many different ways, one of the most common in control systems being "saturation" in which an element of the system reaches a hard physical limit to its operation. Fortunately, over a sufficiently small operating range (think tangent line near a curve), the dynamics of most systems are approximately linear. In this case, the system of first-order differential equations can be represented as a matrix equation, that is, $\dot{\mathbf{x}} = A\mathbf{x} + B\mathbf{u}$.

Until the advent of digital computers (and to a large extent thereafter), it was only practical to analyze linear time-invariant (LTI) systems. Consequently, most of the results of control theory are based on these assumptions. Fortunately, as we shall see, these results have proven to be remarkably effective and many significant engineering challenges have been solved using LTI techniques. In fact, the true power of feedback control systems are that they work (are robust) in the presence of the unavoidable modeling uncertainty.