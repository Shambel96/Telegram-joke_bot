#🤖 Telegram Joke Bot

A simple Telegram bot built with Node.js that demonstrates API integration and message handling. The bot sends random jokes to users using a public jokes API.

## 🚀 Features

Sends a random joke when prompted by the user

Integrates with a public jokes API

Responds to user commands in real-time

Built using Node.js and Telegram Bot API

## 🛠️ Technologies Used

1. Node.js

2. Telegram Bot API

3. Axios or node-fetch for API requests (depending on your implementation)

## 💻 Setup & Installation

1. Clone the repository:

git clone https://github.com/yourusername/telegram-joke-bot.git
cd telegram-joke-bot



2. Install dependencies:

npm install


3. Create a .env file and add your Telegram Bot token:

TELEGRAM_BOT_TOKEN=your_bot_token_here


4. Start the bot:

node index.js


5. Interact with your bot on Telegram by sending /joke (or your defined command).

## 📂 Project Structure
├── index.js       # Main bot logic and API integration
├── package.json   # Project dependencies
└── .env           # Environment variables (Telegram Bot token)

## 💡 Learning Objectives

This project helped me practice:

Building a Telegram bot using Node.js

API integration and fetching data from external sources

Handling user input and commands

Sending dynamic messages using Telegram Bot API

## 🤝 Contribution

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to add or improve.