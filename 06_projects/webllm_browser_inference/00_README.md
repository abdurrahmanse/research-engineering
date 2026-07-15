# 02 — WebLLM Browser Inference

Run open-weight LLMs directly in the browser with WebGPU and Web Workers.
No server, no API costs, full privacy.

## Files

- `01_model_loader.ts` — Lazy-loads model weights, caches in IndexedDB
- `02_webgpu_worker.ts` — Off-thread inference worker to keep the main thread responsive
- `03_inference_pipeline.ts` — Prompt templating, sampling, streaming token callback
- `04_progress_ui.tsx` — React component that shows model download + decode progress

## Stack

TypeScript · WebLLM · WebGPU · Web Workers · React
