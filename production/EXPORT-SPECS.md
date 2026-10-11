# Shorts export specs — checklist

Run this **once per master file** before upload. Pair with [`PRODUCTION-CHECKLIST.md`](PRODUCTION-CHECKLIST.md) and [`publish/POSTING-SOP.md`](../publish/POSTING-SOP.md). Verify anything marked “platform” against **current YouTube Shorts upload guidance** in Studio or Help—this doc does not replace official specs.

**Master filename:** `YYYY-MM-DD_<script-slug>_master_v1.mp4` (see [`calendar/BATCH-DAY-RUNBOOK.md`](../calendar/BATCH-DAY-RUNBOOK.md)).

---

## Format & geometry

- [ ] **Aspect ratio:** vertical **9:16** (portrait)—no letterboxed 16:9 masters for Shorts feed.
- [ ] **Resolution:** at least **1080×1920** (or higher if source allows); no upscaled soft 720p unless intentional test.
- [ ] **Orientation:** subject upright; rotate before export if recorded sideways.
- [ ] **Codec / container:** **H.264** (or **HEVC** if your toolchain and Studio accept it) in a common container (typically **.mp4**).
- [ ] **Frame rate:** constant frame rate matching camera source (avoid accidental 24 vs 30 mix in one file).

---

## Duration & pacing

- [ ] **Length:** within Shorts limits (scripts in this repo target **under ~60s** unless you intentionally publish longer—confirm current max in Studio).
- [ ] **Hook:** meaningful visual or spoken hook in **first 1–3 seconds** (no long logo stings).
- [ ] **End:** CTA / on-screen text holds long enough to read on a phone once at normal speed.
- [ ] **Dead air:** trimmed; jump cuts OK if on-brand ([`channel/BRAND-VOICE.md`](../channel/BRAND-VOICE.md)).

---

## Text, captions & safe zones

- [ ] **Captions:** burned in **or** accurate Shorts captions uploaded—viewer can follow without sound.
- [ ] **Safe zones:** primary text in **middle ~60%** of frame; avoid top/bottom UI overlap (see [`THUMBNAIL-TEXT.md`](THUMBNAIL-TEXT.md)).
- [ ] **Legibility:** high contrast; short lines (3–5 words per card where possible).
- [ ] **First frame:** readable at thumbnail scale (often same as hook text).
- [ ] **Compliance lines:** disclaimers visible when script requires (`NOT LEGAL ADVICE`, `#ad`, product disclosure, **LAB FOOTAGE**).

---

## Audio

- [ ] **Clarity:** voice intelligible on phone speaker; no clipping or heavy room echo.
- [ ] **Levels:** no sudden volume jumps between cuts; music ducking under voice if music used.
- [ ] **Loudness:** spot-check against **current YouTube / platform loudness recommendations** (use your NLE meter or a loudness tool—do not guess numeric targets here).
- [ ] **Music / SFX:** licensed or platform-safe; rights documented if queried.
- [ ] **Comment keywords:** spoken clearly at least once when publish pack uses keyword CTA.

---

## Visual & content integrity

- [ ] **Exposure / color:** consistent across cuts in one Short; no accidental filter shift mid-video.
- [ ] **No fake metrics:** blurred or placeholder analytics only ([`B-ROLL-SHOT-BANK.md`](B-ROLL-SHOT-BANK.md)).
- [ ] **AI / altered footage:** labeled in video or description when your policy requires ([`AI-PIPELINE.md`](AI-PIPELINE.md), Creator Shelf consent script).
- [ ] **Title / thumbnail promise:** matches [`publish/FILM-WEEK-POST-PACK.md`](../publish/FILM-WEEK-POST-PACK.md) or your publish pack—no bait-and-switch.

---

## File hygiene & backup

- [ ] **Naming:** lowercase kebab-case slug matches repo script filename.
- [ ] **Version:** bump `_v2` only when **content** changes, not every re-export attempt.
- [ ] **Storage:** master lives **outside git**; path noted in publish pack internal notes.
- [ ] **Spot watch:** full play on a **phone** once before Studio upload.

---

## Sign-off

| Field | Value |
| --- | --- |
| **Script slug** | |
| **Export path** | |
| **Path used (A / B / C)** | [`AI-PIPELINE.md`](AI-PIPELINE.md) |
| **Ready for POSTING-SOP** | ☐ |
