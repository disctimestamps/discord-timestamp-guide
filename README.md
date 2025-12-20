# DiscTimestamps - The Ultimate Discord Utility Suite 🛠️

![Project Banner](https://disctimestamps.com/og-image.png)

**DiscTimestamps** is a comprehensive web application designed to help Discord power users, community managers, and developers create dynamic content for their servers. 

> **Live Site:** [https://disctimestamps.com](https://disctimestamps.com)  
> **Twitter/X:** [@DiscTimestamps](https://x.com/DiscTimestamps)  
> **Medium Guide:** [Read the Technical Breakdown](https://medium.com/@disctimestamps/how-to-create-dynamic-timestamps-in-discord-the-complete-2025-guide-07dd70aea08f)

---

## 🚀 Features

This project is not just a date picker; it is a suite of 5 distinct tools built into a single SPA (Single Page Application).

### 1. Smart Timestamp Generator (Home)
- **Natural Language Parsing:** Type *"Next Friday at 8pm"* or *"Christmas noon"* and the app uses AI logic to convert it into a timestamp instantly.
- **Auto-Timezone Sync:** Automatically detects the user's local browser time to ensure accurate conversions.
- **Format Gallery:** One-click copy for all Discord styles (`:R`, `:f`, `:D`, etc.).

### 2. Discord Text Formatter
- **ANSI Color Generator:** A GUI for creating colored text in Discord code blocks.
- **Smart Logic:** Automatically disables incompatible styles (like *Italic* or *Spoiler*) when Color Mode is active.
- **Mobile Warnings:** Detects and warns users about limitations on Discord Mobile.

### 3. Countdown Builder
- **Live Preview:** Visualizes exactly how the timer will look inside the Discord client.
- **Dual Modes:** Switch between "Relative Duration" (e.g., 10 minutes) and "Fixed Date" (e.g., New Year's Eve).

### 4. Developer Tools (Unix & Snowflake)
- **Visual Learning:** Includes custom **React SVG Components** to visualize complex concepts like the *64-bit Snowflake Structure* and the *Unix Epoch Timeline*.
- **Bi-Directional Conversion:** Instantly syncs between Integer timestamps and Human-readable dates.
- **Regex Validation:** Robust error handling for invalid IDs.

---

## 🛠️ Tech Stack

* **Framework:** [React 18](https://reactjs.org/)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/) (Dark Mode First design)
* **Icons:** [Lucide React](https://lucide.dev/)
* **Routing:** React Router DOM v6
* **Build Tool:** Vite
* **Deployment:** Vercel / Netlify

---

## 📦 Getting Started

If you want to run this project locally:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/yourusername/disctimestamps.git](https://github.com/yourusername/disctimestamps.git)
    cd disctimestamps
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Start the development server**
    ```bash
    npm run dev
    ```

---

## 🤝 Contributing

Contributions are welcome! If you have an idea for a new tool (e.g., an Embed Builder or Emoji Stealer), feel free to open an issue or submit a Pull Request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---
