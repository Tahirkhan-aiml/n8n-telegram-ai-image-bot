Telegram AI Image Generator

Type any idea → Get a stunning AI image in seconds.

> "A cat astronaut drinking coffee on Mars" → Gets DALL·E-powered image

![DALL·E](https://img.shields.io/badge/%F0%9F%96%BC%EF%B8%8F%20DALL%C2%B7E-00D26A?style=for-the-badge) ![Telegram](https://img.shields.io/badge/%F0%9F%93%B1%20Telegram-229ED9?style=for-the-badge&logo=telegram)


 Features

| Feature | Description |
|--------|-------------|
| Zero setup | Just import & run |
| Real-time image generation | Instant DALL·E response |
| DALL·E 3 via OpenAI | High-quality AI art |
| Telegram-native | No app needed |
| Fast & reliable | Aggregate + Merge nodes |
| Binary-safe | Sends image directly in chat |


 How to Use

 1. Import Workflow
→ Click [telegram-ai-image-generator.json](telegram-ai-image-generator.json) → Copy all
→ In n8n: Workflows → New → Import from Clipboard (or drag file)

 2. Fix Red Warnings (Credentials)

| Credential | Name |
|----------|------|
| OpenAI API | `OpenAi account` |
| Telegram Bot | `Telegram account` |

 Setup: OpenAI
1. Go to [platform.openai.com/api-keys](https://platform.openai.com/api-keys)  
2. Copy your API key  
3. In n8n → Credentials → OpenAI API → Name: `OpenAi account` → Paste key

 Setup: Telegram Bot
1. Open Telegram → Talk to [@BotFather](https://t.me/BotFather)  
2. Type `/newbot` → Follow steps → Get Bot Token  
3. In n8n → Credentials → Telegram API → Name: `Telegram account` → Paste token

 3. Activate & Test
1. Click "Activate" in n8n  
2. Open Telegram → Search your bot  
3. Type:  
   > `A dragon playing piano in a forest`

Bot replies with AI-generated image in <10 seconds!


 Live Bot Example

Try it now:  
[@YourImageBot](https://t.me/YourImageBot) (after deployment)

> Replace `@YourImageBot` with your actual bot username


 How It Works

```mermaid
graph LR
    A[User Sends Prompt] --> B[Telegram Trigger]
    B --> C[OpenAI → DALL·E 3]
    C --> D[Merge with Original Message]
    D --> E[Aggregate Binary Data]
    E --> F[Send Photo in Chat]
