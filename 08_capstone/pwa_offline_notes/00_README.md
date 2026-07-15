# 05 — PWA Offline-First Note App

Notes that work everywhere — even with no network. Installable, syncable, conflict-free.

## Files

- `01_service_worker.ts` — App shell + asset + API caching strategies
- `02_indexeddb_store.ts` — Typed IndexedDB wrapper for notes and attachments
- `03_sync_engine.ts` — Background sync queue with exponential backoff
- `04_conflict_resolver.ts` — CRDT-based merge for concurrent edits
- `05_editor_component.tsx` — Rich-text editor with markdown export

## Stack

TypeScript · Workbox · IndexedDB · Yjs / Automerge · Service Workers · React
