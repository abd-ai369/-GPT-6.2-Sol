# GPT-6.2 Astra Chat UI

A clean, professional ChatGPT-style interface for **GPT-6.2 Astra** and **GPT-6.2 Sol**, powered by [Puter.js](https://puter.com).

## Features

- Modern dark theme with smooth animations
- Model switcher (Astra / Sol)
- Chat history sidebar
- Typing indicator
- Suggestion prompts
- Fully responsive
- Client-side AI via Puter (no backend needed)

## How to use

1. Open `index.html` in a browser (or host it)
2. Select **Astra** or **Sol**
3. Start chatting

The UI uses:

```js
puter.ai.chat(prompt, {
  model: "gpt-6.2-astra"   // or "openai/gpt-6.2-sol"
})
```

## Live

Just open the HTML file or deploy to any static host (GitHub Pages, Netlify, Vercel, etc.).
