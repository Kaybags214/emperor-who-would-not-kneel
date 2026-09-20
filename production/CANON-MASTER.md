# CANON MASTER — The Emperor Who Would Not Kneel

> **Purpose.** This is the entry point for any AI-assisted production system (Astra → n8n).
> Read this file first. It tells you what is canon, what is not, and which file wins when two
> disagree. It is a **summary and an index** — it does not replace the source material, and
> where it is thinner than a source file, the source file wins on detail.
>
> **Last reconciled:** 2026-09-20 (final canon reconciliation pass).
> **Canon status:** Arc 1 locked. Arc 2 unwritten. Several items still awaiting author decision — see
> `NON-CANON-EXCLUSIONS.md` and the flags below.

---

## 1. The Hard Rules

1. **The 12 chapter scripts in `chapters/arc-01-the-refusal/chapter-01…12-*.md` are the
   highest authority in this repository.** If any bible, note, guide or lock file contradicts a
   finished chapter script, **the chapter script wins** and the other file is the bug.
2. **Never generate from a file marked `ARCHIVED — NON-CANON — DO NOT USE FOR PRODUCTION`.**
   The full list is in `NON-CANON-EXCLUSIONS.md`.
3. **Never resolve an `AUTHOR DECISION REQUIRED` flag on your own.** Stop and surface it.
4. **Do not invent.** No new battles, no new origins, no new characters, no romance, no
   softening of the philosophy, no "polish" passes on dialogue. If something is missing, it is
   missing on purpose or it is an open question — not an invitation.
5. **`.docx` and `.pdf` files are exports, not sources.** Generate from the `.md` only. The
   exports were produced before this pass and have not been regenerated; where they differ,
   the `.md` is correct.

---

## 2. Authority Order

```
1. chapters/arc-01-the-refusal/chapter-*.md      ← the finished scripts. Final word.
2. chapters/arc-01-the-refusal/arc-overview.md   ← reconciled against the scripts
3. production/*-LOCKS.md                         ← this folder (summaries of 1–2)
4. characters/** , world/** , power-system/** , story-bible/** , art-notes/**
5. EDITORIAL-NOTES.md                            ← audit trail, not canon
6. PUBLISHING-GUIDE.md                           ← business doc. NOT a canon source. See §6.
—  ARCHIVED files                                ← never
```

---

## 3. Logline & Premise

A conqueror dies, wakes on the black plain between the Gate of Heaven and the Gate of Hell,
is offered a crown by each, and refuses both — then walks into the Wastes and builds
something out of people who *choose* to stand with him rather than people he commands.

**Core question:** *If you refuse every god, are you truly free — or are you merely serving
your own ambition?*

**Arc 1 question:** Can a man build something out of free choice instead of command — and how
long can he keep refusing power before refusing it costs him his life?

**Tone:** Seinen philosophical action. Berserk / Vagabond, not shonen. Spectacle exists, but
every arc is driven by an argument. The philosophy is the product — do not sand it down.

---

## 4. Arc 1 — Locked Structure

**12 chapters, 320 pages.** Page counts below are the verified actuals (every chapter's last
page heading), and every chapter header now matches.

| # | Title | Pages | Load-bearing beat |
|---|---|---:|---|
| 1 | The Last Breath | 12 | Dies; wakes on the black plain; does not kneel. Both powers step forward. |
| 2 | Two Crowns | 12 | Grips both powers by the wrist, shoves both crowns to the stone, walks out as the gates close. |
| 3 | The First Subject | 11 | Arghun, a scribe from his own empire, chooses to follow. |
| 4 | The Wastes | 31 | The Hollow Men; will, not violence, drives them off; the saved are afraid of him. |
| 5 | The Heavenly Envoy | 43 | Seraphel argues Heaven's case; Egris offers the camp a choice, not an order; the host descends. |
| 6 | The Infernal Bargain | 63 | Satan's iron crown refused; Seraphel withdraws without a blow; **Suro revealed**. |
| 7 | The Line in the Ash | 22 | The Former Rival's argument; **the Mark first seen**; the Reaper's first full appearance (p.21 splash). |
| 8 | The Weight of Refusal | 22 | Three-way chamber piece. *"I do not know."* The Rival leaves disappointed. |
| 9 | The Gathering Dark | 24 | Camp is 43. Thirty Echo Warriors offer command. |
| 10 | No Kings in the Ash | 26 | Refuses the echoes; they dissolve (p.13 splash). Mark past the wrist. |
| 11 | What Walks the Wastes | 28 | The colossus. Thirty-three choose to stand. It collapses (p.27). |
| 12 | The Cost of Walking Alone | 26 | The Reaper in camp; the third path named; Mark paused, not cured; the Rival is raising a real army. |

**Locked counts — do not drift:** camp = **43** souls (Ch.9, Ch.10, Ch.11, Ch.12) · Echo
Warriors = **30** · souls who stand against the colossus = **33** (10 remain behind) · colossus
height = **20 feet** · Arghun's service = **22 years in Samarkand**.

**The three escalating tests of the same principle** — Ch.5 (angelic host), Ch.9–10 (echo
army), Ch.11 (colossus). Each time the question is identical: will people stand without being
commanded? Each time the answer costs Egris a further stage of the Mark.

---

## 5. Series Direction (beyond Arc 1 — outline only, unwritten)

From `story-bible/premise.md`. Treat as the author's stated destination, not as script:
Egris defeats God, Satan and the Reaper, **refuses the throne and destroys it**; Heaven, Hell
and the Wastes collapse into one world; souls must build their own societies; Egris disappears
into it, no longer an emperor. Final page: a young soul asks an old soldier whether Egris
conquered the afterlife. *"No. He conquered the thing that wanted to own it."*

**Do not change this ending.** Do not generate it as finished content either — it is an
outline, not a script.

---

## 6. Standing Flags — AUTHOR DECISION REQUIRED

These are unresolved and were deliberately **not** decided in this pass.

- **`AUTHOR DECISION REQUIRED` — Egris's ethnic identity.** Everything in the story canon
  reads Mongol (art-notes: *"Mongol features. Not westernized."*; Ch.2 *"the chaos of the
  steppes"*; Ch.3 Samarkand; his concept sheet is lettered "GENGHIS KHAN"). `PUBLISHING-GUIDE.md`
  describes him as **Black** in three places (lines 23, 73, 249). Both cannot be true. This was
  raised in a previous pass and left open by the author; it is still open. **Nothing was
  changed.** See `CHARACTER-LOCKS.md §Egris`.
- **`AUTHOR DECISION REQUIRED` — the Reaper's eyes.** Three chapter scripts give her
  **"snake-slit pupils"** (Ch.7 p.22, Ch.12 p.8, Ch.12 p.13). Her bible and her finished
  concept sheet give her **human, round, dark eyes**, with the reveal being *darkened whites
  and a muted blood-red ring around the iris* — no slit. See `CHARACTER-LOCKS.md §The Reaper`.
- **`AUTHOR DECISION REQUIRED` — the origin of the Reaper's Mark.** Egris already bears it,
  and already knows who she is, the first time it is shown (Ch.7 p.14–17: *"She's been
  following the mark."* / *"He has felt this presence before."*). Nothing in Ch.1–6 shows him
  receiving it. See `POWER-SYSTEM-LOCKS.md §The Reaper's Mark`.
- **`AUTHOR DECISION REQUIRED` — Suro's story hook #4.** Flagged in place in his bible.
- **`AUTHOR DECISION REQUIRED` — Icarus & Incubus.** Art exists, no story exists. See
  `concept/future-canon/icarus-and-incubus/README.md`.
- **`AUTHOR DECISION REQUIRED` — Adé / the Black Samurai.** Full bible and art, appears in
  zero chapters.

---

## 7. Index

| Need | Read |
|---|---|
| Character rules, names, aliases | `production/CHARACTER-LOCKS.md` |
| Realms, geography, factions | `production/WORLD-LOCKS.md` |
| Faith / Fear / Legacy, the Mark | `production/POWER-SYSTEM-LOCKS.md` |
| Art direction, panel language | `production/VISUAL-STYLE-BIBLE.md` |
| What must never be generated from | `production/NON-CANON-EXCLUSIONS.md` |
| The scripts themselves | `chapters/arc-01-the-refusal/` |
| Audit trail of past fixes | `EDITORIAL-NOTES.md` |

**No music bible exists.** No music material is present in the repository, so none was created.
