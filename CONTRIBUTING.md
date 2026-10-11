# Contributing

This repo is Mon Mon’s YouTube Shorts studio: planning, scripts, production notes, publish metadata, and analytics templates—not a deployed app. Contributions are mostly **content and process** improvements.

## What belongs here

- Markdown templates and checklists
- Idea backlog and finished scripts (if you want them versioned)
- Hook libraries and publish packs
- Workflow doc updates (`WORKFLOW.md`)

## What to avoid committing

- API keys, OAuth tokens, or YouTube credentials
- Large raw video/audio/project files (see `.gitignore`)
- Fabricated analytics; use placeholders or real Studio exports only

## File naming

- **Ideas:** `content/ideas/YYYY-MM-slug.md` or add rows in a shared backlog file you create
- **Scripts:** `content/scripts/YYYY-MM-slug.md`
- **Publish packs:** `publish/YYYY-MM-slug-publish.md`
- **Metrics:** `analytics/YYYY-MM-slug-metrics.md`

Use lowercase slugs and dates so files sort chronologically.

## Changing templates

- Edit `*-TEMPLATE.md` files in place when improving the **default** for future Shorts.
- Do not overwrite template files with a single Short’s content; copy templates to new files instead.

## Pull requests

1. Branch from `main` using `cursor/<short-description>-192c` or your team’s convention.
2. One logical change per PR (e.g. “add retention script template”, “update posting checklist”).
3. Keep tone plain and direct in docs.

## Questions

Open a GitHub issue for structural changes (new folders, automation, CI) before large refactors.
