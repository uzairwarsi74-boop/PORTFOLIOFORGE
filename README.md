# PortfolioForge 🚀

A free, open-source web platform for building stunning, animated portfolio websites. No account required. Export to HTML and deploy to GitHub Pages in minutes.

## ✨ Features

- **8+ Themes** — Cosmic Dark, Emerald Forest, Ember Glow, Ocean Breeze, Rose Gold, Matrix, Noir Minimal, Clean Light
- **15+ Animations** — Typewriter, Glitch, Gradient Shift, Fade Up, Slide, Zoom, Bounce, Flip, Parallax
- **Custom Sections** — Hero, About, Skills, Projects, Testimonials, Contact, Gallery
- **Full Design Control** — Colors, fonts, border radius, spacing, toggles
- **Image Uploads** — Profile photo + per-project images (stored as base64)
- **Live Preview** — Real-time iframe preview as you type
- **Export to HTML** — Single-file download, ready to deploy
- **100% Free** — No server, no backend, no account needed
- **Multiple Users** — Each user saves locally in their browser

---

## 🚀 Deploy to GitHub Pages (Free Hosting)

### Step 1 — Fork or Clone This Repo

```bash
git clone https://github.com/YOUR_USERNAME/portfolio-forge.git
cd portfolio-forge
```

Or click **Fork** on GitHub to get your own copy.

### Step 2 — Enable GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select `main` branch → `/ (root)` folder
4. Click **Save**

Your platform will be live at:
```
https://YOUR_USERNAME.github.io/portfolio-forge/
```

### Step 3 — Share the URL

Anyone with the URL can go to `builder.html` and create their own portfolio!

---

## 📁 File Structure

```
portfolio-forge/
├── index.html          # Landing page
├── builder.html        # Portfolio builder app
└── README.md           # This file
```

That's it! Just 2 HTML files. No build tools, no npm, no dependencies.

---

## 🎯 How Users Build Their Portfolio

1. Visit `https://your-site.github.io/portfolio-forge/builder.html`
2. Fill in their name, role, bio, links
3. Add skills and projects with images
4. Choose a theme and animations
5. Click **Export HTML** → downloads `name-portfolio.html`
6. User uploads that file to their own GitHub repo and enables Pages

---

## 🌍 Deploying the Exported Portfolio

After a user exports their `portfolio.html` file:

### Option A — GitHub Pages (Free)
1. Create a new GitHub repo named `username.github.io`
2. Upload the `portfolio.html` file, rename it to `index.html`
3. Enable GitHub Pages (Settings → Pages → main branch)
4. Live at `https://username.github.io`

### Option B — Netlify Drop (Free, Instant)
1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag and drop the HTML file
3. Live instantly with a `.netlify.app` URL

### Option C — Any Web Host
Just upload the single HTML file. Works on any static hosting.

---

## 🎨 Themes

| Theme | Colors | Best For |
|-------|--------|----------|
| Cosmic Dark | Purple + Cyan | Tech, Dev |
| Emerald Forest | Green tones | Creative, Designer |
| Ember Glow | Orange + Amber | Photographer, Artist |
| Noir Minimal | B&W + Gray | Consultant, Finance |
| Ocean Breeze | Blue tones | Data, Science |
| Rose Gold | Pink + Gold | Fashion, Beauty |
| Matrix | Terminal Green | Hacker, CLI Dev |
| Clean Light | White + Purple | Business, Clean |

---

## 🛠 Customization

All configuration is done through the UI. Advanced users can edit `builder.html` directly:

- Add new themes in the `THEMES` object
- Add new animations in the `ENTRY_ANIMS` / `TEXT_EFFECTS` arrays
- Add new section renderers in the `generatePortfolioHTML` function

---

## 📄 License

MIT License — free for personal and commercial use.

---

Made with ❤️ · Completely Free · No Backend Required
