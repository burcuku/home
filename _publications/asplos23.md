---
title: "[Probabilistic Concurrency Testing for Weak Memory Programs](../files/asplos23-pctwm.pdf)"
collection: publications
permalink: /publication/asplos23
excerpt: ''
date: 2023-02-25
venue: '28th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 2, ASPLOS 2023'
paperurl: ''
citation: 'Mingyu Gao, Soham Chakraborty, Burcu Kulahcioglu Ozkan. &quot;Probabilistic Concurrency Testing for Weak Memory Programs.&quot; Proceedings of the 28th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 2, ASPLOS 2023, Vancouver, BC, Canada, March 25-29, 2023'
---

[**(pdf)**](../files/asplos23-pctwm.pdf) 
**Abstract.** The Probabilistic Concurrency Testing (PCT) algorithm that provides theoretical guarantees on the probability of detecting concurrency bugs does not apply to weak memory programs. The PCT algorithm builds on the interleaving semantics of sequential consistency, which does not hold for weak memory concurrency. It is because weak memory concurrency allows additional behaviors that cannot be produced by any interleaving execution.In this paper, we generalize PCT to address weak memory concurrency and present Probabilistic Concurrency Testing for Weak Memory (PCTWM). We empirically evaluate PCTWM on a set of well-known weak memory program benchmarks in comparison to the state-of-the-art weak memory testing tool C11Tester. Our results show that PCTWM can detect concurrency bugs more frequently than C11Tester.
