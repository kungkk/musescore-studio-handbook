# Chapter 19: Customization — Preferences, Workspaces & Plugins

## Core Idea
**Preferences** (Ctrl+,) sets global behavior: language, theme, audio devices, note-input defaults. **Workspaces** save panel/toolbar layouts. **Plugins** (QML) extend functionality; manage from Home→Plugins or Plugins→Manage plugins.

## Frameworks Introduced
- **Preferences** (Edit→Preferences, Ctrl+,):
  - **General**: language, autosave interval, program-start behavior, user folders.
  - **Appearance**: light/dark/high-contrast theme, accent color, UI font, score paper/background, invert score.
  - **Canvas**: default zoom, mouse zoom precision, scroll direction, selection precision.
  - **Save & publish**: autosave duration, musescore.com/audio.com defaults.
  - **Note input**: advance-on-key-release, color notes outside range, play notes on edit, voice assignment for dynamics.
  - **Score**: default instrument order, default styles.
  - **Audio & MIDI**: audio device, buffer size, sample rate, MIDI in/out, mixer behavior.
  - **MIDI mappings**: map external MIDI keys to actions.
  - **Import**: MusicXML, MIDI, etc.
- **Workspaces**: View→Workspaces. Save/load panel layouts; switch between editing/engraving/part layouts.
- **Templates & styles**: Save a score as a template; load/save .mss style files.
- **Palettes customization**: right-click palettes to add/remove/reorder symbols.
- **Keyboard shortcuts**: Preferences→Shortcuts; search by action; remap.
- **Plugins**:
  - Home→Plugins or Plugins→Manage plugins.
  - Enable/disable pre-installed: Color Notes, Courtesy Accidentals, Lilypond Lyrics, Mirror Intervals, Note Names, Retrograde, Tuning & temperaments.
  - Install: drop .qml files into `Documents/MuseScore4/Plugins/` (configurable in Preferences→Folders).
  - Assign shortcuts: Manage plugins → select → Edit shortcut.
  - **Warning**: third-party plugins are unvetted; download from trusted authors.

## Key Concepts
- **Workspace** — saved panel/toolbar arrangement.
- **Style file (.mss)** — reusable engraving defaults.
- **Template** — starter score with instruments/layout pre-wired.
- **Plugin** — QML script extending MuseScore.

## Mental Models
- Think of Preferences as "global settings," Workspaces as "window layouts," Templates as "starter files."
- Think of plugins as opt-in extensions — enable only what you trust.

## Anti-patterns
- **Installing random .qml plugins without reading the code** — they run with your user privileges.
- **Editing a style directly on a score when you want it reused** — save as .mss and load into new scores.
- **Confusing Preferences (global) with Properties (per-object)** — Ctrl+, is global; left sidebar Properties is per-selected-element.

## Key Takeaways
1. Ctrl+, opens Preferences; sections cover language, theme, audio, note input.
2. Workspaces save panel layouts; switch for editing vs engraving.
3. Plugins live in Documents/MuseScore4/Plugins/; enable from Home→Plugins.
4. Remap shortcuts in Preferences→Shortcuts.
5. Save styles as .mss for reuse across scores.

## Connects To
- **Ch 2**: Interface and panel layout.
- **Ch 15**: Style and formatting defaults.
- **Ch 17**: Audio & MIDI device settings.
