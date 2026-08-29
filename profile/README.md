## Selan

More than half of all AI usage is code, and in most companies nobody can see that line. Selan sits between your team and the model providers, and solves three problems.

### Every dollar has a name

Add the accounts you already own: Claude, GPT, Vertex, OpenRouter. Every request goes to the right account and is logged with who ran it. Limits follow the person rather than the key, by day, week or month.

### One sign-in, every model

Claude, GPT, Kimi and whatever ships next, inside the tools your team already uses, on a single budget.

### Secrets never reach the provider

Keys and credentials are replaced in flight, so the provider never sees them.

### Running it

    curl -fsSL https://dl.selan.ai/install.sh | sh
    selan login
    selan claude

One binary on macOS, Linux and Windows. Claude Code, Claude Desktop and Codex run exactly as they did before. Built and hosted in the EU.

### Open source

[whatileaked](https://github.com/selan-ai/whatileaked) finds credentials your coding agent has already written to disk, across Claude Code, Codex and Cursor transcripts and the instruction files it re-reads every session, and redacts them in place. No network calls, no telemetry, no dependencies.

    npx whatileaked scan

[claude-ai-export](https://github.com/selan-ai/claude-ai-export) exports your claude.ai chats, projects, attachments and scheduled tasks to a zip, and imports them into Claude Desktop. It runs in your browser and uploads nothing.

Both are MIT. Read the source before you trust either of them.

[selan.ai](https://selan.ai)
