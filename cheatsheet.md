# Cheatsheet — MuseScore Studio Decision Guide

## Core Shortcuts

| Action | Shortcut |
|---|---|
| New score | Ctrl+N |
| Save / Save As | Ctrl+S / Ctrl+Shift+S |
| Note input mode | N |
| Duration (128th→breve) | 1–9 |
| Rest | 0 |
| Chord note (add above) | Shift+letter |
| Tie | T |
| Octave up/down | Ctrl+↑/↓ |
| Enharmonic respell | J |
| Dynamic | Ctrl+D |
| Crescendo / diminuendo | `<` / `>` |
| Slur | S |
| Lyrics | Ctrl+L |
| Chord symbol | Ctrl+K |
| Staff text / System text | Ctrl+T / Ctrl+Shift+T |
| Rehearsal mark | Ctrl+M |
| Open instruments dialog | I |
| Open Mixer | M |
| Play / Pause | Space |
| Find / Go to measure | Ctrl+F |
| Preferences | Ctrl+, |
| Undo | Ctrl+Z |

## Note-Entry Decision Tree

1. **Select start note/measure** → press **N**.
2. **Pick duration** (1–9).
3. **Type pitch** (A–G) or **0** (rest).
4. Chord? → **Shift+letter** for upper voices.
5. Need accidental? → prefix `-`/`+`/`=` or post-hoc ↑/↓.
6. Tie to next? → **T**.
7. Done? → **Esc**.

## When to Use Which Text

| Need | Use | Shortcut |
|---|---|---|
| Lyrics | Lyrics | Ctrl+L |
| Chord symbols | Chord symbol | Ctrl+K |
| Rehearsal mark | Rehearsal mark | Ctrl+M |
| Tempo | Tempo marking | Add→Text |
| Instruction to one player | Staff text | Ctrl+T |
| Instruction to all | System text | Ctrl+Shift+T |
| Finger number | Fingering | Add→Text |

## Playback Toggles

- **No sound?** → Check Mixer (M), audio device (Preferences→Audio & MIDI), Muse Sounds installed.
- **Want to skip repeats?** → Playback settings cog → uncheck Play repeats.
- **Want slower rehearsal?** → Playback speed slider (percentage overlay).
- **Hear only one staff?** → Select its measure → Play.

## Common Mistakes

| Symptom | Likely cause | Fix |
|---|---|---|
| Notes inserted unexpectedly | Still in note-input mode | Press Esc or N |
| Layout reflows after edit | System not locked | Right-click system → Lock |
| Old score looks different after v4 upgrade | v4 re-engraves | Adjust spacing; expected |
| No Synthesizer panel | Removed in v4 | Use Mixer (M) |
| Dynamics on wrong voice | Default = all voices | Ctrl+click palette to pin voice |
| Hairpin too long | Endpoint note selected | Select up to (not including) endpoint |

## File Formats

| Task | Format |
|---|---|
| Save working file | .mscz |
| Print | PDF |
| Send to Sibelius/Finale | MusicXML |
| Import to DAW | MIDI |
| Audio export | WAV / MP3 / FLAC |
| Video | MP4 (Publish→Export) |
| Reuse style | .mss |
