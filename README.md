# 🎮 Steam Manifest Downloader

A modern, client-side **Steam Manifest Downloader** that fetches Steam app manifest files directly from GitHub and bundles them into a downloadable ZIP — all from your browser, with **zero backend**.

Built with a sleek UI, animated particles background, and custom cursor effects for a premium user experience.

---

## ✨ Features

- 🔍 Accepts **Steam AppID** or **Steam Store URL**
- 📦 Automatically fetches all manifest files from GitHub
- 🗜️ Packages files into a single **ZIP** using JSZip
- ⚡ Fully **client-side** (no server required)
- ⏱️ Displays download statistics:
  - File count
  - Total size
  - Time taken
- 🎨 Animated particles background (particles.js)
- 🖱️ Custom animated cursor
- 📱 Fully responsive (mobile-friendly)
- 💬 Built-in Discord community link

---

## 🚀 How It Works

1. Enter a Steam **AppID**  
   Example: `570`

   **OR**

   Enter a Steam Store URL  
   Example: `https://store.steampowered.com/app/570`

2. The application automatically extracts the AppID.
3. Manifest files are fetched from the GitHub repository:
  https://github.com/SteamAutoCracks/ManifestHub
4. All files in the AppID branch are downloaded.
5. Files are compressed into a ZIP file in the browser.
6. The ZIP is made available for instant download.

---

## 🧩 Technologies Used

- **HTML5**
- **CSS3** (animations, gradients, responsive layout)
- **JavaScript (ES6+)**
- **JSZip** – client-side ZIP generation
- **particles.js** – animated background
- **GitHub REST API** – file tree and raw content access

---

## 📂 Project Structure


> This is a **single-file static web app**. No backend, no build tools, no dependencies to install.

---

## 🛠️ Installation & Usage

### Local Usage
1. Download or clone the repository
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox)
3. Enter a Steam AppID or Store URL
4. Click **Download Manifest**

### Web Hosting
You can deploy this project on:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

No configuration required.

---

## ⚠️ Notes & Limitations

- Requires public access to the target GitHub repository
- Large manifests may take longer due to GitHub rate limits
- Best performance on Chromium-based browsers
- No Steam API key or authentication required

---

## 🔒 Privacy & Security

- No backend server
- No data storage
- No analytics or tracking
- All operations run locally in the browser

---

## 💬 Community

Join the Discord community for support and updates:  
https://discord.gg/GtkkjXpbfC

---

## 📜 Disclaimer

This project is provided for **educational and archival purposes only**.  
Users are responsible for complying with Steam’s Terms of Service and applicable laws.

---

## ⭐ Credits

- **JSZip**
- **particles.js**
- **GitHub API**



