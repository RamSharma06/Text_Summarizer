# Text Summarizer Bot with Sentiment Analysis 🤖

## Description
This is a Telegram bot that provides text summarization and sentiment analysis using Cohere's NLP model and TextBlob. The bot allows users to send long pieces of text and receive concise summaries along with sentiment classification (Positive, Negative, or Neutral).

## Features
- 📌 **Summarizes long texts** into concise and readable summaries.
- 📊 **Performs sentiment analysis** to determine whether the text is positive, negative, or neutral.
- 🔄 **Automated Telegram bot** that responds instantly.

## Technologies Used
- 🛠 **Python** (Core programming language)
- 🤖 **Cohere API** (Text summarization)
- 📝 **TextBlob** (Sentiment analysis)
- 📡 **Telebot (pyTelegramBotAPI)** (Telegram bot integration)
- 🔒 **Dotenv** (Environment variable management)

## Installation & Setup
### Prerequisites
Make sure you have Python installed on your system. You also need to obtain API keys for:
- [Cohere API](https://cohere.com/)
- [Telegram Bot API](https://core.telegram.org/bots)

### Steps to Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/text-summarizer-bot.git
   cd text-summarizer-bot
2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
3. **Create a .env file and add your API keys:**
    ```bash
    echo "COHERE_API_KEY=your-cohere-api-key" >> .env
    echo "TELEGRAM_BOT_API_KEY=your-telegram-bot-api-key" >> .env
4.**Run the bot**
  ```bash
     python bot.py
