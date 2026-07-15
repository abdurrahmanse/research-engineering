# 03 — Real-time Collaborative Editor

A Google-Docs-style editor: multiple cursors, conflict-free text, low latency.

## Files

- `01_crdt_document.ts` — Yjs-backed CRDT document with text and formatting
- `02_awareness_presence.ts` — Cursor positions, selections, user color, idle state
- `03_editor_component.tsx` — TipTap/ProseMirror editor bound to the CRDT
- `04_websocket_provider.ts` — WebSocket sync provider with reconnection + backoff

## Stack

TypeScript · Yjs · TipTap · WebSocket · React
