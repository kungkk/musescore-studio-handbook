# Chapter 16: File Management & Export

## Core Idea
Native format is **.mscz** (compressed, includes audio/soundfont references). Export to PDF, MusicXML, MIDI, audio (WAV/MP3/FLAC), image (PNG/SVG), or video. Cloud save to musescore.com with visibility control.

## Frameworks Introduced
- **Formats**:
  - **.mscz** — native, compressed score file (recommended).
  - **.mscx** — uncompressed XML (for version control / diff).
  - **.mss** — style template.
- **Open/Import**:
  - File→Open (.mscz/.mscx).
  - Import: MusicXML (.musicxml/.xml), MIDI (.mid/.midi), older MuseScore (.mscz 3.x/2.x), CapXML, Bagpipe Music Writer.
- **Save / Save As**:
  - File→Save (Ctrl+S) — local .mscz.
  - File→Save to Cloud — musescore.com; visibility Private/Unlisted/Public.
- **Export** (Publish→Export):
  - **PDF** — print.
  - **MusicXML** — interchange with other notation software.
  - **MIDI** — playback data.
  - **Audio**: WAV, MP3, FLAC, OGG.
  - **Image**: PNG, SVG.
  - Options: choose parts, combine/split files.
- **Project Properties**: title, composer, copyright, etc.
- **Cloud publishing**: Publish tab → share link; publicly posted scores show on musescore.com.

## Key Concepts
- **.mscz** — native compressed format.
- **MusicXML** — notation interchange.
- **Cloud visibility**: Private / Unlisted / Public.

## Mental Models
- Think of .mscz as "save file," PDF/MusicXML/MIDI as "export formats."
- Think of Cloud as backup + sharing.

## Anti-patterns
- **Editing a .pdf directly** — PDF is export-only; edit .mscz.
- **Expecting MIDI to preserve engraving** — MIDI is notes only; use MusicXML for notation.

## Key Takeaways
1. Save as .mscz; export PDF/MusicXML/MIDI/audio on demand.
2. MusicXML = notation interchange; MIDI = notes only.
3. Cloud save controls visibility (Private/Unlisted/Public).
4. Import MusicXML/MIDI/older MuseScore files.
5. Project Properties store metadata.

## Connects To
- **Ch 1**: Saving first score.
- **Ch 18**: Video export.
