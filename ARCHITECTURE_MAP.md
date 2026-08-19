---
title: BHG Knowledge Architecture Map
document_id: BHG_KNOWLEDGE_ARCHITECTURE_MAP
version: 0.2.0
status: Draft
document_type: Repository Architecture Map
governance_level: Domain
owner: BHG-Knowledge
approval_authority: Inherited from superior BHG governance authority
created: 2026-08-14
last_updated: 2026-08-19
effective_date: null
classification: Internal
language: en
repository: bhg-knowledge

governed_by:
  - BHG Constitution
  - BHG Governance
depends_on:
  - BHG Ecosystem Foundation
related_to:
  - BHG-GOV-CAM-001
  - ZivaLatam
---

# BHG Knowledge Architecture Map

## 1. Purpose

This document defines the local architecture of BHG-Knowledge and its position in the BHG cross-repository authority sequence.

It is a local architecture contract. It does not create enterprise governance authority.

## 2. Authority position

BHG-Knowledge is a downstream domain-specialization repository for organizational knowledge.

Its local rules must remain compatible with:

1. BHG Constitution;
2. BHG-Governance policies and standards;
3. BHG-Ecosystem-Foundation where institutional/ecosystem architecture applies;
4. local knowledge-system contracts;
5. implementation.

When authority or ownership is unclear, BHG-Knowledge must not invent or assume authority. The conflict must be resolved against the applicable superior authority and canonical owner.

## 3. Repository boundary

BHG-Knowledge may define and operate knowledge-specific concerns such as:

- knowledge taxonomy;
- knowledge lifecycle;
- knowledge capture and retrieval workflows;
- research and decision records;
- knowledge services;
- future BKOs implementation contracts.

It must not redefine enterprise:

- constitutional authority;
- enterprise governance authority;
- canonical metadata semantics owned elsewhere;
- canonical relationship semantics owned elsewhere;
- approval authority owned elsewhere;
- authority or ownership of another repository.

## 4. Materialized structure

The repository currently materializes:

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

Knowledge-domain directories described in earlier documentation are **planned until physically materialized and registered**. Documentation must not claim a directory exists merely because it is described as a target.

## 5. Planned knowledge structure

The intended future structure is:

```text
00-GOBERNANZA/
01-ESTRATEGIA/
02-IDEAS/
03-INVESTIGACION/
04-LECCIONES/
05-PROYECTOS/
99-HISTORIAL/
```

These directories shall be materialized only through a controlled architecture change.

## 6. Canonical ownership rule

Before creating or relocating a normative, architectural or knowledge document:

1. identify the subject;
2. identify the intended responsibility;
3. check whether a canonical owner already exists;
4. identify the superior authority;
5. determine whether BHG-Knowledge is actually the correct owner;
6. apply the applicable canonical metadata and relationship vocabulary;
7. declare local specialization explicitly;
8. create the change on a non-main branch;
9. validate structure, metadata, authority and references;
10. preserve the change history.

A new document must not be created merely to duplicate a concept already canonically owned elsewhere.

## 7. Architecture gate

A structural or normative change must not reach `main` until its authority, ownership, location, metadata and references have been validated.

The gate is procedural and does not itself grant approval authority.

## 8. Architectural rule

Knowledge is a downstream specialization. It consumes governance; it does not become a competing governance source.

## 9. Status

```text
status: DRAFT
canonical: false
effective: false
automation_ready: false
```
