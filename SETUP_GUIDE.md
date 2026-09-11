# 🚀 GitHub Profile Setup & Deployment Guide

This repository contains your premium, AI-designed GitHub Profile landing page.

---

## 📂 Repository Structure

Ensure your special repository (`praveenstp09/praveenstp09`) is organized as follows:

```text
praveenstp09/                      <-- Special repository matching your GitHub username
├── .github/                       <-- (Optional) Workflows for snake animation
├── assets/
│   ├── hero-banner.svg            <-- Custom AI/SaaS-themed vector header banner
│   └── cyber-divider.svg          <-- Glowing electric cyan/indigo section divider
├── README.md                      <-- Your main profile landing page
└── SETUP_GUIDE.md                 <-- This configuration guide
```

---

## ⚡ Quick Start: Publishing to Your GitHub Profile

### Step 1: Create the Special Repository (if not already created)
1. Go to [GitHub New Repository](https://github.com/new).
2. Set the **Repository name** to: `praveenstp09` (must match your username exactly).
3. Set the repository visibility to **Public**.
4. Check **Add a README file** (or push this existing folder).

### Step 2: Push the Files
In your terminal (inside this folder `c:\Users\prave\OneDrive\Desktop\Assignment\Github`):

```bash
# Initialize git if needed
git init
git add .
git commit -m "feat: launch premium AI-designed developer profile landing page"
git branch -M main

# Add your GitHub repository remote and push
git remote add origin https://github.com/praveenstp09/praveenstp09.git
git push -u origin main --force
```

---

## 🎨 Asset Paths & Absolute URL Fallback

Your `README.md` uses clean relative asset paths:
- `./assets/hero-banner.svg`
- `./assets/cyber-divider.svg`

GitHub natively renders relative paths inside repository READMEs.

If you ever embed the README or assets across external platforms or prefer raw CDN URLs, you can replace `./assets/...` with:
```html
https://raw.githubusercontent.com/praveenstp09/praveenstp09/main/assets/hero-banner.svg
https://raw.githubusercontent.com/praveenstp09/praveenstp09/main/assets/cyber-divider.svg
```

---

## ⚙️ Customizing Links & Dynamic Widgets

All personal details in `README.md` are pre-wired to your verified accounts:

| Item | Current Value | How to Update |
| :--- | :--- | :--- |
| **Email** | `praveenverma0933@gmail.com` | Search & replace email in `README.md` |
| **LinkedIn** | `https://www.linkedin.com/in/praveen-verma-b90333282/` | Update your custom vanity URL if needed |
| **LeetCode** | `https://leetcode.com/u/praveenstp09/` | Update with your LeetCode username |
| **PharmaCode07 Demo**| `https://github.com/praveenstp09/Pharmacode07` | Replace with your deployed Vercel/Render URL |
| **TechKart Demo** | `https://github.com/praveenstp09/Ecommerce` | Replace with your deployed live store link |

### Dynamic GitHub Widgets Configuration
The widgets in the **Developer Analytics** section use your GitHub handle (`praveenstp09`):
* **Stats & Streak**: Automatically refresh daily as you make commits.
* **Theme Styling**: The query parameters (`bg_color=090d16&title_color=38bdf8&icon_color=818cf8&text_color=94a3b8`) match your Obsidian & Electric Cyan/Indigo visual identity.
* **Top Languages**: Displays your most-used languages across your public repositories.
* **Contribution Graph**: Renders an interactive commit wave graph.

---

## 🧪 Verifying the Presentation

1. Open your profile at [https://github.com/praveenstp09](https://github.com/praveenstp09).
2. Verify that:
   - The **Hero Banner** loads with sharp vector typography and glowing accents.
   - The **Typing SVG** animates smoothly.
   - The **Project Cards** expand when clicking the `<details>` dropdowns.
   - All contact and social badge links open your respective profiles.
