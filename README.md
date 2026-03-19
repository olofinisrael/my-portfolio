# Israel Olubukola — AI Automation Engineer Portfolio

A futuristic, fully responsive personal portfolio website built for an AI Automation Engineer. Designed with a dark glassmorphism aesthetic, neon blue/purple accents, and smooth animations — built to impress high-paying clients.

---

## 🌐 Live Preview

Open `index.html` in any modern browser — no server or build tools required.

---

## 📁 Project Structure

```
israel-portfolio/
└── index.html       # Complete single-file portfolio (HTML + CSS + JS)
```

Everything is self-contained in one file for easy deployment and portability.

---

## ✨ Features

- **Single-page portfolio** with smooth scroll navigation
- **10 full project case study pages** — each with overview, problem, solution, workflow steps, tools, results, and CTA
- **Dark glassmorphism UI** — blurred cards, glowing borders, soft shadows
- **Animated hero section** — floating orbs, circuit background, staggered text entrance
- **Scroll reveal animations** — sections animate in as you scroll
- **Fully responsive** — mobile, tablet, and desktop layouts
- **Contact section** — Email, WhatsApp, and Fiverr buttons

---

## 🗂️ Sections

| Section | Description |
|---|---|
| Hero | Headline, subheadline, CTA buttons, and key stats |
| About | Personal card, bio, skills, and strength highlights |
| Experience | Numbers, industries worked in, achievements |
| Services | 6 service cards with hover animations |
| Projects | 10 clickable portfolio cards linking to case studies |
| Contact | Email, WhatsApp, and Fiverr buttons |
| Footer | Credit line |

---

## 📬 Contact Info (Pre-configured)

| Channel | Value |
|---|---|
| Email | Olofinisrael1@gmail.com |
| WhatsApp | +234 805 1991 871 |
| Fiverr | Update `fiverr.com/your-profile` in the HTML |

---

## 🚀 Deployment Options

### Option 1 — GitHub Pages (Free)
1. Create a new GitHub repository
2. Upload `index.html` to the repository
3. Go to **Settings → Pages**
4. Set source to `main` branch, root folder
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Option 2 — Netlify (Free, Recommended)
1. Go to [netlify.com](https://netlify.com) and sign up
2. Drag and drop the `israel-portfolio` folder onto the Netlify dashboard
3. Your site is instantly live with a free `.netlify.app` URL
4. Optionally connect a custom domain

### Option 3 — Vercel (Free)
1. Go to [vercel.com](https://vercel.com) and sign up
2. Import the project from GitHub or drag and drop
3. Deploy with one click

### Option 4 — Custom Domain + Hosting
Upload `index.html` to any web host (Hostinger, Namecheap, etc.) via cPanel File Manager or FTP.

---

## 🛠️ Customization Guide

### Update Your Fiverr Link
In `index.html`, search for:
```
fiverr.com/your-profile
```
Replace with your actual Fiverr profile URL.

### Add Your Workflow Screenshots
Each project case study has a placeholder section:
```
Workflow screenshot / diagram placeholder — upload your n8n workflow screenshot here.
```
Replace the placeholder `<div>` with an `<img>` tag pointing to your screenshot:
```html
<img src="your-screenshot.png" alt="Workflow" style="width:100%;border-radius:16px;">
```

### Change Your Name / Bio
All personal content is in the HTML — search for `Israel Olubukola` to find and update any text.

### Add a Real Profile Photo
In the About section, replace the `IO` avatar initials div with:
```html
<img src="your-photo.jpg" alt="Israel Olubukola" style="width:80px;height:80px;border-radius:50%;object-fit:cover;">
```

### Update Project Descriptions
All 10 projects are defined in the JavaScript `projects` array near the bottom of `index.html`. Each project object contains: `title`, `desc`, `tags`, `subtitle`, `overview`, `problem`, `solution`, `steps`, `tools`, `results`, and `features`.

---

## 🎨 Design System

| Token | Value |
|---|---|
| Primary Background | `#030712` |
| Secondary Background | `#060d1f` |
| Accent Blue | `#3b9eff` |
| Accent Purple | `#a855f7` |
| Body Font | DM Sans |
| Heading Font | Syne |

---

## 📱 Browser Support

Works on all modern browsers: Chrome, Firefox, Safari, Edge. Requires JavaScript enabled for project cards and page navigation.

---

## 📄 License

This portfolio was designed and built for **Israel Olubukola**. All rights reserved.

---

*Designed & Built by Israel Olubukola | AI Automation Engineer*
