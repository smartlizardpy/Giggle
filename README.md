# 🤪 Giggle Search Engine

Giggle is a cursed, chaotic, and weirdly useful parody search engine. It fuses real-time web search results with sarcastic AI commentary, text-to-speech roasts, fake sponsored ads, and unexpected easter eggs. Powered by [Langsearch API](https://langsearch.com), it’s like if Google was coded by a GPT with trust issues and a British accent.

---

## 🔍 Features

- ✅ **Real Search Results** – Powered by Langsearch API, returns up to 50 web results
- 🤖 **AI Roast Mode** – Smart GPT-style responses that react based on your query topic (love, Linux, conspiracies, math, etc.)
- 🤯 **Easter Egg Triggers** – Type "fart", "beans", "rick astley", or "linux" and prepare for nonsense
- 🎤 **British TTS Voice** – A polite robotic voice reads your roast aloud (emoji-free)
- 🌐 **Langsearch Summary Support** – When available, full-page summaries are included
- 💸 **Fake Ads** – Clicking on “AI Gummies” will definitely Rickroll you
- 🐧 **Linux Mode** – Triggered automatically on Linux queries
- 📦 **Client-Side Only** – All logic runs in the browser (no need for a server unless you proxy the API)

---

## 💻 How It Works

1. You type something weird.
2. Giggle checks for easter eggs.
3. If your query ends with a `?`, it generates a ChatGPT-style roast.
4. It sends your query to the Langsearch API.
5. Displays results, summaries, URLs, and sarcasm.
6. British voice reads the sass aloud.
7. Everyone cries and giggles a bit.

---

## 🚀 Live Demo

> _(Host it with GitHub Pages, Vercel, Netlify, or PythonAnywhere)_

[🔗 gigglesearch.vercel.app](https://gigglesearch.vercel.app)  
_(replace this with your actual URL)_

---

## 📦 Tech Stack

- HTML + CSS + JavaScript (Vanilla)
- Langsearch API (`/v1/web-search`)
- Web Speech API (Text-to-Speech)
- No frameworks, no dependencies. Pure chaos.

---

## 🧠 Easter Egg Triggers

Here are just a few terms that unlock special behavior:

| Trigger | Effect |
|--------|--------|
| `fart` | 💨 Beans suggestion |
| `rick astley` | 🎶 Never gonna give you up... |
| `linux vs windows` | ⚔️ Holy war |
| `anime` | 🌀 Go touch grass |
| `google` | 👀 “We don’t say that name here.” |
| `love`, `math`, `cringe`, `ai`, `food`, `existential` | Unique roasts |

Add more in the `easterEggs` and `chatResponses` objects inside `index.html`.
