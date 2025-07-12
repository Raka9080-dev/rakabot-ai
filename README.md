# Rakabot AI

Website tanya‑jawab mirip ChatGPT dengan mode manual + GPT hybrid.

## Fitur
- Dark mode UI (ChatGPT style)
- Jawaban manual dari `data-jawaban.json`
- PRO mode (`RAKAPRO123`) untuk akses GPT
- Pertanyaan dikirim ke WhatsApp admin jika belum PRO
- Deploy friendly to Vercel (includes `/api/chatgpt.js`)

## Deploy Steps
1. Fork/clone repo.
2. Add `OPENAI_API_KEY` in Vercel project env variables.
3. `vercel --prod` or import repo in Vercel dashboard.