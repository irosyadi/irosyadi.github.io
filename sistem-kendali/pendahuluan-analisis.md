---
layout: default
author: irosyadi
title:  1.2. Pendahuluan Analisis Sistem
date: 2021-03-28 09:59:58
category: sistem-kendali
tags: ["sistem kendali"]
draft: false
---

# 1.2. Pendahuluan Analisis Sistem

Once appropriate mathematical models of a system have been obtained, either in state-space or transfer function form, we may then analyze these models to predict how the system will respond in both the time and frequency domains. To put this in context, control systems are often designed to improve stability, speed of response, steady-state error, or prevent oscillations. In this section, we will show how to determine these dynamic properties from the system models.

## 1.2.1. Time Response Overview

The time response represents how the state of a dynamic system changes in time when subjected to a particular input. Since the models we have derived consist of differential equations, some integration must be performed in order to determine the time response of the system. For some simple systems, a closed-form analytical solution may be available. However, for most systems, especially nonlinear systems or those subject to complicated inputs, this integration must be carried out numerically. Fortunately, MATLAB provides many useful resources for calculating time responses for many types of inputs, as we shall see in the following sections.

The time response of a linear dynamic system consists of the sum of the transient response which depends on the initial conditions and the steady-state response which depends on the system input. These correspond to the homogenous (free or zero input) and the particular solutions of the governing differential equations, respectively.

## 1.2.2. Frequency Response Overview
All the examples presented in this tutorial are modeled by linear constant coefficient differential equations and are thus linear time-invariant (LTI). LTI systems have the extremely important property that if the input to the system is sinusoidal, then the steady-state output will also be sinusoidal at the same frequency, but, in general, with different magnitude and phase. These magnitude and phase differences are a function of the frequency and comprise the frequency response of the system.

The frequency response of a system can be found from its transfer function in the following way: create a vector of frequencies (varying between zero or "DC" to infinity) and compute the value of the plant transfer function at those frequencies. If $G(s)$ is the open-loop transfer function of a system and $\omega$ is the frequency vector, we then plot $G(j\omega)$ versus $\omega$. Since $G(j\omega)$ is a complex number, we can plot both its magnitude and phase (the Bode Plot) or its position in the complex plane (the Nyquist Diagram). Both methods display the same information, but in different ways.

## 1.2.3. Stability
For our purposes, we will use the Bounded Input Bounded Output (BIBO) definition of stability which states that a system is stable if the output remains bounded for all bounded (finite) inputs. Practically, this means that the system will not "blow up" while in operation.

The transfer function representation is especially useful when analyzing system stability. If all poles of the transfer function (values of $s$ for which the denominator equals zero) have negative real parts, then the system is stable. If any pole has a positive real part, then the system is unstable. If we view the poles on the complex s-plane, then all poles must be in the left-half plane (LHP) to ensure stability. If any pair of poles is on the imaginary axis, then the system is marginally stable and the system will tend to oscillate. A system with purely imaginary poles is not considered BIBO stable. For such a system, there will exist finite inputs that lead to an unbounded response. The poles of an LTI system model can easily be found in MATLAB using the pole command, an example of which is shown below: