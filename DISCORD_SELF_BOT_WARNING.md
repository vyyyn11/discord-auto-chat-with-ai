# Discord Self-Bot Warning

> **Status:** This project uses automation patterns that violate Discord Terms of Service.

## Disclaimer

This project (`discord-auto-chat-with-ai`) implements a **self-bot** — a bot that runs using a user account token instead of an official bot account. This is achieved via the `discord.py-self` library, an unofficial Discord API wrapper designed for user-account automation.

**Using this project may result in permanent account termination.**

## What is a Self-Bot?

A self-bot is an automated script that controls a Discord **user account** (not a bot account) via the Discord API. Unlike official bots created through the Discord Developer Portal, self-bots:

- Use user tokens instead of bot tokens
- Do not go through Discord's official bot verification process
- Operate under the radar of Discord's bot infrastructure
- Are explicitly prohibited by Discord's Terms of Service

## Technical Pattern

This project uses the following self-bot indicators:

| Indicator | Detail |
|-----------|--------|
| Library | `discord.py-self` (unofficial fork) |
| Auth method | User token (`self_bot=True`) |
| Behavior | Auto-reply to messages without human interaction |
| Automation | Scheduled tasks, auto-restart, AI-generated responses |

## Consequences

Discord actively detects and bans self-bot accounts. Possible consequences include:

- **Account suspension** — temporary lock on the account
- **Account termination** — permanent ban, loss of all servers, DMs, and purchase history
- **IP flagging** — repeated violations may lead to IP-level restrictions
- **Developer policy enforcement** — Discord may pursue further action for repeated abuse

## Recommendation

If you need automated Discord functionality, use the **official Discord Bot API**:

1. Create a bot at [Discord Developer Portal](https://discord.com/developers/applications)
2. Use `discord.py` (official library) instead of `discord.py-self`
3. Authenticate with a bot token, not a user token
4. Follow Discord's [Developer Terms of Service](https://discord.com/developers/docs/legal)

## Use at Your Own Risk

This project is provided for **educational purposes only**. The author is not responsible for any account bans, data loss, or other consequences resulting from the use of this software.

> ⚠️ **By using this project, you acknowledge that you understand the risks and accept full responsibility for any consequences.**
