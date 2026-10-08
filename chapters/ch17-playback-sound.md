# Chapter 17: Playback, Sound & MIDI

## Core Idea
The playback toolbar (top right) controls Play/Rewind/Loop/Metronome. The **Mixer** panel (M button or toolbar button) controls per-instrument sound, volume, pan, and lets you switch between **Muse Sounds**, **SoundFonts**, and **VSTi** plugins. Playback speed is a percentage overlay that preserves all notated tempo relationships.

## Frameworks Introduced
- **Playback toolbar**:
  - **Rewind** — jump to start (or loop start).
  - **Play / Pause** (Space).
  - **Toggle loop playback** — select a range → loop button.
  - **Metronome** — ticks during playback; volume controlled in Mixer.
  - **Playback settings cog** — *Play repeats*, *Enable MIDI input*, *MIDI input pitch* (written vs sounding).
  - **Position counters** — time and measure:beat; click to jump.
  - **Playback speed** — percentage slider; preserves notated tempo relationships.
- **Play only selected staves**: Select a measure (or Shift+click across staves) → Play. MuseScore plays only the selected instruments.
- **Mixer panel** (M):
  - Per-instrument channels: mute, solo, volume, pan.
  - Sound selector: Muse Sounds (sample libraries, separate download), SoundFont (.sf2/.sf3), VSTi.
  - Effects sends (VST effects).
  - Metronome channel.
  - v4 removed the old Synthesizer panel — sounds are saved per-score.
- **Muse Sounds**: high-quality sample libraries; install via MuseHub.
- **SoundFonts**: .sf2/.sf3 files; load in Mixer.
- **VSTi / VST effects**: load Windows VST plugins; SFZ playback recommended via free VST samplers (Sfizz, Sforzando).
- **Sound flags**: per-note playback overrides (e.g. force staccato, disable tremolo) via Properties.
- **Swing playback**: toggle swing feel in Playback settings.
- **Working with MIDI**: MIDI keyboard input; map keys in Preferences→MIDI mappings.

## Key Concepts
- **Muse Sounds** — MuseScore's own sample libraries.
- **SoundFont** — .sf2/.sf3 sample bank.
- **VSTi** — Virtual instrument plugin.
- **Playback speed overlay** — percentage that scales all tempi uniformly.
- **Per-staff playback** — select measures to audition only those instruments.

## Mental Models
- Think of the Mixer as the DAW console: mute/solo/volume/pan per track.
- Think of playback speed as "rehearsal tempo" — slows everything down uniformly.
- Think of *Play repeats* toggle as "audition straight vs. with repeats."

## Anti-patterns
- **Looking for the v3 Synthesizer panel** — it's gone; all per-score sounds live in the Mixer.
- **Expecting SFZ files to play natively** — load them in a VST sampler (Sfizz, Sforzando).
- **Changing playback speed expecting it to print on the score** — it's an audition overlay, not a tempo marking.

## Reference Tables — Playback Controls

| Control | How |
|---|---|
| Play / Pause | Space |
| Rewind | Toolbar button |
| Loop selected range | Select range → Toggle loop |
| Metronome | Toolbar button |
| Play only selected staves | Select measure(s) → Play |
| Playback speed slider | Playback speed button → drag |
| Open Mixer | M or toolbar Mixer button |
| Toggle play repeats | Playback settings cog |

## Key Takeaways
1. Space plays/pauses; select measures to audition only those staves.
2. Mixer (M) is the one-stop sound board: Muse Sounds, SoundFonts, VSTi.
3. Playback speed is a percentage overlay; doesn't alter the score.
4. v4 removed the Synthesizer panel; sounds are per-score.
5. MIDI input pitch: choose written vs sounding for transposing instruments.

## Connects To
- **Ch 8**: Dynamics drive playback volume.
- **Ch 14**: Tempo markings set notated BPM.
- **Ch 19**: Preferences→Audio & MIDI configures devices.
