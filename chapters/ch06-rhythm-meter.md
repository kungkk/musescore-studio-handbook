# Chapter 6: Rhythm, Meter & Measures

## Core Idea
Time signatures live on the Time signatures palette; changes happen at measure boundaries and re-bar subsequent music. Custom meters (e.g. 5/8, 7/8) are created via the *Create Time Signature* dialog, where you also control **beam groups**. Tuplets (3:2 triplets, etc.) are inserted from the note-input toolbar.

## Frameworks Introduced
- **Adding time signature**: Select a measure/note → click a time signature in the Time signatures palette (or drag). Changes only at measure start; re-bars following music (check for lost items).
- **Deleting**: select → Del. Deleting the opening time signature defaults to nominal 4/4.
- **Custom time signature**: palette → More → *Create time signature* (or Shift+F9 Master palette). Set Value (num/den), Text (display override), **Beam groups**.
- **Local time signature**: hold **Ctrl** (Cmd) while adding — applies to one staff only; bar length matches global (acts like an invisible tuplet). Example: Bach Goldberg var. 26 — right hand 18/16 over global 3/4.
- **Time signature visibility**: Staff/Part properties → *Show time signature* (per staff); or select → Properties → uncheck Visible (V).
- **Courtesy time signatures**: at system breaks, a cautionary appears at the end of the previous system. Toggle in Format→Style→Clefs, keys & time signatures.
- **Time signature position styles** (Format→Style): *On all staves* (default), *Above staves* (large, treated as system markings), *Across staves* (even larger, band/film scores).
- **Tuplets**: from note-input toolbar → Tuplets menu, or use the tuplet shortcut (e.g. Ctrl+3 for triplet). Select a note → choose tuplet ratio.
- **Beaming**: auto-rewritten by time signature's beam groups; override in *Beam groups* dialog or per-beam via Properties.
- **Barlines**: single, double, repeat, bold, etc. from Barlines palette; placed at measure boundaries.
- **Measure numbering**: Format→Style → choose show every N measures, or hide; offset for pickup.
- **Multimeasure rests**: collapse empty measures into a single rest with a count number (Format→Measure→Multimeasure rests).

## Key Concepts
- **Beam groups** — how eighth/sixteenth notes are grouped under beams; tied to the time signature's natural divisions.
- **Local time signature** — per-staff meter with same total bar length.
- **Courtesy (cautionary) time signature** — reminder at system end.
- **Pickup / anacrusis** — incomplete first measure.
- **Multimeasure rest** — collapsed empty bars for parts.

## Mental Models
- Think of time signature changes as "re-bar everything after here."
- Think of **Ctrl+drag** time signature = "only this staff."
- Think of beam groups as the default beaming rulebook per meter.

## Anti-patterns
- **Changing time signature mid-piece without checking re-bar results** — notes can shift/be lost.
- **Trying local time signatures on staves that already have music after the change** — unsupported.
- **Expecting local time signatures to allow different bar lengths** — they don't; they're invisible tuplets.

## Reference Tables — Rhythm Shortcuts

| Item | How to add |
|---|---|
| Time signature | Palette click / drag; changes at measure start |
| Custom meter | Palette → More → Create time signature |
| Local time signature | Ctrl+click palette item on target staff |
| Tuplet | Note-input toolbar → Tuplets; or Ctrl+ratio shortcut |
| Barline | Barlines palette; drag to measure |
| Multimeasure rest | Format → Measure → Multimeasure rests |
| Courtesy ts toggle | Format→Style→Clefs, keys & time signatures |

## Key Takeaways
1. Time signatures re-bar from the change point onward — verify after editing.
2. Ctrl+drag = local (per-staff) time signature.
3. Custom meters let you define beam groups in the Create Time Signature dialog.
4. Courtesy time signatures at system breaks are on by default; toggle in Style.
5. Multimeasure rests clean up empty bars in parts.

## Connects To
- **Ch 4**: Note entry durations (1–9).
- **Ch 9**: Repeats and jumps interact with measure numbering.
- **Ch 15**: Layout and spacing.
