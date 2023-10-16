---
layout: post
title:  "State equation"
date:   2023-08-05 20:07:47 -0700
categories: jekyll update
---
![Screenshot from 2023-10-08 20-36-61](/img/Screenshot from 2023-10-08 20-36-61.png)

## Vector Space
A vector space $V$ over $\mathbb{K}$ is a set of elements along with operations +, x for combining these elements such that

- $u+v \in V; a \times v \in V$
  
To have a vector space, the eight following axioms must be satisfied for all $u, v, w \in V$, and $a, b \in \mathbb{K}$. and  $\mathbb{K} = \mathbb{R}$ or $\mathbb{C}$.
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
A normed vector space is a vector space on which a norm is defined. 
- $\{\{v \in V: ||v|| < \infty \}\}$

If $V$ is a vector space, and $|| \cdot ||$ is a norm on $V$, then the ordered pair $(V, || \cdot ||)$ is called a normed vector space.

- $l^p$ space
  
A $l^p(N; \mathbb{R}^m)$ space is a subspace of $\mathbb{K}^N$ such that their $l^p$-norm is finite, $1 \leq p < \infty$: 

$$\|x\|_{l^p} \coloneqq \left( \sum_n ||x_n||^p \right)^{1/p} < \infty$$

where $||\cdot||$ is any norm on $\mathbb{R}^m$ 


- $L^p$ space
  
A $L^p(D; \mathbb{R}^m)$ space is a space of measurable functions $f: D \rightarrow \mathbb{R}^m$ such that their $L^p$-norm is finite, $1 \leq p < \infty$: 

here, $D \subset \mathbb{R}^d$ bounded and open. 

$$||f||_{L^p} \coloneqq (\int_D ||f(x)||^p \ dx )^{1/p} < \infty$$

where $||\cdot||$ is any norm on $\mathbb{R}^m$ 

