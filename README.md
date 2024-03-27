# Reddit Weekly Bot

> Telegram bot that allows subscribing to weekly popular Reddit posts in subreddits of your choice.

# how to run 
`docker build -t redditbot:v1.0 .`

`docker run -d --name redditbot -e TG_TOKEN=token -e DATABASE_URL=file:./reddit.db -e TG_AUTHOR=yourID -e BOT_NAME=yourBotName redditbot:v1.0`


![build-test-publish](https://github.com/aldis-ameriks/reddit-bot/workflows/build-test-publish/badge.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<p align="center">
  <img src="bot.png" width="668">
</p>
