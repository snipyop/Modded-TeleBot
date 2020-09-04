# TeleBot - Telegram UserBot
<p align="left">
    <a href="https://t.me/TeleBotHelpChat"> <img src="https://img.shields.io/badge/telegram-Support_Group-blue?style=social&logo=telegram" alt="Support" /></a>
    <a href="https://github.com/xditya/TeleBot/stargazers"><img src="https://img.shields.io/github/stars/xditya/TeleBot?style=social"></a>
    <a href="https://github.com/xditya/TeleBot"><img src="https://img.shields.io/github/last-commit/xditya/TeleBot?style=flat-square"></a>
</p>
    
## Video Tutorial on deploying
Click the below button to watch the video tutorial on deploying

<a href="https://youtu.be/XmvdDHiIDb4"><img src="https://img.shields.io/badge/How%20To-Deploy-blue.svg?logo=Youtube"></a>
<a href="https://youtu.be/XmvdDHiIDb4"><img src="https://img.shields.io/youtube/views/XmvdDHiIDb4?style=social">
## The Easier Way to install

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/xditya/TeleBot)

## Support
Join [TeleBot Support group](https://t.me/TeleBotHelp) for updates and new plugin suggestions.
Do fork and star the repo 

### Session String 
<a href="https://telebot-sessionstring-generator.xditya.repl.run/" target="_blank"><img src="https://img.shields.io/badge/run-string__session.py-red?style=for-the-badge&logo=repl.it" alt="generate_string" /></a>

### The Normal Way

Simply clone the repository and run the main file:
```sh
git clone https://github.com/xditya/TeleBot
cd TeleBot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create local_config.py with variables as given below>
python3 -m userbot
```

An example `local_config.py` file could be:

**Not All of the variables are mandatory**

__The Userbot should work by setting only the first two variables__

```python3
from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
```

### UniBorg Configuration

The UniBorg Config is situated in `userbot/uniborgConfig.py`.

**Heroku Configuration**
Simply just leave the Config as it is.

**Local Configuration**
Check [Line 111](https://github.com/Total-Noob-69/X-tra-Telegram/blob/master/userbot/uniborgConfig.py#L111) and start adding your vars there.
Fortunately there are no Mandatory vars for the UniBorg Support Config.

## Mandatory Vars

- Only two of the environment variables are mandatory.
- This is because of `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`
    - `APP_ID`:   You can get this value from https://my.telegram.org
    - `API_HASH`:   You can get this value from https://my.telegram.org
- The userbot will not work without setting the mandatory vars.

# Disclaimer
```
/**
    Your Telegram account may get banned.
    I am not responsible for any improper use of this bot
    This bot is intended for the purpose of having fun with memes,
    as well as efficiently managing groups.
    You ended up spamming groups, getting reported left and right,
    and you ended up in a Finale Battle with Telegram and at the end
    Telegram Team deleted your account?
    And after that, then you pointed your fingers at us
    for getting your acoount deleted?
    I will be rolling on the floor laughing at you.
/**
```


