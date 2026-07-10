---
title: Security risk assessment
phase: Beta
domain: Security
status: draft
related_service_standard_points:
  - Create a secure service
owner_role: Security Lead
last_updated: 2026-07-10
---

# Purpose

Assess security threats, vulnerabilities, controls, residual risks and decisions.

# When to use this

Use during Beta and before releases that affect security posture.

# Inputs

- Technical architecture overview
- Data dictionary
- Threat modelling outputs
- Security testing evidence

# Template

Use this structure to assess service-specific threats, controls and residual risks before release.

## 1. Security context

| <abbr title="The name of the information item to complete.">Field</abbr> | <abbr title="The content to complete for the field.">Response</abbr> |
| --- | --- |
| <abbr title="The part of the service covered by the artefact.">Service area</abbr> |  |
| <abbr title="The assets included in the security assessment.">Assets in scope</abbr> |  |
| <abbr title="The sensitivity or handling category of the data.">Data classification</abbr> |  |
| <abbr title="A link to threat modelling evidence.">Threat model link</abbr> |  |
| <abbr title="The person accountable for security risk management.">Security owner</abbr> |  |

## 2. Risks and controls

| <abbr title="A unique identifier for the risk.">Risk ID</abbr> | <abbr title="A potential attack, weakness or exposure.">Threat or vulnerability</abbr> | <abbr title="The service asset, data, component or process affected by a security risk.">Asset affected</abbr> | <abbr title="How likely the risk is to occur.">Likelihood</abbr> | <abbr title="The effect on users, operations, policy, delivery or technology.">Impact</abbr> | <abbr title="The control, action or process used to reduce a risk.">Control or mitigation</abbr> | <abbr title="The level of risk remaining after controls or mitigations are applied.">Residual risk</abbr> | <abbr title="The decision made or needed.">Decision</abbr> |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SEC-001 |  |  | Low / Medium / High | Low / Medium / High |  | Low / Medium / High |  |

## 3. Assurance evidence

| <abbr title="The research, data, observation or source that supports the statement.">Evidence</abbr> | <abbr title="The boundaries of what is included.">Scope</abbr> | <abbr title="The outcome of an assessment, test or measure.">Result</abbr> | <abbr title="The person or role accountable for the item.">Owner</abbr> | <abbr title="The date the item was recorded or changed.">Date</abbr> |
| --- | --- | --- | --- | --- |
| Penetration test |  |  |  |  |
| Vulnerability scan |  |  |  |  |
| Secure design review |  |  |  |  |

## 4. Residual risk acceptance

| <abbr title="A unique identifier for the risk.">Risk ID</abbr> | <abbr title="The person or role that accepts the residual risk.">Accepted by</abbr> | <abbr title="Conditions that must be met for the decision, approval or acceptance to remain valid.">Conditions</abbr> | <abbr title="The date an item should be reviewed.">Review date</abbr> |
| --- | --- | --- | --- |
|  |  |  |  |

## Worked example

See [beta-worked-example.md](../../examples/beta/beta-worked-example.md) for related Beta readiness and security evidence context.

# Quality checklist

- Risks are specific to the service architecture and data.
- Controls are practical and testable.
- Residual risks have explicit acceptance or treatment decisions.

# Related templates

- Risk register
- Privacy assessment
- Non-functional requirements

# Reference examples and sources

- GOV.UK Service Standard, [Point 9: Create a secure service](https://www.gov.uk/service-manual/service-standard/point-9-create-a-secure-service), credited to GOV.UK Service Manual contributors and published under the Open Government Licence v3.0.
- National Cyber Security Centre, [Cyber Assessment Framework](https://www.ncsc.gov.uk/collection/caf), credited to the National Cyber Security Centre.

# Field glossary

Hover over table headers, and some field-name cells, to see short definitions in renderers that support HTML title text.

- **Accepted by**: The person or role that accepts the residual risk.
- **Asset affected**: The service asset, data, component or process affected by a security risk.
- **Assets in scope**: The assets included in the security assessment.
- **Conditions**: Conditions that must be met for the decision, approval or acceptance to remain valid.
- **Control or mitigation**: The control, action or process used to reduce a risk.
- **Data classification**: The sensitivity or handling category of the data.
- **Date**: The date the item was recorded or changed.
- **Decision**: The decision made or needed.
- **Evidence**: The research, data, observation or source that supports the statement.
- **Field**: The name of the information item to complete.
- **Impact**: The effect on users, operations, policy, delivery or technology.
- **Likelihood**: How likely the risk is to occur.
- **Owner**: The person or role accountable for the item.
- **Residual risk**: The level of risk remaining after controls or mitigations are applied.
- **Response**: The content to complete for the field.
- **Result**: The outcome of an assessment, test or measure.
- **Review date**: The date an item should be reviewed.
- **Risk ID**: A unique identifier for the risk.
- **Scope**: The boundaries of what is included.
- **Security owner**: The person accountable for security risk management.
- **Service area**: The part of the service covered by the artefact.
- **Threat model link**: A link to threat modelling evidence.
- **Threat or vulnerability**: A potential attack, weakness or exposure.
