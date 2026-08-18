---
title: BHG Idea Record Standard
document_id: BHG-KNOW-IDEA-RECORD
version: 0.1.0
status: Draft
document_type: Knowledge Standard
governance_level: Repository Architecture
owner: BHG Knowledge
language: en
classification: Internal
created: '2026-08-18'
last_updated: '2026-08-18'
---

# BHG Idea Record Standard

Defines the minimum identity and metadata model for an institutional idea record.

## Required fields

```yaml
idea_id: IDEA-YYYY-NNNN
title: <human-readable title>
version: 0.1.0
status: captured
type: business|product|technology|governance|architecture|finance|legal|operations|research|other
maturity: L4
owner: <person-or-role>
created: YYYY-MM-DD
last_updated: YYYY-MM-DD
```

## Recommended fields

```yaml
provenance:
  source: human|ai|research|meeting|external|derived
  source_reference: <reference>
problem_statement: <statement>
hypothesis: <statement>
strategic_alignment: []
dependencies: []
evidence: []
related_ideas: []
related_projects: []
related_entities: []
next_gate: G0
review_date: YYYY-MM-DD
```

## Identity rules

- `idea_id` is immutable.
- Version changes do not create a new identity.
- Supersession creates an explicit relationship rather than deleting history.
- AI-originated ideas must preserve sufficient provenance to identify the originating interaction or source where permitted.
- An idea record must never silently change meaning through metadata-only edits.

## Lifecycle and maturity

`status` and `maturity` are independent fields and must both be recorded.

## Evidence

Evidence references must identify the supporting artifact rather than merely claiming that evidence exists.

## Privacy and security

Idea records must not contain secrets, credentials, unnecessary personal data, or restricted evidence. Sensitive material should be referenced through the applicable protected evidence system.

## Current status

Draft. The schema requires reconciliation with BHG metadata standards before being treated as an enforced repository standard.
