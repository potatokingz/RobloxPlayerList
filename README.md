# Server Presence Logger 🛰️

This utility is designed to notify the owner whenever a new session is started in-game, providing a snapshot of the current players.

## 📋 What It Does

When the script is executed, it sends a webhook with:

- ✅ Player names and display names
- 🆔 User IDs
- 📅 Account ages
- 🤖 Approximate NPC status
- 🟢 Indicator for the local player

The data is sent in a clean embed format to a remote endpoint for easy tracking.

## 🛠️ Setup

1. Paste the script into a LocalScript under `StarterPlayerScripts` or `PlayerScripts`.
2. Set your webhook URL here:
   ```lua
   local webhookUrl = "https://your.webhook.url"
   ```

## Make sure HTTP requests are enabled in game settings (Studio: Home → Game Settings → Security → Enable HTTP Requests).

## 💡 Intended Use
Primarily for session monitoring, testing environments, and administration visibility.
Avoid use in public games without disclosing data practices, per platform guidelines.

