# Channel Auto-Post Bot

This bot can send all new messages from one channel, directly to another channel (or group, just in case), without the forwarded tag!

## Setting up 
* First:
> `APP_ID` and `API_HASH` - Get it from my.telegram.org   
> `BOT_TOKEN` - Get it from [@BotFather](https://t.me/BotFather)  
> `FROM_CHANNEL` - Channel id which you forward posts from
> `TO_CHANNEL` - Channel which you want to forward posts

You must add your bot to both channels as admin before deploy

* Chose a platform to deploy on:
<details>
<summary>Heroku/Kintohub/Zeet</summary>
<br>
Add the above values to the environment vars and deploy the bot.
</details>
<details>
<summary>Local Deploys</summary>
<br>
- Clone the repo:   <code>git clone https://github.com/ImJanindu/ChannelAutoPost</code></br>
- Make a <code>.env</code> file in the root of the repo, like <a href="https://github.com/ImJanindu/ChannelAutoPost/blob/main/.env.sample">.env.sample</a> and fill in the values.</br>
- Use <code>python3 bot.py</code> to start the bot.</br>  
</details>

## Usage
Add the bot to both channels with admin permission, and thats it!
All new messages will be auto-posted!!

Visit [@Infinity_BOTs](https://t.me/Infinity_BOTs) for updates.
## Credits
> [Lonami](https://github.com/LonamiWebs), for [Telethon](https://github.com/LonamiWebs/Telethon).   
> [xditya](https://github.com/xditya)   
> [@ettan_fan](https://t.me/ettan_fan)
