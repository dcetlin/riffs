# riffs

Dan's voice notes, riffs, and thinking-in-progress — cleaned transcriptions and synthesized frameworks.

## Structure

### `voice-notes/`
Cleaned transcriptions of voice notes, dated markdown files. Each file represents a single riff or thinking session, lightly edited for readability while preserving the original register and load-bearing vocabulary.

### `frameworks/`
Synthesized frameworks distilled from voice notes. These are more structured artifacts — models, vocabularies, conceptual architectures — drawn from patterns across multiple riffs.

## Frontmatter Schema

All documents use the following frontmatter fields:

```yaml
---
title: ""
date: YYYY-MM-DD
type: learning | philosophy | design | practice | other
duration_min: ~N         # approximate duration of source voice note
blog_candidate: true|false
philosophy_engine: true|false  # feeds the philosophy/vocabulary system
vocabulary_seeds:
  - term one
  - term two
source: voice-note | essay | conversation | synthesis
cleaned: true|false
---
```

### Field notes

- **`blog_candidate`** — worth developing into a public post
- **`philosophy_engine`** — contributes vocabulary or conceptual structure to the evolving framework
- **`vocabulary_seeds`** — load-bearing terms introduced or refined in this document; feeds the vocabulary reference
