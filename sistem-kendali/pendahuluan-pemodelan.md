---
layout: default
author: irosyadi
title:  1.1. Pendahuluan Pemodelan Sistem
date: 2021-03-28 09:58:58
category: sistem-kendali
tags: ["sistem kendali"]
draft: false
---

# 1.1. Pendahuluan Pemodelan Sistem

## 1.1.1. Sistem Dinamik

Sistem dinamik adalah sistem yang berubah seiring waktu berdasarkan sebuah hukum yang tetap. Pada sebagian besar sistem fisika, hukum tersebut dapat dinyatakan sebagai persamaan diferensial orde-satu:

$$
\dot{\mathbf{x}} = \frac{d\mathbf{x}}{dt} = \mathbf{f}\left( \mathbf{x}(t), \mathbf{u}(t), t \right)
$$ 
(1)

Pada persamaan tersebut, $\mathbf{x}(t)$ adalah vektor keadaan, sebuah himpunan variabel yang menyatakan konfigurasi sistem pada waktu $t$. For instance, in a simple mechanical mass-spring-damper system, the two state variables could be the position and velocity of the mass. $\mathbf{u}(t)$ is the vector of external inputs to the system at time $t$, and $\mathbf{f}$ is a (possibly nonlinear) function producing the time derivative (rate of change) of the state vector, $d\mathbf{x}/dt$, for a particular instant of time.

The state at any future time, $\mathbf{x}(t_1)$, may be determined exactly given knowledge of the initial state, $\mathbf{x}(t_0)$, and the time history of the inputs, $\mathbf{u}(t)$, between $t_0$ and $t_1$ by integrating Equation (1). Though the state variables themselves are not unique, there is a minimum number of state variables, $n$, required in order to capture the "state" of a given system and to be able to predict the system's future behavior (solve the state equations). $n$ is referred to as the system order and determines the dimensionality of the state-space. The system order usually corresponds to the number of independent energy storage elements in the system.

The relationship given in Equation (1) is very general and can be used to describe a wide variety of different systems; unfortunately, it may be very difficult to analyze. There are two common simplifications which make the problem more tractable. First, if the function $\mathbf{f}$ does not depend explicitly on time, i.e. $\dot{\mathbf{x}} = \mathbf{f}(\mathbf{x},\mathbf{u})$, then the system is said to be time invariant. This is often a very reasonable assumption because the underlying physical laws themselves do not typically depend on time. For time-invariant systems, the parameters or coefficients of the function $\mathbf{f}$ are constant. The state variables, $\mathbf{x}(t)$, and control inputs, $\mathbf{u}(t)$, however, may still be time dependent.

The second common assumption concerns the linearity of the system. In reality, nearly every physical system is nonlinear. In other words, $\mathbf{f}$ is typically some complicated function of the state and inputs. These nonlinearities arise in many different ways, one of the most common in control systems being "saturation" in which an element of the system reaches a hard physical limit to its operation. Fortunately, over a sufficiently small operating range (think tangent line near a curve), the dynamics of most systems are approximately linear. In this case, the system of first-order differential equations can be represented as a matrix equation, that is, $\dot{\mathbf{x}} = A\mathbf{x} + B\mathbf{u}$.

Until the advent of digital computers (and to a large extent thereafter), it was only practical to analyze linear time-invariant (LTI) systems. Consequently, most of the results of control theory are based on these assumptions. Fortunately, as we shall see, these results have proven to be remarkably effective and many significant engineering challenges have been solved using LTI techniques. In fact, the true power of feedback control systems are that they work (are robust) in the presence of the unavoidable modeling uncertainty.

## 1.1.2. State-Space Representation

For continuous linear time-invariant (LTI) systems, the standard state-space representation is given below:

$$
\dot{\mathbf{x}} = A\mathbf{x} + B\mathbf{u}
$$
(2)

$$
\mathbf{y} = C\mathbf{x} + D\mathbf{u}
$$
(3)

where $\mathbf{x}$ is the vector of state variables (nx1), $\dot{\mathbf{x}}$ is the time derivative of the state vector (nx1), $\mathbf{u}$ is the input or control vector (px1), $\mathbf{y}$ is the output vector (qx1), $A$ is the system matrix (nxn), $B$ is the input matrix (nxp), $C$ is the output matrix (qxn), and $D$ is the feedforward matrix (qxp).

The output equation, Equation (3), is necessary because often there are state variables which are not directly observed or are otherwise not of interest. The output matrix, $C$, is used to specify which state variables (or combinations thereof) are available for use by the controller. Also, it is often the case that the outputs do not directly depend on the inputs (only through the state variables), in which case $D$ is the zero matrix.

The state-space representation, also referred to as the time-domain representation, can easily handle multi-input/multi-output (MIMO) systems, systems with non-zero initial conditions, and nonlinear systems via Equation (1). Consequently, the state-space representation is used extensively in "modern" control theory.

## 1.1.3. Transfer Function Representation
LTI systems have the extremely important property that if the input to the system is sinusoidal, then the output will also be sinusoidal with the same frequency as the input, but with possibly different magnitude and phase. These magnitude and phase differences are a function of frequency and capture what is known as the frequency response of the system.

Using the Laplace transform, it is possible to convert a system's time-domain representation into a frequency-domain input/output representation, known as the transfer function. In so doing, it also transforms the governing differential equation into an algebraic equation which is often easier to analyze.

The Laplace transform of a time domain function, $f(t)$, is defined below:

(4)

$$
F(s) = \mathcal{L}\{f(t)\} = \int_0^\infty e^{-st}f(t)dt
$$

where the parameter $s=\sigma+j\omega$ is a complex frequency variable. It is very rare in practice that you will have to directly evaluate a Laplace transform (though you should certainly know how to). It is much more common to look up the transform of a time function in a table such as the one found here: Laplace Transform Table

The Laplace transform of the nth derivative of a function is particularly important:

(5)

$$
\mathcal{L}\left\{ \frac{d^nf}{dt^n} \right\} = s^n F(s)- s^{n-1} f(0) - s^{n-2} \dot{f}(0) - ... - f^{(n-1)}(0)
$$

Frequency-domain methods are most often used for analyzing LTI single-input/single-output (SISO) systems, e.g. those governed by a constant coefficient differential equation, as shown below:

(6)

$$
a_n \frac{d^ny}{dt^n} + ... + a_1 \frac{dy}{dt} + a_0 y(t) = b_m \frac{d^mu}{dt^m} + ... + b_1 \frac{du}{dt} + b_0 u(t)
$$

The Laplace transform of this equation is given below:

(7)

$$
a_n s^n Y(s) + ... + a_1 sY(s)+ a_0 Y(s) = b_m s^m U(s) + ... + b_1 sU(s)+ b_0 U(s)
$$

where $Y(s)$ and $U(s)$ are the Laplace Transforms of $y(t)$ and $u(t)$, respectively. Note that when finding transfer functions, we always assume that the each of the initial conditions, $y(0)$, $\dot{y}(0)$, $u(0)$, etc. is zero. The transfer function from input $U(s)$ to output $Y(s)$ is, therefore:

(8)

$$
G(s) = \frac{Y(s)}{U(s)} = \frac{b_m s^m + b_{m-1} s^{m-1} + ... + b_1 s + b_0}{a_n s^n + a_{n-1} s^{n-1} + ... + a_1 s + a_0}
$$

It is useful to factor the numerator and denominator of the transfer function into what is termed zero-pole-gain form:

(9)

$$
G(s) = \frac{N(s)}{D(s)} = K \frac{(s-z_1)(s-z_2)...(s-z_{m-1})(s-z_m)}{(s-p_1)(s-p_2)...(s-p_{n-1})(s-p_n)}
$$

The zeros of the transfer function, $z_1,\ldots,z_m$, are the roots of the numerator polynomial, i.e. the values of $s$ such that $N(s)=0$. The poles of the transfer function, $p_1, \ldots,p_n$, are the roots of the denominator polynomial, i.e. the values of $s$ such that $D(s)=0$. Both the zeros and poles may be complex valued (have both real and imaginary parts). The system Gain is $K = b_m/a_n$.

Note that we can also determine the transfer function directly from the state-space representation as follows:

(10)

$$
G(s) = \frac{Y(s)}{U(s)} = C(s\mathbf{I}-A)^{-1}B+D
$$