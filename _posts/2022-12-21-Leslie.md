---
layout: post
title: Leslie Matrices, part 1
subtitle: 
---

### Of Life, Death and Linear Algebra

In this first post we explore a family of Population growth models based on simple linear algebra.

![_config.yml]({{ site.baseurl }}/images/leslie_illustration.png)

The basic idea is to structure a population demographics by age, grouping population of close age.
This is then encoded in a vector $$N_t$$. To give a concrete example, let's consider the case of a human population we would like to model. We focus on the women population for reasons that will be clearer below. We divide this populations by age group 

<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>