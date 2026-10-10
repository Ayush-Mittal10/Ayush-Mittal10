# Ayush Mittal

Founding Engineer at **Robin AI**, building [hiRobin](https://www.hirobin.ai) — an AI call-handling app for the Indian market, now past **1M+ Play Store downloads** at a 4.5★ rating and a 99% crash-free rate.

I work across mobile, backend and applied LLM systems. Most of what I build ships to real users.

- 🔭 Currently: AI voice-agent pipelines and in-device call automation at Robin AI
- 🧪 Side project: [Browse Buddy](https://github.com/Ayush-Mittal10/Browse-Buddy) — an autonomous LLM browser agent
- 🎓 B.Tech Computer Science, Rajiv Gandhi Institute of Petroleum Technology (2026)
- 📍 Bangalore, India

---

## Selected work

### [Browse Buddy](https://github.com/Ayush-Mittal10/Browse-Buddy) · [Live demo](https://browse-buddy-238184580204.asia-south1.run.app/)
An autonomous LLM browser agent that executes natural-language tasks in a real Chromium instance.

Instead of prompting the model with raw HTML, it builds a compact numbered-element DOM snapshot — no brittle CSS/XPath selectors, and per-step context bounded to 120 elements. Provider-agnostic across Anthropic, OpenAI, Gemini and local Ollama, with automatic fallback. Local 8B inference tuned to ~2s per step via KV-cache reuse and disabled reasoning mode, down from a 27.7s baseline. Ships a self-hostable web UI that streams the headless browser at ~10 FPS (67 KB/s) over the Chrome DevTools Protocol.

`Python` `FastAPI` `Playwright` `Chrome DevTools Protocol` `Ollama` `Cloud Run`

### [Quizzly](https://github.com/Ayush-Mittal10/Quizzly) · [Live](https://quizzly-lime.vercel.app/)
A quiz platform with real-time integrity monitoring for educational institutions. WebRTC proctoring decodes and analyses webcam streams entirely client-side at 30 FPS, so no video ever leaves the browser. Includes an analytics dashboard surfacing score distributions and question-level difficulty.

`React` `TypeScript` `WebRTC` `Tailwind CSS` `Supabase`

### [ByteGuide](https://github.com/Ayush-Mittal10/ByteGuide) · [Live](https://byteguide.onrender.com/)
Generates semester-wise learning plans for engineering students in under 5 seconds, built on a scraping pipeline that turns external coding profiles into structured input for the model.

`React` `Node.js` `Gemini API`

---

## Stack

**Languages** Python · TypeScript · JavaScript · SQL · C++
**Frontend** React · React Native · Next.js · Tailwind CSS
**Backend** FastAPI · Node.js · Express · Django
**Data** PostgreSQL · MongoDB · Firebase · Supabase
**Infra** Google Cloud Platform · Cloud Run · Cloudflare

---

## Elsewhere

[Portfolio](https://ayush-mittal.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/ayushmittal10) · [X](https://x.com/ayushmittal105) · [Codolio](https://codolio.com/profile/ayushmittal)
