---
title: "[Liveness Checking of the HotStuff Protocol Family](https://arxiv.org/abs/2310.09006)"
collection: publications
permalink: /publication/prdc23
excerpt: ''
date: 2023-10-24
venue: '28th IEEE Pacific Rim International Symposium on Dependable Computing (PRDC 2023)'
paperurl: ''
citation: 'Jérémie Decouchant, Burcu Kulahcioglu Ozkan, Yanzhuo Zhou. &quot;Liveness Checking of the HotStuff Protocol Family.&quot; Proceedings of the 28th IEEE Pacific Rim International Symposium on Dependable Computing (PRDC 2023), Singapore, Singapore, October 24-27, 2023'
---

**Abstract.** Byzantine consensus protocols aim at maintaining safety guarantees under any network synchrony model and at providing liveness in partially or fully synchronous networks. However, several Byzantine consensus protocols have been shown to violate liveness properties under certain scenarios. Existing testing methods for checking the liveness of consensus protocols check for time-bounded liveness violations, which generate a large number of false positives. In this work, for the first time, we check the liveness of Byzantine consensus protocols using the temperature and lasso detection methods, which require the definition of ad-hoc system state abstractions. We focus on the HotStuff protocol family that has been recently developed for blockchain consensus. In this family, the HotStuff protocol is both safe and live under the partial synchrony assumption, while the 2-Phase Hotstuff and Sync HotStuff protocols are known to violate liveness in subtle fault scenarios. We implemented our liveness checking methods on top of the Twins automated unit test generator to test the HotStuff protocol family. Our results indicate that our methods successfully detect all known liveness violations and produce fewer false positives than the traditional time-bounded liveness checks.

