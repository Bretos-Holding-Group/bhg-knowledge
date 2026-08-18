---
title: BHG Idea Maturity Model
document_id: BHG-KNOW-IDEA-MATURITY
version: 0.1.0
status: Draft
document_type: Maturity Model
governance_level: Repository Architecture
owner: BHG Knowledge
language: en
classification: Internal
created: '2026-08-18'
last_updated: '2026-08-18'
---

# BHG Idea Maturity Model

## Principle

Maturity measures the degree of institutional confidence and authority earned by an idea or its resulting practice. It is independent from lifecycle state.

## L4 — Experimental

Purpose: exploration without institutional commitment.

Typical content:

- hypotheses;
- concepts;
- prototypes;
- speculative technologies;
- alternative business models;
- unvalidated governance mechanisms.

Minimum expectation: clear hypothesis, scope, owner, risks, and evidence plan.

## L3 — Operational

Purpose: controlled use after demonstrated viability.

Expected evidence may include:

- repeatable results;
- operational metrics;
- documented procedures;
- identified controls;
- known failure modes;
- bounded dependencies.

L3 does not imply architectural permanence.

## L2 — Architectural

Purpose: institutional design or standardization.

Expected evidence increases to include:

- sustained effectiveness;
- interoperability;
- maintainability;
- auditability;
- dependency analysis;
- continuity and succession analysis;
- legal, financial, security, and governance impact where applicable;
- independent verification where required.

L2 elements remain versionable.

## L1 — Constitutional

Purpose: exceptionally stable principles or constraints that should guide BHG across generations.

L1 candidates require the highest proof burden and must demonstrate, as applicable:

- constitutional compatibility;
- long-term necessity;
- institutional continuity value;
- broad impact assessment;
- independence from temporary technology or vendor choices;
- resilience under organizational change;
- explicit authority for canonicalization;
- independent verification and certification appropriate to the proposed authority.

L1 is not reached by age, popularity, founder preference, or successful implementation alone.

## Promotion rule

```text
L4 → L3 → L2 → L1
```

Each upward transition requires a distinct gate. A proposal may remain at its current level indefinitely, be rejected, archived, superseded, or return to a lower operational relevance state where justified.

## Anti-canonization rule

No technology, tool, methodology, vendor, temporary process, or experimental hypothesis should become constitutional merely because it is useful at a particular time.
