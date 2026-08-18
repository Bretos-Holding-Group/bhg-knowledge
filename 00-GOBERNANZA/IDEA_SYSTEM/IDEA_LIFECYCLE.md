---
title: BHG Idea Lifecycle

document_id: BHG-KNOW-IDEA-LIFECYCLE
version: 0.1.0
status: Draft
document_type: Lifecycle Model
governance_level: Repository Architecture
owner: BHG Knowledge
language: en
classification: Internal
created: '2026-08-18'
last_updated: '2026-08-18'
---

# BHG Idea Lifecycle

This is a preliminary lifecycle model. It is not yet a mandatory operating standard.

## States

`CAPTURED` — idea has been registered with minimum provenance and context.

`CLASSIFIED` — initial domain, type, relevance, and relationships have been assigned.

`DRAFT` — idea is being clarified without requesting institutional adoption.

`PROPOSED` — explicit proposal for evaluation exists.

`UNDER_REVIEW` — formal review is active.

`EXPERIMENTAL` — idea is being tested under Experimental Governance.

`VALIDATED` — defined success criteria have been met with sufficient evidence for the applicable gate.

`IN_DEVELOPMENT` — approved implementation work is active.

`IMPLEMENTED` — intended implementation is complete and verified.

`MONITORED` — implementation remains under observation for performance, risk, and continued relevance.

`PROMOTED` — the resulting practice or standard has advanced to a higher maturity level through the applicable gate.

## Terminal states

`REJECTED` — evidence or governance review determined that the proposal should not advance.

`DEFERRED` — intentionally paused pending conditions or future evidence.

`ARCHIVED` — retained for institutional memory but no longer active.

`SUPERSEDED` — replaced by a later version or alternative.

`ABANDONED` — discontinued without expected near-term continuation.

## Rules

1. Every state transition must be traceable.
2. A transition must identify the decision basis.
3. Promotion must identify the applicable gate.
4. Evidence must be referenced rather than implied.
5. Terminal states preserve historical identity.
6. Lifecycle state and maturity level are independent fields.
7. No lifecycle state grants constitutional authority by itself.

## Initial transition model

```text
CAPTURED → CLASSIFIED → DRAFT → PROPOSED → UNDER_REVIEW
                                      │
                                      ▼
                                 EXPERIMENTAL
                                      │
                              ┌───────┴───────┐
                              ▼               ▼
                          VALIDATED       DEFERRED
                              │
                              ▼
                        IN_DEVELOPMENT
                              │
                              ▼
                         IMPLEMENTED
                              │
                              ▼
                           MONITORED
                              │
                              ▼
                           PROMOTED
```

Rejection, archival, supersession, and abandonment may occur where justified and must preserve provenance.
