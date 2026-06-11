# AI Studio → Android: Complete Deployment Guide v2.0

> A professional, interactive web guide for deploying Google AI Studio projects as installable Android PWAs — published by **[Techbase Consultant Services](https://techbasengr.com.ng)**.

**Live site:** [babatundeawo.github.io/ai-studio-android-guide](https://babatundeawo.github.io/ai-studio-android-guide)

---

## What This Is

A comprehensive step-by-step deployment guide that walks developers through the full pipeline:

- Setting up **Google AI Studio** and obtaining a Gemini API key
- Building and configuring the project files (`manifest.json`, service worker, `vercel.json`)
- Deploying to **Vercel** via GitHub integration
- Installing the live web app as a **Progressive Web App (PWA)** on Android
- Managing updates, debugging common issues, and maintaining the deployment

The guide is a single-file HTML document with an embedded sidebar navigation, interactive code blocks with one-click copy, an accordion troubleshooting section, and a reading progress bar — no build tools or dependencies required.

---

## Features

| Feature | Detail |
|---|---|
| 📋 Sidebar navigation | Fixed nav with active-section highlighting |
| 💻 Code blocks | Syntax-highlighted with one-click copy |
| 🔽 Accordion troubleshooting | 6 common issues with fixes |
| 📊 Free-tier reference table | Limits for AI Studio, Vercel, and GitHub |
| 📖 Glossary | 12 key terms defined |
| 📱 Responsive | Fully usable on mobile |
| ⚡ Zero dependencies | Pure HTML/CSS/JS, no build step |

---

## Tech Stack

- **HTML5 / CSS3 / Vanilla JS** — no frameworks
- **JetBrains Mono** — monospace font (Google Fonts)
- **Barlow / Barlow Condensed** — display and body fonts (Google Fonts)
- **GitHub Pages** — hosting

---

## File Structure

```
ai-studio-android-guide/
├── index.html      ← The entire guide (self-contained)
└── README.md       ← This file
```

---

## Local Preview

No build step needed. Just open `index.html` in any browser:

```bash
# Clone the repo
git clone https://github.com/babatundeawo/ai-studio-android-guide.git
cd ai-studio-android-guide

# Open directly (macOS / Linux)
open index.html

# Or start a simple local server
python3 -m http.server 8080
# Then visit http://localhost:8080
```

---

## Deployment (GitHub Pages)

This site is deployed automatically via GitHub Pages from the `main` branch.

Any push to `main` goes live within ~60 seconds at:
`https://babatundeawo.github.io/ai-studio-android-guide`

---

## Updating the Guide

1. Edit `index.html` locally
2. Commit and push to `main`
3. GitHub Pages rebuilds automatically — no action needed

```bash
git add index.html
git commit -m "docs: update [section name]"
git push origin main
```

---

## Author

**Babatunde Awoyemi** — Atmospheric Physicist & Lead Consultant  
[Techbase Consultant Services](https://techbasengr.com.ng) · Ibadan, Nigeria  
[github.com/babatundeawo](https://github.com/babatundeawo) · [x.com/ba_awoyemi](https://x.com/ba_awoyemi)

---

## Licence

© 2025 Techbase Consultant Services. All rights reserved.  
This guide is published for educational reference. You may share and adapt it with attribution.
