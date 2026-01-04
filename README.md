# DreamJar Website

This folder contains the support pages for DreamJar app.

## Quick Setup with GitHub Pages

### Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Name it: `dreamjar-site` (or any name you prefer)
3. Make it **Public** (required for free GitHub Pages)
4. Click "Create repository"

### Step 2: Push These Files
Run these commands in Terminal:

```bash
cd "/Users/zakmcintyre/Documents/iOS Projects/DreamJar/WebPages"
git init
git add .
git commit -m "Initial commit - DreamJar support pages"
git branch -M main
git remote add origin https://github.com/zakmcintyre/dreamjar-site.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repo: https://github.com/zakmcintyre/dreamjar-site
2. Click **Settings** tab
3. Click **Pages** in the left sidebar
4. Under "Source", select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**

### Step 4: Your URLs (within ~2 minutes)
- **Support URL:** `https://zakmcintyre.github.io/dreamjar-site/support.html`
- **Privacy Policy URL:** `https://zakmcintyre.github.io/dreamjar-site/privacy-policy.html`
- **Homepage:** `https://zakmcintyre.github.io/dreamjar-site/`

## Files Included
- `index.html` - Landing page
- `support.html` - Support/FAQ page (use this for App Store)
- `privacy-policy.html` - Privacy Policy (use this for App Store)

## Customization
- Edit the HTML files to update content
- Push changes with `git add . && git commit -m "Update" && git push`
