# GDS Templates 101

This is a short guide to how the templates fit together across a typical GDS-style service lifecycle.

The templates are not a mandatory sequence. Use them to create enough evidence for the decisions your team needs to make.

## Timeline

```text
Discovery
  start: problem statement, stakeholder map
  research: user needs, journey map, service blueprint, assumptions log
  end: options assessment, findings report, discovery evidence pack

Alpha
  start: alpha plan, research plan, prototype description
  test: user testing findings, architecture overview, ADRs, non-functional requirements
  end: MVP definition, alpha evidence pack

Beta
  start: beta delivery plan, release plan, test strategy
  build and assure: accessibility, privacy, security, support model
  release: operational readiness checklist, beta evidence pack

Live
  start: live service management plan, dashboard, runbook, incident process
  operate: service reviews, continual improvement plan
  prove value: benefits realisation report, live evidence pack
```

## Discovery: understand before deciding

Start with the [problem statement](../templates/discovery/problem-statement.md) and [stakeholder map](../templates/discovery/stakeholder-map.md). These help the team avoid jumping straight to a solution.

As research progresses, create the [user needs catalogue](../templates/discovery/user-needs-catalogue.md), [current state journey map](../templates/discovery/current-state-journey-map.md) and [current state service blueprint](../templates/discovery/service-blueprint-current-state.md). Keep an [assumptions log](../templates/discovery/assumptions-log.md) running from the start.

At the end of Discovery, use the [options assessment](../templates/discovery/options-assessment.md) and [discovery findings report](../templates/discovery/discovery-findings-report.md) to recommend whether to stop, re-scope, hand over or move to Alpha.

## Alpha: test the riskiest ideas

Start Alpha with an [alpha plan](../templates/alpha/alpha-plan.md), [user research plan](../templates/alpha/user-research-plan.md) and [prototype description](../templates/alpha/prototype-description.md). These should focus on learning, not building the final service.

As the team prototypes, record [user testing findings](../templates/alpha/user-testing-findings.md). Capture technical thinking in the [technical architecture overview](../templates/alpha/technical-architecture-overview.md), [architecture decision records](../templates/alpha/architecture-decision-record.md) and [non-functional requirements](../templates/alpha/non-functional-requirements.md).

At the end of Alpha, use the [MVP definition](../templates/alpha/mvp-definition.md) and [alpha evidence pack](../templates/alpha/alpha-assessment-evidence-pack.md) to decide whether there is a viable Beta.

## Beta: build, test and prepare to run

Start Beta with a [beta delivery plan](../templates/beta/beta-delivery-plan.md), [release plan](../templates/beta/release-plan.md) and [test strategy](../templates/beta/test-strategy.md).

As the service is built, maintain evidence for [accessibility](../templates/beta/accessibility-assessment.md), [privacy](../templates/beta/privacy-assessment.md), [security](../templates/beta/security-risk-assessment.md) and [support](../templates/beta/support-model.md).

Before release or assessment, use the [operational readiness checklist](../templates/beta/operational-readiness-checklist.md) and [beta evidence pack](../templates/beta/beta-assessment-evidence-pack.md) to check whether the service is ready for wider use.

## Live: operate and improve

When the service goes Live, start with the [live service management plan](../templates/live/live-service-management-plan.md), [service dashboard](../templates/live/service-dashboard.md), [operational runbook](../templates/live/operational-runbook.md) and [incident management process](../templates/live/incident-management-process.md).

Use regular [service reviews](../templates/live/service-review.md) to look at performance, support, incidents, accessibility, risks and user feedback. Feed agreed actions into the [continual improvement plan](../templates/live/continual-improvement-plan.md).

Use the [benefits realisation report](../templates/live/benefits-realisation-report.md) and [live evidence pack](../templates/live/live-assessment-evidence-pack.md) to show whether the service is delivering the expected value.

## Cross-cutting templates

Some templates are useful throughout:

- [Risk register](../templates/cross-cutting/risk-register.md)
- [Issue register](../templates/cross-cutting/issue-register.md)
- [Decision log](../templates/cross-cutting/decision-log.md)
- [Dependency register](../templates/cross-cutting/dependency-register.md)
- [Requirements catalogue](../templates/cross-cutting/requirements-catalogue.md)
- [Traceability matrix](../templates/cross-cutting/traceability-matrix.md)

Use these when they help the team make decisions, show evidence or manage delivery. Do not maintain them just because they exist.

## Rule of thumb

Start documents early, keep them lightweight, and update them when evidence changes.

The best template is one that helps the team make a better decision.

