# NON-CANON EXCLUSIONS

> **Read this before generating anything.** Every path listed here is either archived,
> superseded, or not a canon source. A production system must not draw story, dialogue,
> design, or continuity from any of it.

---

## 1. Hard Exclusions — Never Generate From These

| Path | Why | Use instead |
|---|---|---|
| `scripts/chapter-01-the-last-breath.md` | Early standalone draft predating the script conversion. Compresses what became Ch.1 **and** Ch.2 into one chapter. Opens on a "1227 AD. The Mongolian steppe" date card, a Mongol army and a tent — none of which is in the finished Ch.1. **Still contains the crown driven into the stone.** Kept deliberately as a historical draft, per the author's own direction. | `chapters/arc-01-the-refusal/chapter-01-the-last-breath.md` and `chapter-02-two-crowns.md` |
| `characters/the-reaper.md` | Superseded Reaper sheet — "he", no distinct forms. Contradicts current canon on gender, form and powers. | `characters/the-reaper/the-reaper.md` |
| `suro-the-blind-blade.md` (repo root) | Stale duplicate of the Suro bible. Byte-identical except one line that still called Egris "a Khan" — a pre-rename leftover the repo-wide fix never reached. | `characters/suro-the-blind-blade/suro-the-blind-blade.md` |
| `world/concept-art/superseded/the-crown-in-the-stone.png` | Finished splash of a scene that **is not in the story.** See §2. | `world/concept-art/the-border-gates.png` |
| `concept/duplicate-uploads-ARCHIVED/` (5 PNGs) | Byte-identical duplicates of art already filed elsewhere. MD5-verified. | the canonical paths listed in that folder's README |
| **All `.docx` and `.pdf` files** | Exports, not sources. Produced before this pass and **not regenerated** — the Ch.2 and Ch.3 page-count corrections are not reflected in them. | the matching `.md` |
| `PUBLISHING-GUIDE.md` | A **business document**, not a canon source. It contains an unresolved contradiction about the protagonist (see §3). | the bibles and scripts |
| `EDITORIAL-NOTES.md` | An audit trail of past fixes. Describes problems, some already solved. Not a description of current canon. | `production/CANON-MASTER.md` |

---

## 2. Retired Story Elements — Never Reintroduce

### ❌ The crown driven into the stone
An earlier version had Egris drive a crown into the black stone between the Gates as a
territorial stake, and a **finished splash illustration of it exists**. It is not canon.
✅ **What actually happens:** he grips God and Satan by the wrists, shoves **both** crowns to
the ground, and walks into the Wastes as the gates close behind him. **The walking away is the
claim.** Confirmed by the author, and consistent across both the prose draft and the finished
script. The art was retired rather than the scene rewritten.

### ❌ The Mark as a resource that costs a follower's memory
An earlier concept had the Reaper's Mark cost one of Egris's followers a memory per use. It
appears **nowhere** in the finished chapters and has been removed from the power-system file
and Egris's bible.
✅ **What it actually is:** a mortality countdown on **Egris alone**, growing on its own each
time he refuses a major offer of authority. Costs his followers nothing. See
`production/POWER-SYSTEM-LOCKS.md`.

### ❌ A 7-chapter Arc 1
Arc 1 is **12 chapters, 320 pages.** An older overview described 7 chapters with a Seraphel
sword duel and a defeated rival in Ch.5–6 — events that were never written at any length.
✅ There is **no sword duel with Seraphel.** He withdraws Heaven's host in Ch.6 without a single
blow struck.

### ❌ "Khan" / "Genghis Khan" as the protagonist's name
His name is **Egris**. The one surviving instance in `PUBLISHING-GUIDE.md` ("a Genghis
Khan-caliber emperor") is an intentional pitch comparison, not his name.
⚠ `characters/egris/egris-character-sheet.png` still has **"GENGHIS KHAN" lettered into the
image**. It cannot be corrected by a text edit and needs re-lettering.

### ❌ A male Reaper
The Reaper is a woman. Any "he/him" Reaper material is superseded.

### ❌ The Reaper's mark reveal as a quiet non-event in Ch.7
An old art note described it that way. The finished Ch.7 builds the Reaper's arrival into a
full-page splash (p.21).

---

## 3. Unresolved — `AUTHOR DECISION REQUIRED`

**Do not resolve any of these. Stop and surface them.**

1. **Egris's ethnic identity.** Story canon reads Mongol (art-notes: *"Mongol features. Not
   westernized."*; Ch.2 "the chaos of the steppes"; Ch.3 Samarkand; the art sheet's "GENGHIS
   KHAN" lettering). `PUBLISHING-GUIDE.md` calls him **Black** at lines 23, 73 and 249. Both
   cannot be true. Raised in a previous pass, left open by the author, still open.
   🛑 **Do not generate Egris character art until this is ruled on.**
2. **The Reaper's eyes.** Scripts: **"snake-slit pupils"** (Ch.7 p.22, Ch.12 p.8, Ch.12 p.13).
   Bible + finished concept sheet: **human round pupils**, with a **muted blood-red ring**
   appearing on the reveal. Three scripts against the bible and the art.
   🛑 **Do not render the Reaper's eyes until this is ruled on.**
3. **The origin of the Reaper's Mark.** Egris already bears it, and already knows who she is,
   the first time it appears (Ch.7 p.14–17). Nothing in Ch.1–6 shows him receiving it.
   🛑 **Do not invent an origin scene.**
4. **Suro's story hook #4** — written as a future "crossing paths" beat, but they met in Ch.6
   and have travelled together since. Flagged in place in his bible.
5. **Icarus & Incubus** — two finished design sheets, zero written material. Future-canon only.
   🛑 **Do not place them in Arc 1.** See `concept/future-canon/icarus-and-incubus/README.md`.
6. **Adé / the Black Samurai** — full bible and finished art, appears in **zero** chapters.
   Standalone concept. 🛑 Do not insert him into Arc 1.

---

## 4. Known Gaps — Absence Is Not Permission

These things are missing. **Missing is not an invitation to invent.**

- **No Arc 2 exists.** Not outlined, not drafted. The only forward material is the Ch.12 hook
  (the Rival's real army) and the series ending direction in `story-bible/premise.md`.
- **The Former Rival has no name**, on purpose. Do not give him one.
- **The Reaper has no name**, on purpose. Do not give her one.
- **The specific betrayal between Egris and the Rival** is referenced but never detailed. It is
  an open Arc 2 thread. Do not fill it in.
- **The Reaper's Absence form** is bible/design material with no on-page appearance. Do not
  render it in Arc 1.
- **What can make the Reaper bleed** is "a door left open on purpose." Leave it open.
- **No concept art** for Arghun, Borchu, Seraphel, the Hollow Men, the Echo Warriors, the
  colossus, or any interior of Heaven or Hell.
- **No music material of any kind exists**, which is why no music bible was created.
- **`download (4).png` and `download (5).png` were never uploaded.** The delivered sequence runs
  1, 2, 3, 6, 7, 8, 9. If two assets are missing from that drop, they are those two.

---

## 5. Archive Marker

Any file whose first lines contain:

```
ARCHIVED — NON-CANON — DO NOT USE FOR PRODUCTION
```

is excluded, whether or not it is listed above. Check for this string before ingesting any file.
