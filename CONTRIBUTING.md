# Contributing

Contributions are welcome from people working on or around UK government digital services.

## Principles

- Use plain, professional UK English.
- Keep templates practical and easy to adapt.
- Avoid creating process for its own sake.
- Link templates to user needs, service outcomes and evidence.
- Treat templates as starting points, not mandatory formats.
- Prefer concise guidance over long explanations.

## Template format

New templates should be Markdown files with front matter:

```yaml
---
title:
phase:
domain:
status: placeholder
related_service_standard_points:
owner_role:
last_updated:
---
```

They should include these sections:

```markdown
# Purpose

# When to use this

# Inputs

# Template

# Quality checklist

# Related templates

# Field glossary
```

For templates with tables, table headers should use Markdown-compatible HTML hover text:

```html
<abbr title="A stable identifier used to track the item across documents.">ID</abbr>
```

Add a `Field glossary` at the end of the template that explains each table field in plain English. If a placeholder template does not yet contain structured tables, include a short note saying that field definitions should be added when the template is expanded.

## Status values

Use one of:

- `placeholder`: structure exists but content still needs development.
- `draft`: usable but still being reviewed.
- `complete`: reviewed and considered ready for general use.

## Review expectations

Before proposing a change, check that it:

- supports a real delivery need
- is clear enough for a multidisciplinary team
- avoids unnecessary jargon
- can be adapted across departments and services
- does not imply that there is a single mandatory GDS format

## Referencing public examples and guidance

Templates should credit public guidance, examples and source material when those sources influenced the template shape.

Use a `Reference examples and sources` section for phase templates. Include:

- title of the source
- author, team, department or organisation where available
- link to the source
- licence or reuse note where clear
- a short explanation of why the source is relevant

Prefer primary public sources such as GOV.UK Service Manual pages, GOV.UK blog posts, public repositories and published assessment or assurance material.

Do not copy large sections of source material. Summarise, link and credit instead.

For GOV.UK and GOV.UK blog content, check the footer or page metadata. Most content is available under the Open Government Licence v3.0 unless otherwise stated, but some images, logos or third-party material may be excluded.

Do not include sensitive, unpublished or internal government material in examples. Worked examples should be fictional unless the source is explicitly public and reusable.

## Worked examples

Worked examples should:

- use realistic but fictional services unless based on clearly public material
- avoid personal data, operational secrets and live case details
- show the expected level of detail for a usable artefact
- match the structure of the related template
- state clearly that they are examples, not mandatory formats
