# AI Website Generator (bolt.diy + Ollama)

A personal learning project. It is not an original codebase: it is based on the
open-source bolt.diy (https://github.com/stackblitz-labs/bolt.diy) by StackBlitz
and contributors (MIT License). I set it up to generate websites from
natural-language prompts using local LLMs through Ollama.

## What I did
- Set up and configured bolt.diy (Remix, React, TypeScript, Vite).
- Connected it to a local Ollama server so models run on my own machine.
- Configured other providers (Groq, Google Gemini) for comparison.

## Run locally
1. Install Node.js 18.18+, pnpm and Ollama.
2. Pull a model: ollama pull <model-name>
3. Copy .env.example to .env.local (keep OLLAMA_API_BASE_URL=http://127.0.0.1:11434)
4. pnpm install, then pnpm run dev
5. Open the app, choose Ollama as provider, pick your model, and enter a prompt.

Fully offline use works only with the Ollama provider. Cloud providers need API keys.

## Models I used
<un Ollama models name inga ezhudhu>

## Credits
Original project: StackBlitz, Inc. and bolt.diy contributors.
