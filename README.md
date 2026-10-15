# 🚀 Standalone Deployment Guide: ExamGuard AI Portfolio

This directory (`portfolio-site/`) contains a completely standalone, self-contained single-page portfolio website for **ExamGuard AI**.

It has **zero Python dependencies**, requires **no backend server**, and can be deployed anywhere in 1 minute.

---

## 🌐 Option 1: Deploy on Vercel (Recommended - Free, Instant)

### Via Vercel Web Dashboard:
1. Push this folder to a new GitHub repository (e.g. `examguard-portfolio`).
2. Log into [vercel.com](https://vercel.com).
3. Click **"Add New Project"** and import the repository.
4. Leave root directory as default (or select `./portfolio-site`).
5. Click **Deploy**. Your portfolio will be live at `https://examguard-portfolio.vercel.app`.

### Via Vercel CLI (30 seconds):
```bash
cd "d:\Online Examination System with Anti-Cheating Detection\portfolio-site"
npx vercel
```

---

## ⚡ Option 2: Deploy on Netlify (Drag & Drop - 10 Seconds)

1. Open [app.netlify.com/drop](https://app.netlify.com/drop) in your browser.
2. Drag and drop the `portfolio-site` folder directly into the browser window.
3. Your portfolio is immediately live with a custom URL and free SSL!

---

## 🐙 Option 3: Deploy on GitHub Pages (Free)

1. Create a new GitHub repo named `portfolio` or `<your-username>.github.io`.
2. Copy `portfolio-site/index.html` to the root of that repository.
3. In GitHub repo Settings &rarr; **Pages** &rarr; Select `main` branch & `/ (root)`.
4. Click **Save**. It will be live at `https://<your-username>.github.io`.

---

## 💻 Local Preview

Simply double click `index.html` in Windows Explorer, or run:
```bash
cd portfolio-site
python -m http.server 8000
```
Open `http://localhost:8000` in your browser.
