---
title: Non-functional requirements
phase: Alpha
domain: Architecture
status: draft
related_service_standard_points:
  - Create a secure service
  - Operate a reliable service
owner_role: Technical Architect
last_updated: 2026-07-10
---

# Purpose

Capture service qualities such as performance, resilience, security, accessibility and supportability.

# When to use this

Use during Alpha and refine throughout Beta as the service design matures.

# Inputs

- User needs
- Operational constraints
- Security and privacy requirements
- Service performance targets

# Template

Use this structure to capture measurable service qualities that will need design, build or test evidence.

## 1. Requirement catalogue

| <abbr title="A stable identifier used to track the item across documents.">ID</abbr> | <abbr title="A functional, non-functional, policy or operational requirement.">Requirement</abbr> | <abbr title="The type of requirement or service quality being recorded.">Category</abbr> | <abbr title="Why the requirement, decision or approach is needed.">Rationale</abbr> | <abbr title="The measurable threshold or target for the requirement.">Measure or target</abbr> | <abbr title="The relative importance of the item.">Priority</abbr> | <abbr title="The person or role accountable for the item.">Owner</abbr> | <abbr title="Evidence that shows the requirement has been met.">Acceptance evidence</abbr> |
| --- | --- | --- | --- | --- | --- | --- | --- |
| NFR-001 |  | Performance / Security / Accessibility / Reliability / Supportability |  |  | Must / Should / Could |  |  |

## 2. Service quality risks

| <abbr title="An uncertain event or condition that could affect outcomes.">Risk</abbr> | <abbr title="The requirement linked to this risk, test or action.">Related requirement</abbr> | <abbr title="The effect on users, operations, policy, delivery or technology.">Impact</abbr> | <abbr title="The action or control used to reduce impact or likelihood.">Mitigation</abbr> | <abbr title="The person or role accountable for the item.">Owner</abbr> |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |

## 3. Test and assurance approach

| <abbr title="The type of requirement or service quality being recorded.">Category</abbr> | <abbr title="The method used to prove whether the requirement has been met.">How it will be tested</abbr> | <abbr title="The evidence the team expects to produce or collect in Beta.">Evidence expected in Beta</abbr> |
| --- | --- | --- |
| Performance |  |  |
| Security |  |  |
| Accessibility |  |  |
| Reliability |  |  |
| Supportability |  |  |

## Worked example

See [alpha-worked-example.md](../../examples/alpha/alpha-worked-example.md) for related Alpha service-quality evidence context.

# Quality checklist

- Requirements are measurable where possible.
- Critical service qualities have clear owners.
- Requirements are linked to tests or acceptance evidence.

# Related templates

- Test strategy
- Security risk assessment
- Operational readiness checklist

# Reference examples and sources

- GOV.UK Service Standard, [Point 9: Create a secure service](https://www.gov.uk/service-manual/service-standard/point-9-create-a-secure-service), credited to GOV.UK Service Manual contributors and published under the Open Government Licence v3.0.
- GOV.UK Service Standard, [Point 14: Operate a reliable service](https://www.gov.uk/service-manual/service-standard/point-14-operate-a-reliable-service), credited to GOV.UK Service Manual contributors and published under the Open Government Licence v3.0.

# Field glossary

Hover over table headers, and some field-name cells, to see short definitions in renderers that support HTML title text.

- **Acceptance evidence**: Evidence that shows the requirement has been met.
- **Category**: The type of requirement or service quality being recorded.
- **Evidence expected in Beta**: The evidence the team expects to produce or collect in Beta.
- **How it will be tested**: The method used to prove whether the requirement has been met.
- **ID**: A stable identifier used to track the item across documents.
- **Impact**: The effect on users, operations, policy, delivery or technology.
- **Measure or target**: The measurable threshold or target for the requirement.
- **Mitigation**: The action or control used to reduce impact or likelihood.
- **Owner**: The person or role accountable for the item.
- **Priority**: The relative importance of the item.
- **Rationale**: Why the requirement, decision or approach is needed.
- **Related requirement**: The requirement linked to this risk, test or action.
- **Requirement**: A functional, non-functional, policy or operational requirement.
- **Risk**: An uncertain event or condition that could affect outcomes.
