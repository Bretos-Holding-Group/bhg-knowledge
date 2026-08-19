# Repository Structure

> **Una arquitectura clara reduce la complejidad y preserva el conocimiento.**

---

# Purpose

This document defines the intended directory structure of the BHG-Knowledge repository.

Every document must belong to a well-defined location with a clearly defined responsibility.

The repository structure is a local architecture concern operating under the BHG cross-repository authority sequence. It does not create enterprise governance authority.

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

Every materialized directory has exactly one primary responsibility.

A planned directory is not considered present until it is physically materialized and registered through a controlled architecture change.

---

# Materialized Top-Level Structure

The current materialized structure is:

```text
/
├── .github/
├── docs/
│   └── repository/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
└── CHANGELOG.md
```

The knowledge-domain directories below are architectural targets, not current filesystem facts.

---

# Planned Knowledge Structure

```text
00-GOBERNANZA/
01-ESTRATEGIA/
02-IDEAS/
03-INVESTIGACION/
04-LECCIONES/
05-PROYECTOS/
99-HISTORIAL/
```

These directories shall be materialized only through a controlled architecture change that verifies authority, responsibility, metadata and references.

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

Technical documentation governing repository engineering and local architecture.

Examples:

- Repository Standards
- Engineering Standards
- Naming Standards
- Metadata Standards
- AI Standards

These documents must remain compatible with superior BHG governance and must not redefine it.

---

## 00-GOBERNANZA/

Planned local governance-interface area.

If materialized, it may contain local knowledge-system rules, lifecycle definitions, taxonomies and operating contracts that are subordinate to superior BHG authority.

It must not be treated as a substitute for BHG constitutional or enterprise governance repositories.

---

## 01-ESTRATEGIA/

Long-term strategic knowledge within the scope assigned to BHG-Knowledge.

---

## 02-IDEAS/

Knowledge capture.

Contains, when materialized:

- incoming ideas;
- brainstorming;
- concept registration.

Ideas are preserved according to the applicable lifecycle rules.

---

## 03-INVESTIGACION/

Research activities.

Contains, when materialized:

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

An idea reaches this directory only after satisfying the applicable project-entry criteria.

The implementation itself belongs in the dedicated project repository when such a repository exists.

---

## 99-HISTORIAL/

Historical preservation.

Contains, when materialized:

- archived material;
- superseded documents;
- historical references.

Knowledge should remain discoverable and traceable.

---

# Repository Expansion

Future directories may be added only when:

- they solve a distinct responsibility;
- existing directories cannot reasonably contain the new content;
- the proposed owner and authority are identifiable;
- the change passes the repository creation gate;
- architecture documentation is updated consistently.

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

Documents should never exist in multiple directories unless an explicit archival or reference mechanism requires it.

Cross-references should be used instead of duplication.

Before creating a document, determine whether another repository or directory is already the canonical owner.

---

# AI Navigation

AI systems should determine document locations using repository architecture and applicable governance rather than heuristics.

When uncertainty exists:

1. consult superior authority;
2. consult the repository architecture contract;
3. identify the canonical owner;
4. preserve consistency;
5. stop rather than invent authority when the conflict cannot be resolved.

---

# Final Principle

Repository structure is not about folders.

It is the architecture that allows knowledge to remain understandable decades into the future, while preserving clear boundaries of authority and responsibility.
