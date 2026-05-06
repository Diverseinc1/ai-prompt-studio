# 🧠 AI Prompt Studio – Agency Management Suite

A powerful, all‑in‑one prompt editor for building full‑featured agency management platforms.  
**Live demo:** [your-site-url] (replace with your GitHub Pages URL)

![Screenshot](https://via.placeholder.com/800x400?text=AI+Prompt+Studio+Preview)  
*(Add a real screenshot later for best results)*

---

## ✨ Features

- **24+ modular AI prompts** – covers user auth, leads, CRM, projects, invoicing, tickets, and more.
- **Business context filtering** – tailor prompts for Marketing, Dev, Creative, Consulting, Real Estate, E‑commerce, IT.
- **Live editing** – all prompts, master blueprint, and quick helpers are fully editable.
- **One‑click copy** – copy any prompt or the entire filtered set to your clipboard.
- **Dark / Light theme** – toggle with a single button, persists across visits.
- **Save / Load to Browser** – your edits stay in local storage (no server needed).
- **Export to JSON** – backup or share your custom prompt library.
- **Download as PDF** – print the master prompt + visible modules as a clean PDF.
- **Optional cloud sync** (Firebase) – sync your work across multiple devices.

---

## 🚀 Quick Start

### 1. Use the live version (no installation)
Just visit your GitHub Pages URL:  
`https://YOUR_USERNAME.github.io/REPO_NAME/`

### 2. Run locally
- Download `index.html`
- Double‑click to open in your browser  
*(all features work offline except cloud sync)*

### 3. Deploy your own copy to GitHub Pages
Follow the guide below.

---

## 🛠️ How to Deploy (GitHub Pages)

1. **Create a public repository** on GitHub (no README, no .gitignore).
2. **Upload `index.html`** to the root of the repository.
3. Go to **Settings → Pages** → set branch to `main` and folder to `/ (root)` → click **Save**.
4. After 1 minute, your site is live at:  
   `https://YOUR_USERNAME.github.io/REPO_NAME/`

> 💡 **Pro tip:** Rename the file to `index.html` – GitHub Pages automatically serves it as the homepage.

---

## ☁️ Enable Cloud Sync (Firebase – optional)

Cross‑device sync requires a free Firebase project.

1. Create a project at [firebase.google.com](https://firebase.google.com).
2. Add a web app and copy the `firebaseConfig` object.
3. In `index.html`, locate the commented Firebase block (around line 660–700).  
   Uncomment it and paste your config.
4. Re‑upload `index.html` – the **Sync to Cloud** / **Load from Cloud** buttons will now work.

> No backend code needed – Firebase handles all storage.

---

## 📁 File Structure
