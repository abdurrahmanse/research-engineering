# 12 — Streaming Markdown Renderer

Render markdown as it streams from an LLM, token by token, with safe HTML.

## Files

- `01_token_parser.ts` — Incremental markdown parser tolerant of partial input
- `02_safe_sanitizer.ts` — Allowlist-based sanitizer for inline HTML and links
- `03_renderer_component.tsx` — React renderer with syntax highlighting + code copy

## Stack

TypeScript · React · unified / remark / rehype · Shiki / Prism · DOMPurify
