# Chapter 15: Layout, Formatting & Spacing

## Core Idea
**Format→Page settings** controls page size/margins/staff space (sp). **Format→Style** controls engraving defaults (spacing, text styles, beams, etc.). MuseScore auto-justifies staves vertically and measures horizontally like a word processor. Lock systems to prevent reflow.

## Frameworks Introduced
- **Page settings** (Format→Page settings):
  - Page size (Letter default in Americas, A4 elsewhere), orientation, margins (15mm default).
  - Two-sided: independent odd/even margins.
  - **Staff space (sp / spatium)**: distance between staff lines; default 1.75mm (7mm staff). Scales nearly everything.
  - First page number; unit (mm/inch).
  - *Apply to all parts*.
- **Vertical spacing** (Format→Style→Spacing):
  - *Enable vertical justification*: staves fill the page evenly.
  - **Factors**: distance between systems (×basic), above/below bracket, above/below brace.
  - Min/max system and staff distances; max grand staff distance; max page fill.
  - *Disable vertical justification*: fixed staff distance, ragged bottom.
- **Horizontal spacing**:
  - **System density** (default 100%): measures per system.
  - **Spacing ratio** (default 1.5): half note takes 1.5× quarter space. 1.0 = equal space; 2.0 = space-time proportional.
- **Lock systems/measures**: right-click a system → Lock; prevents auto-reflow.
- **Style settings** (Format→Style):
  - Text styles, beams, clefs/keys/time signatures, lyrics, dynamics, fretboard diagrams, etc.
  - Save as .mss template.
- **Frames**: horizontal/vertical frames for titles, blank space, images.
- **Measure numbers**: Format→Style → show every N, offset for pickup.

## Key Concepts
- **Staff space (spatium)** — the master scale unit.
- **Vertical justification** — staves spread to fill page height.
- **Spacing ratio** — horizontal space vs duration.
- **Lock** — pin a system/measure against reflow.

## Mental Models
- Think of staff space as "font size for notation" — everything scales from it.
- Think of justification as "word-processor justify" but for staves.

## Anti-patterns
- **Manually dragging every staff** — adjust spacing factors instead; auto-layout does the rest.
- **Forgetting to lock systems before editing** — inserted notes reflow everything.

## Key Takeaways
1. Format→Page settings: staff space (sp) is the master scale.
2. Vertical justification spreads staves; adjust factors in Style.
3. Spacing ratio 1.0 = equal, 2.0 = proportional, 1.5 = default.
4. Lock systems to prevent reflow.
5. Save styles as .mss for reuse.

## Connects To
- **Ch 3**: Score setup.
- **Ch 19**: Customizing styles and workspaces.
