# The Smaller Infinity — Claude Code Plugin

Read, search, and explore *The Smaller Infinity* with your own Claude.

## Install

In Claude Code:

```
/plugin marketplace add jeremedia/smaller-infinity-plugin
/plugin install smaller-infinity@smaller-infinity
```

## What You Get

30+ read-only tools for interacting with the book:

- **Read** any chapter, part, or the full book
- **Search** by text or semantic similarity
- **Explore** revision history, releases, annotations, and discussions
- **Analyze** editorial metadata, concept dependencies, reading paths, and glossary consistency
- **Brief** — one-call session start with open discussions, pending proposals, stale metadata, and manuscript stats

## Authenticated Mode

With an API key or OAuth, you get additional write tools:

- **create_annotation** — anchor notes, questions, connections, or corrections to specific text
- **create_discussion** — start threaded discussions on chapters
- **reply_to_discussion** — continue existing discussions
- **resolve_discussion** — resolve, close, reopen, or wontfix discussions
- **create_edit_proposal** — propose text changes (triggers AI review)
- **create_tooling_request** — request new tools or improvements when you hit a gap

Use `/smaller-infinity:about` for the full tools reference.

### Setup

**Option A: OAuth (claude.ai)** — Configure the MCP server in Claude.ai settings. OAuth handles authentication automatically via passkey login.

**Option B: API Key (Claude Code)** — For CLI usage:

1. Create an account at [smallerinfinity.app](https://smallerinfinity.app)
2. Generate an API key at [smallerinfinity.app/settings](https://smallerinfinity.app/settings)
3. Edit your `.mcp.json` to add the auth header:

```json
{
  "mcpServers": {
    "smaller-infinity": {
      "type": "http",
      "url": "https://smallerinfinity.app/mcp",
      "headers": {
        "Authorization": "Bearer si_YOUR_KEY_HERE"
      }
    }
  }
}
```

## Quick Start

After installing, ask Claude:

- "What does the book argue about literacy?"
- "Read the table of contents"
- "Search for 'shaped unshaped'"
- "What are the editorial voice conventions?"

## About the Book

*The Smaller Infinity* is a book about what happens when language learns to speak back. It explores how language models are transforming literacy itself, through essays, model-voice chapters, and personal narrative.

Read it in the browser at [smallerinfinity.app](https://smallerinfinity.app).
