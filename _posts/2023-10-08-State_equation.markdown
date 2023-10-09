---
layout: post
title:  "State equation"
date:   2023-08-05 20:07:47 -0700
categories: jekyll update
---

## Definiation
Dynamic systems can be described by differential equations.
$$x_{k+1}=f(X, u)$$
This means "How the system is chaining = f(current state)" and is called 'State equation'.
For a 'Linear Time-Invariant (LTI)' System, the above equation is linearized as
$$x_{k+1} = Ax_k + Bu_k,$$ 
$$x_0 = a$$
where the state vector is an n-dimensional vector $x_k \in R^n$, and u is an m-dimensional vector $u_k \in R^m\$, where m i the number of inputs, $A \in R^{n \times n}$, $B \in R^{n \times m}$


## Ex: Mass-Spring-Damper System
![Screenshot from 2023-10-08 20-36-51](/img/Screenshot from 2023-10-07 20-36-51.png)
- This system stores energy as forms of potential energy (spring) and kinetic energy (mass).
- Thus, The state vector is represented as $x = [p; \dot{p}]$
- &\dot{p} = -\frac{k}{m}p -\frac{k}{m}\dot{p} +\frac{1}{m}u &
![Screenshot from 2023-10-08 20-36-51](/img/Screenshot from 2023-10-07 20-36-52.png)

