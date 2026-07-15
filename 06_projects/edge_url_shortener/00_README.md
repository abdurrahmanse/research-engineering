# 05 — Edge-Deployed URL Shortener

A globally-fast URL shortener running on edge functions with KV storage.

## Files

- `01_kv_store.ts` — Typed wrapper around edge KV with TTL helpers
- `02_shortcode_generator.ts` — Base62 encoding, collision retries, custom aliases
- `03_redirect_handler.ts` — Edge handler: 301 redirect, hot-path optimization
- `04_analytics_collector.ts` — Click counting, referer parsing, geo from headers

## Stack

TypeScript · Cloudflare Workers / Vercel Edge · Edge KV · TypeScript types
