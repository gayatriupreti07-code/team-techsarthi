# 🏔️ Shikayat Saathi (शिकायत साथी)
**Built by Team TechSarthi — PRAYAS 2026 (Uttarakhand Web & Mobile App Hackathon)**

**Shikayat Saathi** is a bilingual (Hindi & English) citizen grievance redressal and public service portal designed for the citizens of Uttarakhand. It eliminates complex bureaucratic forms by allowing residents across all 13 districts to type or speak their problems in plain language, automatically routes complaints to the right department, and helps them discover eligible state welfare schemes.

🌐 **Live Demo:** `[Your-Netlify-Link]`

---

## ✨ Key Features

- **🌐 Complete Bilingual Interface (हिन्दी & English):** One-click toggle that dynamically translates the entire UI, department names, welfare schemes, service guides, and AI assistant responses.
- **🎙️ Voice-First & Natural-Language Complaint Filing:** Citizens can speak (`hi-IN` / `en-IN` via Web Speech API) or type their grievance in everyday language, attach photo evidence, and let built-in classification automatically detect the **Department** (Jal Sansthan, UPCL, PWD, Health, Local Body), **Urgency Level**, and **District/Locality**.
- **🤖 Pahadi Sahayak AI (पहाड़ी सहायक AI):** An interactive bilingual chatbot that understands citizen queries, tracks complaint IDs, navigates tabs, and auto-fills the complaint form directly from chat messages.
- **📍 Live Complaint Tracking:** Generates unique `UK-2026-XXXXX` tracking IDs with a visual step-by-step resolution timeline.
- **🎯 Personalized Welfare Scheme Finder:** Matches citizens with eligible Uttarakhand government schemes (*Atal Ayushman*, *Nanda Gaura Yojana*, *Mukhyamantri Swarozgar Yojana*, *Motorcycle Taxi Yojana*, and social security pensions) based on age, occupation, and household details.
- **📜 Apuni Sarkar Service Guides & RTS Helpdesk:** Step-by-step application guides for 75+ certificates (Domicile, Income, Caste, Birth/Death, Land Records), along with the **1905** helpline and **Uttarakhand Right to Service Act (2011)** appeal information.
- **📊 Real-Time Portal Dashboard:** Visualizes total complaints filed, on-time resolution rate (`96.4%`), and department-wise resolution progress across all 13 districts.
- **🌓 Accessible & Flexible:** Includes instant **Guest Mode** (no mandatory login), demo OTP login (`1234`), Dark/Light theme switcher, and a responsive mobile-first design.

---

## 🛠️ Tech Stack

- **Frontend:** Semantic HTML5, Modern CSS3 (Custom Properties, Responsive Grid/Flexbox, Dark Mode)
- **Logic & Interactivity:** Vanilla JavaScript (ES6+), Web Speech API (`SpeechRecognition`), `localStorage` state persistence
- **Deployment:** GitHub + Netlify Continuous Deployment

---

## 🚀 How to Use (Demo Guide)

1. **Login or Continue as Guest:** Enter any 10-digit mobile number with demo OTP `1234`, or click **"Skip for now" (अभी छोड़ें)** to enter directly as a Guest.
2. **File a Complaint:** Type or use **🎤 Speak instead** to describe an issue (e.g., *"तीन दिन से पानी नहीं आ रहा"*), review the auto-detected department and district, and submit to receive a `UK-2026-XXXXX` tracking ID.
3. **Track or Chat:** Paste your tracking ID into the **Track (स्थिति)** tab or ask **पहाड़ी सहायक AI** in the bottom-right corner.
4. **Discover Schemes:** Open **Schemes (योजनाएँ)**, enter your age and details, and view matched state welfare programs.

---

## 👥 Team TechSarthi
Created for **PRAYAS 2026** to bridge the gap between Uttarakhand's citizens and governance.
