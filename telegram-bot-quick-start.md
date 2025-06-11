---
title: Telegram Bot
layout: home
nav_order: 2
---

# Telegram Bot Quick Start

Accept payments and generate links directly from Telegram with the Scionx Bot.

---

## Step 1: Add the Bot in Telegram

- Open Telegram and search for your bot (e.g., `@scionx_bot`)
- Start a private chat or add the bot to your group

---

## Step 2: Link Your Organization

1. In the chat, type `/start`
2. The bot will ask for your Scionx API key  
   (You can find this in your Scionx dashboard under **Settings → API Keys**)
3. Paste your API key to securely link your Telegram account with your organization

---

## Step 3: Create a Payment Link

Type `/pay` and follow the guided prompts:

- Enter the payment amount (e.g., `100`)
- Enter the currency code (e.g., `USD`, `AED`, etc.)
- Enter the settlement token (e.g., `USDT`, `USDC`, `DAI`)
- Add a note, or type `skip` to leave blank

The bot will instantly generate a payment link and display a summary in the chat.

---

## Step 4: Share or Track Payments

- Share the generated payment link with your customer  
- Track payment status from your Scionx dashboard or directly in Telegram

---

## Supported Commands

- `/start` — Link your organization with API key
- `/pay` — Create a new payment link
- `/status` — Check your linked organization
- `/help` — List all commands

---

## Troubleshooting

- **Webhook not working?** Make sure your Rails app is public (use ngrok in dev) and your webhook URL matches your current bot.
- **API key not accepted?** Double-check your key in Scionx dashboard.
- **Need help?** Reach out to Scionx support or your dev team.

---

Ready to automate crypto payments right from your chat!
