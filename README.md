# aria-telegram-mirror-bot

## This one supports Index Links. (Copy `index.ts` to your heroku Repo and add `INDEX_DOMAIN: '',` in `.constants.js`

## Watch Video
https://drive.google.com/file/d/1q5VVCCreOuXsujRzZkBAv12WJ1KZvQ0I/view

Avoid the Heroku Part

## Basic Documentation

* Fork this Repo
* Create a Telegram Bot
* Change Token in [Line 2](https://github.com/ParveenBhadooOfficial/aria-telegram-mirror-bot/blob/master/src/.constants.js)
* Please change Index URI or other as per your need.
* Create a Folder inside you Google Drive, open it and Copy it's ID.
* For `https://drive.google.com/drive/folders/1p7pHhSh2yboWePmo53DnVr3xkAYiojP9` `1p7pHhSh2yboWePmo53DnVr3xkAYiojP9` is ID.
* client_secret.json already added. Don't change unless you know what you're doing.
* Start an EC2 AWS Virtual Machine or Your Own Linux Machine.
* `bash <(curl -s https://cdn.jsdelivr.net/gh/jscdn/scripts@master/aria-telegram-mirror-bot-ready-server.sh)`
* `sudo git clone https://github.com/ParveenBhadooOfficial/aria-telegram-mirror-bot` Change this url to your fork url.
* `cd aria-telegram-mirror-bot`
* `sudo nano src/.constants.js` Use this to edit bot config in terminal
* `bash <(curl -s https://cdn.jsdelivr.net/gh/jscdn/scripts@master/aria-telegram-mirror-bot-start-bot.sh)`
* Your Bot is Started. Send `/mirror https://github.com/ParveenBhadooOfficial/aria-telegram-mirror-bot/blob/master/README.md` to your Telegram Bot.
* In Terminal Copy the accounts.google.com full url and paste in browser and authenticate your drive.
* Paste the Token you received in terminal.
* `sudo screen` at the beginning.
* This will run your bot in background even you close terminal. (otherwise Bot will go offline as soon as terminal session ends)
* To end all sessions and stop bot use `sudo reboot`

## License
The MIT License (MIT)

Copyright © 2020 out386
