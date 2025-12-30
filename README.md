# Build LLM Prompt

Source code for [buildllmprompt.com](https://buildllmprompt.com) - a prompt builder for AI coding assistants.

## What is this?

A simple tool to create structured prompts for Claude Code, Codex CLI, and other AI coding assistants. Configure:

- **Exploration scope** - How much should the AI explore your codebase?
- **Planning level** - Execute immediately or plan first?
- **Tool preferences** - Which tools to prefer, avoid, or require
- **Behavior modifiers** - No stalling, test-first, tight scope, etc.

## Privacy

100% client-side. Nothing leaves your browser - all prompt generation happens locally.

## Development

Single HTML file in `public/index.html`. No build step required.

```bash
# Local development - just open the file
open public/index.html

# Or use any static server
npx serve public
```

## Deployment

Hosted on Cloudflare Pages.

```bash
npx wrangler pages deploy public --project-name=buildllmprompt
```
