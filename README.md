# YouTube Shorts Studio

Planning, scripting, and production workspace for **Mon Mon**’s YouTube Shorts—built around a repeatable pipeline and **monetization-aware** choices (ad-friendly topics, clear CTAs, disclosures, and metrics you can act on).

This repo is **docs and templates first**: no fake stats, no credentials. Add real scripts and publish packs as you go; keep heavy media out of git (see `.gitignore`).

## What this repo is for

| Area | Purpose |
| --- | --- |
| **Content** | Ideas, scripts, and reusable hooks |
| **Production** | Checklists and shot lists so shoots stay consistent |
| **Publish** | Titles, descriptions, hashtags, and posting checks |
| **Analytics** | Simple per-Short metric notes from YouTube Studio |

## Folder guide

```text
youtube-shorts-studio/
├── content/
│   ├── ideas/      Idea backlog and IDEA-TEMPLATE
│   ├── scripts/    Shorts scripts (hook, body, CTA, length)
│   └── hooks/      Reusable opening lines
├── production/     Production checklist + shot list templates
├── publish/        Publish pack + posting checklist
├── analytics/      Metrics tracking template (real data only)
├── WORKFLOW.md     Idea → script → produce → publish → review
└── CONTRIBUTING.md Naming, commits, what not to commit
```

### `content/ideas/`

Capture angles before you script. Use `IDEA-TEMPLATE.md` and prioritize what fits your niche and monetization goals.

### `content/scripts/`

One Short per script file. `SCRIPT-TEMPLATE.md` enforces hook, body, CTA, and a length target (typical Shorts: under 60 seconds).

### `content/hooks/`

Store lines that worked or you want to test again. Tie hooks to topics—not generic filler.

### `production/`

`PRODUCTION-CHECKLIST.md` and `SHOT-LIST-TEMPLATE.md` for vertical video, captions, and export readiness.

### `publish/`

`PUBLISH-PACK-TEMPLATE.md` for metadata; `POSTING-CHECKLIST.md` before you hit publish.

### `analytics/`

`METRICS-TEMPLATE.md` for views, retention, CTR, and revenue notes—**fill from YouTube Studio only**.

## Quick start

1. Read **`WORKFLOW.md`** once for the full pipeline.
2. Copy **`content/ideas/IDEA-TEMPLATE.md`** → pick your next Short.
3. Copy **`content/scripts/SCRIPT-TEMPLATE.md`** → write the script.
4. Copy production and publish templates when you shoot and upload.
5. After data exists, copy **`analytics/METRICS-TEMPLATE.md`** and note what to repeat or fix.

## Next steps

- [ ] Add your channel niche and content pillars in a new doc (e.g. `content/ideas/PILLARS.md`) when ready.
- [ ] Copy an idea template and script your first Short.
- [ ] After publish, log metrics in `analytics/` and update `content/hooks/` with what worked.
- [ ] Optional later: git LFS or external drive for exports; automation only if a tiny script clearly saves time.

## License & repo

Public scaffold for **MonMonMars/youtube-shorts-studio**. Adjust templates as your format evolves.
