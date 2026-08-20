# Project-specific Codex instructions

This file is an example. Copy/adapt it to the repository root as `AGENTS.md`.

## Project overview
- Purpose: <one paragraph>
- Main users: <users>
- Critical constraints: <constraints>

## Stack
- Language/runtime:
- Framework:
- Database:
- Package manager/build tool:
- Deployment target:

## Repository map
- `<path>` — <purpose>

## Working agreements
- Prefer the smallest change that satisfies the approved requirements.
- Do not change public interfaces without documenting compatibility impact.
- Do not introduce production dependencies without explaining why they are needed.
- Never commit secrets or real credentials.
- Keep unrelated refactoring out of feature/bug-fix changes.

## Commands
- Install/setup: `<command>`
- Lint/static checks: `<command>`
- Unit tests: `<command>`
- Integration tests: `<command>`
- Build: `<command>`
- Local run: `<command>`

## Testing rules
- Run: <minimum checks after code changes>
- Critical flows that always need regression coverage:
  - 

## Deployment rules
- Development environment:
- Homologation/staging:
- Production:
- Deploy command/process:
- Smoke test:
- Rollback process:

## Domain rules / invariants
Document rules that code must never violate.
- 

## Code Review Rules
- Flag behavior changes that are not represented in requirements/acceptance criteria.
- Flag new dependencies without justification.
- Flag missing regression tests for modified critical behavior.
