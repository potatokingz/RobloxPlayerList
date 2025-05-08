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
   `local webhookUrl = "https://webhook.whitehill.group/your/custom/path"`

   ⚠️ *Important*: Roblox blocks direct Discord webhook URLs (`discord.com/api/webhooks/...`).  
   To bypass this, use a forwarding service like `https://webhook.whitehill.group/` which relays the data to Discord.

3. Enable HTTP requests:  
   `Studio → Home → Game Settings → Security → Enable HTTP Requests ✅`

## 💡 Intended Use

Primarily for session monitoring, testing environments, and administration visibility.  
Avoid use in public games without disclosing data practices, per platform guidelines.
