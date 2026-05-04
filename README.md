# LLM-proxy-router

Smart AI Proxy Router for Developers

One endpoint. Multiple models. No vendor lock-in.

---

## Overview

LLM-proxy-router is an OpenAI-compatible proxy that allows you to route requests to multiple AI providers (local or cloud) through a single unified API.

It integrates seamlessly with developer tools such as VS Code extensions, CLI tools, and any OpenAI SDK-compatible client.

---

## Features

- Smart routing (e.g., debugging tasks to stronger models, simple tasks to lightweight models)
- OpenAI-compatible API (`/v1/chat/completions`)
- Multi-provider support:
  - OpenRouter
  - NVIDIA NIM
  - Local models (Ollama)
- Streaming support (SSE)
- Bring your own API keys (no shared billing or lock-in)
- Compatible with VS Code tools (Cline, Continue, etc.)
