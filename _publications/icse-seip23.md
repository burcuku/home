---
title: "Evolutionary Approach for Concurrency Testing of Ripple Blockchain Consensus Algorithm"
collection: publications
permalink: /publication/icse-seip23
excerpt: ''
date: 2023-05-14
venue: '45th IEEE/ACM International Conference on Software Engineering: Software Engineering in Practice, ICSE (SEIP) 2023, Melbourne, Australia, May 14-20, 2023'
paperurl: ''
citation: 'Martijn van Meerten, Burcu Kulahcioglu Ozkan, Annibale Panichella. &quot;Evolutionary Approach for Concurrency Testing ofRipple Blockchain Consensus Algorithm.&quot; Proceedings of the 45th IEEE/ACM International Conference on Software Engineering: Software Engineering in Practice, ICSE (SEIP) 2023'
---

**Abstract.** Blockchain systems are prone to concurrency bugs due to the nondeterminism in the delivery order of messages between the distributed nodes. These bugs are hard to detect since they can only be triggered by a specific order or timing of concurrent events in the execution. Systematic concurrency testing techniques, which explore all possible delivery orderings of messages to uncover concurrency bugs, are not scalable to large distributed systems such as blockchains. Random concurrency testing methods search for bugs in a randomly generated set of executions and offer a practical testing method.In this paper, we investigate the effectiveness of random concurrency testing on blockchain systems using a case study on the XRP Ledger of the Ripple blockchain, which maintains one of the most popular cryptocurrencies in the market today. We test the Ripple consensus algorithm of the XRP Ledger by exploring different delivery orderings of consensus protocol messages. Moreover, we design an evolutionary algorithm to guide the random test case generation toward certain system behaviors to discover concurrency bugs more efficiently. Our case study shows that random concurrency testing is effective at detecting concurrency bugs in blockchains, and the evolutionary approach for test generation improves test efficiency. Our experiments could successfully detect the bugs we seeded in the Ripple source code. Moreover, we discovered a previously unknown concurrency bug in the production implementation of Ripple.
