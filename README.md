# Leadify — مدير العملاء المحتملين

<p align="center">
  <img src="https://img.shields.io/badge/HTML-Single%20File-orange?style=flat-square&logo=html5" />
  <img src="https://img.shields.io/badge/CSS-Vanilla-blue?style=flat-square&logo=css3" />
  <img src="https://img.shields.io/badge/JS-Vanilla-yellow?style=flat-square&logo=javascript" />
  <img src="https://img.shields.io/badge/Backend-None%20(LocalStorage)-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Language-Arabic%20UI-teal?style=flat-square" />
</p>

> A production-grade, single-file CRM tool built for web agencies in Jordan/Syria that cold-call local businesses to sell them websites.

---

## 🚀 Live Demo

Just open `index.html` in any browser — **no installation, no server, no dependencies**.

---

## ✨ Features

### 📋 Leads Table
- Full-featured data table with 13 columns
- Duplicate detection with fuzzy matching (Arabic/English)
- WhatsApp quick-action links
- Instagram / Facebook / TikTok social icons
- Color-coded badges for Website Status, Lead Status & Tier
- Priority stars (High / Medium / Low)
- Hover-to-copy phone numbers
- Right-click context menu (Edit, Delete, Copy Phone, WhatsApp, Mark Contacted, Mark Sold)

### ➕ Add / Edit Lead Modal
- 3-step form with animated progress bar
- Slide transitions between steps
- Inline duplicate warning as you type
- Form validation with shake animation on errors

### 🔍 Smart Import (Scraper Panel)
- Simulates Google Maps scraping with realistic loading animation
- Pool of 62+ real Jordanian businesses (restaurants, cafes, salons, factories, car shops...)
- Bulk select & import results directly into your leads table
- Auto-detects already-added businesses (grays them out)

### 📊 Dashboard
- Bento-grid layout with animated stat counters
- Donut charts (pure Canvas — no chart libraries)
- Bar charts for business type and top cities
- Tier distribution (Gold / Silver / Bronze)
- Top priority leads list with quick-action buttons

### 🔎 Filtering & Search
- Global search (name, phone, city simultaneously)
- 6 filter dropdowns (Type, City, Website Status, Lead Status, Tier, Priority)
- Active filter chips (dismissible)
- Sort by: Date, Name, Priority, Status

### 📤 Export
- Export to CSV (real file download with UTF-8 BOM for Arabic)
- Print-friendly report via browser print

### ⚡ Quick Actions
- Floating Action Button (+) to add new lead
- Keyboard shortcuts: `N` = new lead, `F` = focus search, `Esc` = close modal
- Bulk select: multi-delete, bulk status update
- Undo delete (toast notification with undo button)

### 📱 Lead Detail Drawer
- Right-side drawer with full lead profile
- Timeline of status changes
- Quick action buttons (Call, WhatsApp, Email, Log Contact)

---

## 🎨 Design System

| Token | Value |
|---|---|
| Base Background | `#0f0e0d` |
| Surface | `#161513` / `#1e1c1a` |
| Teal Accent | `#01696f` / `#4f98a3` |
| Font — Body | Satoshi (Fontshare) |
| Font — Headings | Cabinet Grotesk (Fontshare) |
| Dark/Light | Toggle with persistence |
| Spacing | 4px system |
| Type Scale | `clamp()` fluid |

---

## 📦 Tech Stack

- **HTML5** — semantic structure
- **Vanilla CSS** — design tokens, animations, responsive layout
- **Vanilla JavaScript** — all logic, no frameworks
- **Lucide Icons** — via CDN
- **localStorage** — data persistence
- **Canvas API** — donut/pie charts (no Chart.js needed)

---

## 🗂️ Project Structure

```
leadify/
└── index.html    ← Everything. Open and go.
```

---

## 🌍 Supported Cities (Mock Data)
- عمّان (Amman)
- الزرقاء (Zarqa)
- إربد (Irbid)
- العقبة (Aqaba)
- السلط (Salt)

---

## 🛠️ Getting Started

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/leadify.git

# Open in browser
start leadify/index.html
```

No `npm install`. No build step. No server. Just open the file.

---

## 📄 License

MIT License — free to use, modify, and distribute.
