# Phish Telegram Bot

The bot is called `@gone_phishing_bot`

Deployed at `https://phish-telegram-bot.herokuapp.com/`

Commands:
Still in development

Notes:
Environmental variables are stored as [heroku config vars](https://devcenter.heroku.com/articles/config-vars)

The environmental variables stored are:
1. BOT_TOKEN=`bot_token` (token for `@gone_phishing_bot` from BotFather)
2. BOT_USERNAME=`username` (username for `@gone_phishing_bot` from BotFather)
3. URL=`url` (url of heroku app)
4. PHISHNET_API_KEY=`api_key` (API Key for Phish.Net, [retrieved here](https://api.phish.net/request-key))
5. PHISHIN_API_KEY=`api_key` (API Key for Phish.in can be requested at the [contacts page](https://phish.in/contact-info) and info about the api can be found in the [api docs](https://phish.in/api-docs))

To Do:
1. Make sure json responses for required functions are not more than one page with if/else
2. Set option for only soundboards?
3. Make date format acceptance broader than just YYYY-MM-DD
4. Pytest
5. Mypy
6. Black
7. Phish Trivia Game!
8. `make dev` Makefile, include setting up environment if doesn't exist, logging in to heroku if not logged in (try if/else statement) and then export creds to environment
9. Create md file for commands