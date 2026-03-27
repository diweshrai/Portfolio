# Diwesh Rai — Portfolio Website

A clean, premium, light-themed single-page portfolio built with pure HTML, CSS, and JavaScript. No build step required — works instantly on GitHub Pages or Vercel.

## 🚀 Quick Start (Local Preview)

```bash
cd MYPORTFOLIO
npx serve .
# Opens at http://localhost:3000
```

Or simply open `index.html` directly in your browser.

---

## 📁 Project Structure

```
MYPORTFOLIO/
├── index.html           # Main SPA
├── style.css            # Premium light theme
├── script.js            # Interactions & animations
├── assets/
│   ├── profile.jpg      # Your profile photo
│   └── Diwesh_Rai_Resume.pdf  # Your resume (replace!)
└── README.md
```

---

## ✏️ Personalising the Content

| What to change | Where |
|---|---|
| Email, phone, links | `index.html` → `#contact` section |
| Job history | `index.html` → `#experience` section |
| Projects | `index.html` → `#projects` section |
| Profile photo | Replace `assets/profile.jpg` |
| Resume | Replace `assets/Diwesh_Rai_Resume.pdf` |
| LinkedIn / GitHub / social URLs | Search for `diweshrai` in `index.html` |

---

## 🌐 Deploying

### GitHub Pages
1. Push this folder to a GitHub repo (e.g., `yourusername.github.io`)
2. Go to **Settings → Pages → Source → main branch → / (root)**
3. Your site is live at `https://yourusername.github.io`

### Vercel
1. Go to [vercel.com](https://vercel.com) → **Add New Project**
2. Import your GitHub repo
3. Leave all settings as default (no build command needed)
4. Click **Deploy** — done! ✅

---

## 📦 Libraries Used (CDN — no install)

| Library | Purpose |
|---|---|
| [AOS](https://michalsnik.github.io/aos/) | Scroll animations |
| [Font Awesome 6](https://fontawesome.com/) | Icons |
| [Google Fonts — Inter + Plus Jakarta Sans](https://fonts.google.com/) | Typography |
