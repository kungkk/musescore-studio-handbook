# musescore-studio-handbook

An agent skill that distills the [MuseScore Studio Handbook](https://handbook.musescore.org/) (v4+) into actionable, on-demand reference for any AI agent that supports the Agent Skills format.

Use it when writing or engraving notation in MuseScore Studio: entering notes/lyrics/chords, setting up scores, working with guitar tablature or drum staves, configuring playback, or troubleshooting.

## What's inside

```
musescore-studio-handbook/
├── SKILL.md              # core workflows + chapter index + topic index
├── glossary.md           # all key terms, referenced by chapter
├── patterns.md           # reusable techniques and workflows
├── cheatsheet.md         # one-page shortcuts, decision trees, fixes
└── chapters/             # 21 on-demand chapter files
    ├── ch01-getting-started.md
    ├── ch02-interface-navigation.md
    ├── ch03-score-setup.md
    ├── ch04-note-entry.md
    ├── ch05-instruments-staves.md
    ├── ch06-rhythm-meter.md
    ├── ch07-pitch-keys.md
    ├── ch08-expressive-markings.md
    ├── ch09-repeats-jumps.md
    ├── ch10-idiomatic-keyboard.md
    ├── ch11-idiomatic-guitar.md
    ├── ch12-idiomatic-other.md
    ├── ch13-alternative-notation.md
    ├── ch14-text-lyrics.md
    ├── ch15-layout-formatting.md
    ├── ch16-file-management.md
    ├── ch17-playback-sound.md
    ├── ch18-video-export.md
    ├── ch19-customization.md
    ├── ch20-support.md
    └── ch21-appendix.md
```

## Install

On any Agent-Skills-compatible host:

```bash
npx skills add https://github.com/<your-username>/musescore-studio-handbook --skill musescore-studio-handbook
```

Or clone into your personal skills directory:

```bash
git clone https://github.com/<your-username>/musescore-studio-handbook ~/.agents/skills/musescore-studio-handbook
```

## Usage

Ask your agent anything MuseScore-related:

- "How do I enter lyrics in MuseScore?"
- "Set up a guitar tab staff paired with standard notation."
- "What's the difference between a slur and a tie?"
- "D.S. al Coda — how do I notate that?"
- "Why is there no Synthesizer panel in MuseScore 4?"

The agent loads the relevant chapter file on demand.

## Source & License

This skill is a synthesized, distilled reference — not a copy of the original handbook text. It is derived from the public [MuseScore Studio Handbook](https://handbook.musescore.org/), © MuseScore Limited and contributors, licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

Per the ShareAlike term, this derivative work is also released under **CC BY-SA 4.0**:

[![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

You are free to share and adapt this skill, provided you give appropriate credit to the original MuseScore Handbook, indicate changes, and distribute your contributions under the same license.

## Acknowledgements

Built with [book-to-skill](https://github.com/virgiliojr94/book-to-skill).
