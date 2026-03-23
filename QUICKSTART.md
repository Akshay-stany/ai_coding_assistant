# ⚡ Quick Start - Voice Chat Feature

## 🎯 What's New?

Your AI Coding Mentor now has **voice chat**! Speak your coding questions and hear AI responses.

---

## 🚀 Get Started in 3 Steps

### Step 1: Install Dependencies
```bash
pip install flask flask-cors python-dotenv groq
```

### Step 2: Set Groq API Key
Create `.env` file in project folder:
```
GROQ_API_KEY=your_api_key_here
PORT=5001
```
[Get free API key here](https://console.groq.com)

### Step 3: Start Backend
```bash
python chatbot_backend.py
```

### Step 4: Open Frontend
Open `chatbot_frontend.html` in your browser ✅

---

## 🎤 How to Use Voice

1. **Click 🎤 button** - Start listening
2. **Speak your question** - "How do I write a Python function?"
3. **See text appear** - Real-time recognition
4. **Stop speaking or press Escape** - Message sends automatically
5. **Listen to AI response** - Voice plays automatically! 🔊

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Enter` | Send text message |
| `Escape` | Stop recording |
| `🎤 Click` | Toggle voice |

---

## ✨ Features

✅ **Speech-to-Text** - Talk to the AI  
✅ **Text-to-Speech** - AI talks back  
✅ **Real-time Recognition** - See words as you speak  
✅ **Error Handling** - Helpful error messages  
✅ **Beautiful UI** - Modern, interactive design  
✅ **Chat History** - All conversations saved  
✅ **Statistics** - Track your learning  

---

## 🌐 Browser Support

| Browser | Status |
|---------|--------|
| Chrome | ✅ Best |
| Edge | ✅ Excellent |
| Safari | ✅ Great |
| Firefox | ✅ Good |
| Others | ⚠️ Limited |

---

## 🔧 Troubleshooting

### Microphone Not Working?
```
1. Check browser allows microphone (URL bar icon)
2. Test microphone works (system settings)
3. Try different browser
4. Restart browser
```

### Backend Not Running?
```
Error: "Connection error"
Solution: Run: python chatbot_backend.py
```

### API Key Error?
```
Error: "GROQ_API_KEY not set"
Solution: Create .env with: GROQ_API_KEY=your_key
```

### Speech Not Recognized?
```
Tips:
• Speak clearly and slowly
• Reduce background noise
• Use good microphone
• Try another sentence
```

---

## 📁 Project Files

```
├── chatbot_backend.py       ← Flask server
├── chatbot_frontend.html    ← Web interface (with voice!)
├── .env                     ← Your API key
├── chatbot.db              ← Chat history
├── VOICE_CHAT_GUIDE.md     ← Full voice guide
├── SETUP_GUIDE.md          ← Complete setup
└── VOICE_IMPLEMENTATION.md ← Technical details
```

---

## 📞 Documentation

- 📖 **VOICE_CHAT_GUIDE.md** - How to use voice features
- 🚀 **SETUP_GUIDE.md** - Complete installation guide
- ⚙️ **VOICE_IMPLEMENTATION.md** - Technical implementation

---

## 💡 Example Use Cases

### Example 1: Quick Question
```
You: "How do I make a loop?"
AI: Explains with voice + text
```

### Example 2: Complex Explanation
```
You (speaking): "Explain async await"
You (reading): Detailed explanation on screen
You (listening): AI reading it aloud
```

### Example 3: Mixed
```
You: Speak → Gets recognized → Edit text → Send
AI: Responds in voice + text
```

---

## ✅ What's Included

✨ **Enhanced Frontend**
- Microphone button with animations
- Real-time speech recognition
- Automatic voice responses
- Beautiful, modern UI
- Mobile responsive

✨ **Backend (Unchanged)**
- Flask API server (already working)
- Groq LLM integration
- SQLite database
- Chat history tracking
- Insights generation

✨ **Documentation**
- Voice usage guide
- Setup instructions
- Technical details
- Troubleshooting help

---

## 🎉 Ready to Go!

```
1. Run backend:        python chatbot_backend.py
2. Open frontend:      chatbot_frontend.html
3. Allow microphone:   (browser will ask)
4. Click 🎤 or type:   Start chatting!
5. Hear AI respond:    Automatic voice + text
```

**That's it! Enjoy your voice-enabled AI mentor! 🚀**

---

## 🆘 Still Having Issues?

### Check the Full Guides
- 📖 **VOICE_CHAT_GUIDE.md** - Comprehensive voice guide
- 🚀 **SETUP_GUIDE.md** - Step-by-step setup help
- ⚙️ **Console (F12)** - See error details

### Common Fixes
| Problem | Solution |
|---------|----------|
| No microphone | Check permissions in URL bar |
| Backend error | Verify Python packages installed |
| API key error | Create .env with GROQ_API_KEY=... |
| Speech not working | Try Chrome or Safari |
| No audio playing | Check system volume |

---

## 📊 System Requirements

```
✓ Python 3.8+
✓ Modern web browser (Chrome/Edge/Safari)
✓ Microphone (for voice input)
✓ Internet connection (for Groq API)
✓ Free Groq API key
```

---

## 🎯 Next Steps

1. ✅ Install dependencies
2. ✅ Get Groq API key
3. ✅ Create .env file
4. ✅ Start backend
5. ✅ Open frontend
6. ✅ Test microphone
7. ✅ Start learning!

---

**Version**: 2.0 with Voice Chat
**Status**: ✅ Production Ready
**Last Updated**: March 23, 2026

**Happy coding! 🚀🎤**
