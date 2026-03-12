# Vaelyn Hargrave — Portfolio Website

A multi-page personal portfolio website mirroring the design and layout of kysondana.com.  
White background · Black serif headlines · Minimal nav · Large typography · Photo scroll strips.

---

## 🚀 GitHub Pages Setup (5 minutes)

### Option A — User Site (your URL will be `yourusername.github.io`)
1. Create a repo named exactly: `yourusername.github.io`
2. Upload **all files** in this folder to the repo root
3. Go to **Settings → Pages → Source → Deploy from branch `main` / root**
4. Live in ~60 seconds

### Option B — Project Site (URL will be `yourusername.github.io/portfolio`)
1. Create any repo (e.g., `portfolio`)
2. Upload all files to root
3. Settings → Pages → same steps as above

---

## 📁 File Structure

```
/
├── index.html              ← Home page
├── style.css               ← Shared styles (all pages)
├── scroll.js               ← Shared scroll-reveal animation
├── README.md
├── work/
│   └── index.html          ← Work showcase page
├── about/
│   └── index.html          ← About + Timeline + Skills
├── invest/
│   └── index.html          ← CPG M&A + Setmore booking embed
├── contact/
│   └── index.html          ← Contact page
└── assets/
    ├── images/
    │   ├── hero_portrait.jpg
    │   ├── about_portrait.jpg
    │   ├── work_portrait.jpg
    │   ├── headshot.jpg
    │   ├── portrait.jpg
    │   └── hero_edit.jpg
    └── videos/
        ├── starbucks_crema.mp4
        └── starbucks_via.mp4
```

---

## ✏️ Key Customizations Before Going Live

| What | Where | Find & Replace |
|------|-------|----------------|
| Email address | All HTML files | `hello@vaelynh.com` |
| LinkedIn URL | All HTML files | `https://linkedin.com` |
| Your name | All HTML files | `Vaelyn Hargrave` |
| Setmore booking | `invest/index.html` | Already set to `vaelynhargrave.setmore.com` |

---

## 🎨 Design System

- **Colors**: `#0d0d0d` black · `#ffffff` white · `#f7f5f1` off-white · `#ebebeb` light gray
- **Serif font**: Playfair Display (Google Fonts — loaded via CDN)
- **Sans font**: Inter (Google Fonts — loaded via CDN)
- **No build tools** — pure HTML/CSS/JS, works offline and deploys anywhere

---

## 📄 Pages

| Page | Path | Description |
|------|------|-------------|
| Home | `/` | Hero, video reel, logo strip, work cards, photo strip |
| Work | `/work/` | Full project showcase with metrics |
| About | `/about/` | Bio, career timeline, skills, education, photo strip |
| Invest | `/invest/` | CPG M&A philosophy + Setmore booking embed |
| Contact | `/contact/` | Contact info + photo |
