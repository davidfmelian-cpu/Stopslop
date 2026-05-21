# Stop Slop

A skill for removing AI tells from prose.

<img width="3840" height="2160" alt="G-Yg4RVbIAAhVxW" src="https://github.com/user-attachments/assets/902afc15-1f40-4a9d-af24-8cd67afb8ebf" />

## What this is

AI writing has patterns. Predictable phrases, structures, rhythms. This skill teaches Claude (or any LLM) to catch and remove them.

## Skill Structure

```
stop-slop/
├── SKILL.md              # Core instructions (English)
├── SKILL.es.md           # Core instructions (Spanish)
├── references/
│   ├── phrases.md        # Phrases to remove (English)
│   ├── phrases.es.md     # Phrases to remove (Spanish)
│   ├── structures.md     # Structural patterns to avoid (English)
│   ├── structures.es.md  # Structural patterns to avoid (Spanish)
│   ├── examples.md       # Before/after transformations (English)
│   └── examples.es.md    # Before/after transformations (Spanish)
├── README.md
└── LICENSE
```

## Quick start

**Claude Code:** Add this folder as a skill.

**Claude Projects:** Upload `SKILL.md` and reference files to project knowledge.

**Custom instructions:** Copy core rules from `SKILL.md`.

**API calls:** Include `SKILL.md` in your system prompt. Reference files load on demand.

## What it catches

**Banned phrases** - Throat-clearing openers, emphasis crutches, business jargon, all adverbs, vague declaratives, meta-commentary. See `references/phrases.md`.

**Structural clichés** - Binary contrasts, negative listings, dramatic fragmentation, rhetorical setups, false agency, narrator-from-a-distance voice, passive voice. See `references/structures.md`.

**Sentence-level rules** - No Wh- sentence starters, no em dashes, no staccato fragmentation, no lazy extremes, active voice required.

## Scoring

Rate 1-10 on each dimension:

| Dimension | Question |
|-----------|----------|
| Directness | Statements or announcements? |
| Rhythm | Varied or metronomic? |
| Trust | Respects reader intelligence? |
| Authenticity | Sounds human? |
| Density | Anything cuttable? |

Below 35/50: revise.

## Versión en castellano

Hay una adaptación al castellano del skill, con frases, estructuras y ejemplos propios del idioma (pasiva refleja, adverbios en -mente, jerga corporativa española, gerundios encadenados, etc.):

- [`SKILL.es.md`](SKILL.es.md) — instrucciones core
- [`references/phrases.es.md`](references/phrases.es.md) — frases a eliminar
- [`references/structures.es.md`](references/structures.es.md) — estructuras a evitar
- [`references/examples.es.md`](references/examples.es.md) — ejemplos antes/después

## Author

[Hardik Pandya](https://hvpandya.com)

## License

MIT. Use freely, share widely.
