
# AffMedics Website

A professional 2-page static website for **AffMedics**, a mobile occupational health business specializing in Audiometric testing, Mask Fit Testing, and Hearing Protection Devices (HPD).

---

## 🩺 Project Overview

AffMedics provides mobile occupational health services, ensuring workplace compliance with the **Occupational Health and Safety Act (OHS Act)** through professional on-site testing and documentation.

This repository contains a simple, fast-loading static HTML/CSS website ready to host on **GitHub Pages**.

---

## 📁 Folder Structure

```
AffMedics-Website/
├─ index.html              # Home page
├─ services.html           # Services & Contact page
├─ style.css               # Stylesheet
├─ assets/
│  ├─ logo.svg             # Redesigned logo (SVG)
│  ├─ logo_original.png    # Original logo (backup)
│  └─ hero.png             # Hero section image
└─ README.md               # This guide
```

---

## 🚀 How to Deploy to GitHub Pages

1. **Create a new GitHub repository**
   - Go to [https://github.com/new](https://github.com/new)
   - Name it **AffMedics-Website**
   - Choose “Public”
   - Don’t initialize with a README (you already have one)

2. **Upload your website files**
   - Click **"Upload files"** on the new repo page.
   - Drag and drop all files and folders from this ZIP into the repository.
   - Commit the changes.

3. **Enable GitHub Pages**
   - Go to **Settings → Pages** in your repo.
   - Under **“Build and deployment”**, select:
     - *Source:* `Deploy from a branch`
     - *Branch:* `main` (or `master`), and folder `/ (root)`
   - Save.

4. **View your live site!**
   - After a few minutes, GitHub Pages will publish your site.
   - It will be live at:
     ```
     https://<your-username>.github.io/AffMedics-Website/
     ```

---

## 🧩 Customization Tips

- **Colors & Fonts:** Edit `style.css` to change the look and feel.
- **Content:** Modify the HTML files directly to update text or add new sections.
- **Images:** Replace images in the `/assets` folder with your own.

---

## ⚙️ Optional Development Setup

If you use Git locally:

```bash
git clone https://github.com/<your-username>/AffMedics-Website.git
cd AffMedics-Website
# Make edits, then push updates
git add .
git commit -m "Updated content"
git push
```

---

© 2025 AffMedics. All rights reserved.
