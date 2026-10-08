# Chapter 1: Getting Started (Introduction)

## Core Idea
MuseScore Studio 4+ is a free, cross-platform (Windows/macOS/Linux) notation editor. The shortest path to a score: **New score → pick a template → press N → type note names A–G → export**.

## Frameworks Introduced
- **Template-first workflow**: Click *New score* on the Scores screen → browse by Category or search → Next → set key/time signature, tempo, pickup measure, measure count (default 32) → Done.
  - When to use: first time, or when starting a common ensemble type.
  - Why: templates pre-wire instruments, transpositions, and part extraction.
- **Note entry mode**: Press **N** to toggle. A blue cursor marks the next input position. Duration chosen from the Note input toolbar or keys **1–7** (1=64th … 7=whole).
  - When to use: any note/rest entry.
  - How: N → pick duration (1–7) → type A B C D E F G.
- **Palette → click-to-add**: Select a target element/range in the score → open a Palette group → click once on the symbol. No drag needed.
- **Properties panel (formerly Inspector in v3)**: Left-side panel; shows settings for whatever is selected. v4 multi-select shows relevant settings regardless of element type.
- **Insert/delete measures**: Select a measure → Properties → Measure section → *Insert measures* / **+** button (supports count and position dropdown). Delete: select → trash icon in Measures popup.
- **Save local vs cloud**: *File→Save* (local .mscz) or *File→Save to Cloud* (musescore.com; visibility Private / Unlisted / Public).
- **Export**: Publish tab → Export → pick parts, format (PDF, MusicXML, MIDI, audio, image), combine or split files.

## Key Concepts
- **MuseScore Studio version 4.0+** — the handbook's covered version. v3/v2/v1 have separate handbooks.
- **MuseHub** — macOS install launcher; installs MuseScore Studio + sound libraries/effects.
- **Pickup measure (anacrusis/upbeat)** — optional incomplete first measure set at score creation.
- **Cloud visibility**: Private = only you; Unlisted = anyone with link; Public = anyone.

## Mental Models
- Think of **N** as the "I am typing notes now" mode — leave it with Esc or N.
- Think of **Palettes** as the toolbox, **Properties** as the wrench on the selected thing.
- Save locally by default; use Cloud when you want to share or back up.

## Anti-patterns
- **Editing in v3 after moving to v4 and expecting identical layout** — v4 re-engraves beams, slurs, spacing; old scores will look different.
- **Using the v3 Synthesizer panel** — removed in v4; sounds are saved per-score in the mixer.
- **Expecting SFZ playback out of the box** — use a free VST sampler (Sfizz, Sforzando) for SFZ in v4.

## Worked Example — First Score End-to-End
1. Open MuseScore → *New score*.
2. Search "Piano" template → Next.
3. Leave C major, 4/4, no tempo marking, 32 measures → Done.
4. Press **N**. Blue cursor appears in bar 1.
5. Press **5** (quarter note) → type C D E F | G F E D | C2 (hold note) …
6. Press **Esc** to exit note entry.
7. Click a notehead → left Palettes → open "Articulations" → click staccato dot.
8. *File→Save* → name it `first-piece.mscz`.
9. *Publish→Export* → PDF → Export.

## Key Takeaways
1. **N** + **1–7** + **A–G** is the entire core note-entry loop.
2. Templates are faster than blank scores for any standard ensemble.
3. v4's Properties panel replaces v3's Inspector; multi-select works.
4. Save local `.mscz`; export PDF/MusicXML/MIDI on demand from Publish.
5. Coming from v3: expect layout changes, new mixer, removed Synthesizer panel.

## Connects To
- **Ch 3**: Score setup & instrument management.
- **Ch 4**: Full note-entry techniques, voices, mouse/keyboard alternatives.
- **Ch 16**: File management, MusicXML, cloud publishing.
