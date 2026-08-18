---
title: BHG Idea Promotion Gates
document_id: BHG-KNOW-IDEA-GATES
version: 0.1.0
status: Draft
document_type: Promotion Gate Model
governance_level: Repository Architecture
owner: BHG Knowledge
language: en
classification: Internal
created: '2026-08-18'
last_updated: '2026-08-18'
---

# BHG Idea Promotion Gates

This is a preliminary gate model. It establishes the concept of increasing proof burden without yet making the gate criteria mandatory.

## Gate 0 — Experimental Readiness

Question: Is the hypothesis sufficiently defined to be tested safely?

Expected evidence:

- identity and provenance;
- objective and hypothesis;
- scope;
- owner;
- success criteria;
- known risks;
- review date.

Outcome: authorize, revise, defer, or reject experimentation.

## Gate 1 — Operational Validation

Question: Does the experiment work sufficiently well and repeatably for bounded operational use?

Expected evidence may include:

- test results;
- measurable outcomes;
- repeatability;
- failure modes;
- operational controls;
- cost and dependency assessment.

Outcome: remain experimental, validate for operational use, defer, or reject.

## Gate 2 — Architectural Certification

Question: Does the validated practice deserve a place in BHG architecture or a governed standard?

Expected evidence may include:

- sustained results;
- interoperability;
- maintainability;
- auditability;
- dependency analysis;
- security and compliance impact;
- continuity and succession analysis;
- reversibility or migration strategy;
- independent verification where appropriate.

Outcome: promote to L2, retain at L3, revise, supersede, or reject.

## Gate 3 — Constitutional Certification

Question: Is the proposal sufficiently fundamental, durable, and necessary to constrain BHG across generations?

Expected evidence may include:

- constitutional compatibility;
- long-term impact assessment;
- institutional continuity assessment;
- authority and power-distribution analysis;
- legal and regulatory review where applicable;
- independence from temporary implementation choices;
- independent verification;
- explicit canonicalization decision.

Outcome: promote to L1 only through the authority defined by BHG constitutional governance. Otherwise remain at L2 or lower.

## Proof-burden principle

The evidence burden increases with requested authority.

```text
L4  →  Gate 0  →  L3  →  Gate 1  →  L2  →  Gate 2  →  L1  →  Gate 3
low                                                        highest
proof burden                                                proof burden
```

## Negative gates

A proposal must not advance where it:

- conflicts with constitutional authority;
- destroys required traceability;
- creates unacceptable or unbounded dependency;
- cannot be meaningfully audited where auditability is required;
- lacks a viable continuity or recovery path for its risk class;
- concentrates authority contrary to applicable governance;
- introduces unacceptable legal, financial, security, or systemic risk.

## Independence

Gate criteria, required evidence, and certification authorities must themselves remain subordinate to the BHG governance hierarchy. This document does not create constitutional authority.
