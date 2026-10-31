# 🇮🇳 Co-Op Mitra | Multilingual Cooperative Governance & Legal AI Chatbot

[![Live Website](https://img.shields.io/badge/Live%20Website-GitHub%20Pages-2563eb?style=for-the-badge&logo=github)](https://rajeshwarij2005.github.io/multilingual-cooperative-governance-legal-assistance-chatbot/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![Python 3.11](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Status](https://img.shields.io/badge/Status-Live%2024%2F7-brightgreen?style=for-the-badge)]()

> **Live Public URL:** [https://rajeshwarij2005.github.io/multilingual-cooperative-governance-legal-assistance-chatbot/](https://rajeshwarij2005.github.io/multilingual-cooperative-governance-legal-assistance-chatbot/)

**Co-Op Mitra** is an AI-powered, multilingual cooperative governance, legal advisory, and citizen grievance assistance system developed for Indian citizens, Primary Agricultural Credit Society (PACS) members, farmers, and cooperative administrators.

---

## 🌟 Key Features

- **🌐 15 Indian Languages Supported:** Full support with native scripts for English, Tamil (தமிழ்), Hindi (हिन्दी), Telugu (తెలుగు), Malayalam (മലയാളം), Kannada (ಕನ್ನಡ), Bengali (বাংলা), Marathi (मराठी), Gujarati (ગુજરાતી), Punjabi (ਪੰਜਾਬੀ), Odia (ଓଡ଼ିଆ), Assamese (অসমীয়া), Urdu (اردو), Nepali (नेपाली), and Konkani (कोंकणी).
- **🎙️ Voice Recognition & Text-to-Speech:** Integrated Web Speech API for voice-based queries and spoken responses in all Indian regional languages.
- **📚 251+ Verified Legal Knowledge Records:** Pre-populated legal & governance advice covering:
  - PACS registration, bylaws & computerization guidelines
  - Kisan Credit Card (KCC) 4% subsidized crop loan eligibility
  - PMFBY (Pradhan Mantri Fasal Bima Yojana) crop insurance claims
  - Democratic member control, voting rights & AGM meeting bylaws
  - Cooperative financial audit and compliance regulations
- **🤖 Dual-Engine Architecture:**
  - **Instant Offline Legal Engine:** 0ms latency, 100% accurate statutory matching based on multi-keyword scoring.
  - **Google Gemini 1.5 Flash AI Engine (Optional):** Generative advisory for open-ended legal inquiries.
- **📝 Citizen Grievance & Enquiry Tracker:** Real-time enquiry submission with automatic reference ID generation and live status tracking.
- **🔐 Administrator Portal:** Built-in dashboard to inspect knowledge records, search the database, and resolve citizen grievances.

---

## 🚀 Live Access

The project is hosted live on GitHub Pages and can be accessed on any device (desktop, tablet, mobile) with no installation required:

👉 **[Launch Co-Op Mitra Live Web App](https://rajeshwarij2005.github.io/multilingual-cooperative-governance-legal-assistance-chatbot/)**

---

## 🛠️ Running Locally (Python Flask)

If you prefer to run the Flask backend on your local computer:

```bash
# 1. Clone repository
git clone https://github.com/RajeshwariJ2005/multilingual-cooperative-governance-legal-assistance-chatbot.git
cd multilingual-cooperative-governance-legal-assistance-chatbot

# 2. Install dependencies
pip install -r requirements.txt

# 3. Start application
python app.py
```
Open [http://127.0.0.1:5000](http://127.0.0.1:5000) in your web browser.

---

## ☁️ 1-Click Cloud Deployment (Render / Railway)

This repository includes `Procfile`, `render.yaml`, and `runtime.txt` ready for 1-click cloud deployment:

- **Render:** Connect this GitHub repository and select **Web Service**. It will automatically detect Python and deploy using Gunicorn (`gunicorn app:app`).
- **Railway:** Click **New Project** -> **Deploy from GitHub repo**.
