# PianoAI — Claude Code Plugin

AI piano player with a 100-song library, structured teaching, and jam sessions. Plays through your speakers — no external software required.

This plugin wraps the [PianoAI](https://github.com/mcp-tool-shop-org/ai_jam_session) MCP server, adding slash commands, agent personalities, and structured workflows for learning and jamming.

## Install

```bash
claude plugin add pianoai
```

The MCP server (`@mcptoolshop/pianoai`) is fetched automatically via npx. Requires Node.js 18+.

## What You Get

### Skills (slash commands)

| Command | Description |
|---------|-------------|
| `/pianoai:teach <song>` | Start a structured teaching session |
| `/pianoai:practice <song> [level]` | Get a personalized practice plan |
| `/pianoai:explore [query]` | Browse the 100-song library by genre, difficulty, or keyword |
| `/pianoai:jam <song or genre>` | Start a jam session — Claude creates its own interpretation |

### Agents

| Agent | Description |
|-------|-------------|
| `piano-teacher` | Patient, pedagogical teacher who meets students where they are |
| `jam-musician` | Laid-back jam band musician — groove-first, encourages experimentation |

### MCP Tools (15)

Browse, play, teach, jam, and manage songs. The plugin's skills orchestrate these tools automatically, but they're also available for direct use.

## Usage

Use slash commands:

```
/pianoai:explore jazz
/pianoai:teach moonlight-sonata-mvt1
/pianoai:practice let-it-be beginner
/pianoai:jam autumn-leaves as blues
/pianoai:jam jazz
```

Or just talk naturally — the agents activate based on context:

```
I want to learn a beginner jazz song on piano.
Help me practice Fur Elise at half speed.
Let's jam on some blues.
```

## Song Library

100 built-in songs across 10 genres (classical, jazz, pop, blues, rock, R&B, latin, film, ragtime, new-age) at beginner, intermediate, and advanced levels.

## Requirements

- Node.js 18+
- Speakers (the piano plays through your system audio)

## Links

- MCP server: [@mcptoolshop/pianoai](https://www.npmjs.com/package/@mcptoolshop/pianoai)
- Source: [mcp-tool-shop-org/ai_jam_session](https://github.com/mcp-tool-shop-org/ai_jam_session)

## License

MIT
