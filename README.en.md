# Product Requirements Discovery Skill

[繁體中文](README.md) · [简体中文](README.zh-CN.md) · **English** · [日本語](README.ja.md)

Turn product ideas, interview notes, or an existing product requirements document (PRD) into requirements a team can review and test. Build a product framework in five layers, then choose from twelve questioning techniques to clarify nine fields for each feature.

## Get started with Codex

1. Extract the package and place the entire `product-requirements-discovery` folder in your Codex skills directory, usually `~/.codex/skills`. If you use a custom location, follow the [installation instructions](USAGE.md#安裝與啟用).
2. In a new chat, select `$product-requirements-discovery` and paste the prompt below. You can also use your own product idea and attach any existing material.

~~~text
$product-requirements-discovery
I want to build a self-service meeting room booking tool for our company. People often book the same room for the same time.
Interview me using the five layers. Build the product framework first, then clarify each feature in scope for this release.
~~~

## What you get

- **Product framework** organized by goals, scenarios, workflow, scope, and acceptance. Each layer captures the findings and evidence from its questioning techniques.
- **Feature list and nine-field feature cards** with stable IDs, workflow steps, and priorities. Each conclusion can be traced back to its source.
- **Acceptance scenarios and open questions** using Given–When–Then to specify preconditions, events, and observable outcomes. Unresolved questions and decisions are recorded for follow-up.
- **Markdown PRD on request** with a consistent structure for the framework, feature specifications, cross-cutting requirements, acceptance criteria, and decision records.

## Package contents

The companion files below are written in Traditional Chinese.

| File | Purpose |
|---|---|
| [User guide](USAGE.md) | Installation, copy-ready prompts, interview steps, and how to check the deliverables. |
| [SKILL.md](SKILL.md) | The skill workflow, interview questions, and completion criteria. |
| [PRD template](assets/prd-template.md) | Fixed sections for a single PRD, nine-field feature cards, acceptance scenarios, and source records. |
| [Twelve questioning techniques](references/question-methods.md) | Find a useful follow-up question for the information missing from a feature card. |
| [Meeting room booking example](references/worked-example.md) | A five-layer framework, feature card, and acceptance scenarios for one product. |
| [Maintenance specification](SPEC.md) and [source notes](SOURCES.md) | When to invoke the skill, what to verify, and where the methods come from. |
