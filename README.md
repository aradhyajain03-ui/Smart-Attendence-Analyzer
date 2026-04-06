# 📊 Smart Attendance Analyzer

<div align="center">

![Smart Attendance Analyzer](https://img.shields.io/badge/Project-Smart%20Attendance%20Analyzer-brightgreen?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)

**A browser-based Student Attendance Tracking & Analytics System**

*Developed by **Aradhya Saraf Jain** | B.Tech – CSE | 2025–26*

[🚀 Live Demo](#) • [📸 Screenshots](#screenshots) • [✨ Features](#features) • [🛠 Tech Stack](#tech-stack)

</div>

---

## 📌 About The Project

**Smart Attendance Analyzer** is a fully functional, 5-page Single Page Application (SPA) built using pure HTML, CSS, and JavaScript. It allows faculty/administrators to:

- Record student attendance subject-wise (Mathematics, Physics, Computer Science)
- Automatically calculate overall attendance percentages
- Classify students as **Safe ✅**, **At Risk ⚠️**, or **Critical 🚨**
- Visualize data through 4 interactive Chart.js charts
- Generate detailed student reports and export to CSV
- Get smart alerts for students needing immediate attention

> **Course:** BCSE203E – Web Programming  
> **Institution:** B.Tech Computer Science Engineering  
> **Academic Year:** 2025–26

---

## ✨ Features

| Feature | Description |
|---|---|
| 🏠 **Creative Intro Page** | Animated hero with live stats, feature pills & profile cards |
| 📊 **Live Dashboard** | 5 KPI boxes + student form + filterable/searchable table |
| 📈 **Analytics Charts** | Bar, Doughnut, Radar & Grouped Bar charts via Chart.js |
| 🗂 **Reports Page** | Per-student cards with subject progress bars + CSV export |
| ⚠️ **Alerts Page** | Auto-generated warnings for Critical & At-Risk students |
| 🔍 **Search & Filter** | Filter by Branch, Status; sort by Name or Percentage |
| 🗑 **Delete Records** | Remove any student from records instantly |
| 📥 **CSV Export** | Download full attendance report as `.csv` file |
| 🎨 **Dark UI** | Elegant dark theme with animated blobs & smooth transitions |

---

## 📸 Screenshots

### 🏠 Intro Page
> Animated hero section with developer info, live stats and feature highlights

### 📊 Dashboard
> KPI cards + student entry form + records table with status badges

### 📈 Analytics
> 4 real-time charts — Bar, Doughnut, Radar, Grouped Bar

### 🗂 Reports
> Student detail cards with progress bars and CSV export

### ⚠️ Alerts
> Smart warnings for Critical and At-Risk students

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and layout |
| **CSS3** | Styling, animations, dark theme, CSS variables |
| **JavaScript (ES6+)** | SPA logic, calculations, DOM rendering |
| **Chart.js v4.4.0** | Interactive data visualizations |
| **Google Fonts** | Syne (headings) + DM Sans (body) |
| **CSS Grid & Flexbox** | Responsive layout system |

---

## 🚀 How to Run

### Option 1 — Direct Open (Easiest)
```bash
# Just double-click the file or open in browser
open index.html
```

### Option 2 — Using VS Code Live Server
```
1. Open project folder in VS Code
2. Right-click on index.html
3. Click "Open with Live Server"
4. Browser opens at http://127.0.0.1:5500
```

### Option 3 — Using Python HTTP Server
```bash
cd smart-attendance-analyzer
python -m http.server 8000
# Open http://localhost:8000
```

> ✅ **No installation required. No dependencies to install. Works 100% in the browser.**

---

## 📁 Project Structure

```
smart-attendance-analyzer/
│
├── index.html          ← Complete 5-page SPA (HTML + CSS + JS)
├── README.md           ← Project documentation
├── LICENSE             ← MIT License
├── .gitignore          ← Git ignore rules
│
└── assets/             ← (optional) screenshots folder
    ├── intro.png
    ├── dashboard.png
    ├── analytics.png
    ├── reports.png
    └── alerts.png
```

---

## 📐 How It Works

```
User opens app
    ↓
Intro Page → Navigate to Dashboard
    ↓
Fill Student Form (Name, Reg No, Branch, Year, Attendance per subject)
    ↓
JavaScript calculates:
  • Subject % = (Attended ÷ Total) × 100
  • Overall % = Average of all 3 subjects
  • Weak Subject = Subject with lowest %
  • Status → Safe (≥75%) | At Risk (60–74%) | Critical (<60%)
    ↓
Records Table updates → KPIs update → Intro stats update
    ↓
Analytics Page → Charts auto-render from data
    ↓
Reports Page → Student cards with filters + CSV export
    ↓
Alerts Page → Auto-flags Critical & At-Risk students
```

---

## 📊 Attendance Status Logic

| Status | Condition | Badge Color |
|---|---|---|
| ✅ Safe | Overall ≥ 75% | Green |
| ⚠️ At Risk | 60% ≤ Overall < 75% | Yellow |
| 🚨 Critical | Overall < 60% | Red |

---

## 👤 Developer

**Aradhya Saraf Jain**  
B.Tech – Computer Science Engineering  
Academic Year: 2025–26  
Course: BCSE203E – Web Programming

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- [Chart.js](https://www.chartjs.org/) — for the powerful charting library
- [Google Fonts](https://fonts.google.com/) — Syne & DM Sans typefaces
- Course: BCSE203E Web Programming

---

<div align="center">
  Made with ❤️ by <b>Aradhya Saraf Jain</b>
</div>
