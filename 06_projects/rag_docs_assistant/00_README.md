# 04 — RAG Documentation Assistant

Ask questions over your docs and get cited answers from an LLM.
The classic 2025–2026 enterprise use case.

## Files

- `01_document_chunker.ts` — Sliding-window + heading-aware markdown chunker
- `02_embedding_client.ts` — Batched embedding calls with retry and rate limiting
- `03_retrieval_chain.ts` — Hybrid (BM25 + dense) retrieval with re-ranking
- `04_chat_interface.tsx` — Streaming chat UI with source citations

## Stack

TypeScript · OpenAI / Cohere · LanceDB / pgvector · React · SSE
