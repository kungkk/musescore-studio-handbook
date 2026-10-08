---
name: musescore-studio-handbook
description: "Knowledge base from the MuseScore Studio 4+ Handbook (handbook.musescore.org). Use when writing or engraving notation in MuseScore, entering notes/lyrics/chords, setting up scores, working with tablature/drum staves, configuring playback, or troubleshooting MuseScore."
---

# MuseScore Studio Handbook
**Source**: https://handbook.musescore.org/ | **Version**: 4.x | **Pages covered**: 149 sections | **Generated**: 2026-10-08

## How to Use This Skill

- **Without arguments** — load core workflows below.
- **With a topic** (e.g. "lyrics", "tab", "dynamics", "repeats") — I find and read the relevant chapter.
- **With chapter** (e.g. `ch04`) — I load that specific chapter file.
- **Browse** — ask "what chapters do you have?" for the full index.

When you ask about a topic not in Core Workflows, I read the relevant chapter file before answering.

---

## Core Workflows

### The note-entry loop
**N** → pick duration (**1–9**; 1=128th … 9=breve) → type pitch (**A–G**) or **0** for rest. **Shift+letter** adds chord tones above. **T** ties to next same-pitch note. **Esc** exits. Accidentals: prefixed `-`/`+`/`=` (flat/sharp/natural), or post-hoc ↑/↓ semitone, Ctrl+↑/↓ octave, **J** enharmonic respell.

### Score setup
**Ctrl+N** → Choose instruments or Create from template → set key/time/tempo/pickup/measure-count → Done. Press **I** or F7 (Layout panel) anytime to add/remove/reorder instruments. **Create a linked staff** pairs notation with tablature.

### Text & markings
- **Ctrl+D** — dynamics popup (type `p`/`mf`/`ff`).
- **<** / **>** — cresc./dim. hairpins (select up to, not including, endpoint).
- **Ctrl+L** — lyrics: `-` = next syllable same word, Space = new word, `_` = melisma.
- **Ctrl+K** — chord symbols (playback accompaniment).
- **Ctrl+M** — rehearsal marks; Ctrl+T staff text; Ctrl+Shift+T system text.

### Instruments
**I** opens the instrument picker. **Linked staff** = notation ↔ tab sync. **System markings** (tempo/rehearsal marks) can be duplicated vertically. Eye = hide (non-destructive); Del = delete.

### Repeats
Repeat barlines pair up; **voltas** number the endings. **D.C.** → start; **D.S.** → Segno; pair with **Fine** or **To Coda → Coda**. Toggle *Play repeats* in playback settings to audition straight through.

### Playback
**Space** plays/pauses. Select a measure → Play to hear only that staff. **M** opens the Mixer: Muse Sounds, SoundFonts, VSTi. Playback speed slider = percentage overlay (doesn't alter score). v4 removed the old Synthesizer panel.

### Layout
**Format→Page settings** → Staff space (sp) is the master scale. **Format→Style→Spacing** controls vertical justification and horizontal density. Lock systems to prevent reflow.

### File export
Save as `.mscz`. Publish→Export → PDF / MusicXML / MIDI / WAV / MP3 / MP4 video. MusicXML = notation interchange; MIDI = notes only.

---

## Chapter Index

| # | Title | Key Topics |
|---|---|---|
| [ch01](chapters/ch01-getting-started.md) | Getting Started | New score, note entry loop, save/export |
| [ch02](chapters/ch02-interface-navigation.md) | Interface & Navigation | Tabs, keyboard nav, Find, braille |
| [ch03](chapters/ch03-score-setup.md) | Score Setup | Instruments, key/time/tempo, parts |
| [ch04](chapters/ch04-note-entry.md) | Note Entry & Editing | Durations, chords, voices, ties |
| [ch05](chapters/ch05-instruments-staves.md) | Instruments & Staves | Layout panel, linked staff, system markings |
| [ch06](chapters/ch06-rhythm-meter.md) | Rhythm & Meter | Time signatures, tuplets, beam groups |
| [ch07](chapters/ch07-pitch-keys.md) | Pitch, Clefs & Keys | Key signatures, transposition, J respell |
| [ch08](chapters/ch08-expressive-markings.md) | Expressive Markings | Dynamics, hairpins, articulations, slurs |
| [ch09](chapters/ch09-repeats-jumps.md) | Repeats & Jumps | Voltas, D.C./D.S., segno/coda/fine |
| [ch10](chapters/ch10-idiomatic-keyboard.md) | Keyboard Notation | Grand staff, pedal lines, cross-staff |
| [ch11](chapters/ch11-idiomatic-guitar.md) | Guitar & Tablature | Tab staff, fretboard, capo, bends |
| [ch12](chapters/ch12-idiomatic-other.md) | Harp & Percussion | Pedage, drumset staff, rolls |
| [ch13](chapters/ch13-alternative-notation.md) | Alternative Notation | Custom staff types, slash notation |
| [ch14](chapters/ch14-text-lyrics.md) | Text, Lyrics & Chords | Lyrics entry, chord symbols, verses |
| [ch15](chapters/ch15-layout-formatting.md) | Layout & Spacing | Page settings, spatium, justification |
| [ch16](chapters/ch16-file-management.md) | File Management | .mscz, export formats, cloud |
| [ch17](chapters/ch17-playback-sound.md) | Playback & Sound | Mixer, Muse Sounds, VSTi, speed |
| [ch18](chapters/ch18-video-export.md) | Video Export | Score-following MP4 |
| [ch19](chapters/ch19-customization.md) | Customization | Preferences, workspaces, plugins |
| [ch20](chapters/ch20-support.md) | Support & Troubleshooting | No sound, crashes, v3→v4 |
| [ch21](chapters/ch21-appendix.md) | Appendix | CLI, shortcuts, upgrade notes, fonts |

## Topic Index

- **Accidentals** → ch04, ch07
- **Braille** → ch02
- **Capo** → ch11
- **Chord symbols** → ch14
- **Clefs** → ch07
- **Cloud save** → ch16
- **Crescendo/diminuendo** → ch08
- **Dynamics** → ch08, ch17
- **Export** → ch16, ch18
- **Fretboard diagrams** → ch11
- **Grand staff** → ch10
- **Hairpins** → ch08
- **Key signatures** → ch07
- **Lyrics** → ch14
- **Measure repeats** → ch09
- **Mixer** → ch17
- **Muse Sounds** → ch17
- **Note entry** → ch04
- **Pedal (piano)** → ch10
- **Percussion** → ch12
- **Plugins** → ch19
- **Preferences** → ch19
- **Rehearsal marks** → ch14
- **Repeats** → ch09
- **Slurs vs ties** → ch08, ch04
- **Spacing** → ch15
- **Staff space (sp)** → ch15
- **Tablature** → ch11
- **Templates** → ch03
- **Tempo** → ch14, ch17
- **Time signatures** → ch06
- **Transposition** → ch07, ch11
- **Tuplets** → ch06
- **Upgrading from v3** → ch20, ch21
- **VSTi** → ch17
- **Voices** → ch04
- **Voltas** → ch09

## Supporting Files

- [glossary.md](glossary.md) — all key terms with chapter references.
- [patterns.md](patterns.md) — reusable techniques and workflows.
- [cheatsheet.md](cheatsheet.md) — one-page shortcuts, decision trees, and fixes.

## Scope & Limits

This skill synthesizes the public MuseScore Studio 4+ Handbook (handbook.musescore.org). It covers notation workflow, not programming MuseScore internals. For plugin development see the Developers' Handbook. For issues, consult the musescore.org support forum.
