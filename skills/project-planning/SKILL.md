---
name: project-planning
description: >-
  Use before building a tech demo under apps/<slug>/. Write a short PLAN.md,
  then implement only that scoped MVP.
---

# Project planning (tech demos)

## When

Before implementing a new `apps/<kebab-slug>/` demo (or a major expansion of one).

## Steps

1. Restate the approved tech and demo angle in one paragraph.
2. List MVP acceptance criteria (3–7 bullets). Cut anything that is not needed to feel the tech.
3. Sketch folder layout under `apps/<kebab-slug>/` (entry, UI, any API stubs).
4. Note run commands: `bun install` and `bun run dev` must work from that folder.
5. Write `apps/<kebab-slug>/PLAN.md` with the above, then implement only what the plan covers.
6. Before opening the PR: capture at least one screenshot and one video of the running app; attach both to the PR.

## Done when

- PLAN.md exists and matches what was built
- App runs with Bun from `apps/<kebab-slug>/`
- PR includes screenshot + video artifacts
