### Srinivas Pendela

Vienna. Telugu. TypeScript, Go, Swift, Python.

<a href="https://x.com/_sriinnu_">X</a> &middot; <a href="https://invisibledharma.substack.com">Substack</a> &middot; <a href="https://www.npmjs.com/~sriinnu">npm</a>

---

I spend most of my time building tools I actually want to use. Some of them turned into real systems.

The thread running through everything: I don't think AI agents should be stateless request-response machines. They should remember, consolidate, predict, and have something resembling a point of view. So I started building that — and the architecture ended up borrowing heavily from Indian epistemology. Not as branding. The Nyaya school's six sources of knowledge became actual type categories for how memories get classified. Dream consolidation from Yoga Nidra became the literal model for between-session learning. It fit better than anything I found in the ML literature.

The LLM is a tool in these systems, not the brain. Most of the cognition runs on heuristics at zero token cost.

### Core Stack

**[Chitragupta](https://github.com/sriinnu/chitragupta)** — 17-package TypeScript monorepo. Memory, identity, attention, affect, intention, deliberation, self-evolution. CLI + HTTP server + MCP server + web dashboard. 12,000+ tests. This is the brain that everything else plugs into.

**[Takumi](https://github.com/sriinnu/takumi)** — Terminal coding agent. Custom renderer (I didn't want React/Ink), streaming agent loop, multi-agent orchestration with planner/worker/validator roles. Talks to Chitragupta for memory and predictions.

**[PAKT](https://github.com/sriinnu/clipforge-PAKT)** — Lossless prompt compression. 30-50% fewer tokens on JSON, YAML, CSV, markdown. Every token should carry meaning, not syntax. Library + CLI + MCP server + Chrome extension + Tauri desktop app. On [npm](https://www.npmjs.com/package/@sriinnu/pakt).

**[Kosha Discovery](https://github.com/sriinnu/kosha-discovery)** — Finds every AI model and provider on your machine and cloud accounts. Anthropic, OpenAI, Google, Bedrock, Vertex, Ollama, OpenRouter. Library + CLI + HTTP API.

### Work in Progress

**[Tring](https://github.com/sriinnu/tring-cli)** — Cross-platform messaging CLI in Go. One JSON command surface for WhatsApp, Signal, and Telegram. SQLite-first, daemon mode, muting policies. Built because I wanted my agents to be able to send messages without me opening three apps.

**[Harmon](https://github.com/sriinnu/harmon)** — Music session daemon. AI-compiled listening policies become deterministic constraints — tempo range, energy arcs, no-vocals filters, recency penalties. Daemon-first, Spotify integration, SSE streaming. TypeScript. Because playlists are too manual and radio is too random.

**[Whispr](https://github.com/sriinnu/whispr)** — Self-healing messaging daemon in Go. Signed command envelopes, replay protection, durable delivery queue, channel adapters for iMessage, Signal, Discord, Slack, Google Messages. The reliable delivery layer that Tring routes through.

### Smaller Things

| | |
|---|---|
| **[Helix](https://github.com/sriinnu/helix)** | CLI parsing framework for Swift. Property wrappers, validation, subcommands. |
| **[Silo](https://github.com/sriinnu/Silo)** | Browser cookie extraction. Safari, Chrome, Firefox, Edge, Arc, Brave. Swift. |
| **[LedgerFlow](https://github.com/sriinnu/LedgerFlow)** | Bills and receipts tracker. Append-only ledger, OCR, AI spending analysis. Python. |
| **[Web Suddhi](https://github.com/sriinnu/web-suddhi)** | Browser extension. Ads, trackers, cookies, paywalls — gone. |
| **[PortPilot](https://github.com/sriinnu/portpilot)** | macOS menu bar app to find and kill port processes. Swift. |
| **[Kairos](https://github.com/sriinnu/kairos)** | Work hours tracker. Go. |
| **[Command Relay](https://github.com/sriinnu/command-relay)** | Bi-directional tmux bridge for remote terminal streaming. |

### Writing

I also write about dharma and inner life at **[Invisible Dharma](https://invisibledharma.substack.com)**. Different voice, same person. Quiet lessons from a noisy life.

---

*Every module in Chitragupta carries a Sanskrit name that maps to its cognitive function. Smriti is memory. Swapna is dream consolidation. Buddhi is intelligence. Scarlett is health monitoring (okay, not all of them are Sanskrit). Externally, everything speaks English.*
