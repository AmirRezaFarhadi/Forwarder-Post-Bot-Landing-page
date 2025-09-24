# Forwarder Post Bot

**Forwarder Post Bot** is a Telegram bot designed to help channel admins **automatically forward posts from a source channel to their own channel**. The bot guides users step-by-step through account authentication, supports two-factor authentication (2FA), and can schedule up to 100 posts per session. Perfect for Telegram channel admins who want to save time and streamline content posting.

---

## Features

- **Force Join Verification:** Ensures users join a required group or channel before using the bot.
- **Step-by-Step Setup:** Bot collects the following information:
  - Footer text
  - Source channel
  - Destination channel
  - Phone number
  - API ID & API hash
  - Session name
  - Telegram login code
  - 2FA password (if enabled)
- **Automatic Login:** For accounts without 2FA, login happens automatically.
- **Forward & Schedule Posts:** Forward up to 100 posts from the source channel and schedule them in your channel.
- **Admin Requirement:** The bot must be added as an admin to the source channel.

---

## How It Works

1. Start the bot on Telegram.
2. Complete the **force-join verification**.
3. Follow the step-by-step prompts to provide all required details.
4. Enter your Telegram login code and 2FA password (if prompted).
5. The bot logs into your account.
6. The bot **forwards and schedules posts** from the source channel to your channel automatically.

---

## Requirements

- Telegram account
- Telegram API credentials (API ID & API hash)
- Admin access to the source channel

---

## Usage

1. Start the bot on Telegram.
2. Follow the guided setup prompts.
3. Ensure the bot is an admin in the source channel.
4. Sit back while your posts are forwarded and scheduled automatically.

---

## Notes

- Maximum of 100 posts per session.
- Make sure your API credentials and 2FA password are correct.
- The bot is ideal for channel admins who want to save time and automate content posting.
