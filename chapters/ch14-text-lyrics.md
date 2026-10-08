# Chapter 14: Text, Lyrics & Chord Symbols

## Core Idea
Lyrics are entered syllable-by-syllable with **Ctrl+L**: `-` connects syllables in a word, **Space** advances to the next word, `_` draws a melisma line. Multiple verses stack automatically. Chord symbols (Dm7, G7) are added with **Ctrl+K** and play back as guitar/piano voicings.

## Frameworks Introduced
- **Lyrics**:
  - Select start note → **Ctrl+L** (Cmd+L).
  - Type syllable. Then:
    - `-` = next syllable in same word (hyphen drawn).
    - **Space** = new word on next note.
    - `_` = melisma (syllable held over multiple notes; underscore line drawn).
  - Long melisma shortcut: type first syllable → select last note of melisma → press `-` or `_` once; line fills the gap.
  - Rest skip: cursor skips rests; to attach a lyric to a rest, select the rest → Ctrl+L explicitly.
  - Reserved chars: Ctrl+Space = literal space, Ctrl+- = literal hyphen, Ctrl+Shift+- = literal underscore, Ctrl+Return = line break.
  - **Multiple verses**: re-run Ctrl+L; auto-stacks below. Up/Down arrows move between verses.
  - Verse numbers: prefix first syllable with number + Ctrl+Space.
- **Staff / system / expression text**: Add → Text → *Staff text* (Ctrl+T) / *System text* (Ctrl+Shift+T) / *Expression text*. Staff text applies to one staff; system text to all.
- **Tempo markings**: Add → Text → *Tempo marking*. Predefined ♩=BPM values; also set playback tempo.
- **Rehearsal marks**: Add → Text → *Rehearsal mark* (Ctrl+M). Auto-numbers (A, B, C… or 1, 2, 3…).
- **Chord symbols**: Select note → **Ctrl+K** → type chord (`C`, `Dm7`, `G7sus4`, `F#m7b5`) → Esc. Auto-placed above staff; playback uses them in guitar/piano.
- **Figured bass**: Add → Text → *Figured bass* → type numbers.
- **Fingering**: Add → Text → *Fingering* → type 1–5.
- **Header / footer**: File → Project properties or Format → Style → Header/Footer.
- **Text blocks** (frames): Add → Text → *Text frame* for title pages.

## Key Concepts
- **Melisma** — one syllable stretched over multiple notes.
- **Verse** — stacked lyric line; verse 1 on top.
- **Chord symbol** — harmonic shorthand (e.g. Cmaj7); drives playback accompaniment.
- **Staff text vs system text** — staff = one instrument; system = all instruments.

## Mental Models
- Think of `-` as "next syllable, same word" and Space as "next word."
- Think of `_` as "hold this syllable under a long note."
- Think of chord symbols as *playable* harmony, not just labels.

## Anti-patterns
- **Typing hyphens/spaces literally inside syllables** — they trigger navigation; use Ctrl+Space / Ctrl+-.
- **Forgetting to re-run Ctrl+L for verse 2** — lyrics don't auto-create new verses.
- **Using staff text for instructions meant for all instruments** — use system text.

## Reference Tables — Text Shortcuts

| Item | Shortcut |
|---|---|
| Lyrics | Select note → Ctrl+L |
| Chord symbol | Select note → Ctrl+K |
| Staff text | Ctrl+T |
| System text | Ctrl+Shift+T |
| Rehearsal mark | Ctrl+M |
| Tempo marking | Add → Text → Tempo marking |
| Fingering | Add → Text → Fingering |

## Key Takeaways
1. Ctrl+L starts lyrics; `-` = word-internal, Space = new word, `_` = melisma.
2. Re-run Ctrl+L for each verse; they stack.
3. Ctrl+K adds chord symbols that drive playback.
4. Staff text = one instrument; system text = all.
5. Rehearsal marks (Ctrl+M) auto-number.

## Connects To
- **Ch 8**: Expressive markings pair with text.
- **Ch 11**: Guitar chord symbols pair with fretboard diagrams.
- **Ch 17**: Chord symbols drive playback accompaniment.
