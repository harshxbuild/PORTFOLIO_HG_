# Harsh Girhe — Cyber Security Portfolio

Static portfolio (HTML/CSS/JS, Three.js + GSAP via CDN). No build step.

## Structure
```
index.html
assets/        certificate images
vercel.json    caching + security headers
```

## Run locally
```bash
npx serve .
```

## Deploy to GitHub
```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/harshxbuild/portfolio.git
git push -u origin main
```

## Deploy to Vercel
1. Go to vercel.com/new and import the GitHub repo.
2. Framework Preset: **Other**. Leave build command and output directory empty.
3. Deploy. Every push to `main` redeploys automatically.

Or via CLI: `npx vercel --prod`

## After deploying
Point the "Live demo on Vercel" button in `index.html` (`id="live"`) at your AURA demo URL.
