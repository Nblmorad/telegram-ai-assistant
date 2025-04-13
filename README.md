
# Telegram AI Assistant Bot

This is a smart Telegram bot connected to ChatGPT (OpenAI) with the ability to:
- Respond to any user message with GPT.
- Translate any text using `/translate` command.

## Environment Variables
- `TELEGRAM_TOKEN`
- `OPENAI_API_KEY`

## Run Locally
```
pip install -r requirements.txt
python bot.py
```

## Deploy to Render
- Connect your GitHub repo.
- Set build command: `pip install -r requirements.txt`
- Set start command: `python bot.py`
