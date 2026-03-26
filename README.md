# ⚡ llmeter

> Real-time cost calculator & comparator for LLM APIs

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Made with ❤️](https://img.shields.io/badge/made%20with-%E2%9D%A4%EF%B8%8F-red.svg)](https://github.com/themominpro/llmeter)

**llmeter** helps developers instantly calculate and compare the cost of running prompts across major LLM providers — before they get a surprise bill.

👉 **[Try it live →](https://llmeter.vercel.app)** *(coming soon)*

![llmeter screenshot](screenshot.png)

---

## 🤔 Why llmeter?

You write a prompt. You're not sure whether to use Claude, GPT-4, or Gemini. They all have different pricing models, token limits, and costs.

**llmeter answers in seconds:**
- How much will this prompt cost on each provider?
- Which model gives the best value?
- How does cost scale as my prompt grows?

No more guessing. No more surprise bills.

---

## ✨ Features

- ⚡ **Real-time cost calculation** — paste your prompt, see costs instantly
- 🔄 **Side-by-side comparison** — Claude vs GPT vs Gemini at a glance
- 🧮 **Token counter** — see exactly how many tokens your prompt uses
- 💰 **Always up-to-date pricing** — we track provider price changes
- 🌙 **Dark mode** — because developers live in the dark
- 📱 **Fully responsive** — works on mobile too

---

## 🤖 Supported Providers

| Provider | Models |
|----------|--------|
| **Anthropic** | Claude 3.5 Sonnet, Claude 3 Opus, Claude 3 Haiku |
| **OpenAI** | GPT-4o, GPT-4 Turbo, GPT-3.5 Turbo |
| **Google** | Gemini 1.5 Pro, Gemini 1.5 Flash, Gemini 1.0 Pro |

More providers coming soon — contributions welcome!

---

## 🚀 Getting Started

### Use online
Visit **[llmeter.vercel.app](https://llmeter.vercel.app)** — no install needed.

### Run locally

```bash
# Clone the repo
git clone https://github.com/themominpro/llmeter.git
cd llmeter

# Install dependencies
npm install

# Start the dev server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🛠️ Built With

- [Next.js](https://nextjs.org/) — React framework
- [Tailwind CSS](https://tailwindcss.com/) — Styling
- [Tiktoken](https://github.com/dqbd/tiktoken) — Token counting

---

## 🤝 Contributing

Contributions are what make open source amazing! Here's how you can help:

- 💰 **Update pricing** — LLM prices change often, PRs to update are always welcome
- 🤖 **Add a provider** — Missing your favorite LLM? Add it!
- 🐛 **Report bugs** — Open an issue
- 💡 **Suggest features** — We'd love to hear ideas

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 📊 Pricing Data

All pricing data is sourced directly from official provider documentation and updated manually. If you spot an outdated price, please [open an issue](https://github.com/themominpro/llmeter/issues) or submit a PR.

---

## 📜 License

MIT © [themominpro](https://github.com/themominpro)

---

<p align="center">
  If llmeter saved you money, give it a ⭐ — it helps more developers find it!
</p>
