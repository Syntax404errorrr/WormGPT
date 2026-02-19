# 🐛 WormGPT CLI - OpenRouter Edition

**WormGPT CLI** is a sleek command-line interface (CLI) for interacting with LLMs via OpenRouter API. It supports multiple models, automatic language detection, and customizable settings — all in a terminal-friendly format.

> ⚡ Lightweight. Powerful. Fully terminal-based. Made with ❤️ by [@Syntax404errorrr](https://github.com/Syntax404errorrr)

---

## 🚀 Features

- 🔗 OpenRouter API integration
- 🌍 Auto language detection (via `langdetect`)
- 🗣️ Multi-language support: English, Indonesian, Spanish, Arabic, Thai, Portuguese
- 💬 Interactive chat session with typing effect
- 🎨 Stylish CLI UI with colors and banners
- 🔧 Easy configuration of API key and model
- 💾 Config auto-saved in `wormgpt_config.json`

---

## 📦 Requirements

- Python 3.6+
- `pip` installed
- Deepseek API key ([get one here](https://platform.deepseek.com/))

---

## ⚙️ Installation

Clone the repo:

```bash
git clone https://github.com/Syntax404errorrr/WormGPT
cd WormGPT
python3 wormgpt.py
```

## 🔑 Set Your API Key

You can set your OpenRouter API key via the main menu:
```
[3] Set API Key
```

Or manually edit the config file:
```
{
  "api_key": "YOUR_APIKEY_OPENROUTER",
  "base_url": "https://openrouter.ai/api/v1",
  "model": "deepseek/deepseek-chat-v3-0324:free",
  "language": "English"
}
```

## 🧠 Usage Example

```
python3 wormgpt.py
```

## Menu will appear:

```
[ Main Menu ]
1. Language: English
2. Model: gemini-1.5-flash
3. Set API Key
4. Start Chat
5. Exit
```

## 🧪 Custom Models

From the menu, you can enter your own model ID (from OpenRouter).

Example:
```
01-ai/Yi-34B-Chat
meta-llama/llama-3-8b-instruct:nitro
```

### 📷 Example Screenshot
![WormGPT CLI Example](assets/example.jpg)

