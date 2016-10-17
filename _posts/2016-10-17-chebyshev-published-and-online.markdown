---
layout: post
title:  "Accelerating Real-Time Time-Dependent Density Functional Theory with a Non-Recursive Chebyshev Expansion of the Quantum Propagator Published and Published Online"
date:   2016-10-17 12:13:00 -0700
categories: [publication,chebyshev,RTTDDFT,JCTC]
permalink: /posts/cheb-rttddft
---

<script type="text/javascript"
    src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
    </script>

My recent work on the reformulation of the Chebyshev expansion of the quantum propagator has been accepted to
the Journal of Chemical Theory and Computation (JCTC). The paper may now be found [online](http://doi.org/10.1021/acs.jctc.6b00693).

Traditionally, the [Chebyshsev expansion](https://en.wikipedia.org/wiki/Chebyshev_polynomials) of the complex operator
exponential utilizes Chebyshev polynomials which are generated in a recursive fashion. In real-time implementations that
utilize the [Taylor expansion](https://en.wikipedia.org/wiki/Taylor_series) of the exponential, the extension to the
Chebyshev expansion constitutes an unnecessary complication for the improvement in accuracy. In this work, we've made the 
realization that one need not build the Chebyshev polynomials by explicit recursion, but rather by determination of the
closed-form expression for the expansion coefficients in terms of the matrix powers themselves. Thus, the Chebyshev expansion
may be adapted to exactly resemble the Taylor expansion with a simple change in the expansion coefficients. This also allows for
a bifurcation of the range of matrix powers to allow for order \\(2N\\) accuracy with only order \\(N\\) matrix multiplies. Thus
a factor of 2 speedup over a naive implementation.

Further, we have shown that the Chebyshev expansion is not only suitable for weak perturbations as has been previously demonstrated,
but rather that it may be used in the general case of a strong time-dependent perturbation with relatively stable time-propagation
relative to the "exact" eigen-decomposition method.
