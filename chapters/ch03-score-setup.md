# Chapter 3: Score Setup, Instruments & Measures

## Core Idea
A score is built by choosing instruments (or a template), then setting key/time/tempo/pickup/measure-count. After creation, the **Layout panel** (F7) is the one-stop shop for adding, removing, reordering, and replacing instruments.

## Frameworks Introduced
- **New Score dialog** (Ctrl+N): Two tabs — *Choose instruments* or *Create from template*.
  - Choose instruments: browse 500+ instruments by Family, double-click to add; reorder with ↑/↓; remove with trash can.
  - Templates: pre-wired ensemble layouts (choose Category → template → Done).
- **Additional score information** (Next screen):
  - **Key signature**: default C major; toggle Minor tab for minor keys.
  - **Time signature**: default 4/4; set beats + beat-quality dropdown; includes common / cut-common (alla-breve).
  - **Tempo**: default ♩=120; tick "Show tempo marking on my score" to print a metronome mark.
  - **Measures**: default 32; tick "Create pickup measure" + set beats + beat value.
  - **Title / Composer / Subtitle / Lyricist / Copyright** — auto-placed, stored in Project Properties.
- **Changing instruments after creation** (3 ways):
  1. Press **I** in the Score tab.
  2. Click *Add* in the Layout panel (F7 / View→Layout).
  3. *Replace instrument* in Staff/Part properties (right-click a staff).
- **Insert / delete measures**: Select a measure → Properties→Measure→*Insert measures* / **+** (set count and position dropdown). Delete: select → trash icon in Measures popup.
- **Parts**: The *Parts* button (top center) opens the Parts dialog to create, edit, delete instrumental part scores. v4 auto-generates parts from the instrument list.

## Key Concepts
- **Family dropdown** — groups instruments into standard orchestral families (Strings, Woodwinds, Brass, etc.).
- **Pickup measure (anacrusis)** — optional incomplete first measure; set at creation or later.
- **Project Properties** — title/composer/etc. metadata; editable any time.
- **Layout panel** — v4's integrated instrument manager, replaces v3's Manage Instruments dialog.

## Mental Models
- Think of **templates** as "done-for-you instrument rosters" and **Choose instruments** as "build your own."
- Think of the **Layout panel (F7)** as the instrument railroad: add cars (instruments), reorder them, swap engines (replace instrument).
- Pickup measure is a property of the first measure, not a setting that goes away.

## Anti-patterns
- **Editing instruments only at creation** — press I or use Layout panel anytime; templates are not locked.
- **Forgetting the Minor tab** when setting a minor-key score — defaults to relative major.
- **Assuming 32 measures is a hard limit** — insert/delete freely; the initial count is just a starting buffer.

## Worked Example — Build a Piano Trio Score
1. Ctrl+N → Create from template → Category "Chamber" → "Piano Trio" → Done.
2. (If building manually: Choose instruments → Strings → Violin, Cello; Keyboard → Piano → reorder so Piano is last/keyboard at bottom.)
3. Next: set key signature to F major, time 6/8, tempo ♩.=108 with marking, no pickup, 64 measures.
4. Add Title "Trio in F", Composer "You" → Done.
5. Later decide to swap Cello for Clarinet: press **I** → select Cello → Replace instrument → Woodwinds → Clarinet in B♭.

## Key Takeaways
1. Ctrl+N opens the New Score dialog; templates beat manual setup for standard ensembles.
2. Press **I** (or F7 Layout panel) anytime to edit the instrument roster.
3. Key/time/tempo/pickup/measure-count all live on the Next screen; defaults are C maj / 4/4 / ♩=120 / 32 measures.
4. Parts are auto-derived from instruments; use the Parts button to extract them.
5. Title/composer/etc. become Project Properties and print on the score.

## Connects To
- **Ch 4**: Note entry on the staves you just created.
- **Ch 5**: Instruments, staves, brackets, mid-score instrument changes.
- **Ch 16**: Project Properties and file export.
