# ⏱️ Beautiful & Simple React Countdown Dashboard

A polished, modern, and responsive Countdown & Event Dashboard built with **React**, **HTML (JSX)**, and **CSS**. It runs 100% on the frontend with zero external UI libraries, keeping the codebase clean, readable, and lightning fast.

---

## ✨ Features

- **🔴 Real-Time Live Countdown Tickers**:
  - Dynamically recalculates remaining time every single second.
  - Displays hardware-style digital tiles for **Days**, **Hours**, **Minutes**, and **Seconds**.
  - Animated seconds indicator gives a live visual pulse.
  - Gracefully handles arrived/past events with a celebratory status banner (`🎉 The moment has arrived!`).
- **📝 Clean Add Event Form**:
  - Input field for Event Title.
  - Native datetime picker (`<input type="datetime-local" />`).
  - Category selector (Celebration, Work & Launch, Travel, Milestone/Goal, Personal) with dedicated color themes.
  - Quick date presets (`+24 Hours`, `+1 Week`, `+1 Month`, `+100 Days`) for fast scheduling.
  - Inline validation with friendly error banners.
- **🗑️ Delete & Clear Events**:
  - Instant delete button on every countdown card.
  - "Clear All" option for a fresh start.
- **💾 LocalStorage Persistence**:
  - Automatically preserves your events across browser refreshes using `localStorage`.
- **🎛️ Filter & Sorting Controls**:
  - Filter by **All**, **Active**, or **Arrived**.
  - Sort by **Nearest First**, **Furthest First**, or **Alphabetical (A-Z)**.
- **🎨 Modern Dark Glassmorphic Aesthetic**:
  - Deep slate/indigo background with radial ambient glows.
  - Glassmorphic card surfaces (`backdrop-filter: blur(...)`).
  - Responsive CSS Grid layout for phones, tablets, and large displays.
  - Smooth hover lifts and glowing color accents (Cyan, Violet, Emerald, Amber, Rose).
- **⏳ Friendly Empty State**:
  - Displays a clean empty state card with an icon and a 1-click **⚡ Load Sample Events** button.

---

## 📁 File Structure

The core app logic and design are consolidated into the two requested primary files:

```
WebTech Project/
├── src/
│   ├── App.js        # Entire application state, timer ticker, add/delete handlers & JSX
│   ├── App.css       # Complete design system, glassmorphism, responsive grid & animations
│   └── index.js      # Minimal React 19 root mounting
├── index.html        # HTML entry point with Inter & JetBrains Mono Google Fonts
├── vite.config.js    # Ultra-fast bundler configuration
└── package.json      # Dependencies and run scripts
```

---

## 🚀 Getting Started

### 1. Start the Development Server
```bash
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

### 2. Build for Production
```bash
npm run build
```
Creates an optimized static production bundle inside the `dist/` folder.

---

## 🛠️ Tech Stack
- **React 19** (`useState`, `useEffect`)
- **Native JavaScript Date & Intervals**
- **Modern CSS3** (CSS Grid, Flexbox, Custom Properties, Glassmorphism, Animations)
- **Vite** (Instant HMR & fast builds)
