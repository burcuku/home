---
title: "[GRAIL: Checking Transaction Isolation Violations with Graph Queries](https://dl.acm.org/doi/10.1145/3639478.3643094)"
collection: publications
permalink: /publication/icse24
excerpt: ''
date: 2024-05-23
venue: 'ICSE-Companion'24: Proceedings of the 2024 IEEE/ACM 46th International Conference on Software Engineering: Companion Proceedings'
paperurl: ''
citation: 'Stefania Dumbrava, Zhao Jin, Burcu Kulahcioglu Ozkan, Jingxuan Qiu. &quot;GRAIL: Checking Transaction Isolation Violations with Graph Queries.&quot; Proceedings of the 2024 {IEEE/ACM} 46th International Conference on Software Engineering: Companion Proceedings, {ICSE} Companion 2024, Lisbon, Portugal, April 14-20, 2024'
---

**Abstract.** Distributed databases are surging in popularity with the growing need for performance and fault tolerance. However, implementing transaction isolation models on distributed databases is more challenging due to their sharding and replication. As a result, they can produce executions that violate their claimed isolation guarantees.
In this work, we propose a novel isolation model-agnostic approach that utilizes graph databases to efficiently detect isolation violations expressed as anti-patterns in transactional dependency graphs. To illustrate our approach, we introduce the GRAIL framework, implemented on top of the popular ArangoDB and Neo4j graph databases. GRAIL combines soundness guarantees and high performance with understandable, detailed counter-examples.
