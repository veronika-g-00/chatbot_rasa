# chatbot_rasa

This project is a chatbot built with Rasa and integrated with Discord, designed to handle customer inquiries for a restaurant.

**Set up:**

1. Create a virtual environment
```
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate  # Windows
```

2. Install dependencies

```
pip install rasa
pip install discord
```

3. Set the Discord bot token
```
export DISCORD_TOKEN="YOUR_TOKEN"  # Linux/macOS  
set DISCORD_TOKEN=YOUR_TOKEN  # Windows (CMD)  
$env:DISCORD_TOKEN="YOUR_TOKEN"  # Windows (PowerShell)  
```

4. Run the Discord bot
```
python discord_connector.py
```

5. Start Rasa actions server
```
rasa run actions
```

6. Run the chatbot
```
rasa run
```
