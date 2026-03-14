# ViralForge — Setup & Usage Guide

> Complete step-by-step guide to get ViralForge running in under 5 minutes.

---

## ⚡ Zero-Config Option (Recommended)

ViralForge is a **single HTML file**. There is nothing to install, configure, or deploy.

**To start using it:**
1. Double-click `index.html` — it opens immediately in your browser.
2. Connect an AI Provider API key (see Step 1).
3. Start generating content!

---

## 🔑 Step 1 — Get an API Key (Providers)

ViralForge supports 4 major AI providers. You only need **one** to start working. If you want to use the app for *free*, we highly recommend **OpenRouter** or **Google AI Studio**.

### Opción A: OpenRouter (Recomendado - Modelos Gratuitos)
Permite usar los mejores modelos open-source (Llama 3.3, DeepSeek R1) totalmente gratis.
1. Ve a [openrouter.ai/keys](https://openrouter.ai/keys)
2. Crea una cuenta y pulsa "Create Key".
3. Copia tu API key.
4. En ViralForge, selecciona **"OpenRouter"** y pega tu key. Podrás usar todos los modelos marcados con **($0)** sin coste.

### Opción B: Google AI Studio (Modelos Gratuitos)
Permite usar Gemini 2.5 Flash, Gemini 1.5 Pro, etc., con límites gratuitos muy generosos.
1. Ve a [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Crea una "API Key" gratis.
3. En ViralForge, selecciona **"Google AI Studio"** e inserta la key.

### Opción C: OpenAI (Pago)
1. Ve a [platform.openai.com/api-keys](https://platform.openai.com/api-keys)
2. Genera tu key y asegúrate de tener saldo/método de pago en *Billing*.
3. En ViralForge, selecciona **"OpenAI"** y pégala. Te permite usar GPT-4o, GPT-4 Turbo, etc.

### Opción D: Anthropic Claude (Pago)
1. Ve a [console.anthropic.com/keys](https://console.anthropic.com/keys)
2. En ViralForge, selecciona **"Anthropic Claude"** y pega la key. (Requiere saldo en tu dashboard de Anthropic).

---

## 🔌 Step 2 — Connect Your API Key

1. Open `index.html` in your browser.
2. Click the **"Connect API"** / **"Manage API Key"** button in the header.
3. Select your provider in the dropdown.
4. Paste your key.
5. Select your pre-configured model (ej. Gemini 2.5 Flash, GPT-4o, Claude 4.6).
6. Click **"💾 Save & Connect"**.

The header will update to show exactly which provider is connected (ej. "OpenRouter Connected").

> 🔒 **Security:** Your API key is stored locally in your browser's `localStorage`. It is NEVER sent to any external server besides the official provider you selected.

---

## 🎬 Step 3 — Generate Content

### 3.1 Select Your Platform
- **▶ YouTube**: Long videos, timestamps, heavy SEO tags.
- **♪ TikTok**: Fast-paced short scripts.
- **◎ Instagram**: Reels formatting and hashtags.
- **👤 LinkedIn**: Professional formatting.
- **👭 Facebook**: Community-style posts.
- **✕ X (Twitter)**: Short, punchy threads.

### 3.2 Enter Your Topic
Type a clear, specific topic.
**✅ Good:** "3 formas prácticas de invertir $1000 en 2026 sin riesgo alto"
**❌ Bad:** "invertir dinero"

### 3.3 Choose Settings
- **Tone** — The emotional hook/personality of the script.
- **Niche** — Your channel's industry.
- **Video Length** — Influences how long the script is.
- **Language** — ALL text (hooks, script, titles) will be enforced to match this language perfectly.

### 3.4 Generate
Click **"✦ Generate Content"** and wait ~10-15 seconds.

---

## 📋 Step 4 — Use Your Content (Output Tabs)

- **🪝 Hooks**: 5 options to grab attention in the first 2 seconds.
- **📌 Titles**: 7 highly-clickable CTR-optimized titles.
- **📝 Script**: A full layout (Hook, Intro, Main Body, CTA) tailored to the platform selected.
- **🔍 SEO**: Description text, 10 tags, and 5 keywords ready to copy-paste.

Use the **Copy All** buttons to quickly send formatting to your clipboard.

---

## 🌐 Optional — Host Online

If you want a public URL to access ViralForge from your phone or share it:

- **Netlify Drop (Free / 5 sec):** Go to [app.netlify.com/drop](https://app.netlify.com/drop) and drag the folder containing `index.html` into the screen.
- **GitHub Pages (Free):** Upload `index.html` to a public repo and enable 'Pages' in Settings.
- **cPanel / Any Host:** Upload the `index.html` file inside your `public_html`.

---

## ❓ Troubleshooting

| Problem | Cause / Solution |
|---------|---------|
| **"Invalid API key"** / 401 | You entered the wrong key format, or forgot to copy a character. |
| **"Rate limit"** / 429 | You made too many requests too fast. Wait 60 seconds. |
| **"Quota Exceeded" / Billing** | If using a Paid tier, your balance ran out. If using Google/Gemini and it fails on PRO models, try selecting *Gemini 2.5 Flash* (free tier handles it better). |
| **CORS / Network Error** | Specifically with direct Anthropic API, some setups block direct calls. Solution: Use Anthropic models via **OpenRouter** instead. |
| **Nothing happens on generate** | Check your browser console (F12) for blocked extensions. |

---

*ViralForge Setup Guide — March 2026*
