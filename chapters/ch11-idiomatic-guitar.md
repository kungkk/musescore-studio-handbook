# Chapter 11: Idiomatic Notation — Guitar & Tablature

## Core Idea
Guitar tablature staves show strings (lines) and fret numbers. **Linked** tab staves auto-sync with standard notation; **unlinked** ones are independent. Fretboard diagrams, chord symbols, capo, bends, and tremolos are all palette-driven.

## Frameworks Introduced
- **Creating tablature**:
  - New score: Templates → Solo → "Guitar + Tablature" (linked pair), or Choose instruments → Strings – Plucked → tab instrument.
  - Existing score: press **I** → Strings – Plucked → choose tab type.
  - Convert staff: Staff/Part properties → Staff type → tablature.
- **Linked vs unlinked staves**:
  - **Linked**: edit notation, tab auto-updates (and vice versa).
  - **Unlinked**: independent; copy-paste to sync.
  - Both share the same instrument.
- **Entering tab**:
  - Select a fret on the tab line → type fret number (0–24).
  - Strings are selected by line; duration picked as usual (1–9).
  - Note names can be entered on the standard staff; linked tab auto-updates.
- **Fretboard diagrams** (chord boxes):
  - Chords palette → fretboard diagram.
  - Properties: number of strings/frets, barre, fingerings.
  - Placed above staff; pairs with chord symbol (Ctrl+K).
- **Capo**:
  - Staff/Part properties → Capo fret.
  - Notation stays in open position; playback transposes.
- **Bends / slides / vibrato / harmonics / palm mutes**:
  - Articulations and Lines palettes.
  - Bend: drag upward; Properties sets bend amount (half/whole step).
- **Tremolo picking / strum**:
  - Tremolo palette; measured/unmeasured.
- **Tuning**: standard, drop-D, open tunings — Staff/Part properties → Strings.

## Key Concepts
- **Tablature** — string lines with fret numbers.
- **Linked staff** — notation ↔ tab sync.
- **Fretboard diagram** — chord box showing finger positions.
- **Capo** — transposition by fret position.

## Mental Models
- Think of tab as "fret numbers on strings"; linked tab = two views of the same music.
- Think of capo as "play in open position, sound transposed."

## Anti-patterns
- **Adding an unlinked tab when you want sync** — use *Create a linked staff* (Ch 5).
- **Entering fret numbers on the wrong string** — click the correct tab line first.

## Key Takeaways
1. Templates → "Guitar + Tablature" gives linked pair out of the box.
2. Press I → Strings – Plucked to add tab to existing scores.
3. Enter tab by clicking a string line and typing the fret number.
4. Fretboard diagrams pair with chord symbols (Ctrl+K).
5. Capo set in Staff/Part properties.

## Connects To
- **Ch 5**: Linked staff creation.
- **Ch 14**: Chord symbols.
