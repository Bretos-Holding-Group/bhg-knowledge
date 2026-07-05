# Repository Structure

> **Una arquitectura clara reduce la complejidad y preserva el conocimiento.**

---

# Purpose

This document defines the official directory structure of the BHG-Knowledge repository.

Every document must belong to a well-defined location with a clearly defined responsibility.

The repository structure is part of the governance of the ecosystem.

---

# Architectural Principles

The repository shall be:

- modular;
- deterministic;
- scalable;
- maintainable;
- human-friendly;
- AI-friendly;
- traceable.

Every directory has exactly one primary responsibility.

---

# Top-Level Structure

```
/
├── .github/
├── docs/
├── 00-GOBERNANZA/
├── 01-ESTRATEGIA/
├── 02-IDEAS/
├── 03-INVESTIGACION/
├── 04-LECCIONES/
├── 05-PROYECTOS/
├── 99-HISTORIAL/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
└── CHANGELOG.md
```

---

# Directory Responsibilities

## .github/

Repository automation.

Examples:

- Copilot Instructions
- Pull Request Templates
- Issue Templates
- GitHub Workflows (future)

---

## docs/

Technical documentation governing repository engineering.

Examples:

- Repository Standards
- Engineering Standards
- Naming Standards
- Metadata Standards
- AI Standards

---

## 00-GOBERNANZA/

Repository governance.

Defines:

- purpose;
- principles;
- lifecycle;
- taxonomy;
- governance rules.

---

## 01-ESTRATEGIA/

Long-term strategic knowledge.

Contains:

- strategic decisions;
- corporate vision;
- permanent policies.

---

## 02-IDEAS/

Knowledge capture.

Contains:

- incoming ideas;
- brainstorming;
- concept registration.

Ideas are never discarded.

---

## 03-INVESTIGACION/

Research activities.

Contains:

- studies;
- evaluations;
- comparisons;
- feasibility analyses;
- supporting evidence.

---

## 04-LECCIONES/

Lessons learned.

Documents:

- mistakes;
- discoveries;
- improvements;
- best practices.

---

## 05-PROYECTOS/

Knowledge transition.

An idea reaches this directory only after becoming an approved project.

The implementation itself belongs in a dedicated project repository.

---

## 99-HISTORIAL/

Historical preservation.

Contains:

- archived material;
- superseded documents;
- historical references.

Knowledge should remain discoverable.

---

# Repository Expansion

Future directories may be added only when:

- they solve a distinct responsibility;
- existing directories cannot reasonably contain the new content;
- governance documentation is updated.

---

# Directory Naming Rules

Directories should:

- use descriptive names;
- remain stable over time;
- avoid abbreviations unless officially defined;
- preserve numbering where ordering is intentional.

---

# Document Placement Rules

Every document shall have exactly one canonical location.

Documents should never exist in multiple directories.

Cross-references should be used instead of duplication.

---

# AI Navigation

AI systems should determine document locations using repository governance rather than heuristics.

When uncertainty exists:

1. consult governance;
2. consult repository standards;
3. preserve consistency.

---

# Final Principle

Repository structure is not about folders.

It is the architecture that allows knowledge to remain understandable decades into the future.
