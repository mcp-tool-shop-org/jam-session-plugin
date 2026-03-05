---
title: Getting Started
description: Install jam-session-plugin and play your first song.
sidebar:
  order: 1
---

## Install

Add the plugin to Claude Code:

```bash
claude plugin add ai-jam-session
```

The MCP server is fetched automatically via npx the first time you use a command. No separate install step needed.

## Requirements

- **Node.js 18+** -- the MCP server runs on Node
- **Speakers or headphones** -- audio plays through your system's default output
- **Claude Code** -- the plugin runs inside Claude Code sessions

## Quick start

### Browse the library

```
/ai-jam-session:explore jazz
```

Shows all jazz songs with title, composer, difficulty, and measure count. Try `explore beginner classical` or `explore blues` to narrow results.

### Learn a song

```
/ai-jam-session:teach moonlight-sonata-mvt1
```

Starts a structured teaching session: song analysis, teaching goals, key moments, and a practice plan. The piano-teacher agent walks you through the piece step by step.

### Get a practice plan

```
/ai-jam-session:practice let-it-be beginner
```

Returns a personalized practice configuration with recommended tempo, playback mode, and a progression path. Includes trouble-spot detection and sing-along warmup suggestions.

### Start a jam

```
/ai-jam-session:jam autumn-leaves as blues
```

Claude pulls up the chord map and melody skeleton, suggests creative directions, composes a new interpretation, and plays it back. The jam-musician agent keeps the vibe loose and experimental.

## Natural language works too

You do not have to memorize slash commands. These all work:

- "Show me some beginner jazz songs"
- "Teach me Fur Elise"
- "Let's jam on some blues"
- "I want to practice Clair de Lune at a slow tempo"

Claude figures out which skill and tools to use from context.
