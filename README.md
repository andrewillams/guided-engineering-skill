# Guided Engineering Delivery — Codex Skill

A reusable Codex skill designed for users who know their problem domain but are not experienced software developers.

## What it solves

- vague prompts and difficulty structuring requests;
- jumping into code before requirements are understood;
- repeated rework caused by missing acceptance criteria;
- excessive context/token consumption;
- poor visibility of progress;
- ad-hoc testing;
- risky or poorly documented deployments.

## Suggested installation

For a personal skill usable across repositories, place the folder under:

`$HOME/.agents/skills/guided-engineering-delivery/`

For a repository-scoped skill, place it under:

`<repo>/.agents/skills/guided-engineering-delivery/`

Codex can invoke the skill explicitly with `$guided-engineering-delivery` or match it from the skill description.

## Recommended project structure created during use

```text
docs/
  engineering/
    STATUS.md
    REQUIREMENTS.md
    SOURCES.md
    ANALYSIS.md
    EPIC.md
    TEST_PLAN.md
    DEPLOYMENT.md
```

## Important distinction

- `SKILL.md`: reusable **process/workflow**.
- `AGENTS.md`: **project-specific** architecture, commands, conventions, restrictions and deploy rules.

Start instruction-only. Add scripts later only for deterministic/repetitive operations such as project validation, test orchestration, release packaging or log collection.
