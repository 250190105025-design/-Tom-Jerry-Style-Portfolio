# 🚀 Deployment Guide

## Option 1 — GitHub Pages (Free, Recommended)

### Step 1 — Push to GitHub
```bash
# Initialize git (if not done)
git init
git add .
git commit -m "feat: initial portfolio launch 🐭🧀"

# Create repo on GitHub (replace with your username)
git remote add origin https://github.com/YOUR_USERNAME/jerry-portfolio.git
git branch -M main
git push -u origin main
```

### Step 2 — Enable GitHub Pages
1. Go to your repo on GitHub
2. Click **Settings** (top menu)
3. Scroll to **Pages** (left sidebar)
4. Under **Source** → select **Deploy from a branch**
5. Branch: `main` · Folder: `/ (root)`
6. Click **Save**

### Step 3 — Wait ~60 seconds
Your site will be live at:
```
https://YOUR_USERNAME.github.io/jerry-portfolio
```

### Step 4 — (Optional) Auto-deploy with Actions
The `.github/workflows/deploy.yml` file is already included.  
It automatically deploys every time you push to `main`.  
To enable it:
1. Go to **Settings → Pages**
2. Change Source to **GitHub Actions**
3. Done! Future pushes auto-deploy. 🎉

---

## Option 2 — Netlify (Free, Drag & Drop)

1. Go to [netlify.com](https://netlify.com) and sign up/log in
2. Click **"Add new site"** → **"Deploy manually"**
3. Drag your `index.html` file (or the whole folder) onto the deploy zone
4. Netlify gives you a URL like `https://random-name.netlify.app`
5. (Optional) Connect your GitHub repo for auto-deploys

---

## Option 3 — Vercel (Free)

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy from project folder
cd jerry-portfolio
vercel

# Follow the prompts — it auto-detects static HTML
# Your URL: https://jerry-portfolio.vercel.app
```

---

## Option 4 — Cloudflare Pages (Free, Fast CDN)

1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Connect your GitHub account
3. Select your `jerry-portfolio` repository
4. Build settings:
   - **Framework preset:** None
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/` (root)
5. Click **Save and Deploy**

---

## Custom Domain (All Platforms)

After deploying, you can attach a custom domain like `jerry.dev`:

### GitHub Pages
1. Settings → Pages → Custom domain → enter your domain
2. Add a `CNAME` file to the repo root containing just your domain:
   ```
   jerry.dev
   ```
3. Point your domain's DNS to GitHub's IPs or add a CNAME record

### Netlify / Vercel / Cloudflare
All three have a "Custom Domain" section in their dashboard. Follow the UI — it's straightforward.

---

## 🔄 Updating Your Portfolio

```bash
# Make changes to index.html, then:
git add .
git commit -m "feat: add new project — ChatBurst 💬"
git push

# GitHub Pages / Vercel / Netlify will auto-deploy in ~30-60 seconds
```
