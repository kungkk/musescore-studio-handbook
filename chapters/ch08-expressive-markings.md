# Chapter 8: Expressive Markings

## Core Idea
Dynamics (p, mf, ff) come from the Dynamics palette or **Ctrl+D** popup; hairpins (cresc./dim.) use **<** / **>**. Articulations (staccato, tenuto, accent) are palette clicks on a selected note. Slurs vs ties: slurs = legato phrasing across different pitches; ties = combine same-pitch durations.

## Frameworks Introduced
- **Dynamics**:
  - Add: select note → click Dynamics palette, or **Ctrl+D** popup → type `pp`/`mf`/`ff` → Esc.
  - Drag from dynamic's right handle to chain into a hairpin; release → pick endpoint dynamic.
  - **Voice assignment**: default = all voices. Ctrl+click palette = assign to selected note's voice. Shortcuts: **Ctrl+Alt+1–4** for voices 1–4, **Ctrl+Alt+0** for all.
  - Position: Format→Style→Dynamics & hairpins; voice-1 dynamics go below if single-voice, above if multi-voice; voice 3 above; voices 2/4 below. Grand-staff instruments auto-center between staves.
- **Hairpins (cresc./dim.)**:
  - **<** = crescendo, **>** = diminuendo.
  - Select range *excluding the final note* (hairpin ends just before the next note after the range).
  - Drag height handle to adjust opening width; Properties → Allow diagonal for angled hairpins.
  - Cresc./dim. *text lines* function the same for longer spans.
- **Articulations**: staccato, tenuto, accent, marcatissimo, fermata, etc. Select note → click Articulations palette. Stack multiple on one note.
- **Slurs**: Select a range of notes → Slurs palette (or **S**). Slurs curve across different pitches = legato. Drag endpoints to adjust.
- **Ties**: **T** during note entry connects same-pitch notes; see Ch 4.
- **Grace notes**: Grace notes palette; select a note → add an appoggiatura/acciaccatura before it.
- **Ornaments**: trill, mordent, turn, tremolo — Ornaments palette.
- **Arpeggios & glissandos**: Arpeggio (wavy line) and glissando lines from palette; drag across chord.
- **Breaths & pauses**: comma (breath), fermata; Breaths & pauses palette.
- **Tremolos & rolls**: measured/unmeasured tremolo between notes; rolls on percussion.

## Key Concepts
- **Voice assignment of dynamics** — which voice(s) a dynamic affects in playback.
- **Hairpin range** — select notes *up to but not including* the endpoint.
- **Slur vs tie** — slur = phrasing across pitches; tie = combined duration of same pitch.
- **Grace note** — small-note ornament before a main note.

## Mental Models
- Think of **Ctrl+D** as the "type the dynamic" shortcut.
- Think of **<** and **>** as "open" and "close" hairpins.
- Think of slurs as phrasing curves; ties as duration connectors.

## Anti-patterns
- **Including the endpoint note in a hairpin selection** — the hairpin ends before the next note; don't select it.
- **Using slurs for same-pitch note connections** — that's a tie (T).
- **Expecting dynamics placed on a specific voice to affect all voices** — check voice assignment; Ctrl+click palette to pin to a voice.

## Reference Tables — Expressive Shortcuts

| Item | How |
|---|---|
| Dynamic | Select note → Ctrl+D → type `p`/`mf`/`ff` → Esc |
| Crescendo hairpin | Select range (excl. endpoint) → **<** |
| Diminuendo hairpin | Select range → **>** |
| Articulation | Select note → Articulations palette click |
| Slur | Select note range → Slurs palette / **S** |
| Tie | During entry → **T** |
| Grace note | Select note → Grace notes palette |

## Key Takeaways
1. Ctrl+D opens the dynamic popup; type the letters directly.
2. **<** and **>** insert cresc./dim. hairpins.
3. Slurs = legato phrasing; ties = same-pitch duration.
4. Dynamics default to all voices; Ctrl+click pins to one voice.
5. Select the range up to (not including) the hairpin endpoint.

## Connects To
- **Ch 4**: Ties during note entry.
- **Ch 17**: Dynamics drive playback volume.
- **Ch 14**: Tempo markings and text.
