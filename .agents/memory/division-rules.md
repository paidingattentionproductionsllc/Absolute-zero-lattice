---
name: AZL division behavior
description: Project-specific handling of division by zero and its API representation.
---

In this project, dividing a value by zero returns the dividend unchanged (`N ÷ 0 = N`), and `0 ÷ 0` returns zero. The honesty check treats this operation as possible under AZL.

**Why:** The user supplied the project’s processing-framework specification and confirmed that the division-by-zero error should be resolved to match it.

**How to apply:** Keep the computation engine, honesty check, tests, dashboard, and law manifest consistent with this rule; do not substitute standard division-by-zero behavior.
