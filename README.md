# tech-demos

Sticky monorepo for weekday X-bookmark tech demos.

Each approved pick lands under `apps/<kebab-slug>/` as a self-contained Bun app (`bun install && bun run dev`). Cloud agents only touch that app folder, open one PR, and must attach at least one screenshot **and** one video of the running app.

## Layout

- `AGENTS.md` — rules for cloud agents
- `skills/project-planning/` — plan before build
- `apps/` — one demo app per pick
- `tracking/seen-bookmarks.json` — bookmarks already proposed or built

## Cloudflare previews

One Pages project for the whole repo (path per `apps/<slug>/`), not one project per app. Needs repo secrets `CLOUDFLARE_API_TOKEN` and `CLOUDFLARE_ACCOUNT_ID`.
