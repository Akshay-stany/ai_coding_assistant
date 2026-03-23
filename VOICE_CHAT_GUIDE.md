# 🎤 AI Coding Mentor - Voice Chat Feature Guide

## Overview
Your AI Coding Mentor now has real-time voice chat capabilities! You can:
- **Speak your coding questions** using your microphone
- **Receive AI responses as voice** automatically played back
- **See real-time text transcription** as you speak
- **Mix and match** typing and speaking

---

## ✨ Features

### 1. **Voice Recognition (Speech-to-Text)**
- Click the 🎤 **Microphone button** to start speaking
- The app displays text as you speak in real-time
- Press **Escape** or click the button again to stop recording
- Your spoken text is automatically sent to the AI mentor

### 2. **Voice Response (Text-to-Speech)**
- AI responses are automatically converted to voice
- Listen while reading the text in the chat
- Control volume through your system settings

### 3. **Visual Feedback**
- **🎤 Listening indicator** - Shows when the mic is active with animated dots
- **Green pulsing animation** on the mic button during recording
- **Real-time text display** - See what you're saying as you speak
- **Error messages** - Clear notifications if anything goes wrong

### 4. **Smart Controls**
- **Microphone Button (🎤)** - Toggle voice recording on/off
- **Send Button (📤)** - Send your message (text or voice)
- **Clear Button (🗑️)** - Clear all chat history
- **Enter Key** - Send text messages quickly
- **Escape Key** - Stop recording during voice input

---

## 🚀 How to Use

### Getting Started
1. **Open the webpage** - Load `chatbot_frontend.html` in your browser
2. **Grant microphone permission** - Your browser will ask for permission
3. **Type or speak** - Choose your preferred input method

### Speaking to the AI
1. Click the 🎤 button to start listening
2. Wait for "Listening..." indicator to appear
3. Speak your coding question naturally
4. Stop speaking or press Escape
5. Your message is sent automatically
6. Listen to the AI's response in voice

### Typing to the AI (Traditional)
1. Type your question in the text box
2. Press Enter or click Send button
3. You'll still hear the AI's voice response

### Mixed Mode
- Start with voice input
- Edit the recognized text by typing in the textbox
- Send your edited question

---

## 🔧 Browser Support

| Browser | Support | Notes |
|---------|---------|-------|
| ✅ Chrome | Full | Best support for both speech recognition and synthesis |
| ✅ Edge | Full | Excellent support |
| ✅ Safari | Full | Works great on Mac/iOS |
| ✅ Firefox | Partial | Speech synthesis works; recognition may vary |
| ❌ Opera | Limited | Basic support |
| ❌ IE | No | Not supported |

---

## 🎯 Example Conversations

### Example 1: Pure Voice Chat
```
User (speaking): "How do I write a Python function?"
AI Response: "A function in Python is defined using the def keyword..."
[Voice plays automatically]
```

### Example 2: Voice with Correction
```
User (speaking): "What is a loop"
Recognized text: "What is a loop"
[User edits to: "What is a for loop in Python?"]
[Send]
AI Response: "A for loop iterates over sequences..."
```

### Example 3: Quick Questions
```
User: Clicks 🎤 → "Show me an async await example" 
AI: Answers in text + voice simultaneously
```

---

## ⚙️ Troubleshooting

### "Microphone not found"
- Check if your device has a microphone
- Restart your browser
- Try a different browser

### "Permission denied"
- Go to browser settings
- Find microphone permissions
- Allow this website to use microphone
- Refresh the page

### "No speech detected"
- Speak louder
- Get closer to your microphone
- Check microphone is not muted
- Try again with clearer speech

### "Speech recognition not working"
- Use Chrome, Edge, or Safari
- Check your internet connection
- Disable VPN if using one
- Clear browser cache and try again

### "Speech not being recognized correctly"
- Speak more slowly and clearly
- Reduce background noise
- Try shorter sentences
- Check microphone quality

### "Audio not playing"
- Check your system volume
- Unmute your speakers
- Check browser volume permissions
- Refresh the page

---

## 🔐 Privacy & Security

- **Microphone access** - Only active when you click the 🎤 button
- **No cloud recording** - Your speech is processed locally and sent to the backend
- **Backend secure** - Uses the same secure Groq API as before
- **Chat history** - Stored locally in database as before

---

## 🎨 Keyboard Shortcuts

| Key | Action |
|-----|--------|
| **Enter** | Send text message |
| **Escape** | Stop voice recording |
| **Click 🎤** | Toggle voice recording |
| **Click 📤** | Send message |
| **Click 🗑️** | Clear chat history |

---

## 📝 Tips for Best Results

1. **Speak naturally** - Don't rush or pause too much
2. **Use clear English** - Speak in English for best recognition
3. **Complete thoughts** - Say full sentences, not just words
4. **Reduce noise** - Use in a quiet environment
5. **Good microphone** - Better microphone = better results
6. **Fast internet** - Stable connection helps
7. **Turn up volume** - Hear responses clearly

---

## 🐛 Known Limitations

- Only supports English language currently
- Works best with English accent
- Recognizes continuous speech up to ~30 seconds
- Some regional accents may need clarification
- Background noise can affect recognition
- Requires internet connection for Groq API

---

## 🆘 Getting Help

If you encounter issues:
1. Check browser console (F12) for error messages
2. Ensure backend is running on `http://127.0.0.1:5001`
3. Check your internet connection
4. Try in a different browser
5. Clear cache and restart browser
6. Check that GROQ_API_KEY is set correctly

---

## 🎉 Enjoy Your Voice Chat Mentor!

You now have an interactive AI coding mentor that can listen and speak! Perfect for hands-free coding help and learning on the go.

**Happy coding! 🚀**
