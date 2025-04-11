# 🤖 Crypto News Visual Bot (N8n + GPT + Telegram)

This is an end-to-end automated **Crypto News Summarizer Bot** built in [N8n](https://n8n.io) that:

- Scrapes breaking crypto news from [CryptoPanic](https://cryptopanic.com)
- Summarizes articles with **GPT-3.5** & **GPT-4o**
- Auto-generates an image using OpenAI (DALL·E 3-style prompt)
- Posts to a Telegram channel with summary + visual
- Runs every 3 hours using a scheduled trigger

---

## ⚙️ Tech Stack

- 🔗 [N8n](https://n8n.io)
- 💬 OpenAI GPT (text + image)
- 📡 CryptoPanic API (news)
- 📲 Telegram Bot API
- 🧠 Python/JS code nodes for logic, filtering, structuring

---

## 📁 Files

- `crypto-news-visual-bot.json`: Full workflow
- `README.md`: This file

---

## 📦 Features

✅ Auto-pulls crypto news  
✅ Filters for only fresh “news” kind (last 30 mins)  
✅ GPT-4o generates Twitter + Telegram messages in JSON  
✅ AI image generation using descriptive Telegram message  
✅ Telegram posts include both image + summary  
✅ Fallback logic if no image or caption is available

---

## 📋 How to Use

1. Import the `.json` workflow in your [N8n](https://n8n.io) instance
2. Configure credentials:
   - `OPENAI_API_KEY`
   - `CryptoPanic API Token`
   - `Telegram Bot Token`
3. Schedule it or run manually
4. Watch your Telegram channel update itself like a real news outlet 🚀

---

## 📌 Note

🔐 Make sure to **insert your own credentials** in the N8n Credential Manager:
- Replace `"OPENAI_API_CREDENTIAL_NAME"` with your actual OpenAI credential name
- Replace `"TELEGRAM_API_CREDENTIAL_NAME"` with your Telegram credential name

---

📂 [Download the workflow JSON here](./crypto-news-visual-bot.json)


---

## 🔁 Workflow Preview

![Crypto News Bot Flow](./flow-preview.png)


Made with ⚡ by [@Rocky_AMG](https://x.com/Rocky_AMG)  
More tools: [linktr.ee/buildwithrocky](https://linktr.ee/buildwithrocky)
