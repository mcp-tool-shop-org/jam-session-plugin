# PianoAI — Claude Code Plugin

AI piano player with a 100-song library, structured teaching, and jam sessions. Plays through your speakers — no external software required.

This plugin wraps the [PianoAI](https://github.com/mcp-tool-shop-org/ai_jam_session) MCP server, adding slash commands, agent personalities, and structured workflows for learning and jamming.

## Install

```bash
claude plugin add ai-jam-session
```

The MCP server (`@mcptoolshop/ai_jam_session`) is fetched automatically via npx. Requires Node.js 18+.

## What You Get

### Skills (slash commands)

| Command | Description |
|---------|-------------|
| `/ai-jam-session:teach <song>` | Start a structured teaching session |
| `/ai-jam-session:practice <song> [level]` | Get a personalized practice plan |
| `/ai-jam-session:explore [query]` | Browse the 100-song library by genre, difficulty, or keyword |
| `/ai-jam-session:jam <song or genre>` | Start a jam session — Claude creates its own interpretation |

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
/ai-jam-session:explore jazz
/ai-jam-session:teach moonlight-sonata-mvt1
/ai-jam-session:practice let-it-be beginner
/ai-jam-session:jam autumn-leaves as blues
/ai-jam-session:jam jazz
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

- MCP server: [@mcptoolshop/ai_jam_session](https://www.npmjs.com/package/@mcptoolshop/ai_jam_session)
- Source: [mcp-tool-shop-org/ai_jam_session](https://github.com/mcp-tool-shop-org/ai_jam_session)

## License

MIT
