# 01 — AI Chat UI Kit

Reusable chat UI primitives for LLM-powered applications.
Streaming-first, accessible, and token-aware.

## Files

- `01_chat_message_component.tsx` — Message bubble, role variants, copy, regenerate
- `02_streaming_response_handler.ts` — SSE / fetch reader parser for incremental token rendering
- `03_token_usage_tracker.ts` — Per-message and per-session token + cost accounting

## Stack

TypeScript · React 18 · Server-Sent Events · ARIA live regions
