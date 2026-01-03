# Society Guard Entry Bot 🛡️

## 📌 Overview
The **Society Guard Entry Bot** is a Hindi voice-to-text solution designed for residential societies.  
It simplifies **visitor/staff/delivery entry logging** and integrates **maintenance fee tracking** into one easy-to-use system.  
Guards interact through a **Hindi-first interface with voice input**, while RWAs (Resident Welfare Associations) get **live dashboards and automated reports**.

---

## ✨ Features
- 🎤 **Voice-to-Text (Hindi)**: Guards can speak entries like *“फ्लैट 302, मेड सुनीता”* and the system auto-converts to structured text.
- 🧑‍💼 **Category Buttons**: Staff, Vehicle, Delivery — large, easy-to-tap options for guards.
- 📝 **Correction Screen**: Manual edit option before saving.
- 📊 **RWA Dashboard**: Live logs of entries + maintenance fee records.
- 📱 **Resident Notifications**: Optional WhatsApp/SMS alerts for staff/delivery arrivals.
- 📑 **Daily Summary Report**: Auto-generated in Hindi for RWAs.

---

## 🏗️ Project Structure
```
society-guard-entry-bot/
├── frontend/                # Streamlit / Flutter UI
│   ├── streamlit_app.py
│   └── correction_ui.py
│
├── backend/                 # Voice capture, STT, parser, notifier, reports
│   ├── voice_capture.py
│   ├── stt_engine.py
│   ├── parser.py
│   ├── notifier.py
│   └── reports.py
│
├── database/                # Google Sheets / Firebase connectors
│   ├── sheets_api.py
│   └── firebase_api.py
│
├── dashboard/               # RWA dashboard
│   └── rwa_dashboard.py
│
├── config/                  # Settings & API keys
│   └── settings.yaml
│
└── README.md                # Project documentation
```

---

## 🚀 Tech Stack
- **Frontend:** Streamlit (demo) / Flutter (mobile app)
- **Backend:** Python + LangChain/LangGraph for parsing
- **Voice Engine:** Google Speech-to-Text API / Vosk (offline Hindi STT)
- **Database:** Google Sheets API / Firebase
- **Notifications:** Twilio / WhatsApp API

---

## 📅 Sprint Plan
- **Day 1:** Repo setup + folder structure ✅
- **Day 2:** Hindi STT module
- **Day 3:** Parser logic (flat, category, name)
- **Day 4:** UI prototype
- **Day 5:** Database integration
- **Day 6:** Fee reminder module
- **Day 7:** Dashboard + daily summary

---

## 🔮 Future Enhancements
- Complaint management
- Parking allocation
- Resident app integration
- Offline-first support for guards

---

## 👨‍💻 Author
**Ambikesh Mishra**  
Freelance AI & Automation Specialist | Focused on practical, outcome-driven solutions for RWAs and SMEs.

---

## 📜 License
This project is open-source under the MIT License.
