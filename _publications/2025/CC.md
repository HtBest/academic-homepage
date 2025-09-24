---
title: "NP-Hardness and ETH-Based Inapproximability of Communication Complexity via Relaxed Interlacing"
date: 2025-09-27 00:01:00 +0800
selected: true
# pub:            "arXiv"
# pub_pre: "Submitted to STACS"
# pub_post:       'Under review.'
# pub_last: ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
# pub_date: "2026"

abstract: >-
  We prove that computing the deterministic communication complexity D(f) of a Boolean function is NP-hard in the standard protocol-tree model, answering, independently and concurrently with Hirahara-Llango-Loff (arXiv:2507.10426), a question first posed by Yao (1979). Our reduction builds and expands on a suite of structural "interlacing" lemmas introduced by Mackenzie and Saffidine (arXiv:2411.19003); these lemmas can be reused as black boxes in future lower-bound constructions.
    The instances produced by our reduction admit optimal protocols for self-similar constructions with strong structural properties, giving a flexible framework for the design of reductions showing NP-hardness of deciding the communication complexity of a Boolean matrix. This complements the work by Hirahara, Ilango, and Loff, which establishes NP-hardness in the same model via a different route; our analysis additionally yields reusable structural guarantees and underpins further consequences concerning inapproximability.
    Because the gadgets in our construction are self-similar, they can be recursively embedded. We sketch how this yields, under the Exponential-Time Hypothesis, an additive inapproximability gap that grows without bound. Furthermore we outline a route toward NP-hardness of approximating D(f) within a fixed constant additive error. Full details of the ETH-based inapproximability results will appear in a future version.
    Beyond settling the complexity of deterministic communication complexity itself, the modular framework we develop opens the door to a wider class of reductions and, we believe, will prove useful in tackling other long-standing questions in communication complexity.

cover: /assets/images/covers/cover4.png
authors:
  - Serge Gaspers
  - Tao Zixu He
  - Simon Mackenzie
links:
  arXiv: https://arxiv.org/abs/2508.05597
#   Code: https://github.com/AlgorithmsWorkingGroup/coloring_pwa
---
