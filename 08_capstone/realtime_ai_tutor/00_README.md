# 02 — Real-time AI Tutor Platform

Live, voice-driven AI tutor with a shared whiteboard and progress tracking.
The 2026 shape of education apps.

## Files

- `01_lesson_state_machine.ts` — Topic → question → hint → evaluate transitions
- `02_tutor_agent.ts` — LLM agent with curriculum + student-level prompt
- `03_voice_streaming.ts` — Bidirectional WebRTC audio + VAD for natural turn-taking
- `04_whiteboard_component.tsx` — Live, multi-user drawing on a shared canvas
- `05_progress_tracker.ts` — Mastery scores, time-on-task, retry analytics

## Stack

TypeScript · React · WebRTC · OpenAI Realtime API · XState · tldraw / Excalidraw
