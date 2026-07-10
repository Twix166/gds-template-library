---
title: Technical architecture overview
phase: Alpha
domain: Architecture
status: draft
related_service_standard_points:
  - Choose appropriate tools and technology
  - Make new source code open
owner_role: Technical Architect
last_updated: 2026-07-10
---

# Purpose

Describe the proposed technical architecture, constraints, trade-offs and open questions.

# When to use this

Use during Alpha to support technical decisions and Beta planning.

# Inputs

- Service blueprint
- Non-functional requirements
- Data dictionary
- Existing system information

# Template

Use this structure to summarise the proposed technical approach and the decisions still to make before Beta.

## 1. Context

| <abbr title="The name of the information item to complete.">Field</abbr> | <abbr title="The content to complete for the field.">Response</abbr> |
| --- | --- |
| <abbr title="The user, policy, operational and technical context for the service.">Service context</abbr> |  |
| <abbr title="The user journeys the architecture needs to support.">User journeys supported</abbr> |  |
| <abbr title="Existing systems, platforms or services involved in the architecture.">Existing systems involved</abbr> |  |
| <abbr title="Known limits, such as policy, legislation, technology, budget or operational constraints.">Constraints</abbr> |  |
| <abbr title="Technical questions still to answer before moving forward.">Open technical questions</abbr> |  |

## 2. Architecture view

| <abbr title="A system, service, module or part of the technical architecture.">Component</abbr> | <abbr title="What the role, team or component is responsible for.">Responsibility</abbr> | <abbr title="The data collected, stored, processed or transferred by a component.">Data handled</abbr> | <abbr title="The person or role accountable for the item.">Owner</abbr> | <abbr title="The current state of the item.">Status</abbr> |
| --- | --- | --- | --- | --- |
|  |  |  |  | Existing / Proposed / Unknown |

## 3. Integrations and data

| <abbr title="A connection or data movement between systems or teams.">Integration or data flow</abbr> | <abbr title="Where the data or evidence comes from.">Source</abbr> | <abbr title="Where data or a request is sent.">Destination</abbr> | <abbr title="The sensitivity or handling category of the data.">Data classification</abbr> | <abbr title="A risk, limitation or condition affecting the data flow or integration.">Risk or constraint</abbr> |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |

## 4. Quality and operations

| <abbr title="The part of the service, organisation or delivery context this row relates to.">Area</abbr> | <abbr title="The planned method or way of working for this area.">Approach</abbr> | <abbr title="Evidence or a decision still needed to progress the architecture.">Evidence or decision needed</abbr> |
| --- | --- | --- |
| Security |  |  |
| Privacy |  |  |
| Accessibility |  |  |
| Reliability |  |  |
| Observability |  |  |
| Open source and standards |  |  |

## 5. Architecture risks and decisions

| <abbr title="A risk or decision related to architecture or delivery.">Risk or decision</abbr> | <abbr title="The effect on users, operations, policy, delivery or technology.">Impact</abbr> | <abbr title="The person or role accountable for the item.">Owner</abbr> | <abbr title="The architecture decision record linked to the risk or decision.">Linked ADR</abbr> |
| --- | --- | --- | --- |
|  |  |  |  |

## Worked example

See [alpha-worked-example.md](../../examples/alpha/alpha-worked-example.md) for related Alpha architecture and feasibility evidence context.

# Quality checklist

- Choices are linked to user and service needs.
- Constraints and trade-offs are visible.
- Open source and standards considerations are covered.

# Related templates

- Architecture decision record
- Non-functional requirements
- Data dictionary

# Reference examples and sources

- GOV.UK Service Manual, [How the alpha phase works](https://www.gov.uk/service-manual/agile-delivery/how-the-alpha-phase-works), credited to the Agile delivery community and published under the Open Government Licence v3.0.
- Cabinet Office Central Digital and Data Office, [Technology Code of Practice](https://www.gov.uk/guidance/the-technology-code-of-practice), published under the Open Government Licence v3.0.

# Field glossary

Hover over table headers, and some field-name cells, to see short definitions in renderers that support HTML title text.

- **Approach**: The planned method or way of working for this area.
- **Area**: The part of the service, organisation or delivery context this row relates to.
- **Component**: A system, service, module or part of the technical architecture.
- **Constraints**: Known limits, such as policy, legislation, technology, budget or operational constraints.
- **Data classification**: The sensitivity or handling category of the data.
- **Data handled**: The data collected, stored, processed or transferred by a component.
- **Destination**: Where data or a request is sent.
- **Evidence or decision needed**: Evidence or a decision still needed to progress the architecture.
- **Existing systems involved**: Existing systems, platforms or services involved in the architecture.
- **Field**: The name of the information item to complete.
- **Impact**: The effect on users, operations, policy, delivery or technology.
- **Integration or data flow**: A connection or data movement between systems or teams.
- **Linked ADR**: The architecture decision record linked to the risk or decision.
- **Open technical questions**: Technical questions still to answer before moving forward.
- **Owner**: The person or role accountable for the item.
- **Response**: The content to complete for the field.
- **Responsibility**: What the role, team or component is responsible for.
- **Risk or constraint**: A risk, limitation or condition affecting the data flow or integration.
- **Risk or decision**: A risk or decision related to architecture or delivery.
- **Service context**: The user, policy, operational and technical context for the service.
- **Source**: Where the data or evidence comes from.
- **Status**: The current state of the item.
- **User journeys supported**: The user journeys the architecture needs to support.
