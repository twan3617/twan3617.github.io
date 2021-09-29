---
layout: post
title:  "Introduction"
date:   2021-09-29 4:28pm  +1000
categories: Introductions
author: Tony Wang
---
Of course, one must have some ideas on what to write on before beginning to write! I am thinking of the following:
Basic distributions/statistics summary
Bayesian inference introduction
Basic machine learning algorithms

To be honest, I still have a lot to learn before I can confidently write on these topics. 


The Bayesian Framework:

$$ \pi(\theta \mid x) = \frac{\pi(x \mid \theta)\pi(\theta)}{m(x)}
$$

where $$m(x)$$ represents the marginal distribution of $$x$$, $$\pi(\theta)$$ is the prior distribution of the parameters $$\theta$$ and $$\pi(x\mid \theta)$$ is the likelihood function. Beware, however, that we are viewing $$\pi(x\mid \theta)$$ as a function of the parameters $$\theta$$ and the data $$x$$ is fixed; often, this dependence is made explicit by writing 
$$ \pi(x\mid \theta) = L(\theta; x).
$$

 
