# 09 — Browser-Based Voice Agent

Always-on voice assistant that lives entirely in the browser.
Wake-word detection, speech recognition, and synthesis in the page.

## Files

- `01_speech_recognition.ts` — Web Speech API + Whisper.cpp fallback
- `02_wake_word_detector.ts` — ONNX-based keyword spotting
- `03_tts_synthesizer.ts` — Streaming text-to-speech with voice selection
- `04_voice_state_machine.ts` — Listening → thinking → speaking state graph

## Stack

TypeScript · Web Audio API · Web Speech API · ONNX Runtime Web · XState
