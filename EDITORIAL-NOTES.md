# Editorial Notes — Consistency Pass

This folder is a cleaned-up copy of your GitHub repo (`Kaybags214/emperor-who-would-not-kneel`), pulled after fetching everything that was on the remote but not yet on this machine — the full 12-chapter Arc 1, three new character bibles, and the publishing guide. Your GitHub repo itself was also touched (see "Also done on GitHub" below) — everything else here lives only in this local copy.

**Confirmed:** all 12 Arc 1 chapters exist, in full manga script format, ~320 pages, marked "ready to shop to publishers" in your own PR notes.

---

## Also done on GitHub (by request)

- **Merged PR #4** — "Fix speaker labels: KHAN → EGRIS" — this had been sitting open and unmerged, meaning the bug was still live in your real `main` branch. It's fixed there now, not just in this local copy.
- **Closed PR #5** — "Add Chapter 7 — The Line in the Ash" — superseded by the later 12-chapter PR, which already added a different, final version of Chapter 7. Closed with a comment explaining why, nothing lost.

---

## Fixed in this copy

1. **"Khan" / "Genghis Khan" regression** — the character rename to Egris was completed and confirmed ("the rest of the repo already uses Egris consistently" per your own PR #4 description), but it crept back into three *later* character-bible PRs: Suro's, the Black Samurai's, and the new Reaper's. All five instances replaced with Egris.

2. **Two contradictory Reaper character sheets.** `characters/the-reaper.md` (original — "he," no special forms) directly conflicted with the newer, more developed `characters/the-reaper/the-reaper.md` (an ancient Black woman with two forms — the Woman and the Absence). Kept the newer one as canonical, replaced the old one with a one-line pointer so the supersession stays visible instead of just vanishing.

3. **The Reaper's Mark mechanic had drifted from its own rulebook.** `power-system/authority.md` and `characters/egris.md` both still described the mark as costing *a follower's memory* per use. That's not what happens anywhere in the finished chapters — the mark is a mortality countdown on **Egris himself**, growing one stage further up his arm every time he refuses a major offer of power (Ch.7 → Ch.8 → Ch.10 → Ch.12), which the Reaper can pause but not cure. Rewrote both docs to match, and added a dedicated "Reaper's Mark" section to her bible tracking exactly where it appears across the arc.

4. **The crown-planting image — now resolved.** In my first pass I found this described as the series' defining image in `world/` and `art-notes/` but absent from the 6-chapter prose I had, so I added it. Once I had the full 12-chapter canon, both written drafts (prose *and* its script conversion) agreed the crowns are dropped, not planted — so I reversed course and fixed the docs to match the writing instead. I then found finished concept art of exactly the crown-in-the-stone scene in your Google Drive, which disagreed with the finished script. **Your call: keep the script as-is, retire the art.** Moved the image to `world/concept-art/superseded/the-crown-in-the-stone.png` with a short README explaining it predates the current scene and isn't a guide for illustrating Ch.2.

5. **`arc-overview.md` was still describing a 7-chapter arc** with outlined events for Chapters 5–6 (a sword duel, a defeated rival) that never matched what was written even at 7 chapters, and no coverage at all of Chapters 8–12. Rewrote it to accurately summarize all 12 finished chapters.

6. **Four recurring characters had no bible entry anywhere**, despite being present across most of the arc: **Arghun** (first follower, Ch.3–12), **Borchu** (Ch.5–12), **Seraphel** (God's envoy, the whole of Ch.5–6), and **the Former Rival** (the arc's actual antagonist, Ch.6–12 — note he's credited only as "the Former Rival" throughout, no proper name, which reads as a deliberate choice rather than an oversight). Added one file each, pulled directly from what's on the page — nothing invented.

7. **The Black Samurai (Adé) doesn't appear in any of the 12 chapters.** Flagged directly in his own bible file so he doesn't get mistaken for integrated canon — he's a standalone concept that could anchor his own series or be woven into Arc 2, per his own bible's framing.

8. **Folder structure normalized.** The three newest character bibles (Suro, the Black Samurai, the Reaper) each live in their own subfolder — likely anticipated room for the "visual set" concept art each bible references. Moved Egris, God, and Satan into matching subfolders so the convention is consistent across the whole main cast. Left the four newly-added supporting-cast files (Arghun, Borchu, Seraphel, the Former Rival) as flat files, since they're lighter entries without an implied art asset — worth reconsidering if any of them gets a fuller bible later.

9. **README updated** — folder structure description was backwards (said `/chapters` held "scripts"), and the status checklist still said "Arc 1 outlined (7 chapters)" with Chapter 1's script unchecked, both stale. Corrected and brought current.

---

## Left alone — flagging, not fixing

- **`scripts/chapter-01-the-last-breath.md`** is an early standalone draft of Ch.1 that predates the arc-01 script conversion and still contains the crown-planting scene from the earlier concept. Per your own PR #4 description, this was intentionally left un-synced rather than merged into the current continuity — I added a short note at the top explaining what it is and that it's out of sync, rather than rewriting it.
- **Suro's story-hook #4** floats a Suro/Egris "crossing paths" scene as a future hook — but they've already met and traveled together since Chapter 6. Left as-is since it may just mean a *dedicated* confrontation/duel beat rather than their first meeting; worth a glance from you to confirm that's the intent.

## Flagging — needs your call, didn't touch it

- **`PUBLISHING-GUIDE.md` describes Egris as Black in three places** — the example logline ("A Black former conqueror dies...", line 23), the Saturday AM pitch note ("Your Black protagonist fits their diversity mission," line 73), and the competitive-advantages list ("Black Protagonist," line 249). But Egris's own bible and his own concept-art sheet (`characters/egris/egris-character-sheet.png`, labeled "GENGHIS KHAN") both depict him as Mongol — Suro and the Reaper are the Black-led characters. **You asked to leave this for now, so nothing here was changed** — noting all three locations so whichever way you resolve it, none get missed. I did fix the adjacent "Genghis Khan refuses God and Satan" hook line to say "a Genghis Khan-caliber emperor" instead of using it as his literal name.

- ~~**The Black Samurai's concept art is labeled differently than his bible.**~~ **RESOLVED.** `characters/the-black-samurai/the-black-samurai-character-sheet.png` is titled in Japanese as **黑風 (Kokufū / "Black Wind")**, not Adé. This was confirmed as an earlier working title for the same character and is recorded as such in his bible and in the asset table below; **Adé is the name of record.** (This entry previously contradicted the asset table, which already said "confirmed" — reconciled in the canon pass.)

## Found — the concept art (in Google Drive, not GitHub)

All nine pieces of concept art referenced across the character bibles turned up in your Google Drive, in the same folder as an already-drafted "emperor_arc1_editorial_review.pdf" (see below). Downloaded and organized into the project:

| File | Placed at |
|---|---|
| Egris character sheet (labeled "GENGHIS KHAN" — armor, Reaper's Mark detail, stats) | `characters/egris/egris-character-sheet.png` |
| God character sheet (architectural light-being) | `characters/god/god-character-sheet.png` |
| Satan sample manga page (human, seated, "I did not rebel... because I believed you were wrong") | `characters/satan/satan-sample-page.png` |
| The Reaper character sheet (face/hands/eyes-reveal, both forms) | `characters/the-reaper/the-reaper-character-sheet.png` |
| Suro full turnaround + action poses + sword detail | `characters/suro-the-blind-blade/suro-character-sheet.png` |
| Black Samurai sheet (labeled 黑風 / Kokufū — confirmed as an earlier working title for Adé, same character, noted in his bible) | `characters/the-black-samurai/the-black-samurai-character-sheet.png` |
| Former Rival full turnaround + armor/weapon detail + poses | `characters/the-former-rival-character-sheet.png` |
| The Border Gates — establishing environment shot (Heaven's white gate, Hell's black gate, a lone figure between them) | `world/concept-art/the-border-gates.png` |
| The crown driven into the stone — key scene splash, retired as non-canon (see below) | `world/concept-art/superseded/the-crown-in-the-stone.png` |

No art exists yet for: Arghun, Borchu, Seraphel, or the Echo Warriors/colossus from Ch.9–11 — all newly-documented or later-arc elements that predate this pass.

## Also found — a prior independent editorial review

The same Drive folder had `emperor_arc1_editorial_review.pdf`, a chapter-completeness and continuity audit that appears to have been run earlier by a different tool/session. It independently confirmed several things I also found (the `scripts/` vs `arc-01/` Chapter 1 divergence, including the crown-planting discrepancy) and flagged a few things I hadn't checked closely — **all now fixed in this copy**:

- Chapter 1's header said "Approx. 22 pages" but its own script notes said 12, and the content ends at page 12 — header corrected to 12.
- Chapters 4, 5, and 6 significantly overran their declared page-count headers (Ch.4 said ~24, actually 31; Ch.5 said ~28, actually 43; Ch.6 said ~38, actually 63) — all three headers corrected to match actual content.
- `chapter-06-the-infernal-bargain.md` Page 2 had "TREMBLE" broken across a hard line break — fixed.
- The arc's total page count was quoted as ~295 pages in `PUBLISHING-GUIDE.md`, `arc-overview.md`, and this file — the real total (summed from every chapter's actual last page) is **320 pages**. Corrected everywhere it was quoted.

---

# Final Canon Reconciliation & Cleanup Pass

*Second pass, run after the new PNG uploads landed. Scope: reconcile everything into one
internally consistent canon suitable for AI-assisted manga/video production, and stand up a
`production/` bible so downstream systems don't have to reinterpret the repo each run.*

**Standing rule for this pass:** consistency correction authorized, creative rewriting not.
Anything that needed a creative decision was flagged `AUTHOR DECISION REQUIRED` and left alone.

## Fixed — objective continuity only

1. **Chapter 2 and Chapter 3 page-count headers were wrong.** Ch.2 declared "Approx. 20
   pages" and ends at page 12; Ch.3 declared "Approx. 18 pages" and ends at page 11. (The
   previous pass corrected Ch.1, 4, 5 and 6 but missed these two.) Both headers corrected.
   The arc total of **320 pages is unchanged and now verified** — it was already computed
   from actual last pages, not from the headers: 12+12+11+31+43+63+22+22+24+26+28+26 = 320.
2. **A "Khan" naming remnant survived at the repo root.** `suro-the-blind-blade.md` sat
   outside `characters/`, was a byte-identical duplicate of the real Suro bible apart from one
   line still calling Egris "a Khan," and the repo-wide rename never reached it. Replaced with
   an `ARCHIVED — NON-CANON` pointer to the canonical file.
3. **The Reaper still had male pronouns in two places** the earlier pass missed:
   `story-bible/premise.md` ("He believes the throne...") and `art-notes/visual-direction.md`
   panel-layout section ("when he appears... his presence"). Both corrected to she/her.
4. **The retired crown-in-the-stone image was still being cited as current canon** in
   `characters/the-black-samurai/the-black-samurai.md`, which anchored Adé's name to "the
   crown driven into the black stone between the two Gates." Reworded to the crown motif that
   actually happens — the two crowns Egris is offered and shoves to the stone.
5. **`arc-overview.md` described a Chapter 1 that isn't the finished Chapter 1.** It said
   "Egris dies on the Mongolian steppe" — that detail comes from the archived `scripts/` draft
   (which opens on a "1227 AD. The Mongolian steppe" card, a Mongol army, a tent). The finished
   Ch.1 opens on an unnamed plain of winter grass and a deathbed, names no place and no date,
   and shows no battlefield. Corrected to describe what is on the page.
6. **`EDITORIAL-NOTES.md` contradicted itself about Kokufū.** The "needs your call" section
   asked for confirmation that 黑風 and Adé were the same character while the asset table two
   sections below already said "confirmed," as does his bible. Reconciled — marked RESOLVED,
   Adé is the name of record.
7. **Ch.7 script-note typo** — "Pages 14 —" corrected to "Page 14 —".
8. **Egris's bible now specifies the Mark is on his left hand**, matching all four chapter
   appearances.
9. **Archive banners standardised.** `characters/the-reaper.md`,
   `scripts/chapter-01-the-last-breath.md` and `world/concept-art/superseded/README.md` now all
   carry the literal string `ARCHIVED — NON-CANON — DO NOT USE FOR PRODUCTION` so a production
   system can exclude on one grep.

## Verified clean — checked and found consistent

- Numeric continuity across the arc: camp = 43 (Ch.9–12), Echo Warriors = 30 (Ch.9–10), souls
  standing against the colossus = 33 with 10 remaining behind (Ch.11–12), Arghun's 22 years in
  Samarkand, colossus at 20 feet. No drift anywhere.
- The Reaper's Mark progression (Ch.7 p.14 → Ch.8 p.1 → Ch.10 p.24 → Ch.12 p.2, paused Ch.12
  p.18) matches her bible, the power-system file and Egris's bible exactly.
- Every page reference in `art-notes/visual-direction.md`'s "Key Visual Moments" was checked
  against the scripts: Ch.2 p.9, Ch.2 p.12, Ch.7 p.21, Ch.10 p.13, Ch.11 p.27 — all correct.
- No remaining 7-chapter references. No remaining ~295-page references.
- Speaker labels: inconsistent across chapters (WHITE FIGURE/WHITE POWER for God,
  FORMER RIVAL/RIVAL/RIVAL'S VOICE, SCRIBE→ARGHUN, STRANGER→SURO) but **deliberately so** —
  characters are unnamed until the story names them. **Left untouched**; an alias resolution
  table was added to `production/CHARACTER-LOCKS.md` instead so production can parse them
  without the scripts being flattened.

## New image assets — resolved

Seven PNGs had been uploaded to the repo root as `download (N).png`. MD5-compared against
every existing art file:

| Upload | Content | Confidence | Action |
|---|---|---|---|
| `download (1).png` | Black Samurai / 黑風 Kokufū sheet | Certain — byte-identical | Archived as duplicate |
| `download (2).png` | The Border Gates | Certain — byte-identical | Archived as duplicate |
| `download (3).png` | God character sheet | Certain — byte-identical | Archived as duplicate |
| `download (6).png` | Suro character sheet | Certain — byte-identical | Archived as duplicate |
| `download (7).png` | The Reaper character sheet | Certain — byte-identical | Archived as duplicate |
| `download (8).png` | **ICARUS — Architect of the Absolute** | Certain — self-titled on the art | → `concept/future-canon/icarus-and-incubus/icarus-character-sheet.png` |
| `download (9).png` | **INCUBUS — Voice of the Bleeding Dark** | Certain — self-titled on the art | → `concept/future-canon/icarus-and-incubus/incubus-character-sheet.png` |

No asset was renamed on a guess. The five duplicates were **moved, not deleted**, into
`concept/duplicate-uploads-ARCHIVED/` with a README recording each one's MD5 and canonical
twin — safe to delete once you've confirmed.

**`download (4).png` and `download (5).png` were never uploaded.** If two assets are missing
from that drop, they are those two.

## Newly discovered contradictions — flagged, NOT resolved

- **The Reaper's eyes.** Three chapter scripts give her **"snake-slit pupils"** (Ch.7 p.22,
  Ch.12 p.8, Ch.12 p.13). Her bible says her eyes are **human and dark** in the Woman form,
  with the reveal being darkened whites and a **muted blood-red ring around the iris** — and
  her finished concept sheet draws exactly that, round pupils and all, in a panel literally
  labelled "EYES (REVEAL)." Scripts vs. bible **and** finished art. `AUTHOR DECISION REQUIRED`.
- **The Mark has no origin.** Egris already wears it, and already knows whose it is, the first
  time we see it — Ch.7 p.17, *"She's been following the mark,"* with the direction reading
  *"He has felt this presence before."* Nothing in Ch.1–6 shows him receiving it or explains
  it. `AUTHOR DECISION REQUIRED` — no origin was invented.
- **The Reaper's Absence form never appears in Arc 1.** Only the Woman form does. Not a
  contradiction, but production needed to be told, so it is now in the locks.
- **God is never named on the page in Arc 1** — no `GOD` speaker label exists anywhere. Satan
  is named once, in Ch.6. This asymmetry looks deliberate and was preserved.

## Still open from the previous pass

- **Egris's ethnic identity** — Mongol everywhere in story canon, Black in three places in
  `PUBLISHING-GUIDE.md`. Still unresolved. A flag block was added at the top of that guide
  naming all three locations; **none of the three lines was changed.** Note that
  `characters/egris/egris-character-sheet.png` has "GENGHIS KHAN" lettered into the image
  itself and will need re-lettering whichever way this lands.
- **Suro's story hook #4** — now flagged inline in his bible rather than only mentioned here.

## Created

`production/CANON-MASTER.md`, `CHARACTER-LOCKS.md`, `WORLD-LOCKS.md`,
`POWER-SYSTEM-LOCKS.md`, `VISUAL-STYLE-BIBLE.md`, `NON-CANON-EXCLUSIONS.md`, plus
`concept/future-canon/icarus-and-incubus/README.md`. These summarize approved canon and index
the sources — they **do not replace** the full material, and where they are thinner than a
source file, the source file wins.

**No music bible was created** — no music material exists in the repository.
