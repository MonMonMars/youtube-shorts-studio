# AI-assisted production pipeline

How to turn [`calendar/FILM-THIS-WEEK.md`](../calendar/FILM-THIS-WEEK.md) scripts into finished Shorts **without guessing** which path to use. Pick **one primary path per Short**; you can reuse the same source capture across paths when it saves time.

**Always finish on:** [`EXPORT-SPECS.md`](EXPORT-SPECS.md) → [`PRODUCTION-CHECKLIST.md`](PRODUCTION-CHECKLIST.md) → [`publish/POSTING-SOP.md`](../publish/POSTING-SOP.md) with copy from [`publish/FILM-WEEK-POST-PACK.md`](../publish/FILM-WEEK-POST-PACK.md).

**Consent & labeling:** If footage is altered by AI in a way viewers should know about, follow your channel standards and scripts like [`content/scripts/creator-shelf-ep03-ai-video-consent-workflow.md`](../content/scripts/creator-shelf-ep03-ai-video-consent-workflow.md). Label in Studio when policy or brand voice requires it ([`channel/BRAND-VOICE.md`](../channel/BRAND-VOICE.md)).

---

## Choose your path

| Path | Best when | Primary docs |
| --- | --- | --- |
| **A — Film yourself** | You on camera or clear screen record; fastest trust for founder/monetization lanes | [`calendar/BATCH-DAY-RUNBOOK.md`](../calendar/BATCH-DAY-RUNBOOK.md), [`calendar/FILM-THIS-WEEK.md`](../calendar/FILM-THIS-WEEK.md) |
| **B — AI restyle** | You have **4–120s** of usable source video and want a stylized cut via Higgsfield Shorts Studio (**paid credits**) | This doc § B, [`SOURCE-CLIP-BRIEF.md`](SOURCE-CLIP-BRIEF.md), [`EXPORT-SPECS.md`](EXPORT-SPECS.md) |
| **C — Faceless / motion** | No talking-head day; text-led story with stock/B-roll | [`THUMBNAIL-TEXT.md`](THUMBNAIL-TEXT.md), [`B-ROLL-SHOT-BANK.md`](B-ROLL-SHOT-BANK.md), voiceover optional |

You do **not** need all three for one Short. Path A is the default for film week unless you explicitly choose B or C.

---

## Path A — Film yourself (human on camera / screen record)

Standard batch flow—no AI restyle required.

### Before the session

1. Queue scripts from [`calendar/FILM-THIS-WEEK.md`](../calendar/FILM-THIS-WEEK.md) (or your own pick list).
2. Per script: note shot bank IDs in the script table; optional detail in [`SOURCE-CLIP-BRIEF.md`](SOURCE-CLIP-BRIEF.md).
3. Copy [`production/SHOT-LIST-TEMPLATE.md`](SHOT-LIST-TEMPLATE.md) for the day.
4. On-screen lines: [`production/THUMBNAIL-TEXT.md`](THUMBNAIL-TEXT.md).

### During the session

Follow [`calendar/BATCH-DAY-RUNBOOK.md`](../calendar/BATCH-DAY-RUNBOOK.md):

- **Block A** — hooks (face cam, vertical 9:16).
- **Block B** — shared B-roll from [`B-ROLL-SHOT-BANK.md`](B-ROLL-SHOT-BANK.md).
- **Block C** — bodies per script.
- **Block D** — CTAs (say comment keywords clearly when the script uses them).
- **Block E** — disclaimers (`NOT LEGAL ADVICE`, `#ad`, `LAB FOOTAGE` as needed).

Slate takes verbally (`script-slug — hook take 2`) for faster edit search.

### Edit → export → post

1. Assemble in your NLE: hook in first 1–3s, captions, safe zones per [`THUMBNAIL-TEXT.md`](THUMBNAIL-TEXT.md).
2. Export master using naming in BATCH-DAY-RUNBOOK (`YYYY-MM-DD_<script-slug>_master_v1.mp4`).
3. Run [`EXPORT-SPECS.md`](EXPORT-SPECS.md) + [`PRODUCTION-CHECKLIST.md`](PRODUCTION-CHECKLIST.md).
4. Upload via [`publish/POSTING-SOP.md`](../publish/POSTING-SOP.md).

**Optional:** Capture a **clean 4–120s source clip** (stable framing, minimal jump cuts) while filming Path A if you might try Path B later—see [`SOURCE-CLIP-BRIEF.md`](SOURCE-CLIP-BRIEF.md).

---

## Path B — AI restyle (Higgsfield Shorts Studio)

High-level workflow only. **Confirm current Higgsfield pricing and credit costs before running**—this repo does not track live prices or API details.

### What Shorts Studio expects (product constraints)

- A **source video** roughly **4–120 seconds** (one continuous take or a simple assembled clip—not a finished Short with heavy graphics).
- A **style preset** you choose inside Shorts Studio (visual treatment / pacing template—pick what matches the script lane, not generic “viral” noise).
- **Paid credits** per run; treat each generation as a budgeted experiment, not a default for every Short.

### Workflow (capture → publish)

| Step | What you do | Repo pointers |
| --- | --- | --- |
| **1. Capture / source** | Record or export source that matches the script brief: face + audio, or screen + voice, stable exposure, no fake metrics on screen | [`SOURCE-CLIP-BRIEF.md`](SOURCE-CLIP-BRIEF.md), [`B-ROLL-SHOT-BANK.md`](B-ROLL-SHOT-BANK.md) |
| **2. Upload** | In Higgsfield Shorts Studio, upload the source file; stay within the product’s duration limits | — |
| **3. Pick preset** | Choose a preset that fits **tone** (founder desk, product UI, policy/education)—preview if the product offers it | [`channel/BRAND-VOICE.md`](../channel/BRAND-VOICE.md) |
| **4. Review clips** | Watch full outputs; reject takes with wrong lip sync, illegible text, or off-brand motion. **Do not** publish AI output that contradicts the script promise | Script file in `content/scripts/` |
| **5. Export master** | Export the chosen vertical clip; store outside git | [`EXPORT-SPECS.md`](EXPORT-SPECS.md) |
| **6. Finish in edit (if needed)** | Add or fix **captions**, on-screen hook text from [`THUMBNAIL-TEXT.md`](THUMBNAIL-TEXT.md), compliance cards, CTA readability | [`PRODUCTION-CHECKLIST.md`](PRODUCTION-CHECKLIST.md) |
| **7. Post** | Same as Path A: [`publish/POSTING-SOP.md`](../publish/POSTING-SOP.md) + film-week pack | [`publish/FILM-WEEK-POST-PACK.md`](../publish/FILM-WEEK-POST-PACK.md) |

### When Path B is worth it

- You want a **stylized look** without learning a new motion template from scratch.
- You already have **strong A-roll** (you on camera or clean screen record) and need variation for tests—not a substitute for missing script content.

### When to skip Path B

- No source clip yet → film Path A first (or use Path C with voiceover).
- Script requires **precise UI**, **whiteboard diagrams**, or **keyword CTAs** spoken on camera—verify the restyle didn’t mangle words; re-record or caption-fix before post.
- Budget unclear → **confirm current Higgsfield pricing before running**; use Path A or C instead.

---

## Path C — Faceless / motion (text + stock / B-roll)

For Shorts where the story is **text-led** or **B-roll-led**, with optional voiceover (your voice or TTS—only if on-brand and disclosed when required).

### Build order

1. **Script & timing** — Read [`content/scripts/…`](../content/scripts/) aloud; mark beat lengths (~3–8s per beat for literacy Shorts).
2. **On-screen text** — Pull lines from [`THUMBNAIL-TEXT.md`](THUMBNAIL-TEXT.md); one idea per card; middle 60% safe zone.
3. **Visuals** — Pull clips by ID from [`B-ROLL-SHOT-BANK.md`](B-ROLL-SHOT-BANK.md) (desk, Studio blur, phone UI, Figma blur, etc.). Use licensed stock only when bank shots aren’t enough—no fake analytics.
4. **Audio** — Voiceover recorded like BATCH-DAY audio checklist, or music-only if script allows (check music rights).
5. **Edit** — Hook text in first 1–3s; jump cuts on beats; end hold for CTA line.
6. **Export & post** — [`EXPORT-SPECS.md`](EXPORT-SPECS.md) → [`POSTING-SOP.md`](../publish/POSTING-SOP.md).

Path C fits monetization “explainer” Shorts when you’re not camera-ready; product lanes (Spark / Companion) still benefit from **real UI or Figma** inserts from the shot bank rather than generic stock.

---

## Decision flow (quick)

```text
Have a finished script from film week?
  ├─ Will you be on camera or screen-record this week?
  │    YES → Path A (default). Optional: save 4–120s source for Path B later.
  │    NO  → Path C (THUMBNAIL-TEXT + B-ROLL-SHOT-BANK)
  └─ Already have 4–120s source + budget for Shorts Studio?
       YES → Path B after SOURCE-CLIP-BRIEF check → review clips hard → EXPORT-SPECS → POSTING-SOP
       NO  → Path A or C
```

---

## Related

| Doc | Role |
| --- | --- |
| [`SOURCE-CLIP-BRIEF.md`](SOURCE-CLIP-BRIEF.md) | Per–film-week Short: what to capture for edit or AI restyle |
| [`EXPORT-SPECS.md`](EXPORT-SPECS.md) | Pre-upload technical checklist |
| [`WORKFLOW.md`](../WORKFLOW.md) | Idea → script → produce → publish → review |
| [`ROADMAP.md`](../ROADMAP.md) | Pack status and next phases |
