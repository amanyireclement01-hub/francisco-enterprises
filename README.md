# Francisco Enterprises Website

**Motto:** Building Wealth Together

A professional, mobile-responsive single-page website for Francisco Enterprises — a member-based savings, investment and business development initiative in Uganda.

---

## Project Structure

```
francisco-enterprises/
├── index.html
├── README.md
├── css/
│   └── style.css
├── js/
│   └── script.js
└── assets/
    ├── logo/
    │   └── francisco-enterprises-logo.png   ← Official logo (already placed)
    └── images/                             ← Optional local images folder
```

---

## How to Deploy (Beginner Guide)

### 1. Create a GitHub Repository

1. Go to [https://github.com](https://github.com) and sign in.
2. Click the **+** button → **New repository**.
3. Name it exactly: `francisco-enterprises`
4. Leave it **Public**.
5. Do **not** add a README, .gitignore or license (we already have files).
6. Click **Create repository**.

### 2. Upload the Website Files

**Option A — Using the GitHub website (easiest for beginners)**

1. On the new empty repository page, click **uploading an existing file**.
2. Drag and drop **all** the files and folders from this project:
   - `index.html`
   - `README.md`
   - the entire `css/` folder
   - the entire `js/` folder
   - the entire `assets/` folder
3. Make sure `index.html` is in the **root** of the repository (not inside another folder).
4. Click **Commit changes**.

**Option B — Using Git (if you know Git)**

```bash
git init
git add .
git commit -m "Initial Francisco Enterprises website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/francisco-enterprises.git
git push -u origin main
```

### 3. Deploy on Render as a Static Site

1. Go to [https://render.com](https://render.com) and sign up / log in (you can use your GitHub account).
2. Click **New +** → **Static Site**.
3. Connect the `francisco-enterprises` repository.
4. Configure the settings exactly like this:

| Setting              | Value                  |
|----------------------|------------------------|
| **Name**             | francisco-enterprises  |
| **Branch**           | main                   |
| **Root Directory**   | *(leave empty)*        |
| **Build Command**    | *(leave empty)*        |
| **Publish Directory**| `.`                    |

5. Click **Create Static Site**.
6. Wait 1–2 minutes. Render will give you a live URL such as:  
   `https://francisco-enterprises.onrender.com`

Your website is now live!

---

## Local Testing

Simply open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).  
All styles and scripts use relative paths, so everything works offline except the external photos (Unsplash) and Google Fonts.

---

## Brand Colors

| Color            | Hex       | Usage                    |
|------------------|-----------|--------------------------|
| Dark Green       | `#0d5c2e` | Headers, primary text    |
| Green            | `#1a7a3a` | Buttons, accents         |
| Light Green      | `#2d9a52` | Hover states             |
| Gold / Yellow    | `#d4a017` | CTAs, highlights         |
| Cream / White    | `#faf8f2` | Backgrounds              |

---

## Important Notes

- The official logo is already placed at `assets/logo/francisco-enterprises-logo.png`.
- Business activity images currently use high-quality Unsplash photos. You can later replace them with your own photos by:
  1. Adding images to `assets/images/`
  2. Updating the `src` attributes in `index.html`
- The contact form opens the visitor’s email client. For a fully automated form you can later connect services such as Formspree, Netlify Forms, or Google Forms.
- No statistics, testimonials or profit guarantees have been invented.
- The site is static (HTML + CSS + vanilla JS) — no React, no Node.js, no database.

---

## Contact Information (as shown on the site)

**CEO:** Alituha Francis — +256 775 179667  
**President:** Atukwase Penlope — +256 774 664625  
**Location:** Kampala / Sheema, Uganda  
**WhatsApp:** [https://wa.me/256775179667](https://wa.me/256775179667)

---

© 2026 Francisco Enterprises. All rights reserved.
