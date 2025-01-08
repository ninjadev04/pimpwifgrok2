# Blockchain Pimp Bot 🤖💎

Blockchain Pimp Bot is a smart, witty, and assertive Discord bot powered by the **GROK API**. Designed for the blockchain and crypto community, it combines humor, blockchain jargon, and swagger to engage users while managing tasks like sentiment analysis, extracting entities, and responding to questions concisely. This bot can even post tweets, tag users in Discord, and engage with custom responses tailored for crypto enthusiasts.

---

## Features 🌟

- **GROK API Integration**: Generates concise, intelligent, and humorous responses using the GROK-2 model.
- **Discord Integration**: Responds to users on Discord with mentions and dynamic interactions.
- **Twitter Integration**: Posts scheduled tweets every 30 minutes with insights, humor, and trends in crypto.
- **Sentiment Analysis**: Analyzes user input sentiment using VADER for better contextual responses.
- **Entity Extraction**: Uses spaCy NLP to extract crypto-related keywords and entities.
- **Custom Responses**: Predefined responses for specific queries like promoting `$PAIMP`.
- **User Mentions**: Automatically tags users in Discord responses to create engaging and interactive replies.
- **Error Handling**: Robust error handling with logging for HTTP and system-level issues.

---

## How It Works 🛠️

1. **Discord Bot**: Listens to messages in Discord channels and responds with swagger using GROK-2.
2. **Twitter Bot**: Posts crypto-related tweets at regular intervals to maintain engagement.
3. **NLP Processing**: Sanitizes user inputs, performs sentiment analysis, and extracts entities to tailor responses.
4. **GROK API**: Calls the GROK-2 model to generate AI-based responses with humor and intelligence.

---

## Setup 🧩

### Prerequisites
- Python 3.11 or later
- A Discord Bot token
- GROK API Key
- Twitter Developer Keys
- Required Python dependencies (see `requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ninjadev04/pimpwifgrok2.git
   cd pimpwifgrok2
2. Create a virtual environment:
bash
python -m venv pimpgrok_env
source pimpgrok_env/bin/activate  # For Windows: pimpgrok_env\Scripts\activate

3. Install dependencies:
bash
pip install -r requirements.txt

4. Configure your credentials in configs/config.json:
json
{
    "DISCORD_TOKEN": "your_discord_token",
    "GROK_API_KEY": "your_grok_api_key",
    "TWITTER_API_KEY": "your_twitter_api_key",
    "TWITTER_API_SECRET_KEY": "your_twitter_secret_key",
    "TWITTER_ACCESS_TOKEN": "your_twitter_access_token",
    "TWITTER_ACCESS_TOKEN_SECRET": "your_twitter_access_secret"
}

5. Run the bot:
bash
python grok2.py

### Usage 🚀
Discord Commands: Mention the bot or ask questions, and it will reply with humorous and blockchain-savvy responses.
Twitter Posting: Automatically posts tweets with blockchain and crypto insights every 30 minutes.
User Mentions: When users are tagged in Discord, the bot will tag them back in its replies.

### Key Technologies 💻
- Discord.py: For Discord bot integration.
- GROK API: Powers the AI-driven responses.
- spaCy & VADER: Handles sentiment analysis and entity recognition.
- Tweepy: For seamless Twitter integration.
- httpx: Used for secure and efficient API requests.

### Contributing 🤝
Contributions are welcome! Feel free to fork this repository, create a branch, and submit a pull request. Ensure your changes are well-tested and documented.

### License 📜
This project is licensed under the MIT License. See the LICENSE file for details.
