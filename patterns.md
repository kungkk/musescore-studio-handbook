# Patterns — MuseScore Studio Techniques

## Note Entry Loop
**When to use**: Any time you're entering notation.
**How**: N → pick duration (1–9) → type pitch (A–G) or 0 for rest. Shift+letter adds chord tones. T ties. Esc exits.
**Trade-offs**: Fast for melodies; chords built bottom-up with Shift.

## Duration-First vs Pitch-First
**When to use**: Default duration-first for most users; pitch-first (duration mode) for instrumentalists who think pitch-first.
**How**: Toggle in note-input toolbar.
**Trade-offs**: Duration-first is faster on QWERTY; pitch-first matches instrumental thinking.

## Voice Layering
**When to use**: Polyphonic passages on one staff (piano left hand, vocal duet on one staff).
**How**: Toggle voice 1–4 in note-input toolbar. Each voice independent.
**Trade-offs**: Multiple voices per staff get complex; use separate staves for independent parts.

## Linked Staff Pair (Notation + Tab)
**When to use**: Guitar/ukulele scores needing both standard notation and tab.
**How**: Templates → "Guitar + Tablature" (linked), or Layout panel → Create a linked staff.
**Trade-offs**: Linked = auto-sync but can't differ; unlinked = independent but must copy-paste.

## Ctrl+D Dynamics Popup
**When to use**: Adding any dynamic marking.
**How**: Select note → Ctrl+D → type `p`/`mf`/`ff` → Esc.
**Trade-offs**: Faster than palette clicks; voice assignment defaults to all voices.

## Hairpin Selection Range
**When to use**: Adding cresc./dim. hairpins.
**How**: Select notes *up to but not including* the endpoint note → press `<` or `>`.
**Trade-offs**: Hairpin ends just before next note; selecting endpoint double-spaces.

## Lyrics Syllable Entry
**When to use**: Adding vocal lyrics.
**How**: Ctrl+L → type syllable → `-` (next syllable, same word) / Space (new word) / `_` (melisma).
**Trade-offs**: Re-run Ctrl+L for each verse; they stack automatically.

## Chord Symbol Entry
**When to use**: Lead sheets, comping parts, jazz scores.
**How**: Select note → Ctrl+K → type chord name → Esc.
**Trade-offs**: Drives playback accompaniment; pairs with fretboard diagrams for guitar.

## Repeats Structure
**When to use**: Any repeated section.
**How**: Repeat barlines pair → voltas number endings → D.C./D.S. + markers for long jumps.
**Trade-offs**: Toggle "Play repeats" off to audition straight through.

## Vertical Justification
**When to use**: Want staves to fill page height evenly.
**How**: Format→Style→Spacing → Enable vertical justification; adjust factors.
**Trade-offs**: Filled pages look clean; ragged-bottom (disable) is closer to hand-engraved.

## Staff Space (Spatium) Scaling
**When to use**: Resizing the whole score.
**How**: Format→Page settings → Staff space (sp).
**Trade-offs**: One setting scales nearly everything; text/frames can be absolute.

## Selective Staff Playback
**When to use**: Auditioning one section/instrument without muting.
**How**: Select a measure (or Shift+click across staves) → Play.
**Trade-offs**: Faster than solo/mute in Mixer; temporary.
