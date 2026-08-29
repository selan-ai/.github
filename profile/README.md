## Selan

We keep credentials out of AI coding agents.

Agents read your files, run your commands and talk to model providers on your behalf. Secrets leak into that flow in ways normal tooling never looks at: pasted into a chat, read out of a .env, or sitting in an instruction file the agent re-reads every session.

### Open source

**[whatileaked](https://github.com/selan-ai/whatileaked)** finds credentials your coding agent has already written to disk, across Claude Code, Codex and Cursor transcripts and memory files. Redacts them in place. No network calls, no telemetry, zero dependencies.

    npx whatileaked scan

**[claude-ai-export](https://github.com/selan-ai/claude-ai-export)** exports your claude.ai chats, projects, attachments and scheduled tasks to a zip, and imports them into Claude Desktop. Runs entirely in your browser, nothing is uploaded.

### Product

[selan.ai](https://selan.ai) is a proxy that redacts credentials before they leave your machine, and routes your agent traffic across model providers.

All of it is MIT and auditable. Read the source before you trust it.
