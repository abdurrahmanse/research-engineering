# 08 — AI Image Generation Studio

Prompt-to-image playground with queueing, history, and gallery persistence.

## Files

- `01_prompt_form.tsx` — Prompt + negative prompt + style + seed controls
- `02_generation_queue.ts` — Rate-limited queue with priority + cancellation
- `03_image_gallery.tsx` — Virtualized grid with lightbox and download
- `04_gallery_persistence.ts` — IndexedDB / Supabase storage of images + metadata

## Stack

TypeScript · React · Replicate / Stable Diffusion / DALL·E · IndexedDB
