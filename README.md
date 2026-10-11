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
│   ├── ideas/      Pillars, backlog, IDEA-TEMPLATE
│   ├── scripts/    Shorts scripts (hook, body, CTA, length)
│   └── hooks/      Reusable opening lines + starter library
├── monetization/   Playbook and Short → offer map
├── calendar/       Posting cadence plans
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
2. Skim **`content/ideas/PILLARS.md`** and pick ideas from **`content/ideas/BACKLOG-SEED.md`**.
3. Script from **`content/scripts/SCRIPT-TEMPLATE.md`** or start from the three finished scripts in `content/scripts/`.
4. Copy production and publish templates when you shoot and upload.
5. Follow **`calendar/30-DAY-PLAN.md`** for batch, post, and review days.
6. After data exists, copy **`analytics/METRICS-TEMPLATE.md`** and note what to repeat or fix.

## What's next / Active packs

| Doc | What it is |
| --- | --- |
| [`content/ideas/PILLARS.md`](content/ideas/PILLARS.md) | Five monetization-aware content pillars + niche customization note |
| [`content/ideas/BACKLOG-SEED.md`](content/ideas/BACKLOG-SEED.md) | Twelve ready idea cards tied to pillars |
| [`monetization/PLAYBOOK.md`](monetization/PLAYBOOK.md) | Shorts monetization paths, compliance reminders, pillar → path decision tree |
| [`monetization/OFFER-MAP.md`](monetization/OFFER-MAP.md) | Short → offer → CTA → tracking template (placeholders until you publish) |
| [`content/scripts/3-second-monetization-check.md`](content/scripts/3-second-monetization-check.md) | Script: pre-record policy / CTA / disclosure check |
| [`content/scripts/views-but-zero-revenue.md`](content/scripts/views-but-zero-revenue.md) | Script: views vs revenue paths |
| [`content/scripts/one-cta-without-killing-retention.md`](content/scripts/one-cta-without-killing-retention.md) | Script: comment-keyword CTA pattern |
| [`content/hooks/STARTER-HOOKS.md`](content/hooks/STARTER-HOOKS.md) | 30 copy-ready hooks by pattern |
| [`calendar/30-DAY-PLAN.md`](calendar/30-DAY-PLAN.md) | 30-day batch / post / review cadence using the seed ideas |

## Next steps

- [ ] Customize pillar names for your niche (see `PILLARS.md`).
- [ ] Film the top three scripts; fill real links in `OFFER-MAP.md` when live.
- [ ] After publish, log metrics in `analytics/` and promote winning hooks from `STARTER-HOOKS.md` into `content/hooks/README.md`.
- [ ] Optional later: git LFS or external drive for exports; automation only if a tiny script clearly saves time.

## License & repo

Public scaffold for **MonMonMars/youtube-shorts-studio**. Adjust templates as your format evolves.
