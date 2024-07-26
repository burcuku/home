---
title: "Understanding Concurrency Bugs in Real-World Programs with Kotlin Coroutines"
collection: publications
permalink: /publication/ecoop24
excerpt: ''
date: 2024-09-16
venue: 'The 38th European Conference on Object-Oriented Programming, (ECOOP) 2024 (to appear)'
paperurl: ''
citation: Bob Brockbernd, Nikita Koval, Arie van Deursen, Burcu Kulahcioglu Ozkan. &quot;Understanding Concurrency Bugs in Real-World Programs with Kotlin Coroutines.&quot; Proceedings of the 38th European Conference on Object-Oriented Programming, {ECOOP} 2024 (to appear)'
---

**Abstract.** 

Kotlin language has recently become prominent for developing both Android and server-side applications. These programs are typically designed to be fast and responsive, with asynchrony and concurrency at their core. To enable developers to write asynchronous and concurrent code safely and concisely, Kotlin provides built-in \emph{coroutines} support. However, developers unfamiliar with the coroutines concept may write programs with subtle concurrency bugs and face unexpected program behaviors. Besides the traditional concurrency bug patterns, such as data races and deadlocks, these bugs may exhibit patterns related to the coroutine semantics. Understanding these coroutine-specific bug patterns in real-world Kotlin applications is essential in avoiding common mistakes and writing correct programs.

In this paper, we present the first study of real-world concurrency bugs related to Kotlin coroutines. We examined 55 concurrency bug cases selected from 7 popular open-source repositories that use Kotlin coroutines, including IntelliJ IDEA, Firefox, and Ktor, and analyzed their bug characteristics and root causes. We identified common bug patterns related to asynchrony and Kotlin’s coroutine semantics, presenting them with their root causes, misconceptions that led to the bugs, and strategies for their automated detection. Overall, this study provides insight into programming with Kotlin coroutines concurrency and its pitfalls, aiming to shed light on common bug patterns and foster further research and development of concurrency analysis tools for Kotlin programs.
