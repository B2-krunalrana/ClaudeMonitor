# ClaudeMonitor

> **Track your Claude.ai token usage across conversations.**
> Made with ❤️ by [Krunal Rana](https://www.linkedin.com/in/krunal-rana/)

## Overview

ClaudeMonitor helps you monitor how much of your Claude usage quota remains. It calculates token consumption from various sources including uploaded files, project knowledge, chat history, and AI responses.

## Features

The extension tracks token usage from:

- **Files** - Documents uploaded to chats or synced via Google Drive, GitHub, etc.
- **Projects** - Knowledge files and custom instructions
- **Personal preferences** - Your configured settings
- **Message history** - Full conversation context
- **System prompts** - Enabled tools (analysis, artifacts) on a per-chat basis
- **MOST MCPs/Integrations** - Some limitations apply (e.g. web search Knowledge objects)

Limitations:
- **Web search results** - Full results are not exposed in conversation history
- **Research** - Most happens on the backend and cannot be tracked

Token calculation is handled either through Anthropic's API (if you provide your key) or via [gpt-tokenizer](https://github.com/niieani/gpt-tokenizer).

## Privacy

The extension fetches your organization ID from claude.ai to synchronize usage data across devices using Firebase. For full details, see the [privacy policy](PRIVACY.md).

## UI

Most elements in the chat UI (length, cost, estimate, caching status) have a tooltip explaining them further.

---

Made with ❤️ by [Krunal Rana](https://www.linkedin.com/in/krunal-rana/)
