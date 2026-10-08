# Chapter 7: Pitch — Clefs, Key Signatures & Transposition

## Core Idea
Clefs, key signatures, and accidentals are all palette-driven. Key signatures are *sounding-pitch* — when writing for transposing instruments, apply the sounding key, not the written one. **Transpose** (Tools menu) shifts selected music by interval. **J** respells enharmonics.

## Frameworks Introduced
- **Clefs**: Clefs palette; drag onto a note/staff. Mid-score clef changes are supported. Staff/Part properties → change default clef.
- **Key signatures**:
  - Add: select measure/note → click Key signatures palette. Changes at measure start (or mid-measure on a note).
  - Delete: select → Del. **Cannot delete the opening key signature** — replace it from the palette.
  - **Local key signature**: Ctrl+click — per-staff, can be placed mid-measure.
  - **Open/atonal key signature**: for French horn, timpani; looks like C major but ignores transposition.
  - **Courtesy key signatures**: at system breaks; toggle in Format→Style.
  - **Transposing instruments caveat**: key signatures are *sounding pitch*. For a B♭ clarinet playing written D major, apply **C major** (clarinet reads a whole step above pitch).
- **Custom key signature**: palette → More → Create key signature; drag accidentals onto the staff; Ctrl+drag to reorder.
- **Key signature mode**: select → Properties → Mode dropdown (Major/minor/Dorian/etc.) — exported to MusicXML; not used for playback.
- **Transposition**: Tools→Transpose → choose key or interval up/down; options for transposing keys/chords.
- **Enharmonic respell**: select a note → **J** toggles spelling (e.g. C♯ ↔ D♭).
- **Noteheads**: palette of notehead shapes (normal, diamond, cross, slash, cluster); applied per-note.
- **Octave lines**: 8va / 8vb lines from Lines palette; drag to set extent.
- **Ambitus**: range marking at start of staff; add from palette.

## Key Concepts
- **Sounding pitch vs written pitch** — key signatures are always sounding; concert-pitch toggle in status bar.
- **Open/atonal key signature** — no sharps/flats, unaffected by transposition.
- **Courtesy accidental / key signature** — reminder at system break.
- **Enharmonic spelling** — C♯ vs D♭ sound identical but notate differently.

## Mental Models
- Think of key signatures as "the key the music sounds in," not what the player reads.
- Think of **J** as the "swap spelling" button.
- Think of transposition as a bulk operation on selected music, not a staff property.

## Anti-patterns
- **Applying a written key signature to a transposing instrument part** — always apply sounding pitch; the part auto-transposes.
- **Trying to delete the opening key signature** — replace it from the palette instead.
- **Using accidentals when you mean a key signature change** — mid-measure accidentals only affect those notes; a key signature change re-keys the staff.

## Reference Tables — Pitch Operations

| Task | How |
|---|---|
| Change clef | Clefs palette → drag onto staff/note |
| Add key signature | Key signatures palette → click/drag |
| Local (per-staff) key | Ctrl+click palette item |
| Open/atonal key | Local key signature → open/atonal type |
| Transpose selection | Tools → Transpose |
| Respell enharmonic | Select note → **J** |
| Change notehead shape | Noteheads palette |
| 8va / 8vb line | Lines palette → drag |

## Key Takeaways
1. Key signatures are *sounding pitch* — transposing instrument parts auto-shift.
2. Cannot delete the opening key signature; replace it.
3. J toggles enharmonic spelling.
4. Ctrl+click gives local (per-staff) key signatures.
5. Open/atonal keys (horn, timpani) ignore transposition.

## Connects To
- **Ch 4**: Accidentals during note entry.
- **Ch 5**: Instrument transposition settings.
- **Ch 11**: Guitar capo uses transposition under the hood.
