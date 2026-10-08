# Chapter 5: Instruments, Staves & Systems

## Core Idea
The **Layout panel (F7)** is the instrument railroad: add/remove/reorder instruments, expand to see per-staff controls, add *linked staves* (for tablature alongside notation), and duplicate *system markings* (tempo, rehearsal marks, voltas) at multiple vertical positions on large scores.

## Frameworks Introduced
- **Layout panel** (View→Layout or F7; formerly "Instruments"):
  - **Add instrument**: Add → Add instrument (or press **I**).
  - **Delete**: select instrument → remove button or **Del** (deletes all its music).
  - **Reorder**: ↑/↓ arrows or drag.
  - **Rename**: cog button → *Name on main score* (long, at score start) / *Abbreviated name* (short, after first system) / *Part name* (top of extracted part).
  - **Replace instrument**: cog → Replace instrument.
- **Managing staves** (expand instrument with triangle):
  - **Add staff**: independent staff on same instrument (no shared notation).
  - **Create a linked staff**: notation stays synchronized across staves; staff type can differ — this is how guitar/tab pairs are built.
  - **Delete staff**: only possible when instrument has >1 staff; last staff → delete the instrument.
  - **Staff config** (cog): Staff type (Standard / tablature types), **Small staff** (cue-size), **Hide empty measures (cutaway)**.
- **System markings**: tempo, rehearsal marks, voltas, jumps, measure numbers, large time signatures. Top instance is fixed; add extra instances above other instrument groups (common: duplicate above strings in orchestral scores). Cog → eye toggles which marking types show at that position.
- **Hide vs delete**: eye icon hides instrument/staff (not deleted). Hidden **instruments don't play back**; hidden **staves still do**. To hide but hear: mute in Mixer, or hide staves individually.
- **Mid-score instrument changes**: switch one player from flute to piccolo partway; created via instrument change marking.
- **Implode/Explode**: take a chord on one staff and split notes across multiple staves, or reverse.

## Key Concepts
- **Linked staff** — two staves sharing the same notation, different staff types (e.g. treble + tab).
- **Cutaway staff** — hide measures with no notation (common for piano accompaniment).
- **System markings instance** — a vertical position where tempo/rehearsal marks are drawn.
- **Concert vs transposed pitch** — status-bar toggle; key signatures are always *sounding pitch*.

## Mental Models
- Think of **Layout panel** as a tree: Instrument → Staff. Expand the tree to edit staves.
- Think of **linked staff** as "two views of the same music" (notation + tab).
- Think of **system markings** as anchored labels: top one is mandatory, add more where players need to see them.

## Anti-patterns
- **Deleting an instrument to "hide" it** — loses all music; use the eye icon instead.
- **Adding a plain staff for tablature** — use *Create a linked staff* so the two stay synchronized.
- **Expecting hidden staves to mute playback** — only hidden *instruments* mute; unmute in Mixer.
- **Editing long/short instrument names here when you want global label rules** — use Format→Style→Score→Instrument labels.

## Key Takeaways
1. F7 opens the Layout panel; I opens the Add Instrument dialog.
2. Use **Create a linked staff** for guitar/tab pairs; plain Add staff is independent.
3. System markings can be duplicated vertically (cog → eye to filter types).
4. Eye = hide (non-destructive); Del = delete (destructive).
5. Hidden instruments mute playback; hidden staves don't.

## Connects To
- **Ch 3**: Initial score setup.
- **Ch 11**: Guitar tab staff creation.
- **Ch 15**: Layout and spacing of systems.
