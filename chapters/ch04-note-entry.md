# Chapter 4: Note Entry & Editing Basics

## Core Idea
The core loop is **N → pick duration (1–9) → type pitch (A–G) or 0 for rest**. Chords = Shift+letter. Accidentals prefixed with `-`/`+`/`=`. Ties = **T**. Most editing is selecting an element and using Properties or palette clicks.

## Frameworks Introduced
- **Two entry modes**:
  - **Input by note name** (default): duration first, then pitch.
  - **Input by duration mode**: pitch first, then duration (reverse order).
- **Duration keys 1–9**:
  | Key | Duration |
  |---|---|
  | 1 | 128th (shortest) |
  | 2 | 64th |
  | 3 | 32nd |
  | 4 | 16th |
  | 5 | 8th (quaver) |
  | 6 | quarter (crotchet) |
  | 7 | half (minim) |
  | 8 | whole (semibreve) |
  | 9 | breve (double whole) |
  - Double dots / 128th+ via custom toolbar or shortcuts.
- **Pitch entry methods**:
  - Keyboard: type A–G (auto-picks closest octave).
  - Mouse: click a line/space on the staff.
  - MIDI keyboard: press keys; auto-advances when you release.
  - Virtual piano: View→Piano keyboard or **P**.
- **Chords**: Hold **Shift** + letter to add a note on top; or **Alt+1…9** to add interval above; or play multiple MIDI keys at once. Build from lowest note upward.
- **Rests**: press **0** after picking duration.
- **Accidentals**: pre-press `-` (flat), `+` (sharp), `=` (natural) before the note; or after entry use ↑ (semitone up, spells sharp) / ↓ (semitone down, spells flat). Same-pitch notes in the same measure inherit the accidental.
- **Ties**: enter first note → pick second duration → press **T**. Creates second same-pitch note tied. Chords tie all voices.
- **Octave adjust**: **Ctrl+↑ / Ctrl+↓** (Cmd+↑↓ on Mac) moves last-entered note by octave.
- **Enharmonic respell**: select a note → **J** toggles spelling.
- **Voices**: up to 4 independent voices per staff; toggle in note-input toolbar. Use for polyphonic passages on one staff.
- **Selecting**: click, Shift+click for range, double-click for edit mode. Properties panel shows settings for whatever is selected.

## Key Concepts
- **Note input cursor** — blue highlight marking next entry position.
- **Courtesy / cautionary accidental** — reminder accidental in next measure; doesn't change pitch; add via Accidentals palette or Courtesy Accidentals plugin.
- **Voice** — an independent rhythmic layer on a staff (e.g. upper + lower voice in piano left hand).
- **Undo** — Ctrl+Z, virtually unlimited history.

## Mental Models
- Think of **duration first, pitch second** in default mode.
- Think of **Shift+letter** as "stack another note on this chord" (start low, go high).
- Think of **T** as "copy this note's pitch, advance by X duration, connect with a tie."
- Think of **↑/↓** as nudge by semitone (and pick sharp/flat spelling), **Ctrl+↑/↓** as jump by octave.

## Anti-patterns
- **Clicking far above/below the staff for high/low notes** — MuseScore may misread as adjacent staff. Enter an octave closer, then Ctrl+↑/↓.
- **Using slurs when you mean ties** — ties connect same pitches for one combined duration; slurs are legato phrasing across different pitches.
- **Expecting MIDI-typed accidentals to be spelled your way** — select the accidental in toolbar *before* playing the note, or press J after.
- **Forgetting to exit note-input mode (N/Esc)** before copy-paste or navigation — the cursor keeps inserting notes.

## Reference Tables — Core Note-Entry Shortcuts

| Shortcut | Action |
|---|---|
| N | Toggle note input mode |
| 1–9 | Set duration (1=128th … 9=breve) |
| A–G | Enter note at closest octave |
| 0 | Enter rest |
| Shift+A–G | Add chord note above |
| Alt+1…9 | Add interval above selected note |
| ↑ / ↓ | Semitone up/down (sharp/flat spelling) |
| Ctrl+↑ / ↓ | Octave up/down (last entered note) |
| - / + / = | Flat / sharp / natural accidental for next note |
| T | Tie to next same-pitch note |
| J | Respell enharmonic |
| P | Toggle virtual piano keyboard |
| Ctrl+Z | Undo |
| Esc | Exit note input / text edit |

## Worked Example — Enter a Simple Melody
1. Select bar 1. Press **N**.
2. Press **6** (quarter). Type C D E F.
3. Press **5** (eighth). Type G A B C.
4. Press **-** then **B** (B♭). Type A G F.
5. Press **7** (half). Type E.
6. Press **0** (half rest).
7. Press **Esc**.

## Key Takeaways
1. N → duration → pitch/rest is the entire core loop.
2. Shift+letter builds chords from the bottom up.
3. Accidentals are prefixed (-/+/=) or applied post-entry with ↑/↓.
4. Ties = T; slurs are different (see Ch 8).
5. Voices let you layer independent rhythms on one staff.

## Connects To
- **Ch 8**: Articulations, dynamics, slurs (after notes are in).
- **Ch 5**: Multi-staff and instrument changes.
- **Ch 11**: Guitar tab entry; Ch 12: percussion entry.
