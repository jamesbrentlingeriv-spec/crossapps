# ScriptureFlow

> *Study, reflect, and grow in the Word*

A unified landing page and Progressive Web App that connects your scripture tools—**SermonFlow** and **Bible Study Suite**—in one place. Open either app within the same window, or install ScriptureFlow for quick access from your home screen.

---

## Features

| Feature | Description |
|---------|-------------|
| **Unified Hub** | Single entry point to SermonFlow and Bible Study Suite |
| **In-App Navigation** | Open apps in-iframe with a Home button—no tab switching |
| **Progressive Web App** | Install to home screen for app-like access (desktop & mobile) |
| **Offline Fallback** | Landing page cached for quick load when offline |
| **Responsive Design** | Works across phones, tablets, and desktops |

---

## Apps

### SermonFlow
Listen, organize, and engage with sermon recordings and teachings.

→ [Open SermonFlow](https://sermonflow-840075680860.us-west1.run.app/)

### Bible Study Suite
Read scripture across multiple translations, take notes, and study with parallel texts.

→ [Open Bible Study Suite](https://jamesbrentlingeriv-spec.github.io/biblestudy/)

---

## Installation

ScriptureFlow is a PWA. To install:

1. Open the live site (or serve locally over HTTPS).
2. Use your browser’s **Install** or **Add to Home Screen** option.
3. Launch ScriptureFlow from your home screen or app drawer.

> **Note:** PWAs require HTTPS (or `localhost` for development).

---

## Local Development

Serve the project with any static file server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

---

## Project Structure

```
crossapps/
├── index.html      # Landing page and app shell
├── manifest.json   # PWA manifest
├── sw.js           # Service worker (caching)
├── favicon.ico     # Favicon
├── icon-192.png    # PWA icon (192×192)
├── icon-512.png    # PWA icon (512×512)
└── README.md       # This file
```

---

## Deployment

Deploy the contents of this directory to any static host:

- **GitHub Pages** — push to a repo and enable Pages
- **Netlify** — drag-and-drop or connect the repo
- **Cloudflare Pages** — connect repo or upload
- **Google Cloud Storage / Firebase Hosting** — upload static files

No build step is required.

---

## License

This project is provided as-is for personal and educational use.

---

<p align="center">
  <sub>jamesbrentlinger2026™</sub>
</p>
