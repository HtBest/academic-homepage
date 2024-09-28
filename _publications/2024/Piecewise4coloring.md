---
title:          "A Piecewise Approach for the Analysis of Exact Algorithms"
date:           2024-02-12 00:01:00 +0800
selected:       true
# pub:            "arXiv"
pub_pre:        "Submitted to WALCOM"
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
    To analyze the worst-case running time of branching algorithms, the majority of work in exponential time algorithms focuses on designing complicated branching rules over developing better analysis methods for simple algorithms. In the mid-2000s, Fomin et al. (2005) introduced measure & conquer, an advanced general analysis method, sparking widespread adoption for obtaining tighter worst-case running time upper bounds for many fundamental NP-complete problems. Yet, much potential in this direction remains untapped, as most subsequent work applied it without further advancement.

    Motivated by this, we present piecewise analysis, a new general method that analyzes the running time of branching algorithms. Our approach is to define a similarity ratio that divides instances into groups and then analyze the running time within each group separately. The similarity ratio is a scale between two parameters of an instance I. Instead of relying on a single measure and a single analysis for the whole instance space, our method allows to take advantage of different intrinsic properties of instances with different similarity ratios.

    To showcase its potential, we reanalyze two 17-year-old algorithms from Fomin et al. (2007) that solve 4-Coloring and #3-Coloring respectively. The original analysis in their paper gave running times of \(O(1.7272^n)\) and \(O(1.6262^n)\) respectively for these algorithms, our analysis improves these running times to \(O(1.7207^n)\) and \(O(1.6225^n).\)

cover:          /assets/images/covers/PWA.jpg
authors:
  - Katie Clinch
  - Serge Gaspers
  - Zixu He
  - Abdallah Saffidine
  - Tiankuang Zhang
links:
  arXiv: https://arxiv.org/abs/2402.10015
  Code: https://github.com/AlgorithmsWorkingGroup/coloring_pwa
---
