# Fieldhint League — Blogger Theme

A premium, dark-mode, SEO-optimized, AdSense-ready Blogger (Blogspot) theme for a football league website.

## Features
- 🏆 Live match score ticker with real-time simulation
- 📱 Fully responsive mobile design with hamburger navigation
- 🔍 SEO optimized: JSON-LD schema, OpenGraph, Twitter Cards, meta descriptions
- 💰 AdSense-ready slots: Header, In-Article (Top & Bottom), Sidebar, Footer
- 🏷️ Post labels/tags with category page headers
- 📋 Auto-generated Table of Contents for long posts
- ⏱️ Reading progress bar
- 🍞 Breadcrumb navigation
- 🔗 Social share buttons: Twitter/X, Facebook, WhatsApp, Telegram, LinkedIn, Copy Link
- 🔗 Related posts (auto-fetched by label via Blogger's RSS JSON API)
- 💬 Dark-themed Blogger comments
- 🔢 Pagination (older/newer posts)
- 🔍 Search integration (header + sidebar)
- 🚫 Custom 404 error page
- 🖨️ Clean print stylesheet
- 📡 RSS/Atom feed support
- 🌙 Google Analytics 4 widget slot

## Files
| File | Description |
|------|-------------|
| `theme.xml` | **Main Blogger XML template** — upload this to Blogspot |
| `index.html` | Local preview simulator of the theme |
| `index.css` | Stylesheet for the local preview |
| `app.js` | JavaScript for the local preview |

## How to Install on Blogspot
1. Download / clone this repo.
2. Go to **[Blogger.com](https://www.blogger.com)** → your blog → **Theme**.
3. Click the arrow `▼` next to **Customize** → select **Restore**.
4. Click **Upload** and choose `theme.xml`.
5. After uploading, go to **Layout** and:
   - Edit the **Google Analytics 4** widget to add your GA4 script.
   - Edit the **AdSense** widget slots to add your `<ins class="adsbygoogle">` code.
6. Go to **Settings → Basic** and fill in your blog title and description.

## Local Preview
```bash
npx http-server -p 3000
```
Then open `http://localhost:3000/index.html`

---
© 2026 Fieldhint League. All rights reserved.
