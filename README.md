# JMusicBot on Heroku 🎶
Deploy [jagrosh's Discord music bot](https://github.com/jagrosh/MusicBot/) on Heroku. Click the button below to get started!

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/iCrazyBlaze/music-bot-heroku)

# **DISCLAIMER**
Running the bot on Heroku is not recommended at all if you are running it on multiple servers. The peformance is pretty terrible, and should only really be used as a stop-gap or temporary solution for one server if it's really necessary. See this page for more details: https://jmusicbot.com/hosting

# Setup
Once you have created the app on Heroku, go into **Manage app > Settings > Config Vars** and add a configuration value called `base64_encoded_config`.

Then, take your [config.txt file for MusicBot](https://jmusicbot.com/setup#3%EF%B8%8F%E2%83%A3-edit-the-config-file) and [convert it to base64](https://base64.guru/converter/encode/file).

Paste the base64 value into the value box and save your changes. **Your bot should come online shortly after!**

## Please refer to [Adding Your Bot](https://jmusicbot.com/adding-your-bot) for how to add your bot to your Discord server.
## Check [the wiki](https://jmusicbot.com/setup) for more information!
