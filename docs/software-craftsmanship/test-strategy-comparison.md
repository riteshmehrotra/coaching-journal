---
layout: default
title: Unit testing vs E2E testing
nav_order: 3
parent: Software craftsmanship
has_toc: true
---

# Test strategy comparison


| **Characteristics** | **Unit tests**    | **E2E tests**        |
| ------------------- | ----------------- | -------------------- |
| Focus               | Unit of behaviour | A system flow        |
| Size                | Small             | Large                |
| Coverage            | Immediate         | Not straight forward |
| Feedback            | Immediate         | Takes long time      |
| Blast radius        | Isolated          | Potentially high     |
| Error localization  | Easier            | Harder               |
| Maintainability     | Easy              | Hard to maintain     |


**Focus**: Unit tests focus on an isolated unit of behaviour, while E2E tests target an integrated system flow that may involve multiple components.

**Size**: Unit tests focus on specific behaviors, thus being small in size. In contrast, E2E tests vary in size depending on the flow and number of coordinating components.

**Coverage**: With each unit test, your code coverage could improve immediately. Coverage with E2E is not straight forward and may require additional tooling.

**Feedback**: Unit tests provide instant feedback, running quickly. In contrast, end-to-end (E2E) tests can take hours due to their integrated nature and complexity. 

**Blast radius**: Unit test failures are isolated and do not affect other tests. Conversely, in end-to-end (E2E) tests, a single step failure can cause the entire suite to fail.

**Error localization**: Unit tests' smaller scope makes identifying failure reasons easier, while complex E2E tests may prolong issue identification

**Maintainability**: Unit tests are easily modifiable, whereas E2E tests demand substantial effort 




