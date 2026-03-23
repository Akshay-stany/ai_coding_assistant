# 🚀 AI Coding Mentor with Voice Chat - Complete Setup Guide

## What's New? 🎤

Your AI Coding Mentor now includes **real-time voice chat**:
- 🎤 **Speech-to-Text** - Speak your coding questions
- 🔊 **Text-to-Speech** - AI responds with voice
- ✨ **Beautiful UI** - Modern, interactive interface
- 📊 **Analytics** - Track your learning insights
- 💡 **Smart Features** - Real-time text recognition, error handling

---

## 📋 Prerequisites

Before running the application, make sure you have:

1. **Python 3.8+** installed
2. **Pip package manager**
3. **A microphone** (for voice features)
4. **Groq API Key** (free from https://console.groq.com)
5. **Modern web browser** (Chrome, Edge, Safari, or Firefox)

---

## 🔑 Getting Your Groq API Key

1. Visit [https://console.groq.com](https://console.groq.com)
2. Sign up (free account)
3. Go to API Keys section
4. Create a new API key
5. Copy the key

---

## ⚙️ Installation & Setup

### Step 1: Install Dependencies

```bash
cd "c:\Users\aksha\Downloads\ai_coding-main\ai_coding-main"
pip install flask flask-cors python-dotenv groq
```

### Step 2: Create `.env` File

Create a file named `.env` in the project directory:

```env
GROQ_API_KEY=your_api_key_here
PORT=5001
```

Replace `your_api_key_here` with your actual Groq API key.

### Step 3: Start the Backend

```bash
python chatbot_backend.py
```

You should see:
```
🚀 Starting AI Coding Mentor Chatbot on http://127.0.0.1:5001
 * Running on http://127.0.0.1:5001
```

### Step 4: Open the Frontend

1. Navigate to: `c:\Users\aksha\Downloads\ai_coding-main\ai_coding-main\`
2. Open `chatbot_frontend.html` in your web browser
3. Allow microphone access when prompted
4. Start chatting or speaking!

---

## 📁 Project Structure

```
ai_coding-main/
├── chatbot_backend.py          # Flask API server
├── chatbot_frontend.html       # Interactive web interface (WITH VOICE)
├── chatbot.db                  # SQLite database (auto-created)
├── requirements.txt            # Python dependencies
├── VOICE_CHAT_GUIDE.md         # Voice chat features guide
├── SETUP_GUIDE.md              # This file
└── .env                        # Your API key (create this)
```

---

## 🎯 Key Components

### Backend (Flask)
- **`/chat` endpoint** - Accepts text messages and returns AI responses
- **`/history` endpoint** - Gets chat history and insights
- **`/clear` endpoint** - Clears all chat data
- **`/health` endpoint** - Health check

### Frontend (HTML/CSS/JavaScript)
- **Web Speech API** - Speech recognition (voice-to-text)
- **Speech Synthesis API** - Text-to-speech
- **Modern UI** - Beautiful, responsive design
- **Real-time feedback** - Visual indicators for recording

---

## 🎤 Voice Chat Features

### Microphone Button (🎤)
- Located next to the Send button
- Shows animated pulse when recording
- Red dot indicator when listening
- Click to toggle voice recording

### Real-time Recognition
- See your spoken text as you speak
- Green indicator box shows recognized text
- Automatically sends when you stop speaking

### Voice Response
- AI automatically reads response aloud
- Continues working while you read
- Can be controlled by browser settings

---

## 💡 Usage Examples

### Example 1: Pure Voice
```
1. Click 🎤 button
2. Speak: "How do I write a Python function?"
3. See text appear in real-time
4. AI responds in text AND voice
5. Listen to explanation on functions
```

### Example 2: Mixed Input
```
1. Click 🎤 → Say "Python loops"
2. Text shows: "Python loops"
3. Edit to: "How do for loops work in Python?"
4. Click Send
5. Hear detailed explanation
```

### Example 3: Quick Questions
```
1. Type in textbox (faster than voice)
2. Press Enter
3. Hear AI response automatically
```

---

## 🔧 Troubleshooting

### Backend Won't Start
```
Error: ModuleNotFoundError: No module named 'flask'
Solution: pip install flask flask-cors python-dotenv groq
```

### Connection Error in Frontend
```
Error: "Connection error. Make sure backend is running..."
Solution: 
1. Check backend is running (you should see the server message)
2. Make sure port 5001 is not blocked
3. Restart the backend
```

### Microphone Not Working
```
Steps to fix:
1. Check browser allows microphone access (check URL bar)
2. Test microphone works (system settings)
3. Try a different browser
4. Restart browser and try again
5. Check microphone is not muted
```

### Speech Recognition Not Available
```
Message: "Speech Recognition not supported in your browser"
Solution: Use Chrome, Edge, or Safari
```

### API Key Error
```
Error: "GROQ_API_KEY environment variable not set"
Solution:
1. Create .env file with GROQ_API_KEY
2. Restart the backend
3. Verify .env is in project root
```

---

## 📊 Environment Variables

### `.env` File Options

```env
# Required
GROQ_API_KEY=your_groq_api_key_here

# Optional (defaults shown)
PORT=5001
DEBUG=False
```

---

## 🚀 Running Everything

### Quick Start (3 commands)
```bash
# Terminal 1: Start backend
python chatbot_backend.py

# Then in your browser:
# Open: chatbot_frontend.html
```

### Run in Background
```bash
# Start backend in background (Windows PowerShell)
Start-Process python -ArgumentList "chatbot_backend.py" -NoNewWindow

# Or use task scheduler for persistent running
```

---

## 📝 Features Breakdown

### What Works
✅ Text chat (type and send)
✅ Voice chat (speak and send)
✅ AI text responses
✅ AI voice responses (auto-play)
✅ Chat history tracking
✅ Learning insights database
✅ Real-time text recognition
✅ Beautiful modern UI
✅ Mobile responsive design
✅ Error notifications
✅ Statistics dashboard

### Coming Soon (Possible Enhancements)
🔜 Multiple language support
🔜 Voice recording download
🔜 Chat export to PDF
🔜 Mobile app version
🔜 Advanced analytics

---

## 🔐 Security Notes

- API key should never be committed to version control
- Keep `.env` file private
- Use environment variables for sensitive data
- Chat history stored locally (SQLite)
- All data stays on your local machine

---

## 📈 Performance Tips

1. **Use English** - Best language support
2. **Speak clearly** - Improves recognition
3. **Good microphone** - Better quality recognition
4. **Quiet environment** - Less background noise
5. **Stable internet** - For API calls

---

## 🆘 Getting Help

### Check These First
1. Is backend running? (Port 5001 accessible?)
2. Is API key set in `.env`?
3. Does microphone work in your browser?
4. Are you using a supported browser?
5. Is internet connection stable?

### Debug Mode
Open browser console (F12) to see:
- Detailed error messages
- API responses
- Speech recognition events
- Synthesis events

---

## 📚 Additional Resources

- [Groq API Documentation](https://console.groq.com/docs/api-overview)
- [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)
- [Flask Documentation](https://flask.palletsprojects.com/)
- [Browser Compatibility](https://caniuse.com/)

---

## 📞 Support

If you encounter issues:
1. Check the console (F12) for error messages
2. Read VOICE_CHAT_GUIDE.md for voice-specific help
3. Verify all prerequisites are installed
4. Try the troubleshooting section above
5. Restart browser and backend

---

## 🎉 You're All Set!

Your AI Coding Mentor is now ready to help you learn programming with voice chat capabilities!

**Start the backend, open the frontend, and begin learning! 🚀**

---

**Built with ❤️ | Last Updated: March 2026**
