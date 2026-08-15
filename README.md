# Forblune OS

Forblune OS is a public note about how I carry useful decisions from one project into the next. It is not a downloadable operating system, a live agent platform, or a finished product.

## Current state

This repository currently contains three documents:

- [`START.md`](./START.md): a short entry point for recording a project
- [`DEVELOPMENT_CYCLE.md`](./DEVELOPMENT_CYCLE.md): the build and review cycle
- [`README.md`](./README.md): scope and working rules

No runtime, database, background agent, or automated approval system is included here. Operational material and private project data live outside this public repository.

## The working loop

```text
Problem
  → evidence
  → smallest useful change
  → verification
  → delivery
  → review
  → reusable note or checklist
```

The point is practical: a project should leave behind something that makes the next similar job easier to execute or easier to verify.

Examples include:

- a reproduction checklist for a responsive bug
- a tested content pattern for Korean and English pages
- a release checklist for desktop, tablet, and mobile
- a short postmortem that separates evidence from assumptions

## Working rules

1. Reuse a proven asset before creating another one.
2. Record direct evidence separately from owner reports and assumptions.
3. Keep the first change small enough to review and undo.
4. Treat build, browser QA, deployment, and business outcome as different states.
5. Do not put credentials, customer data, or private operational notes in this public repository.
6. A tool can assist with a decision; responsibility for the decision stays with a person.

## Why this is public

The public version shows the method without exposing the private Company OS, client material, or automation details. It is useful as a reference for collaborators who want to understand how Forblune scopes, verifies, and hands off work.

For customer-facing work, see [portfolio.forblune.com](https://portfolio.forblune.com) and [webcare.forblune.com](https://webcare.forblune.com).
