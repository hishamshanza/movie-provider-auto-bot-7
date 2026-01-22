🎬 Movie Provider Auto Bot 7
A Telegram auto movie provider bot built using Python & Pyrogram, designed to automatically serve movies/files from a database or channel when users search.
🚀 Features
🔍 Auto movie search & filter
📂 Files fetched from Telegram channels
🤖 Fully automatic reply system
⚡ Fast & lightweight
☁️ Easy deployment (Render / Railway / VPS)
🧾 Supports multiple movies with same name
🔐 Admin-only controls
🛠 Tech Stack
Language: Python 3
Library: Pyrogram
Database: MongoDB
Hosting: Render / Railway / VPS
Bot API: Telegram Bot API
📁 Project Structure
Copy code

movie-provider-auto-bot-7/
│
├── bot.py
├── config.py
├── database.py
├── plugins/
│   ├── start.py
│   ├── filter.py
│   └── admin.py
│
├── requirements.txt
├── Procfile
├── Dockerfile
└── README.md
⚙️ Configuration
Create a .env file or set environment variables:
Copy code
Env
BOT_TOKEN=your_bot_token
API_ID=your_api_id
API_HASH=your_api_hash
MONGO_DB_URI=your_mongodb_uri
CHANNEL_ID=your_channel_id
ADMINS=123456789
▶️ Run Locally
Copy code
Bash
git clone https://github.com/hishamshanza/movie-provider-auto-bot-7
cd movie-provider-auto-bot-7
pip install -r requirements.txt
python bot.py
☁️ Deploy on Render
Fork this repo
Go to Render → New Web Service
Connect GitHub repo
Set Environment Variables
Start command:
Copy code
Bash
python bot.py
👑 Admin Commands
Command
Description
/start
Start the bot
/stats
Bot statistics
/broadcast
Message all users
/add
Add new movie
⚠️ Disclaimer
This project is for educational purposes only.
Do NOT use this bot to share copyrighted content illegally.
The developer is not responsible for misuse.
❤️ Credits
Pyrogram
Telegram
Open Source Community
📞 Support
If you face any issues, open an Issue or contact the developer.
