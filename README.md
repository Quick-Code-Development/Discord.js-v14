Quick-Code-Development Discord.js v14 Bot
Welcome to the Quick-Code-Development Discord.js v14 Bot, a feature-rich and flexible Discord bot designed to elevate your server experience. Follow the steps below to set up and unleash the potential of this bot in your community.

# Getting Started
Clone the Repository:

```bash
git clone https://github.com/Quick-Code-Development/Discord.js-v14.git
cd qcd-bot
```
Install Dependencies:

```bash
npm install
```

# Configure Bot Settings:

Copy the config.example.json file to config.json.
Open config.json and fill in the required values:
token: Your Discord bot token.
prefix: Command prefix for the bot.
ownerID: Your Discord user ID.
Features
Command Categories:

General
Moderation
Fun
Utilities
and more...
Customizable Prefix:

Change the bot's command prefix to align with your server's preferences.
Moderation Tools:

Kick, ban, mute, and more to maintain order in your server.
Fun and Games:

Engage your community with entertaining commands and games.
Utilities:

Weather, user info, and other helpful tools.
Database Integration
This bot integrates with MongoDB for extended functionality. Set up MongoDB using the following steps:

Create a MongoDB Cluster:

Visit MongoDB Atlas and create a free cluster.
Get Connection String:

In your MongoDB Atlas dashboard, obtain the connection string.
Configure config.json:

Add the mongoURI field in config.json with your connection string.
Running the Bot
bash
```bash
node index.js
```
# Bot Info
Your Quick-Code-Development Discord.js v14 Bot is now operational! Customize, expand, and enjoy the diverse features it brings to your Discord server.

For detailed information, consult the Documentation.

Contributing
Contributions are encouraged! Fork the repository, make your changes, and submit a pull request.

Happy coding and botting!
