# Pritam Patil — Portfolio Website

A fully self-contained, single-file portfolio. No dependencies to install.

## 🚀 Deploy in 60 Seconds

### Vercel (Recommended)
1. Go to vercel.com → Sign in with GitHub
2. Drag & drop the `portfolio` folder
3. Done! Live URL in seconds.

### GitHub Pages
1. Create repo → upload `index.html` as root
2. Settings → Pages → Deploy from main branch
3. Live at `yourusername.github.io/repo-name`

### Netlify
1. Go to netlify.com → "Add new site" → "Deploy manually"
2. Drag & drop the `portfolio` folder
3. Instant live URL!

## 🔧 Customize

### Update Project Links
In `index.html`, search for:
- `href="https://github.com/thepritampatil"` — replace with actual repo URLs
- `href="https://vercel.com"` — replace with actual live demo URLs

### Add Resume PDF
Replace the `onclick="alert(...)"` on the Resume button with:
```html
href="your-resume.pdf" download="Pritam_Patil_Resume.pdf"
```

## ✅ Features
- Embedded profile photo (no external image hosting needed)
- Custom animated cursor with glow
- Scroll progress bar
- Reveal-on-scroll animations
- DSA counter animation (0 → 450+)
- Project filter tabs (All / Mobile / Web)
- Mobile responsive with hamburger menu
- Tech stack icons from SimpleIcons CDN
- Tilt hover effects on cards
