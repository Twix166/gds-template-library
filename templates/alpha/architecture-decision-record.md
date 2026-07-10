---
title: Architecture decision record
phase: Alpha
domain: Architecture
status: draft
related_service_standard_points:
  - Choose appropriate tools and technology
  - Use and contribute to open standards
owner_role: Technical Architect
last_updated: 2026-07-10
---

# Purpose

Record an important architecture decision, the options considered and the consequences.

# When to use this

Use whenever a technical decision has meaningful impact or future cost.

# Inputs

- Architecture overview
- Technical spike findings
- Security and privacy advice
- Delivery constraints

# Template

Copy this structure for decisions that are significant, difficult to reverse or important for assessment evidence.

## 1. Decision record

| <abbr title="The name of the information item to complete.">Field</abbr> | <abbr title="The content to complete for the field.">Response</abbr> |
| --- | --- |
| <abbr title="A unique identifier for an architecture decision record.">ADR ID</abbr> |  |
| <abbr title="The short title of the decision or artefact.">Title</abbr> |  |
| <abbr title="The current state of the item.">Status</abbr> | Proposed / Accepted / Superseded / Deprecated |
| <abbr title="The date the item was recorded or changed.">Date</abbr> |  |
| <abbr title="The person accountable for making or confirming the decision.">Decision owner</abbr> |  |

## 2. Context

Explain the user, service, technical, policy or operational context that makes a decision necessary.

## 3. Options considered

| <abbr title="A possible course of action.">Option</abbr> | <abbr title="The expected advantages or positive outcomes of the option or decision.">Benefits</abbr> | <abbr title="Negative consequences, limitations or uncertainties.">Risks or drawbacks</abbr> | <abbr title="The relative cost, time, complexity or effort of an option.">Cost or complexity</abbr> | <abbr title="The decision made or needed.">Decision</abbr> |
| --- | --- | --- | --- | --- |
|  |  |  |  | Accepted / Rejected |

## 4. Decision

State the decision clearly in one or two sentences.

## 5. Consequences

| <abbr title="A practical effect or trade-off created by the decision.">Consequence</abbr> | <abbr title="The effect on users, operations, policy, delivery or technology.">Impact</abbr> | <abbr title="The action needed after recording the item.">Follow-up action</abbr> | <abbr title="The person or role accountable for the item.">Owner</abbr> |
| --- | --- | --- | --- |
|  |  |  |  |

## 6. Review and supersession

| <abbr title="The date an item should be reviewed.">Review date</abbr> | <abbr title="An event or condition that should cause the decision to be reviewed.">Review trigger</abbr> | <abbr title="The later decision record or artefact that replaces this one.">Superseded by</abbr> |
| --- | --- | --- |
|  |  |  |

## Worked example

See [alpha-worked-example.md](../../examples/alpha/alpha-worked-example.md) for related Alpha decision and architecture evidence context.

# Quality checklist

- The decision is specific and dated.
- Rejected options and rationale are included.
- Consequences are practical and testable.

# Related templates

- Technical architecture overview
- Decision log
- Risk register

# Reference examples and sources

- Michael Nygard, [Documenting Architecture Decisions](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions), credited as the origin of the widely used ADR pattern.
- ADR GitHub organisation, [Architecture Decision Records](https://adr.github.io/), a public collection of ADR guidance and examples.
- Cabinet Office Central Digital and Data Office, [Technology Code of Practice](https://www.gov.uk/guidance/the-technology-code-of-practice), published under the Open Government Licence v3.0.

# Field glossary

Hover over table headers, and some field-name cells, to see short definitions in renderers that support HTML title text.

- **ADR ID**: A unique identifier for an architecture decision record.
- **Benefits**: The expected advantages or positive outcomes of the option or decision.
- **Consequence**: A practical effect or trade-off created by the decision.
- **Cost or complexity**: The relative cost, time, complexity or effort of an option.
- **Date**: The date the item was recorded or changed.
- **Decision**: The decision made or needed.
- **Decision owner**: The person accountable for making or confirming the decision.
- **Field**: The name of the information item to complete.
- **Follow-up action**: The action needed after recording the item.
- **Impact**: The effect on users, operations, policy, delivery or technology.
- **Option**: A possible course of action.
- **Owner**: The person or role accountable for the item.
- **Response**: The content to complete for the field.
- **Review date**: The date an item should be reviewed.
- **Review trigger**: An event or condition that should cause the decision to be reviewed.
- **Risks or drawbacks**: Negative consequences, limitations or uncertainties.
- **Status**: The current state of the item.
- **Superseded by**: The later decision record or artefact that replaces this one.
- **Title**: The short title of the decision or artefact.
