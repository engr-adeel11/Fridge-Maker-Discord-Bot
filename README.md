# 🧊 Fridge Maker Discord Bot

A fun and interactive Discord bot where users can **open loot boxes to build their own fridge**. Each fridge is unique, comes with random loot items (images), and can be shown off in the server.

---

## ✨ Features
- 🎁 Open a loot box to create your fridge.  
- 🧊 Display your fridge in the server with a slash command.  
- 🎨 Fun animated build messages for a playful experience.  
- 🔒 Each fridge is unique to the user, no duplicates.  

---

## ⚙️ Setup Instructions

1. Clone the repository or download the zip
2. Create a virtual environment
   
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
4. Install dependencies
   
   discord.py
   python-dotenv
5. Add your bot token
   
   In .env file add:
   TOKEN=your_discord_bot_token
6. Add fridge images

   Place your .png images in the same folder as bot.py.
   These will be randomly given when users create their fridge.
6. Run the bot

   python bot.py
