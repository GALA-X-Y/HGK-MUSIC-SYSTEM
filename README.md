# **HGK Music System**
## Introduce you the **NEW** music plugin for your Discord bot
### Features of HGK Music System
- Power by **Discord.py** / **Python**
- **High quality** audio
- Support **YouTube** / **Spotify**
- Last and the most important -- Totally **Free**
### Finding a music plugin for your **Python** Discord bot?
Over **80%** of Discord Music Bot powered by **Discord.js** or **JDA (Java Discord API)**.  
We provided you a choice by using **Discord.py**.  
### Already have a bot powered by Discord.py?  
Don't worry, adding this plugin won't conflict with your own commands.$^1$  
Simply follow steps below in **"Add as external cogs or extensions"**.

### Haven't had a bot yet?
Simply follow steps below in **"Setup guide for beginners"**.
***
## Installation of the plugin
### Extensions required
1. Discord.py 
2. Request
3. PyNaCl
4. FFmpeg (Installation in **"Setup guide for beginners"**)

To install extension upward (Besides FFmpeg) type in cmd:

    pip install (Extension Name)
### Setup guide for beginners
1. Installation of FFmpeg
>1. Install the FFmpeg zip file from its [website](https://ffmpeg.org/download.html#build-windows).
>2. Extract the zip if there is three components. (<kbd>ffmpeg.exe</kbd>, <kbd>ffprobe.exe</kbd>, <kbd>ffplay.exe</kbd>)  
>3. Copy <kbd>ffmpeg.exe</kbd> under your python path. (...\Python\Python39 $^2$\Script)
2. Get your Discord bot token
>1. Go [Discord Developer Portal](https://discord.com/developers/applications).
>2. Click **New Application**.
>3. Select Bot and click **Add Bot**.
>4. Reset your token and click **Copy**. (Don't lost it, or otherwise you need to reset it again)
>5. Select OAuth2/URL Generator and tick the **bot** box in order to get the invite link of the bot.
3. Run the bot
>1. Paste your token to **"Token"** field of <kbd>setting.json</kbd>.
>2. Check if you have installed all extension required and run  <kbd>main.py</kbd>.
>3. Enjoy your music!
### Add as external cogs or extensions
1. Put <kbd>music.py</kbd> into your folder.
2. Add `bot.load_extension("music")` before `bot.run(token)`. (Or `client.load_extension("music")` if you use "client" as bot item)
3. Create a folder with name <kbd>json</kbd> in the main folder.
4. Check if you have installed all extension required and run your bot.
5. Enjoy your music!

##### $^1$: Commands like play, add, remove, queue, disconnect and etc. will conflict with the plugin.
##### $^2$: Number after Python can be different depends on the versions. e.g. Python38, Python310
