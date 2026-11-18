# Amalitech Engineering Standards — Professional Code Quality Reference

> A living reference for Amalitech engineers committed to writing clean, maintainable, production-quality code.

---

## Introduction

This repository is a structured knowledge base covering the engineering standards, conventions, and best practices expected of professional software engineers at Amalitech. It serves two purposes:

1. **Day-to-day reference** — a place to quickly look up naming conventions, commit message formats, checklist items, or clean-code principles while you are actively writing code.
2. **Learning path** — a progressive guide for engineers who want to deepen their understanding of what separates good code from production-quality code.

The material here is organised into numbered sections moving from foundational mindset (what are standards and why do they matter?) through language-specific guidelines, tooling, testing, security, and collaborative workflows. Each section stands alone, so you can jump directly to the topic you need.

### A Note on Official Amalitech Standards

Where this repository refers to "Amalitech standards", it describes professional engineering expectations consistent with industry best practice. **Official Amalitech-specific rules and policies will be extracted from the official Amalitech Engineering Standards PDF when that document is provided.** Sections marked with `⚠️ Pending official Amalitech source` contain general best-practice content as a placeholder until the official document is available. Do not treat unmarked content as an authoritative Amalitech policy statement.

---

## Table of Contents

| # | Section | Description |
|---|---------|-------------|
| [00](./00-introduction/README.md) | Introduction | What standards are, why they matter, the professional engineering mindset |
| [01](./01-clean-code/README.md) | Clean Code | Naming, functions, comments, formatting, refactoring, code smells |
| [02](./02-java-standards/README.md) | Java Standards | Java-specific conventions, idioms, and anti-patterns |
| [03](./03-oop-and-design/README.md) | OOP & Design Principles | SOLID, DRY, KISS, YAGNI, design patterns |
| [04](./04-testing/README.md) | Testing | Unit tests, integration tests, TDD, test quality |
| [05](./05-error-handling/README.md) | Error Handling | Exceptions, logging, fail-fast, defensive programming |
| [06](./06-security-basics/README.md) | Security Basics | Input validation, secrets management, common vulnerabilities |
| [07](./07-git-and-collaboration/README.md) | Git & Collaboration | Branching, commits, pull requests, code review |
| [08](./08-documentation/README.md) | Documentation | Javadoc, READMEs, ADRs, inline comments |
| [09](./09-performance-basics/README.md) | Performance Basics | Profiling, common bottlenecks, Big-O awareness |
| [10](./10-engineering-checklists/README.md) | Engineering Checklists | Pre-commit, pre-PR, code review, and production readiness checklists |
| [11](./11-official-amalitech-reference/README.md) | Official Amalitech Reference | ⚠️ Pending — extracted from official Amalitech PDF |

---

## How to Use This Repository

### For daily reference
Use the Table of Contents to navigate directly to the section relevant to your current task. Each section is self-contained and cross-references related sections where applicable.

### For onboarding
Work through sections 00 through 07 in order. Each builds on the previous. Take the exercises seriously — passive reading does not build habits; applying the material to real code does.

### For code reviews
Keep [Section 10 — Engineering Checklists](./10-engineering-checklists/README.md) open in a browser tab during reviews. Work through the code review checklist before submitting or approving a pull request.

### For team alignment
When a disagreement arises about style or convention, the documented standard in this repository is the agreed reference point. If a consensus emerges that the standard should change, open a pull request to update it, with a clear rationale.

---

## Companion Resource

This repository is designed to accompany the **Java Notebook** — a hands-on collection of Java code examples, patterns, and exercises.

🔗 **Java Notebook:** [https://github.com/john-okyere-282/java-notebook](https://github.com/john-okyere-282/java-notebook)

The Java Notebook contains runnable code corresponding to many of the examples described here. When a section references the notebook, follow the link to see the concept in working code.

---

## Distinguishing Official Amalitech Requirements from General Best Practice

This repository contains two categories of guidance, clearly distinguished throughout:

| Marker | Meaning |
|--------|---------|
| ✅ **Industry best practice** | Widely accepted in professional Java/software engineering; applies regardless of employer |
| 🏢 **Amalitech standard** | Specific to Amalitech's engineering team; sourced from official Amalitech documentation |
| ⚠️ **Pending official source** | Placeholder content following best practice; to be replaced or confirmed once the official Amalitech PDF is available |

When the official Amalitech Engineering Standards PDF is provided, its content will be extracted into Section 11 and cross-referenced into the relevant sections throughout this repository. Any conflict between general best practice and an official Amalitech requirement will be noted explicitly, and the official requirement will take precedence for Amalitech engineers.

---

## Contributing

If you spot an error, want to add an example, or propose a new section:

1. Fork the repository.
2. Create a branch: `docs/describe-your-change`.
3. Make your changes with clear, meaningful commit messages.
4. Open a pull request with a description explaining what you changed and why.

All contributions should follow the conventions described in [Section 07 — Git & Collaboration](./07-git-and-collaboration/README.md).

---

*Last updated: 2025 · Amalitech Engineering*
