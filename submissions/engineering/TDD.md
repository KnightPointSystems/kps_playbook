---
layout: submission
permalink: /submissions/engineering/TDD
---

# Test-Driven Development

There's broad agreement among developers about the value of automated testing. At DID(IT), we value consistency and reliability, and we recognize the essential value of a comprehensive automated test suite for each project in our portfolio.
We never forget that what we really deliver for our end users is a change in the way they do their work. Our work becomes a part of their work flow. We take responsibility for helping our clients to improve their work cadence and effectiveness. In order to do that, we must consistently deliver reliable solutions.

We deploy code via automated tooling, guarranteeing that each release must pass its suite of automated tests. We automatically scan code for coverage statistics, but the true measure of the completeness of a test suite is in the exceptions to which a client is never exposed. We believe the best way to attain that completeness is to have a test for each new feature _before_ the code for it gets written. Much has been written about the benefits of this approach, which we don't need to replicate here (eg; <https://apiumhub.com/tech-blog-barcelona/advantages-of-test-driven-development/>).

Test-driven development (TDD) takes longer up front, and for that reason conscientious developers might feel resistance to taking this approach. We acknowledge the importance of giving developers the opportunity to discover their own best discipline, but we stress the utility of writing tests as a way to frame the problem of writing a feature so that it is expressed clearly and completely. Then, when code is written to satisfy the test, it can more reasonably be expected to satisfy the conditions of use in the wild.

TDD is often described as consisting of short cycles of development, in which a set of requirements for a feature is laid out in failing tests, and then code is written to satisfy those requirements, proven by the tests. What is perhaps not discussed as often is the impact on the developer of this type of tight cycle. The developer is after all, an essential part of the 'factory' producing usable features. We find that writing code to satisfy tests significantly reduces the stress of trying to simultaneously code for the immediate problem and to code 'in advance' for features that may or may not become necessary over time. We believe this enforced focus leads to consistently better code.

We believe that the practice of the entire team benefits in subtle ways when TDD is practiced. Clear acceptance criteria give rise to good tests, and conversely, the need to write good, prescriptive tests encourages the writing of clearly-testable acceptance criteria.

Some articles point to benefits of TDD which only emerge over time (eg; <https://www.madetech.com/blog/9-benefits-of-test-driven-development>, #8). We consider these benefits to be of primary importance. All software projects expand in complexity over time, and the true test of good code is its ability to weather those changes. Various writers have said that, "Programming is about managing complexity." In fact, there was a CS course at Stanford devoted to just this topic. Its outline is worth a look as a rubric for judging well-programmed code. (<https://web.stanford.edu/~ouster/cgi-bin/cs190-spring15/lecture.php?topic=complexity>).

As our clients' practices change, so do their requirements of the tools we make to help them work. Features can be removed but are more likely are added over time. In order to ensure the successful maintenance of our applications and APIs, our test suites must describe, as completely as is practical, both the intended function and likely outcomes arising from each part of the code. Test written in advance of code make excellent documentation. They are both thoughtful and always current, as demonstrated by passing code.
