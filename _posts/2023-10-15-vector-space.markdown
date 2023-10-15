---
layout: post
title:  "State equation"
date:   2023-08-05 20:07:47 -0700
categories: jekyll update
---

## Vector Space
Let $\mathbb{K} = \mathbb{R}$ or $\mathbb{C}$. A vector space $V$ over $\mathbb{K}$ is a set of elements, and operations +, x such that

- $u+v \in V; a \times v \in V$
  
To have a vector space, the eight following axioms must be satisfied for all $u, v, w \in V$, and $a, b \in \mathbb{K}$.
- associativity: $u + (v + w) = (u + v) + w$
- commutativity: $u + v = v + u$
- identiy +: there exists $0 \in V$ such that $v+0 = v$
- inverse +: for all $v \in V$ there exists $-v \in V$ such that $v + (-v) = 0$
- compatibility: $a(bv) = (ab)v$
- identity \times: $1v=v$ 
- distributivity in $V$: $a(u+v) = au \times av$
- distributivity in $\mathbb{K}$: $(a+b)v = av +bv$

In this context, the elements of V are commonly called vectors, and the elements of $\mathbb{K}$ are called scalars.


## Normed vector space
A normed vector space is a vector space on which a norm is defined. If $V$ is a vector space, and $|| \cdot ||$ is a norm on $V$, then the ordered pair $(V, || \cdot ||)$ is called a normed vector space.


![Screenshot from 2023-10-08 20-36-51](/img/Screenshot from 2023-10-08 20-36-51.png)
- This system stores energy as forms of potential energy (spring) and kinetic energy (mass).
- Thus, The state vector is represented as $x = [p; \dot{p}]$
- $\dot{p} = -\frac{k}{m} p -\frac{k}{m} \dot{p} +\frac{1}{m} u $
  
![Screenshot from 2023-10-08 20-36-52](/img/Screenshot from 2023-10-08 20-36-52.png)

