---
layout: post
title:  "Input/output Relationship (Norm perspective)"
date:   2023-08-05 20:07:47 -0700
categories: jekyll update
---

## Is the output small for a disturbance input?
- Suppose that our control analysis involves a requirement of disturbance attenuation.
- Let's say a disturbance input $u$, its effect on the system output $y$, and G is the impulse response from $u$ to $y$.
- How much $u$ affects $y$ according to various measures?
- This is different depending on input signal, measurement ways of the output, and it transfer function.

## System gain table
- If u is known to be a sinusoid of fixed frequency (maybe $u$ comes from a prower source at 60 Hz), then the relative size of $y$ is needed to be measured.
- We want to know the least upper bound on a norm of the output, that is:
  $$\sup (||y|| : u=f(t)) $$

![Screenshot from 2023-10-08 20-36-54](/img/Screenshot from 2023-10-08 20-36-55.png)

- More commonly, the disturbance signal will not be known a prior. Now suppose that $u$ is not a fixed signal but that it can be any signal of 2-norm $\leq 1$.
- The least upper bound on the 2-norm of the output, that is:
  $$\sup (||y||_2 : ||u||_2 \leq 1) $$
  which we can call the 2-norm/2-norm system gain, equals the $\infty-$norm of $\hat{G}$.
 
![Screenshot from 2023-10-08 20-36-55](/img/Screenshot from 2023-10-08 20-36-56.png)

![Screenshot from 2023-10-08 20-36-55](/img/Screenshot from 2023-10-08 20-36-57.png)
