# Telegram voice chatGPT app

Forked from [Vladilen Minin's repository](https://github.com/vladilenm/tgbot-gpt)

## Description

This application allows you to exchange requests with chatGPT in the format of voice messages to the Telegram bot

## Launch

Create config folder with files `default.json` & `production.json`:

```json
{
  "TELEGRAM_TOKEN": "<token>",
  "OPEN_AI_KEY": "<key>",
  "MONGO_URI": "<uri>"
}
```

Run following commands:

```ps
npm i
npm dev #for dev or
npm start #for production 
```

## Notes

`./config` folder (`default.json` & `production.json` files) and `.env` file are ignored by git due to sensitive data (API keys)