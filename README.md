# Simsimi Telegram Bot
This is example how simsimi API work on python for telegram bot

## How to use
First of all, register SimSimi API and Bot Telegram API first.
Register SimSimi API [in here](http://developer.simsimi.com/signUp)
Register Bot Telegram API [in here](http://t.me/BotFather)
Then edit simsimi.py using text editor.
Place your API Telegram bot to `TOKEN` and Simsimi API to `SimsimiKey`
Then open terminal/cmd, install requirements first using `pip install -r requirements.txt`
Last, run bot using `python simsimi.py`, if it say `Running bot success!` it running successfully. Test bot by yourself.

### How to work on telegram groups
Edit simsimi.py using text editor.
See line 31, replace `Filters.private` with `Filters.group`
Note: using `Filters.group` will reply every send text on your group.
More info on `Filters`, [see here](http://python-telegram-bot.readthedocs.io/en/latest/telegram.ext.filters.html)

## Screenshot
![Simsimi bot telegram](http://kentod.heliohost.org/kentod.heliohost.org/ayra/simsimibot.jpg "Simsimi Telegram Bot")

## Q&A
If you need help, join [@NusantaraDevs](https://t.me/NusantaraDevs) and ask me in group, not PM. i will answer you as long as possible.
