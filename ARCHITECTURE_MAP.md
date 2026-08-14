---
title: BHG Knowledge Architecture Map
document_id: BHG_KNOWLEDGE_ARCHITECTURE_MAP
version: 0.1.0
status: Draft
document_type: Repository Architecture Map
governance_level: Domain
owner: BHG-Knowledge
approval_authority: BHG Governance Council
created: 2026-08-14
last_updated: 2026-08-14
effective_date: null
classification: Internal
language: en
repository: bhg-knowledge

governed_by:
  - BHG_REPOSITORY_AUTHORITY_SEQUENCE
depends_on:
  - REPOSITORY_STANDARD
  - REPOSITORY_STRUCTURE
related_to:
  - BHG-GOV-CAM-001
  - BHG-Ecosystem-Foundation
  - ZivaLatam
---

# BHG Knowledge Architecture Map

## 1. Purpose

This document defines the repository architecture of BHG-Knowledge and its position in the BHG cross-repository authority sequence.

It is a local architecture contract. It does not create enterprise governance authority.

## 2. Authority position

BHG-Knowledge is a domain-specialization repository for organizational knowledge.

Its local rules must remain compatible with:

1. BHG Constitution;
2. BHG-Ecosystem-Foundation where institutional/ecosystem architecture applies;
3. BHG-Governance policies and standards;
4. local knowledge-system contracts;
5. implementation.

## 3. Materialized structure

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

## 4. Planned knowledge structure

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

## 5. Local responsibility

BHG-Knowledge may define:

- knowledge taxonomy;
- knowledge lifecycle;
- knowledge capture and retrieval workflows;
- research and decision records;
- knowledge services;
- future BKOs implementation contracts.

It must not redefine enterprise:

- constitutional authority;
- governance authority;
- document metadata semantics;
- document relationship semantics;
- approval authority.

## 6. New-document gate

Before creating a new normative or architectural document:

1. identify the subject and intended directory;
2. check for an existing canonical owner;
3. identify the superior authority;
4. apply the BHG canonical metadata and relationship vocabulary;
5. declare local specialization explicitly;
6. create the change on a non-main branch;
7. validate structure, metadata, authority and references;
8. preserve the change history.

A new document must not be created merely to duplicate a concept already owned elsewhere.

## 7. Architectural rule

Knowledge is a downstream specialization. It consumes governance; it does not become a competing governance source.

## 8. Status

```text
status: DRAFT
canonical: false
effective: false
automation_ready: false
```
