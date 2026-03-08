---
name: about
description: Learn about The Smaller Infinity and the tools available for reading, searching, and exploring the book.
---

# The Smaller Infinity

A book about what happens when language learns to speak back.

## Thesis

Literacy reshaped every human institution it touched. Now language models are doing the same thing to literacy itself. This book asks: what happens when the technology of reading and writing becomes a participant in the conversation rather than just the medium?

The core argument moves through the concept of *shaped/unshaped* — the idea that language is where the loop learned to watch itself. The book explores this through essays, model-voice chapters (written by Claude), and personal narrative.

## Structure

The book has 5 main parts plus standalone sections:

- **How to Read This Book** — orientation
- **Prologue** — entry point
- **Part 1** — foundations
- **Part 2** — development
- **Not a Shape, But a Fold** — standalone
- **Part 3** — deepening
- **Part 4a & 4b** — the turn
- **Part 5** — resolution
- **Vision & Will** — standalone
- **Coda** — closing

Use `read_toc` to see all chapters with word counts and version numbers.

## Available Tools (22)

### Reading
- `read_toc` — Table of contents with slugs, word counts, versions
- `read_chapter` — Read a single chapter by slug
- `read_chapters` — Read multiple chapters at once (up to 8)
- `read_part` — Read all chapters in a book part
- `read_full_book` — Complete book text in order

### Searching
- `search_book` — Text search across all chapters
- `search_annotations` — Semantic search across annotations

### History
- `list_versions` — Version history for a chapter
- `diff_versions` — Compare two consecutive versions

### Releases & Annotations
- `list_releases` — Published book releases
- `list_release_comments` — Comments on a release
- `diff_releases` — Compare two releases
- `list_annotations` — Browse annotations by chapter, user, or type

### Editorial Analysis
- `editorial_guide` — Style rules, voice conventions, thematic threads
- `editorial_map` — All chapters' editorial metadata at a glance
- `query_editorial_map` — Filter chapters by metadata values
- `stale_metadata` — Chapters with changed text since last annotation
- `count_text` — Count exact string occurrences across the book
- `validate_assumes` — Check concept dependency ordering
- `glossary_sync` — Reconcile glossary against term usage

### Model Encounters
- `list_model_encounters` — Models' first encounters with the book
- `read_model_encounter` — Read a specific model's first encounter

## Getting Started

```
read_toc()                          # See the full structure
read_chapter(slug: "the-smaller-infinity")  # Read the title chapter
search_book(query: "shaped unshaped")       # Find where concepts appear
editorial_guide(focus: "voice")             # Understand the voice conventions
```

## More Information

Visit [smallerinfinity.app](https://smallerinfinity.app) to read the book in the browser.
