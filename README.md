# Praveen Jangid — Portfolio

Personal portfolio site for [GitHub Pages](https://pages.github.com/).

**Live URL (after deploy):** https://praveen221.github.io/portfolio/

## What’s in here

| File | Purpose |
|------|---------|
| `index.html` | Single-page portfolio (about, projects, experience, skills, sites, contact) |
| `styles.css` | Dark theme layout and styling |

Static HTML/CSS only — no build step.

## Deploy to GitHub Pages (free)

Yes — GitHub Pages is free for public repos on free GitHub accounts.

### 1. Push this repo

```bash
git add .
git commit -m "Add portfolio site"
git push -u origin master
```

If your default branch is `main` instead of `master`:

```bash
git branch -M main
git push -u origin main
```

### 2. Turn on Pages

1. Open the repo: https://github.com/praveen221/portfolio  
2. **Settings** → **Pages** (left sidebar)  
3. Under **Build and deployment** → **Source**, choose **Deploy from a branch**  
4. **Branch:** `master` (or `main`) · **Folder:** `/ (root)`  
5. Click **Save**

### 3. Wait a minute, then open

Site will be at:

**https://praveen221.github.io/portfolio/**

GitHub shows the exact URL on the same Pages settings page once it’s ready (often 1–2 minutes).

### Optional: custom domain

On the same Pages settings page you can add a custom domain (e.g. `praveenjangid.com`) if you own one.

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
# Python
python3 -m http.server 8080

# then open http://localhost:8080
```

## Updating the site

Edit `index.html` / `styles.css`, commit, and push. Pages redeploys automatically from the branch you configured.
