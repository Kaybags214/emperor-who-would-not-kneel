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

- **The Black Samurai's concept art is labeled differently than his bible.** `characters/the-black-samurai/the-black-samurai-character-sheet.png` is titled in Japanese as **黑風 (Kokufū / "Black Wind")**, not Adé — a katana-wielding samurai design, matching the bible's *look* (Afro silhouette, dark seinen ink, "Afro Samurai" energy — the sheet even repeats "not for show, built for war"-style framing) but not its *name*. Could be an earlier working title before "Adé" was chosen, or the art was generated before the name was finalized. Worth a glance to confirm it's the same character before using it in any pitch materials.

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
