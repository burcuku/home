---
title: "Generalized Concurrency Testing Tool for Distributed Systems"
collection: publications
permalink: /publication/issta24
excerpt: ''
date: 2024-09-18
venue: 'The 33th ACM SIGSOFT International Symposium on Software Testing and Analysis, (ISSTA) 2024'
paperurl: 'https://dl.acm.org/doi/10.1145/3650212.3685309'
citation: Ege Berkay Gulcan, João Neto, Burcu Kulahcioglu Ozkan. &quot;Generalized Concurrency Testing Tool for Distributed Systems.&quot; Proceedings of the 33th ACM SIGSOFT International Symposium on Software Testing and Analysis, (ISSTA) 2024 (to appear)'
---

**Abstract.** 

Controlled concurrency testing (CCT) is an effective approach for testing distributed system implementations. However, the existing CCTtools suffer from the drawbacks of language dependency and the cost of source code instrumentation, which makes them difficult to apply to real-world production systems. We propose DSTest, a generalized CCT tool for testing distributed system implementations. DSTest intercepts messages on the application layer and, hence, eliminates the instrumentation cost and achieves language independence with minimal input. We provide a clean and modular interface to extend DSTest for various event schedulers for CCT. We package DSTest with three well-known event schedulers and validate the tool by applying it to popular production systems.
