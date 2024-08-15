# Telegram Image Sender with Inline Keyboard and Fallback System

This repository contains a Python script to send single or multiple images with an inline keyboard to a Telegram chat. It also includes a fallback system to handle errors and send alerts to Slack.

## Features

- Send single or multiple images to a Telegram chat
- Inline keyboard with options
- Fallback system to send alerts to Slack
- Health and liveness checks using FastAPI
- Store and retrieve data using JSON
- Upload images to Google Drive

## Requirements

- Python 3.7+
- Telegram Bot API token
- Slack Bot API token
- Google Service Account credentials

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/telegram-image-sender.git
    
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up environment variables:

    ```bash
    export TELEGRAM_TOKEN='your-telegram-token'
    export TELEGRAM_CHAT_ID='your-telegram-chat-id'
    export SLACK_BOT_TOKEN='your-slack-bot-token'
    export GOOGLE_CREDS='path-to-your-google-credentials.json'
    ```

## Usage

1. Run the FastAPI server:

    ```bash
    python main.py
    ```

2. Send a POST request to
