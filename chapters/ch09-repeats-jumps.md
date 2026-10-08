# Chapter 9: Repeats, Jumps & Markers

## Core Idea
Repeat barlines (left/right) create local repeats. **Voltas** (1st/2nd endings) are drawn as brackets. **D.C. / D.S.** jumps pair with **Segno / Coda / Fine / To Coda** markers. Playback flow is wired by internal *labels* (defaults work for most scores); toggle *Play repeats* in playback settings to ignore them while auditioning.

## Frameworks Introduced
- **Repeat barlines**: Barlines palette → left/right repeat. A pair (left+right) repeats the enclosed section.
- **Voltas** (1st/2nd endings): Select measures → Repeats & jumps palette → Volta. Edit text/number; Properties controls which repeats play each volta.
- **Jumps** (from Repeats & jumps palette):
  - **D.C.** (da capo) — jump to start.
  - **D.S.** (dal segno) — jump to Segno marker.
  - **D.C. al Fine** — jump to start, play until Fine.
  - **D.S. al Fine** — jump to Segno, play until Fine.
  - **D.C. al Coda** — jump to start, play until "To Coda", then jump to Coda.
  - **D.S. al Coda** — jump to Segno, play until "To Coda", then Coda.
- **Markers**: **Segno**, **Coda**, **Fine**, **To Coda**. Coda/Segno sit at measure start; others at measure end.
- **Label wiring**: Jumps reference marker labels (default: `segno`, `coda`, `codab`). Special labels `start` and `end` bound the score. Most users never need to edit these.
- **Measure / multimeasure repeats**: symbols meaning "repeat previous 1 / 2 / 4 measures"; select the *blank measure after* the repeated section and click the icon.
- **Ignoring repeats in playback**: Playback toolbar cog → uncheck *Play repeats*.

## Key Concepts
- **Volta** — numbered ending bracket (1st time, 2nd time…).
- **Segno / Coda** — signposts; Segno = start-point after D.S., Coda = destination after "To Coda".
- **Fine** — end point after D.C./D.S. al Fine.
- **Label** — internal ID wiring jump→marker; not visible on score.

## Mental Models
- Think of repeats as: draw a box (repeat barlines), number the exits (voltas), then program the long-distance jumps (D.C./D.S. + markers).
- Think of **Play repeats off** as "audition straight through" mode.

## Anti-patterns
- **Mixing up D.C. and D.S.** — D.C. = go to *start*; D.S. = go to *Segno sign*.
- **Forgetting to place the matching marker** — a D.S. with no Segno on the score has nowhere to jump.
- **Editing labels when defaults work** — only touch Properties→labels for non-standard structures.

## Key Takeaways
1. Repeat barlines pair up; voltas number the endings.
2. D.C. → start; D.S. → Segno; pair with Fine or To Coda → Coda.
3. Toggle *Play repeats* off to hear the score straight through.
4. Measure-repeat symbols compress repeated bars in parts.
5. Labels wire playback; defaults work for standard forms.

## Connects To
- **Ch 6**: Barlines and measure numbering.
- **Ch 15**: Volta layout across systems.
