# JARVIS Chatbot - Quick Start Guide ⚡

Get your AI chatbot running in 5 minutes!

## Step 1: Get Your OpenAI API Key

1. Go to [OpenAI API Keys](https://platform.openai.com/api-keys)
2. Create a new API key
3. Copy it (you'll need it in the next step)
4. **Important:** Never share this key publicly!

## Step 2: Setup & Installation

```bash
# Navigate to project directory
cd JARVIS

# Create virtual environment
python3 -m venv venv

# Activate virtual environment
# On macOS/Linux:
source venv/bin/activate
# On Windows:
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Create .env file
cp .env.example .env

# Edit .env file and paste your API key:
# OPENAI_API_KEY=sk-proj-... (your actual key)
```

## Step 3: Run the Application

```bash
python app.py
```

You should see:
```
🤖 JARVIS Chatbot is starting...
📍 Visit http://localhost:5000
```

## Step 4: Open in Browser

Open your browser and go to: **http://localhost:5000**

## Usage

1. **Type a message** in the input field
2. **Press Enter** or click the **➤ Send** button
3. **Wait for response** from JARVIS
4. **Continue chatting** or use action buttons:
   - **🗑️ Clear Chat** - Start a fresh conversation
   - **📊 Status** - Check server information

## Common Commands to Try

```
- "What is Python?"
- "Explain machine learning"
- "How do I learn web development?"
- "Tell me a joke"
- "What is your name?"
- "How can you help me?"
```

## Stopping the Application

Press `Ctrl+C` in your terminal to stop the chatbot.

## Restarting After Stopping

```bash
# Activate virtual environment if needed
source venv/bin/activate  # macOS/Linux
# or
venv\Scripts\activate  # Windows

# Run the app again
python app.py
```

## Troubleshooting

| Problem | Solution |
|---------|----------|
| `OPENAI_API_KEY not found` | Check if `.env` file exists and has your API key |
| `ModuleNotFoundError` | Run `pip install -r requirements.txt` |
| `Port 5000 already in use` | Close other programs using port 5000 or change port in `app.py` |
| No response from AI | Check your internet connection and API key validity |

## Next Steps

- ✅ Read the full [README.md](README.md) for advanced features
- ✅ Customize the UI in `static/styles.css`
- ✅ Modify backend behavior in `app.py`
- ✅ Deploy to cloud (Heroku, AWS, DigitalOcean)

## Need Help?

1. Check [OpenAI Documentation](https://platform.openai.com/docs)
2. Review error messages in terminal
3. Make sure your API key has credits remaining

---

**Enjoy chatting with JARVIS! 🚀**
