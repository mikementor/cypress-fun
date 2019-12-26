# cypress-fun
[![CircleCI](https://circleci.com/gh/mikementor/cypress-fun.svg?style=svg)](https://circleci.com/gh/mikementor/cypress-fun)
Repo with ui tests
# How to install
```
git clone https://github.com/mikementor/cypress-fun.git
npm i
```
# How to make it work in circleci with telegram
    1. go to https://t.me/botfather , create new bot by /newbot command
    2. copy  bot token to (1)
    3. add bot to your group or start chat with bot 
    4. go to https://api.telegram.org/bot<your bot token>/getUpdates to get chatId (2)
    5. At  https://circleci.com/gh/<yourname>/cypress-fun/edit#env-vars
    add 
    TELEGRAM_BOT_TOKEN (1)
    TELEGRAM_CHAT_ID (2)