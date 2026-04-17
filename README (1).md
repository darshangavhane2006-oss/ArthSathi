# 🪙 ArthSathi V10 — India's AI Money Companion

[![Live Demo](https://img.shields.io/badge/Live-Demo-F0B90B?style=for-the-badge)](https://your-username.github.io/arthsathi)
![Version](https://img.shields.io/badge/Version-10.0-0ECB81?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

> India's smartest all-in-one tax & finance web app — built with vanilla HTML/CSS/JS. No frameworks, no build tools. Just open and use.

---

## ✨ Features

| Module | Description |
|--------|-------------|
| 📊 **Dashboard** | Live cashflow chart, tax saved widget, deadlines ticker |
| 🤖 **Financial Coach** | AI literacy in Hindi & English |
| 💸 **Expense & GST** | SMS parse, GSTR-3B export, expense tracker |
| 🛡️ **Fraud Shield** | UPI/SMS fraud risk scorer + AI deep analysis |
| 🧮 **Tax Calculator** | New vs Old regime, Budget 2025 rules (₹12L zero tax) |
| 🗣️ **AI Tax Advisor** | Live AI with voice input & streaming |
| 📄 **Document AI** | Form 16, GST invoices, bank statement analyser |
| 🚀 **MicroInvest** | Crowdfunding & micro-investment (₹500+) with portfolio tracker |
| 📰 **Market News** | NIFTY/SENSEX/Gold live + FMP financial news feed |
| 💬 **AI Chatbot** | Gemini 2.0 Flash powered floating bot (Hindi/English/Marathi) |

---

## 🚀 Quick Start

### Option 1 — Just open the file
```bash
# Download index.html and open in any browser
open index.html
```

### Option 2 — GitHub Pages (Recommended)
1. Fork this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Visit `https://your-username.github.io/arthsathi`

### Option 3 — Local server
```bash
npx serve .
# or
python3 -m http.server 8080
```

---

## 🔑 API Keys Used

| API | Purpose | Key Location |
|-----|---------|-------------|
| [Google Gemini](https://aistudio.google.com) | AI Chatbot (Gemini 2.0 Flash) | `GEMINI_API_KEY` in script |
| [Financial Modeling Prep](https://financialmodelingprep.com) | Market news & stock data | `FMP_API_KEY` in script |

> ⚠️ Keys are embedded for demo purposes. For production, use environment variables or a backend proxy.

---

## 🛠️ Tech Stack

- **Frontend**: Vanilla HTML5 + CSS3 + JavaScript (ES2022)
- **Charts**: Chart.js 4.4
- **Fonts**: Space Grotesk + IBM Plex Mono
- **AI**: Google Gemini 2.0 Flash API
- **Finance Data**: Financial Modeling Prep API
- **Storage**: localStorage (per-user namespaced)
- **Auth**: Client-side with localStorage sessions

---

## 📁 Project Structure

```
arthsathi/
├── index.html          # Complete app — single file
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── LICENSE             # MIT License
```

> This is a **single-file app**. Everything (HTML, CSS, JS) lives in `index.html`.

---

## 💡 Features in Detail

### 🔐 Auth System
- Register / Login / Logout
- Password strength checker
- Remember me (30 days)
- Per-user data isolation via namespaced localStorage

### 🧮 Tax Calculator (FY 2025-26)
- Budget 2025: Zero tax up to ₹12L under new regime
- Section 87A rebate
- 80C / 80D / HRA / NPS deductions (old regime)
- Side-by-side new vs old regime comparison

### 🚀 MicroInvest
- Browse 6 startup campaigns (AgriTech, FinTech, HealthTech, EdTech, etc.)
- Filter by category
- Invest from ₹500
- Portfolio tracker with returns

### 🛡️ Fraud Shield
- Rule-based SMS risk scorer (0–100)
- AI deep analysis via Gemini
- Common scam pattern detection

---

## 📸 Screenshots

> Dashboard · MicroInvest · Tax Calculator · Fraud Shield · Market News

---

## 📄 License

MIT © 2026 ArthSathi Team

---

## 🤝 Contributing

Pull requests welcome! For major changes, open an issue first.

```
git clone https://github.com/your-username/arthsathi.git
cd arthsathi
# Edit index.html
# Open in browser to test
```
