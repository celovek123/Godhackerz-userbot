# GOD HACKERZ USERBOT 
   A powerful Userbot Made with Love from Team Godhackerz
   
   
   # <p align="left"><a href="https://github.com/rohithaditya/Godhackerz-userbot"><img src="https://github-readme-stats.vercel.app/api/pin?username=xditya&show_icons=true&theme=dark&hide_border=true&repo=Godhackerz-userbot"></a></p><p align="centre"><a href="https://t.me/Godhackerzuserbot"> <img src="https://img.shields.io/badge/telegram-Support_Group-blue?style=social&logo=telegram" alt="Support" /></a><a href="https://github.com/rohithaditya/Godhackerz-userbot/stargazers"><img src="https://img.shields.io/github/rohithaditya/Godhackerz-userbot/stars/?style=social"></a><a href="https://github.com/rohithaditya/Godhackerz-userbot/fork"><img src="https://img.shields.io/github/forks/rohithaditya/Godhackerz-userbot/?label=Fork&logoColor=blue&style=social"></a>	<a href="https://github.com/rohithaditya/Godhackerz-userbot/"><img src="https://img.shields.io/github/last-commit/rohithaditya/Godhackerz-userbot/?style=flat-square"></a></p>

 
<p align="center">
<img src="https://telegra.ph/file/cffc1ef157c0a8b692924.jpg" alt="GodHackerz USERBOT">


## (C) By Team #GodHackerz

### JOIN SUPPORT GROUP FOR HELP IN 24/7 
<a href="https://t.me/Godhackerzuserbot"><img src="https://img.shields.io/badge/Join-Telegram%20Group-blue.svg?logo=telegram"></a>


### Host YOUR DREAM USERBOT  In Heroku
  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/celovek123/Godhackerz-userbot/tree/main)

## For Your STRING SESSION 
[![Run on Repl.it](https://repl.it/badge/github/rohithaditya/Godhackerz-userbot)](https://GodHackerz-Userbot.rohithaditya.repl.run)

## APP ID AND HASH 
FOR THAT Go to [CLICK HERE FOR YOUR API ID AND HASH](https://my.telegram.org) Login WIth YOUR PHONE NUMBER AND GET YOUR API ID 

## THANKS TO [CharlieJin](https://t.me/Charlie_jin) For Guiding me 


### The Normal Way

Simply clone the repository and run the main file:
```sh
git clone https://github.com/rohithaditya/Godhackerz-userbot
cd Godhackerz-userbot
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
Fortunately there are no Mandatory vars for the UniBorg Support Config.

## Mandatory Vars

- Only two of the environment variables are mandatory.
- This is because of `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`
    - `APP_ID`:   You can get this value from https://my.telegram.org
    - `API_HASH`:   You can get this value from https://my.telegram.org
- The userbot will not work without setting the mandatory vars.
