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
├── channel/        Channel setup checklist + brand voice
├── production/     AI pipeline, export specs, checklists, B-roll bank
├── publish/        Publish pack + posting SOP + film-week packs
├── analytics/      Metrics tracking template (real data only)
├── ROADMAP.md      What’s shipped, film-ready, next phases
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

`AI-PIPELINE.md` (film yourself / AI restyle / faceless), `SOURCE-CLIP-BRIEF.md`, `EXPORT-SPECS.md`, plus `PRODUCTION-CHECKLIST.md`, `THUMBNAIL-TEXT.md`, and `B-ROLL-SHOT-BANK.md` for vertical Shorts.

### `channel/`

`SETUP-CHECKLIST.md` for YouTube Shorts channel setup; `BRAND-VOICE.md` for tone and compliance language.

### `publish/`

`PUBLISH-PACK-TEMPLATE.md` for metadata; `POSTING-SOP.md` for the full upload flow; `FILM-WEEK-POST-PACK.md` when posting this week’s batch.

### `analytics/`

`METRICS-TEMPLATE.md` for views, retention, CTR, and revenue notes—**fill from YouTube Studio only**.

## Quick start

1. Read **`WORKFLOW.md`** once for the full pipeline.
2. Skim **`content/ideas/PILLARS.md`** and pick ideas from **`content/ideas/BACKLOG-SEED.md`**.
3. Script from **`content/scripts/SCRIPT-TEMPLATE.md`** or pick a finished script in `content/scripts/` (full backlog + product lanes).
4. Copy production and publish templates when you shoot and upload.
5. Follow **`calendar/30-DAY-PLAN.md`** (month 1) and **`calendar/60-DAY-PLAN.md`** (month 2) for batch, post, and review days; use **`calendar/BATCH-DAY-RUNBOOK.md`** on film days.
6. After data exists, copy **`analytics/METRICS-TEMPLATE.md`** and run **`analytics/WEEKLY-REVIEW.md`**—no invented numbers.

## What's next / Active packs

### Monetization content pack (merged)

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
| [`calendar/30-DAY-PLAN.md`](calendar/30-DAY-PLAN.md) | Month 1 — 30-day batch / post / review (weeks 1–4) |
| [`calendar/60-DAY-PLAN.md`](calendar/60-DAY-PLAN.md) | Month 2 — days 31–60 (weeks 5–6 film/publish kits) |

### Product & publish content pack

| Doc | What it is |
| --- | --- |
| [`content/ideas/PRODUCT-SERIES.md`](content/ideas/PRODUCT-SERIES.md) | Five founder series lanes (Spark, book, Companion, Robot Face, AI Video)—6 episodes each |
| [`content/scripts/affiliate-without-cringe.md`](content/scripts/affiliate-without-cringe.md) | Script: backlog #4 — affiliate without cringe |
| [`content/scripts/hook-that-pays-rent.md`](content/scripts/hook-that-pays-rent.md) | Script: backlog #6 — retention hook structure |
| [`content/scripts/shorts-ad-policy-plain-english.md`](content/scripts/shorts-ad-policy-plain-english.md) | Script: backlog #11 — ad policy plain English |
| [`content/scripts/spark-lab-why-another-dating-app.md`](content/scripts/spark-lab-why-another-dating-app.md) | Script: Spark Lab pt 1 — build in public |
| [`content/scripts/one-insight-one-page-chapter-test.md`](content/scripts/one-insight-one-page-chapter-test.md) | Script: psychology book — 30s chapter test |
| [`content/scripts/companion-build-not-assistant.md`](content/scripts/companion-build-not-assistant.md) | Script: Companion Build pt 1 — companion vs assistant |
| [`publish/TITLE-PACK.md`](publish/TITLE-PACK.md) | 40 title variants + on-screen lines (curiosity, mistake, list, challenge) |
| [`publish/DESCRIPTION-CTA.md`](publish/DESCRIPTION-CTA.md) | Reusable descriptions + pinned-comment CTAs (follow, link, comment, series) |
| [`production/B-ROLL-SHOT-BANK.md`](production/B-ROLL-SHOT-BANK.md) | Founder / app / book / robot placeholder B-roll shot IDs |

### Script & ops content pack

| Doc | What it is |
| --- | --- |
| [`content/scripts/batch-day-in-60-seconds.md`](content/scripts/batch-day-in-60-seconds.md) | Script: backlog #5 — batch filming order |
| [`content/scripts/map-one-short-to-one-offer.md`](content/scripts/map-one-short-to-one-offer.md) | Script: backlog #7 — hook → value → offer map |
| [`content/scripts/mistake-that-demonetized-my-draft.md`](content/scripts/mistake-that-demonetized-my-draft.md) | Script: backlog #8 — hypothetical policy rewrite |
| [`content/scripts/five-hooks-you-can-film-today.md`](content/scripts/five-hooks-you-can-film-today.md) | Script: backlog #9 — five hooks from STARTER-HOOKS |
| [`content/scripts/why-i-dont-show-earnings.md`](content/scripts/why-i-dont-show-earnings.md) | Script: backlog #10 — process proof over income flex |
| [`content/scripts/comment-keyword-cta-test.md`](content/scripts/comment-keyword-cta-test.md) | Script: backlog #12 — keyword fulfillment loop |
| [`content/scripts/robot-face-different-emoji-set.md`](content/scripts/robot-face-different-emoji-set.md) | Script: Robot Face R&D pt 1 — B2B expressions |
| [`content/scripts/robot-face-unitree-neck-constraints.md`](content/scripts/robot-face-unitree-neck-constraints.md) | Script: Robot Face R&D pt 2 — hardware constraints |
| [`content/scripts/creator-shelf-netflix-fantasy-vs-reality.md`](content/scripts/creator-shelf-netflix-fantasy-vs-reality.md) | Script: Creator Shelf pt 1 — platform economics |
| [`content/scripts/creator-shelf-three-monetization-paths.md`](content/scripts/creator-shelf-three-monetization-paths.md) | Script: Creator Shelf pt 2 — subs / rev-share / tips (design) |
| [`analytics/WEEKLY-REVIEW.md`](analytics/WEEKLY-REVIEW.md) | Weekly checklist: Studio metrics → pillars → next week’s shoot list |
| [`calendar/BATCH-DAY-RUNBOOK.md`](calendar/BATCH-DAY-RUNBOOK.md) | Batch day prep, light/audio, B-roll shoot order, export naming |

### Series expansion pack

| Doc | What it is |
| --- | --- |
| [`content/scripts/INDEX.md`](content/scripts/INDEX.md) | Full script inventory (42 Shorts)—tag, length, CTA type, blank film status |
| [`calendar/FILM-THIS-WEEK.md`](calendar/FILM-THIS-WEEK.md) | Week 1 — 7-Short shoot queue (monetization + founder + series pt 2) |
| [`calendar/FILM-WEEK-2.md`](calendar/FILM-WEEK-2.md) | Week 2 — 7-Short queue (backlog + Spark/Companion/Robot pt 3 + Creator Shelf + batch ops) |
| [`calendar/FILM-WEEK-3.md`](calendar/FILM-WEEK-3.md) | Week 3 — backlog gates/hooks + series pt 4 (four lanes) |
| [`calendar/FILM-WEEK-4.md`](calendar/FILM-WEEK-4.md) | Week 4 — keyword CTA test + Spark/Companion/Robot pts 5–6 finales |
| [`calendar/FILM-WEEK-5.md`](calendar/FILM-WEEK-5.md) | Week 5 — Creator Shelf 1–2, series pt 1 catch-up, One Insight pt 1 |
| [`calendar/FILM-WEEK-6.md`](calendar/FILM-WEEK-6.md) | Week 6 — One Insight pts 2–6 + Creator Shelf pts 5–6 (42-script queue complete) |
| [`content/scripts/spark-lab-ep02-one-screen-three-redesigns.md`](content/scripts/spark-lab-ep02-one-screen-three-redesigns.md) … [`spark-lab-ep06-beta-invite-who-its-for.md`](content/scripts/spark-lab-ep06-beta-invite-who-its-for.md) | Spark Lab pts 2–6 (pt 1 already in repo) |
| [`content/scripts/one-insight-ep01-idea-that-wouldnt-fit-tweet.md`](content/scripts/one-insight-ep01-idea-that-wouldnt-fit-tweet.md) … [`one-insight-ep06-who-this-book-is-for.md`](content/scripts/one-insight-ep06-who-this-book-is-for.md) | One Insight pts 1 & 3–6 (pt 2 = `one-insight-one-page-chapter-test.md`) |
| [`content/scripts/companion-build-ep02-avatar-face-rule.md`](content/scripts/companion-build-ep02-avatar-face-rule.md) … [`companion-build-ep06-testflight-small-group.md`](content/scripts/companion-build-ep06-testflight-small-group.md) | Companion Build pts 2–6 (pt 1 already in repo) |
| [`content/scripts/robot-face-ep03-tesla-vibes-without-copying.md`](content/scripts/robot-face-ep03-tesla-vibes-without-copying.md) … [`robot-face-ep06-honest-icp-who-buys.md`](content/scripts/robot-face-ep06-honest-icp-who-buys.md) | Robot Face R&D pts 3–6 (pts 1–2 already in repo) |
| [`content/scripts/creator-shelf-ep03-ai-video-consent-workflow.md`](content/scripts/creator-shelf-ep03-ai-video-consent-workflow.md) … [`creator-shelf-ep06-founder-ask-pay-creators.md`](content/scripts/creator-shelf-ep06-founder-ask-pay-creators.md) | Creator Shelf pts 3–6 (pts 1–2 already in repo) |

All five [`PRODUCT-SERIES.md`](content/ideas/PRODUCT-SERIES.md) lanes now have **6 scripted episodes each** (30 series scripts + 12 backlog monetization scripts).

### Channel ops & post-week kit

| Doc | What it is |
| --- | --- |
| [`ROADMAP.md`](ROADMAP.md) | Packs 1–6 shipped, film-ready queue, suggested next phases |
| [`channel/SETUP-CHECKLIST.md`](channel/SETUP-CHECKLIST.md) | YouTube channel setup for Shorts (profile, playlists, Community if available) |
| [`channel/BRAND-VOICE.md`](channel/BRAND-VOICE.md) | Voice guide—building in public + monetization education, no fake earnings flex |
| [`publish/POSTING-SOP.md`](publish/POSTING-SOP.md) | Step-by-step post flow per Short (metadata, pin, first-hour engagement) |
| [`publish/FILM-WEEK-POST-PACK.md`](publish/FILM-WEEK-POST-PACK.md) | Week 1 — copy-paste titles, descriptions, pins, hashtags |
| [`publish/FILM-WEEK-2-POST-PACK.md`](publish/FILM-WEEK-2-POST-PACK.md) | Week 2 — same shape for [`FILM-WEEK-2.md`](calendar/FILM-WEEK-2.md) |
| [`publish/FILM-WEEK-3-POST-PACK.md`](publish/FILM-WEEK-3-POST-PACK.md) … [`FILM-WEEK-6-POST-PACK.md`](publish/FILM-WEEK-6-POST-PACK.md) | Weeks 3–6 publish metadata |
| [`production/THUMBNAIL-TEXT.md`](production/THUMBNAIL-TEXT.md) | Week 1 on-screen / hook text (9:16 safe zones) |
| [`production/THUMBNAIL-TEXT-WEEK-2.md`](production/THUMBNAIL-TEXT-WEEK-2.md) … **`WEEK-6`** | Weeks 2–6 on-screen text |
| [`production/SOURCE-CLIP-BRIEF-WEEK-2.md`](production/SOURCE-CLIP-BRIEF-WEEK-2.md) … **`WEEK-6`** | Weeks 2–6 capture briefs for edit / AI source |

### AI production pipeline pack

| Doc | What it is |
| --- | --- |
| [`production/AI-PIPELINE.md`](production/AI-PIPELINE.md) | Three paths: batch film (A), Higgsfield Shorts Studio restyle (B), faceless B-roll (C) → POSTING-SOP |
| [`production/SOURCE-CLIP-BRIEF.md`](production/SOURCE-CLIP-BRIEF.md) | Per–film-week Short: duration, framing, and must-have shots for edit or AI source |
| [`production/EXPORT-SPECS.md`](production/EXPORT-SPECS.md) | Pre-upload checklist: 9:16, resolution, length, captions, audio (verify platform guidance) |

## Next steps

- [ ] Customize pillar names for your niche (see `PILLARS.md`).
- [ ] Pick a production path in [`production/AI-PIPELINE.md`](production/AI-PIPELINE.md); capture using [`production/SOURCE-CLIP-BRIEF.md`](production/SOURCE-CLIP-BRIEF.md).
- [ ] Run [`channel/SETUP-CHECKLIST.md`](channel/SETUP-CHECKLIST.md); film weeks 1–6 per [`30-DAY-PLAN.md`](calendar/30-DAY-PLAN.md) + [`60-DAY-PLAN.md`](calendar/60-DAY-PLAN.md); export with [`production/EXPORT-SPECS.md`](production/EXPORT-SPECS.md); post with the matching `FILM-WEEK*-POST-PACK.md`.
- [ ] Fill real links in `OFFER-MAP.md` when live.
- [ ] After publish, log metrics in `analytics/` and promote winning hooks from `STARTER-HOOKS.md` into `content/hooks/README.md`.
- [ ] Optional later: git LFS or external drive for exports; automation only if a tiny script clearly saves time.

## License & repo

Public scaffold for **MonMonMars/youtube-shorts-studio**. Adjust templates as your format evolves.
