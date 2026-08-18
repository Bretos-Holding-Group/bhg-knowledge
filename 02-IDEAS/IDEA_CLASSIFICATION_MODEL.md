---
id: DOC-IDEA-CLASSIFICATION-MODEL
name: Idea and Knowledge Object Classification Model
version: 0.1.0
status: Draft
maturity: L4
owner: BHG-Knowledge
---

# Idea and Knowledge Object Classification Model

## Purpose

Prevent the institutional idea registry from treating every recovered concept as the same type of object.

## Candidate object classes

| Class | Meaning | Typical authority |
|---|---|---|
| `IDEA` | Potential concept or solution | L4 initially |
| `PRINCIPLE` | Foundational proposition about how BHG should operate | Candidate for L1; requires exceptional review |
| `HYPOTHESIS` | Testable proposition without sufficient evidence | L4 |
| `RESEARCH` | Investigation intended to produce knowledge | L4/L3 |
| `EXPERIMENT` | Controlled test of a hypothesis or design | L4/L3 |
| `ARCHITECTURE` | Structural design for systems or institutions | L2 candidate |
| `STANDARD` | Reusable prescribed practice | L2 candidate |
| `POLICY` | Governed rule for organizational behavior | L2/L1 depending on scope |
| `SYSTEM` | Coherent capability composed of components | L3/L2 |
| `PRODUCT` | Externally or internally delivered offering | L3/L2 |
| `PROJECT` | Time-bounded implementation effort | L3 |
| `FEATURE` | Capability belonging to a product/system | L3 |
| `ASSET` | Controlled resource or property | L2/L3 |
| `DECISION` | Recorded choice and its rationale | Cross-cutting evidence object |

## Classification rules

1. Classification is independent from lifecycle state.
2. Classification is independent from maturity.
3. A single concept may produce multiple related objects.
4. A project is not automatically an idea.
5. A feature is not automatically a strategic initiative.
6. A principle is not constitutional merely because it is classified as `PRINCIPLE`.
7. When uncertain, use the least committal classification and record the uncertainty.

## Relationship vocabulary

- `PARENT_OF`
- `DERIVED_FROM`
- `RELATED_TO`
- `DUPLICATE_OF`
- `MERGED_INTO`
- `SUPERSEDES`
- `IMPLEMENTS`
- `EVIDENCES`
- `DEPENDS_ON`
- `CONFLICTS_WITH`

## Maturity interaction

Classification answers **what the object is**.

Lifecycle answers **where it is in its process**.

Maturity answers **how much institutional confidence and authority it has earned**.

Evidence answers **why its current position is justified**.

These dimensions must not be collapsed into one status field.

## Status

Draft/L4. This model is exploratory and subject to reconciliation with existing Genesis, BHG-Governance, and repository metadata standards.
