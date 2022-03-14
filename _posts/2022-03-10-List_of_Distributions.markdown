---
layout: post
mathjax: true
title:  "Common Distributions"
date:   2022-03-09 12:44am  +1000
categories: Probability
author: Tony Wang
---

In this post, I will write about some of the key distributions that are used by statisticians. The aim is to not just have the formulas, but explain intuition, proofs and uses for these distributions. These will be added in as my time permits. I will mainly be using this page as a reference.

Each distribution will have its probability mass function (pmf) or probability density function (pdf) listed, mean and variance, and some notes on relations to other distributions and derivations. 

# Measure-Theoretic View
Suppose we are working with a process that has sample space $$\Omega$$, set of measurable events $$\mathcal{F}$$ and probability measure $$P$$. A random variable $$X$$ (taking values in $$\overline{\mathbb{R}} = \mathbb{R} \cup \{\infty\}$$) is just a measurable function $$X: \Omega \to \overline{\mathbb{R}}$$. The expectation (or _mean_) of $$X$$ is the (Lebesgue) integral 
$$ \int_\Omega f \: dP,
$$ 
defined in the usual way (this is discussed in a separate blog post). The _probability distribution_ of $$X$$ is the function $$P \circ X^{-1} : \overline{\mathbb{R}} \to [0,1]$$ (with respect to the usual Borel $$\sigma$$-algebra). The probability distribution describes how likely the random variable $$X$$ is to take on some set of values. The _distribution function_ (or _cumulative distribution function_) of $$X$$ is defined as $$F(x) := $(P \circ X^{-1})((-\infty, x]))$$, the probability that $$X$$ takes on values up to and including $$x$$. 

Finally, a _probability density_ of $$X$$ on $$\mathbb{R}$$ is defined as follows. For a non-negative measurable $$f \geq 0$$ on $$(\Omega, \mathcal{F}, P)$$, we can write $$f \cdot P$$ to define a new measure $$\mu$$ by

$$
\mu (A) = (f \cdot P) (A) = \int_A f \: dP \quad \text{for all } A \in \mathcal{F}.
$$
We call $$f$$ the $$P$$-density of $$\mu$$. If the function $$f$$ is the density of $$P \circ X^{-1}$$ with respect to the Lebesgue measure on $$\mathbb{R}$$, then $$f$$ is called the _probability density function_ of $$X$$.  

The rest: to be completed!
# Discrete Probability Distributions 

## Bernoulli and Binomial Distributions

## Geometric Distribution

## Hypergeometric Distribution

## Poisson Distribution


# Continuous Probability Distributions

## Normal Distribution

## Beta Distribution

## Laplace Distribution

## Exponential Distribution


## Gamma Distribution


