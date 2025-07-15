# 🎤 ACoolVENUE Dashboard by ACoolNERD

Welcome to **ACoolVENUE** — your all-in-one interactive dashboard for venue booking, tour planning, and ROI calculation across China, Hong Kong, and beyond.

Built by the ACoolNERD ecosystem in collaboration with TheFCAgency and VBZ Entertainment, this tool helps artists, managers, and creators turn tour data into opportunity.

---

## 🔖 ACoolTAGGED Overview

### 🎯 ACoolPROJECT
**ACoolVENUE** is part of the ACoolOPS toolchain for content creators and music tour strategists. Designed to scale up:
- 🎶 Concert booking & availability
- 📅 Artist performance planning
- 💰 Financial forecasting
- 🗺️ International tour feasibility

---

### 🧰 ACoolFEATURES

| Feature | Description |
|---------|-------------|
| 🎟️ **Venue Cards** | Colorful display of major concert venues in China/HK |
| 🔍 **Artist Availability Input** | Type an artist name and see open date windows |
| 📈 **ROI Calculator** | Uses ticket price, venue cost & capacity to estimate profit |
| 📅 **Free Slot Logic** | Shows availability from now through the next 3 years |
| 📊 **Chart.js Bar Graphs** | Easy-to-read revenue visualizations |
| 🔁 **Sort & Filter Controls** *(coming soon)* | Sort venues by capacity, city, ROI |
| 🧠 **Real Data Integration** *(future)* | Sync with Google Calendar, Firebase, or Sheets API |
| 🚀 **Deployable to GitHub Pages/Vercel** | One-click build and launch live web dashboards |

---

### 🗂️ ACoolSTRUCTURE

```plaintext
ACoolVENUE/
├── docs/               → GitHub Pages deployment files (index.html, CSS, JS)
├── public/             → Original development version
├── backend/            → Optional Node.js Express API
├── data/               → venues.json with name, city, capacity, cost, etc.
├── src/                → Logic for ROI + availability calculations
│   └── utils/roi.js
│   └── utils/calendar.js
└── README.md           → You're reading it!

# 🏟️ ACOOLEVENT VENUE DASHBOARD

## 🎯 ACoolTAG: OVERVIEW
This is the **ACoolVENUE** project – a live, browser-based dashboard built to help artists, managers, and promoters visualize venue options across China (and nearby cities), assess availability, and estimate tour ROI in seconds.

Hosted via GitHub Pages at:
👉 https://acoolnerd.github.io/ACoolVENUE/

---

## 🛠️ ACoolTAG: FEATURES

### ✅ Artist Name Input
Type an artist’s name to simulate booking interest across major venues.

### ✅ Venue Cards
- Each card shows venue name, city, capacity
- Press “Check Availability & ROI” to simulate open dates & expected profit

### ✅ ROI Estimator
- Based on ticket price, capacity, attendance %, and event cost
- Returns a min/max ROI projection

### ✅ Chart Modal
- Visual ROI range shown using Chart.js bar graph
- Quick comparison per venue

---

## 📍 ACoolTAG: LOCATIONS PRELOADED
These venues are currently included:

| Venue | City | Capacity | Ticket Price | Cost |
|-------|------|----------|--------------|------|
| Mercedes‑Benz Arena | Shanghai | 18,000 | $120 | $300,000 |
| Cadillac Arena | Beijing | 18,000 | $110 | $280,000 |
| NCPA | Beijing | 2,400 | $150 | $200,000 |
| SZ Bay Sports Arena | Shenzhen | 13,000 | $100 | $250,000 |
| Oriental Art Center | Shanghai | 1,978 | $90 | $120,000 |
| Shenzhen Concert Hall | Shenzhen | 1,800 | $85 | $100,000 |
| Wen‑Xin Amphitheater | Taichung | 5,000 | $75 | $150,000 |
| HK Coliseum | Hong Kong | 12,500 | $130 | $270,000 |
| HK Cultural Centre | Hong Kong | 2,019 | $100 | $180,000 |
| HK Convention Centre | Hong Kong | 10,000 | $110 | $250,000 |
| HKAPA | Hong Kong | 1,200 | $95 | $90,000 |
| Jazz at Lincoln (SH) | Shanghai | 300 | $60 | $40,000 |

---

## 🧾 ACoolTAG: HOW TO USE (ACoolGUIDE)

### 🧑‍💻 For Local Testing
1. **Clone the repo:**
   ```bash
   git clone https://github.com/ACoolNERD/ACoolVENUE.git
   cd ACoolVENUE
   ```
2. **Install serve:**
   ```bash
   npm install -g serve
   ```
3. **Run it locally:**
   ```bash
   serve docs
   ```
4. **Visit** `http://localhost:3000` in your browser

---

### 🌐 For Live Preview (GitHub Pages)
1. Files live in `/docs/`
2. Go to your GitHub repo > **Settings > Pages**
3. Set Source = `main` branch, folder = `/docs`
4. Save & access your page at:
   👉 https://acoolnerd.github.io/ACoolVENUE/

---

## 🧠 ACoolTAG: FUTURE IDEAS
- ✍️ Add real booking API
- 📅 Save/export results as PDF
- 💬 Add WeChat/Email contact per venue
- 🔍 Filter by city, capacity, cost
- 💡 Add government approval filters

---

## 🧩 ACoolTAG: FILE STRUCTURE
```
ACoolVENUE/
├── backend/             # Future server API
│   └── server.js
├── data/                # Venue database
│   └── venues.json (optional expansion)
├── docs/                # GitHub Pages deploy
│   ├── index.html
│   └── styles.css
├── public/              # Local test assets (optional)
├── src/                 # Main app logic
│   ├── apijs
│   ├── utils
│   └── app.js
├── README.md            # You’re reading it 😎
```

---

## 🙌 Built by: [ACoolNERD](https://github.com/ACoolNERD)
🧠 Inspired by real-world concert planning, Asia-Pacific market trends, and Olympic-level precision.

---

Need more? Say: **"Update with sponsor info"**, **"Add Firebase login"**, or **"Include WeChat links"**.

Let’s rock every city. 🎶📍🚀
