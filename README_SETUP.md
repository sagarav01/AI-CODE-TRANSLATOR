## Gemini & API notes

- The example `utils/gemini.js` includes a mock fallback when `GEMINI_API_KEY` is not present.
- To connect a real model:
  1. Replace the endpoint URL with the real Gemini/LLM endpoint.
  2. Adjust the request payload to match the chosen provider (OpenAI, Google, Anthropic, etc).
  3. Secure your API key: do not commit `.env.local` to source control.
