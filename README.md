<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1215320296391835708/1570817063151345746/image.png?ex=6af878e4&is=6af72764&hm=71acbdeed4464c5f4f065a7484c34e33c7faaa1a558d3e093d4567be0f754f7f&" alt="Discord Chat Bridge" width="256" />
</p>

<h1 align="center">Discord Chat Bridge</h1>
<p align="center">Created by QrystalGG</p>

<p align="center">
  A lightweight, client-sided Fabric mod that creates a two-way chat bridge between your Minecraft client and Discord.
</p>

<p align="center">
  <a href="https://discord.gg/uXJTM6Q5Gp">Client Hub</a>
  •
  <a href="https://github.com/ItsQrystal">GitHub</a>
  •
  <a href="https://itsqrystal.github.io/DiscordAddon/">Website</a>
</p>

<hr />

# How to Use
1. Download the latest release `.jar` file.
2. Place the `.jar` file into your `.minecraft/mods` folder alongside **Fabric API**.
3. Ensure you are running Minecraft **1.21.11** with Fabric Loader.
4. Launch the game and open the mod's configuration menu (or Mod Menu) to enter your Discord credentials.

---

# Features

### Minecraft to Discord
Forwards your in-game Minecraft chat directly into a Discord text channel using webhooks. Incoming chat messages are sent asynchronously so your game performance stays unaffected.

**Setup & Configuration:**
1. Open your target Discord channel's settings, go to **Integrations → Webhooks**, create a webhook, and copy its URL.
2. Open the mod's settings in-game:
   - **Webhook URL**: Paste your Discord Webhook URL here.
3. Toggle the feature on—any in-game chat messages will now forward straight to your Discord channel.

---

### Discord to Minecraft
Relays messages from a target Discord text channel directly into your in-game chat using JDA. Messages sent in that Discord channel will be typed into Minecraft chat by your client.

**Setup & Configuration:**
1. Create an application on the [Discord Developer Portal](https://discord.com/developers/applications).
2. Navigate to the **Bot** tab, enable **Message Content Intent** under Privileged Gateway Intents, and copy your **Bot Token**.
3. Invite the bot to your Discord server with permissions to view channels and read message history.
4. Open the mod's settings in-game:
   - **Bot Token**: Paste your Discord bot token here.
   - **Channel ID**: Paste the ID of the Discord text channel you want to listen to.

<hr />

# Credits
- Created by **QrystalGG**
- Join [Client Hub](https://discord.gg/uXJTM6Q5Gp) for support and updates.
