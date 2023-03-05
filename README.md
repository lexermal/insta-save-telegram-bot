# insta-save-telegram-bot based on [aiogram](https://aiogram.dev/) and [instaloader](https://github.com/instaloader/instaloader)  


This fork includes my experience working with that project, I did not manage to try it out past the login process

---

## Installation
```
git clone https://github.com/kyemets/insta-save-telegram-bot.git
pip install -r requirements.txt
pip install keyboard
```

## Run it
```python3 bot.py```

## Environment variables
- `TOKEN` — Telegram bot token 
- `USERNAME` — Instagram username account 
- `PASSWORD` — Instagram password account

## P.S. ⚠️ The bot does not work with closed instagram profiles ⚠️ 

## Todo
* Docker container
* ENV variables do not get set in script when set in bash
* 2F login does not work, it's always saying code is invalid
