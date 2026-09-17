# Agent rules — tech-demos

## Scope

- This is a **sticky monorepo**. Never create a new GitHub repository for a demo.
- Only add or update files under `apps/<kebab-slug>/` for the current pick (plus a plan at `apps/<kebab-slug>/PLAN.md` if missing).
- Do not modify other apps, root tooling, or `tracking/` unless the task explicitly says so.

## Stack

- **Bun** for install and scripts (`bun install`, `bun run dev`).
- Each app under `apps/<slug>/` must be self-contained: its own `package.json`, README, and `dev` script.
- Prefer a small single-user MVP demo over a production system.

## Planning

- Before building, follow `skills/project-planning/` and write/update `apps/<kebab-slug>/PLAN.md`.
- Keep scope tight: one clear demo angle.

## Pull requests

- Open **one** PR for the pick.
- Attach **both**:
  - at least one **screenshot** of the running app
  - at least one **video** of the running app
- These validation artifacts are required, not optional.

## Model

- Prefer **claude-fable-5 (Fable 5)** for initial prototypes unless the owner asks otherwise.
