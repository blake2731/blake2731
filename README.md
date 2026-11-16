# Blake Schmitt

**Software engineer | Python, TypeScript, React, and practical automation**

I build software to solve concrete problems, from web applications and business workflows to correctness fixes in open source libraries. I earned a B.S. in Computer Science from Southern New Hampshire University, graduating summa cum laude.

## Open source contributions

### NVIDIA cuDF: Nullable Boolean correctness

**[Merged PR #25166](https://github.com/NVIDIA/cudf/pull/25166) | November 16, 2026 | Python, GPU data processing, regression testing**

Fixed incorrect null propagation in nullable Boolean AND and OR operations. Expressions such as `True | <NA>` and `False & <NA>` previously returned null where the correct Boolean result was known. The change routes these operations through the existing libcudf null aware logical operators and adds regression coverage for truth tables, scalar and reflected operations, unchanged bitwise behavior, and DataFrame filtering.

**Engineering focus:** tracing a user visible bug to operator semantics, preserving existing behavior, and building tests around both the original failure and adjacent cases.

[Read the merged implementation and discussion](https://github.com/NVIDIA/cudf/pull/25166)

### BioBase: Codon Adaptation Index

**[Merged PR #15](https://github.com/lignum-vitae/biobase/pull/15) | November 3, 2025 | Python, numerical logic, testing**

Implemented Codon Adaptation Index calculations with DNA/RNA handling, input validation, reference codon weights, and tests for normal and edge cases.

[Explore the merged contribution](https://github.com/lignum-vitae/biobase/pull/15)

## Selected project work

**[Rehearsal](https://github.com/blake2731/astra-challenge)**  
An AI assisted TypeScript and React project for testing tool using agents through synthetic scenarios, constrained actions, and deterministic replay.

**[SmallBizzWizz](https://github.com/blake2731/smallbizzwizz)**  
An AI assisted Next.js and TypeScript project focused on website analysis, input validation, and actionable findings.

**[Portfolio](https://blake2731.github.io/my-portfolio/)**  
A collection of software projects, engineering decisions, and ongoing work.

## How I work

I value reproducible defects, clear acceptance criteria, thoughtful tests, and solutions that simplify real workflows. I use AI tools in my development process and distinguish assisted projects from independently reviewable contributions.

**[LinkedIn](https://www.linkedin.com/in/blake2731/) | [Portfolio](https://blake2731.github.io/my-portfolio/) | [GitHub](https://github.com/blake2731)**
