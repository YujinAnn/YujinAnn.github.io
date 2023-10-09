---
layout: post
title:  "State equation"
date:   2023-08-05 20:07:47 -0700
categories: jekyll update
---

## Definiation
Dynamic systems can be described by differential equations.How the system is chaining = f(current state)
$$x_{k+1}=f(X, u)$$
For a Linear Time-Invariant (LTI) System, the above equation is linearized as
$$x_{k+1} = Ax_k + Bu_k, x_0 = a$$
where the state vector is an n-dimensional vector $x_k \in R^n$, and u is an m-dimensional vector $u_k \in R^m\$, where m i the number of inputs, $A \in R^{n \times n}$, $B \in R^{n \times m}$


## Ex: 
- If $N \subseteq R$, sup(N) does not exiest. inf(N) = 1
- If a set $A = \{1/n | n \in N\} = \{1/1, 1/2, 1/3, ...\}$ and $A \in R$, then sup(A) = 1 and inf(A) = 0.
- If a set $A = \{x \in \mathbb{Q} \mid x^2 < 2\}$ and $A \in \mathbb{R}$, then $-\sqrt{2} < x < \sqrt{2}$. However, $\sup(A) \neq \sqrt{2}$ and $\inf(A) \neq -\sqrt{2}$.
- 
![Screenshot from 2023-10-08 20-36-51](/img/Screenshot from 2023-10-07 20-36-51.png)
