# Chapter 2: Interface, Navigation & Accessibility

## Core Idea
The MuseScore Studio workspace is three tabs — **Home / Score / Publish** — and the Score tab has a left sidebar (Palettes, Properties, Instruments), a central score view, a top note-input toolbar, and a bottom status bar. Master keyboard navigation (`Arrows`, `Ctrl+Arrows`, `Alt+Arrows`, `F6`, `Ctrl+F`) is the fastest way to move around.

## Frameworks Introduced
- **Three-tab model**: Home (account, scores, plugins, learn) | Score (notation workbench) | Publish (print/export/share clutter-free).
- **Score-tab regions**: Parts button, Mixer button, Playback toolbar, Note-input toolbar, Left sidebar, Score view, Status bar. Press **Tab / F6** to cycle regions; arrows move within.
- **View modes** (status-bar popup): Page view | Continuous horizontal | Continuous vertical. Use Page for print preview; Continuous for fast editing.
- **Find / Go-to** (Ctrl+F): type a bare number = measure; `pXX` = page; `rXX` = numeric rehearsal mark; text = alphabetic rehearsal mark.
- **Navigator** (View→Navigator): page thumbnails; drag the blue box to pan.
- **Timeline** (bottom strip): meta rows (key/time sig, tempo, rehearsal marks, jumps) + per-instrument grid; click cells to jump; eye icon toggles staff visibility.
- **Braille panel** (Preferences→Braille→Show braille panel): live braille of current measure; Perkins-style 6-key input with **F D S / J K L** = dots 1–3 / 4–6; **N** toggles braille input mode.

## Key Concepts
- **Print vs braille**: "print" = ordinary staff notation.
- **Range selection**: Shift+←/→ to select a span, then Shift+F10 for context menu (Measure/Staff/Part properties).
- **Concert vs transposed pitch view** — toggle in status bar.
- **Screen readers**: NVDA on Windows, VoiceOver on macOS (disable Quick Nav, set Mouse Pointer→Ignores VoiceOver cursor), Orca on Linux. JAWS support is partial.

## Mental Models
- Think of **Right/Left** as "next/previous chord-or-rest"; **Ctrl+Right/Left** as "next/previous measure"; **Alt+Right/Left** as "next/previous *any* element" (articulations, barlines, hairpins…).
- Think of **Alt+Up/Down** as "walk the voices/staves" within a chord.
- **Ctrl+Home/End** = jump to first/last element.
- **Ctrl+0** = reset zoom to 100%.

## Anti-patterns
- **Naming rehearsal marks "R1", "p3"** — the Find parser confuses them with page/rehearsal syntax. Avoid single letters R/r/P/p + digits.
- **Forgetting to start the screen reader before launching MuseScore on Linux** — accessibility features stay disabled; relaunch.
- **Editing in a text frame and pressing arrows expecting score navigation** — press **Esc** first to leave text-edit mode.

## Reference Tables — Navigation Shortcuts

| Shortcut | Action |
|---|---|
| F6 / ` / Shift+F6 | Move between UI sections |
| Tab / Shift+Tab | Move between control groups |
| ↑↓←→ | Move within group / next note chord |
| Ctrl+←→ | Jump by measure |
| Alt+←→ | Next/previous *any* element |
| Alt+↑↓ | Move up/down to other voice/staff |
| Ctrl+Home / End | First / last element |
| F2 or Alt+Shift+E | Edit selected element (like double-click) |
| Shift+F10 / Menu key | Context menu for selection |
| Ctrl+F | Find / Go to measure, page (`p3`), rehearsal mark (`r5`) |
| Ctrl++ / Ctrl+- / Ctrl+0 | Zoom in / out / reset 100% |
| Shift+scroll | Pan horizontally |
| Ctrl+scroll | Zoom |

## Key Takeaways
1. The Score tab is where you live; Home creates files, Publish exports them.
2. Arrows = chords; Ctrl+Arrows = measures; Alt+Arrows = any element; Alt+↑↓ = voices/staves.
3. Ctrl+F with measure number, `p` + page, `r` + rehearsal number beats scrolling.
4. Braille input uses F-D-S / J-K-L as dots 1-3 / 4-6; N toggles input mode.
5. UI navigation keys (F6, Tab, arrows) are fixed and cannot be rebound.

## Connects To
- **Ch 4**: Note input toolbar details.
- **Ch 15**: Page vs continuous view effects on layout.
- **Ch 19**: Customizing workspaces and rearranging panels.
