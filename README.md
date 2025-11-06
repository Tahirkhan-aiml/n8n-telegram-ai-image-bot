Telegram AI Image Generator

Type any idea → Get a stunning AI image in seconds.

> "A cat astronaut drinking coffee on Mars" → Gets DALL·E-powered image

![DALL·E](https://img.shields.io/badge/%F0%9F%96%BC%EF%B8%8F%20DALL%C2%B7E-00D26A?style=for-the-badge) ![Telegram](https://img.shields.io/badge/%F0%9F%93%B1%20Telegram-229ED9?style=for-the-badge&logo=telegram)



 Features

| Check | Feature |
|-------|--------|
| Check | Zero setup — Just import & run |
| Check | Real-time image generation |
| Check | DALL·E 3 via OpenAI |
| Check | Telegram-native — No app needed |
| Check | Fast & reliable — Aggregate + Merge |
| Check | Binary-safe — Sends image directly |



 How to Use

 1. Import Workflow
→ Click [telegram-ai-image-generator.json](telegram-ai-image-generator.json) → Copy all  
→ In n8n: New → Import from Clipboard (or drag file)

 2. Fix Red Warnings (Credentials)

| Credential | Name |
|----------|------|
| OpenAI API | `OpenAi account` |
| Telegram Bot | `Telegram account` |

Setup:

OpenAI
1. [platform.openai.com/api-keys](https://platform.openai.com/api-keys)
2. Copy key → n8n → Credentials → OpenAI API → Name: `OpenAi account`

 Telegram Bot
1. Talk to [@BotFather](https://t.me/BotFather)
2. `/newbot` → Get token
3. In n8n → Credentials → Telegram API → Name: `Telegram account` → Paste token

 3. Activate & Test

1. Click "Activate"
2. Open Telegram → Search your bot → Say:
   > `A dragon playing piano in a forest`

Bot replies with AI-generated image in <10 seconds!


 Live Bot Example

Try it now:  
[@YourImageBot](https://t.me/YourImageBot) (after deployment)

> Replace with your actual bot username

 How It Works

```mermaid
graph LR
    A[User Types Prompt] --> B[Telegram Trigger]
    B --> C[OpenAI → DALL·E]
    C --> D[Merge with Original]
    D --> E[Aggregate Binary]
    E --> F[Send Photo in Chat]
