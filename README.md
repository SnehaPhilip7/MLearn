# Karma Marathon 2026 — μLearn PRC

[![Event](https://img.shields.io/badge/Event-Karma_Marathon-FF5722?style=for-the-badge)](https://mulearn.org)
[![Platform](https://img.shields.io/badge/Platform-μLearn_PRC-00BFA5?style=for-the-badge)](https://mulearn.org)
[![Audience](https://img.shields.io/badge/Audience-1st_Year_Students_Only-1A1A1A?style=for-the-badge)](https://mulearn.org)
[![Target](https://img.shields.io/badge/Target-3%2C000_Karma-FF5722?style=for-the-badge)](https://mulearn.org)

Official responsive event registration portal for **Karma Marathon** (Karma Mining) hosted by **μLearn PRC**.

---

## 📌 Event Overview

- **Event Name**: Karma Mining / Karma Marathon
- **Platform**: μLearn PRC
- **Dates**: 16 August – 27 August 2026
- **Duration**: 12 Days
- **Eligibility**: Exclusively for 1st-Year Students
- **Qualification Goal**: Minimum 3,000 Karma points to qualify
- **Concept**: Explore μLearn, complete practical tasks from the μJourney pathway, and earn Karma points through verified submissions.

---

## 🏆 Structure & Recognition

- **Group System**: Students are divided into groups, each guided and supported by a dedicated volunteer mentor.
- **Top Student**: Special recognition and prize for the student with the highest Karma points earned.
- **Top Volunteer**: Special recognition and prize for the volunteer whose group achieves the highest overall Karma.

---

## 🚀 Key Portal Features

- **Gamified Community Theme**: Tailored color palette (Bright Orange `#FF5722`, Teal `#00BFA5`, Dark Charcoal `#1A1A1A`, Warm Cream `#FAFAFA`).
- **Interactive Countdown**: Official countdown timer with pre-event, live, and concluded states adhering strictly to event dates.
- **Milestone Progress Bar & Task Simulator**: Visual progress tracking to 3,000 Karma with interactive task selector.
- **12-Field Registration Form**: Complete client-side validation, inline errors, and fixed 1st-year eligibility badge.
- **Confirmed Registration Pass with QR Code**:
  - Scannable verification QR code with dual rendering (client-side `QRCode.js` + high-res SVG fallback).
  - Print & PDF export support (`window.print()`).
  - Copy Registration ID button with clipboard feedback.
  - Browser `localStorage` persistence with quick-access pass viewer.
- **FAQ Accordion**: 9 official Q&As strictly derived from verified event rules.

---

## 🛠️ Tech Stack

- **Core**: HTML5, Vanilla CSS, JavaScript (ES6+)
- **Framework**: React 18 (UMD) & ReactDOM
- **Compiler**: Babel Standalone (JSX transpilation)
- **Styling**: Tailwind CSS (CDN) + Custom Design System
- **Icons & Graphics**: Responsive inline SVGs & Canvas Confetti
- **QR Engine**: QRCode.js client-side generator

---

## 💻 Quick Start & Running Locally

Simply open `index.html` in any modern web browser:

```bash
# Option 1: Double click or open in browser
start index.html

# Option 2: Run local PowerShell static server
powershell -ExecutionPolicy Bypass -File serve.ps1
# Then navigate to: http://localhost:5050/
```

---

## 📄 License & Credits

© 2026 μLearn PRC. All rights reserved.
Built for Karma Mining & Registration.
