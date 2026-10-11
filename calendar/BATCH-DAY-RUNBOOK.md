# Batch filming runbook

One session to capture **multiple Shorts** with consistent light, audio, and framing. Pair with [`production/B-ROLL-SHOT-BANK.md`](../production/B-ROLL-SHOT-BANK.md) and [`production/PRODUCTION-CHECKLIST.md`](../production/PRODUCTION-CHECKLIST.md). Target: hooks batch → bodies batch → CTAs batch (see [`batch-day-in-60-seconds.md`](../content/scripts/batch-day-in-60-seconds.md)).

---

## Prep (day before or morning of)

### Scripts & schedule

- [ ] Pick **3–6 scripts** from `content/scripts/`—same pillar stacks back-to-back when possible.
- [ ] Print or tablet: hook line only on first page for hook batch.
- [ ] Note shot IDs from B-roll bank per script (column in your shot list).
- [ ] Charge phone/camera batteries; clear storage for **vertical** clips.

### Space & gear

- [ ] One primary setup location—avoid moving lights mid-batch.
- [ ] Tripod at eye level; frame headroom for on-screen text safe zone (top/bottom 10%).
- [ ] Teleprompter optional—bullet beats enough for Shorts.

---

## Lighting checklist

| Check | Pass? |
| --- | --- |
| Key light ~45° to face (window or softbox)—no hard nose shadow | |
| Fill or bounce so both eyes readable | |
| No mixed color temps (green office LEDs + warm window)—pick one dominant | |
| Background separation (subject brighter than back wall) | |
| No flicker on LED panels if shooting B-roll (RB-01) | |
| Test clip 10s—scrub timeline for exposure pump (auto ISO off if needed) | |

**Founder look:** consistent across the week matters more than cinematic—match last batch if doing series Parts.

---

## Audio checklist

| Check | Pass? |
| --- | --- |
| Mic **6–8 in** from mouth (lav or shotgun)—same distance all day | |
| Room tone 5s recorded for emergency noise reduction | |
| Clap or hand snap at start of each take for sync if separate audio | |
| Fans, AC, fridge off during takes | |
| Phone on silent; notifications off on record device | |
| Playback headphones: listen for rustle, plosives, echo | |

Re-record hooks only if audio fails—don’t accept “we’ll fix in post” on plosives for spoken Shorts.

---

## Shoot order (recommended)

Film in this order to minimize setup changes. Log shot IDs as you go.

### Block A — Hooks (all scripts)

1. **DK-02** — enter frame, sit, deliver hook (optional pattern interrupt).
2. Face cam: read **hook only** for each script—3 takes max each, pick in edit.
3. **PH-01** phone wake / cold opens if any script needs them.

### Block B — B-roll & screen (shared)

Shoot reusable bank clips **once**, tag for multiple edits:

| Order | Shot IDs | Use for |
| --- | --- | --- |
| 1 | DK-06, DK-03 | Offer map, batch, hooks |
| 2 | YT-02, YT-04, YT-05 | Monetization literacy scripts |
| 3 | DK-01, DK-05, DK-07 | Book / insight |
| 4 | PH-02, PH-03, PH-07 | Spark / Companion |
| 5 | RB-01, RB-04, RB-05 | Robot Face lane |
| 6 | PL-01, PL-02, PL-03 | Creator Shelf lane |
| 7 | CD-01, CD-02 | Build-in-public inserts |

Label **lab / placeholder** in voice or slate if hardware or UI is WIP.

### Block C — Bodies (per script)

- Face cam beats 1–3; jump-cut pacing—pause 1s between sentences for edit room.
- Insert B-roll from Block B where script notes say.

### Block D — CTAs (all scripts)

- Same frame as hooks; shorter energy.
- Comment keywords: say keyword **clearly** twice for keyword-CTA scripts.
- **DK-04** laptop close optional punctuation on last script of day.

### Block E — Safety & pick-ups

- [ ] On-screen disclaimers filmed if needed (**NOT LEGAL ADVICE**, **#ad**, **LAB FOOTAGE**).
- [ ] Any blown line from Block C—CTA block is not the time to redo bodies; schedule 10 min pick-up.

---

## During session

- Slate verbally: `Script slug — hook take 2` for search in camera roll.
- Drink water between blocks—CTA block last when voice still clear.
- If light shifts (sunset), pause and re-white balance before Block C.

---

## Export naming

Use consistent names so publish packs map 1:1 to files on disk / drive:

```text
YYYY-MM-DD_<script-slug>_hook_v1.mp4
YYYY-MM-DD_<script-slug>_body_v1.mp4
YYYY-MM-DD_<script-slug>_cta_v1.mp4
YYYY-MM-DD_<script-slug>_master_v1.mp4
```

| Part | `<script-slug>` example |
| --- | --- |
| Full master | `2026-10-11_batch-day-in-60-seconds_master_v1.mp4` |
| Hook-only reuse | `2026-10-11_hook-that-pays-rent_hook_v2.mp4` |

**Rules:**

- Lowercase kebab-case matching repo script filename (without `.md`).
- Increment `_v2` only when content changes—not every export attempt.
- Keep heavy exports **out of git** (see root `.gitignore`); store path in publish pack.

---

## After batch

- [ ] Run [`PRODUCTION-CHECKLIST.md`](../production/PRODUCTION-CHECKLIST.md) per master export (captions, safe zone, loudness spot-check).
- [ ] Queue publish dates in [`30-DAY-PLAN.md`](30-DAY-PLAN.md).
- [ ] Start empty [`METRICS-TEMPLATE.md`](../analytics/METRICS-TEMPLATE.md) stubs with titles + planned publish dates.

---

## Related

- [`production/SHOT-LIST-TEMPLATE.md`](../production/SHOT-LIST-TEMPLATE.md) — per-day pick list
- [`analytics/WEEKLY-REVIEW.md`](../analytics/WEEKLY-REVIEW.md) — after posts go live
