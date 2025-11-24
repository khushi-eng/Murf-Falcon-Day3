# 🎙️ AI Voice Agents Challenge — Day 3  
## Health & Wellness Voice Companion

This project is part of the **10-Day AI Voice Agents Challenge**.  
The goal for Day 3 was to build a supportive and wellness-focused conversational AI agent that performs daily check-ins and remembers previous conversations.

---

### 🧠 Features

✔ Tracks daily wellness check-ins through voice  
✔ Asks about mood, energy and daily goals  
✔ Stores responses in a JSON file (`wellness_log.json`)  
✔ References previous days to make the interaction feel personal  
✔ Uses an empathetic tone (non-diagnostic and supportive)  
✔ Converts speech to text and responds with natural TTS

---

### 🗂️ Tech Stack

| Component | Tool |
|----------|------|
| Runtime | Python |
| Voice Platform | LiveKit Agents |
| Speech-to-Text | Deepgram |
| LLM | Google Gemini 2.5 Flash |
| Text-to-Speech | **Murf Falcon** (fastest TTS) |
| Turn Detection | Multilingual VAD Model |
| Storage | JSON-based persistence |

---

### 📁 Folder Structure

