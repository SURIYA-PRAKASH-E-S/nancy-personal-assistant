

#🧠 Nancy – Your Personal AI Assistant
---
Nancy is a Python-based AI assistant inspired by Jarvis, capable of:

* 🔍 **Searching the web**
* 🌤️ **Weather checking**
* 📨 **Sending Emails**
* 📷 **Vision through camera** (Web App)
* 🗣️ **Speech interaction**
* 📝 **Chat interface** (Web App)

This project uses **LiveKit** for real-time audio/video and AI tools — and it’s **100% free**!

---

## 🚀 Features

* Real-time conversation using **LiveKit**
* Web search integration (free APIs like DuckDuckGo)
* Weather info from **OpenWeather API**
* Email sending via **Gmail App Password**

---

## 📦 Installation & Setup

### 1️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

### 2️⃣ Activate the Virtual Environment

* **Windows**

```bash
\venv\Scripts\activate
```

* **Mac/Linux**

```bash
 source env/bin/activate
```

* ### Download files for agent
```bash
python agent.py download-files
```
### 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4️⃣ Create `.env` File

Inside the project root, create a file named `.env` and add:

```env
# LiveKit
LIVEKIT_URL=wss://your-livekit-server-url
LIVEKIT_API_KEY=your_livekit_api_key
LIVEKIT_API_SECRET=your_livekit_api_secret

# Gmail (For Email Sending Tool)
GMAIL_USER=your_gmail@gmail.com
GMAIL_APP_PASSWORD=your_gmail_app_password
```

---

## ▶️ Running Nancy

```bash
python .\agent.py console 
```

If using **Livekit Web Interface**:

```bash
python .\agent.py dev
```
---

## 📜 Notes

* **Gmail App Password**: You must enable **2FA** on your Gmail and generate an **App Password**.
* **LiveKit**: Create a free account at [livekit.io](https://livekit.io/) to get credentials.
* Web search can be done with **DuckDuckGo** and **Weather** for free(inbuilt python library).

---

## ❤️ Used tools

* [LiveKit](https://livekit.io/) for real-time communication
* [OpenWeather](https://openweathermap.org/) for weather data
* [DuckDuckGo](https://duckduckgo.com/) for privacy-friendly search

---

