---
layout: post
mathjax: true
title:  "The Basics of Measure Theory"
date:   2021-09-29 4:28pm  +1000
categories: Mathematics
author: Tony Wang
---
Hi! Currently under construction. 
# Motivations 


# Measure Theory

## Notation 
- Write $$\Omega$$ to denote an arbitrary set, $$\mathbb{R}^+$$ to denote the interval $$[0, \infty) \cup \infty = [0, \infty]$$. 
- $$ \mathcal{A}$$ denotes a $\sigma$-algebra on $$\Omega$$.

__Definition 1__: A function $$\mu : \mathcal{A} \to \mathbb{R}^+$$ is a _measure_ if 
1. $$\mu(\emptyset) = 0$$, 
2. The function $$\mu$$ satisfies countable additivity: for any countable collection $$\{U_n\}_{n \in \mathbb{N}} \subset \mathcal{A}$$, we have 

$$\mu(\cup_n U_n) = \sum_{n=0}^\infty \mu(U_n)
$$

