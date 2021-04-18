# Minecraft & Discord Bidirectional Chat Bot

## About
This program connects a Discord Bot and Minecraft Chat Bot together, allowing messages sent on both platforms to be combined into one chat.

Messages sent from a discord channel (or all channels) will be sent to the Minecraft server's chat by the Minecraft bot. Messages sent on the Minecraft server are sent to a Discord channel (or any channel/s) by the Discord Bot.

## Installation

Clone this repository: `git clone https://github.com/ansonfoong/minecraft-discord-chat-bot.git`

Run: `npm install`

Create a `.env` file and add the following variables:

```
MC_HOST=YOUR MINECRAFT SERVER IP ADDRESS FOR BOT TO LOGIN
MC_PORT=PORT OF MINECRAFT SERVER
USERNAME=USERNAME FOR MINECRAFT ACCOUNT
PASSWORD=THIS IS REQUIRED FOR ONLINE MODE SERVERS
BOT_TOKEN=YOUR DISCORD BOT TOKEN
```

An example of a file could look like this:

```
MC_HOST=somedomainip.com
MC_PORT=22223
USERNAME=stuy
PASSWORD=somepassword
BOT_TOKEN=mybottokenfordiscord
```