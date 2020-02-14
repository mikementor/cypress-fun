# cypress-fun

[![CircleCI](https://circleci.com/gh/mikementor/cypress-fun.svg?style=svg)](https://circleci.com/gh/mikementor/cypress-fun)
Repo with ui tests


### Table of Contents

1.  [Requirements](#Requirements)
2.  [Prerequisites](#prerequisites)
3.  [How to install](#how-to-install)
4.  [Environment variables](#environment-variables)
5.  [How to run](#how-to-run)
6.  [Run on different environments](#run-on-different-environments)
7.  [Reporting](#reporting)
8.  [Notifications](#notifications)
9.  [How to write tests](#how-to-write-tests)
10. [Maintainers](#maintainers)
11. [Known issues](#known-issues)
12. [Also](#also)


### Requirements


### Prerequisites
- [Nodejs](https://nodejs.org/en/)

### How to install

```
git clone https://github.com/mikementor/cypress-fun.git
yarn add
```
### Environment variables
### How to run
```
yarn run cy:run
```
### Run on different environments
[TBD]
### Reporting
[TBD]
### Notifications
[TBD]
### How to write tests
[TBD]
### Maintainers
[TBD]
### Known issues
[TBD]

### Also
### How to make it work in circleci with telegram

    1. go to https://t.me/botfather , create new bot by /newbot command
    2. copy  bot token to (1)
    3. add bot to your group or start chat with bot
    4. go to https://api.telegram.org/bot<your bot token>/getUpdates to get chatId (2)
    5. At  https://circleci.com/gh/<yourname>/cypress-fun/edit#env-vars
    add
    TELEGRAM_BOT_TOKEN (1)
    TELEGRAM_CHAT_ID (2)

### How to develop

I've got a pre-hook on commit-msg
So commit msg should meet format :
type(scope?): subject #scope is optional
Examples:
`fix(server): send cors headers`
`feat(blog): add comment section`
See https://github.com/conventional-changelog/commitlint/#what-is-commitlint
