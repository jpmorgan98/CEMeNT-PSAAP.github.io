---
title: "Newton’s Method In Mixed-Precision"
excerpt: "Appering in SIAM Review 2022"
classes: wide

header:
    teaser: assets/Documents/publications/2022/Mixed_Precision.png
    
author: C.T. Kelley

gallery:
  - url: /assets/Documents/publications/2022/Mixed_Precision.pdf
    image_path: /assets/Documents/publications/2022/Mixed_Precision.png
    alt: "Publication!"

---

# Abstract
We investigate the use of reduced precision arithmetic to solve the linear equation for the Newton step. If one neglects the backward error in the linear solve, then well-known convergence theory implies that using single precision in the linear solve has very little negative effect on the nonlinear convergence rate. However, if one considers the effects of backward error, then the usual textbook estimates are very pessimistic and even the state-of-the-art estimates using probabilistic rounding analysis do not fully conform to experiments. We report on experiments with a specific example. We store and factor Jacobians in double, single, and half precision. In the single precision case we observe that the convergence rates for the nonlinear iteration do not degrade as the dimension increases and that the nonlinear iteration statistics are essentially identical to the double precision computation. In half precision we see that the nonlinear convergence rates, while poor, do not degrade as the dimension increases.


{% include gallery %}
