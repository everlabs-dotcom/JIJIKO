# Jijiko Landing Page — GitHub Pages Setup

## What's in this folder
- `index.html` — your landing page, renamed so GitHub Pages recognizes it as the homepage.

GitHub Pages specifically looks for a file called `index.html` at the root of the repo — that's the only rename needed. Everything else (fonts, styles) loads from the internet, so there's nothing else to bundle.

## How to publish (drag-and-drop, no command line)

1. **Create a new repo**
   - Go to https://github.com/new
   - Name it anything, e.g. `jijiko-landing`
   - Set it to **Public** (required for free GitHub Pages)
   - Don't add a README, .gitignore, or license — leave it empty
   - Click **Create repository**

2. **Upload the file**
   - On the new repo's page, click **"uploading an existing file"** (or the **Add file → Upload files** button)
   - Drag `index.html` from this folder into the browser window
   - Scroll down, click **Commit changes**

3. **Turn on GitHub Pages**
   - In the repo, go to **Settings → Pages** (left sidebar)
   - Under **Build and deployment → Source**, choose **Deploy from a branch**
   - Under **Branch**, select `main` and folder `/ (root)`, then **Save**

4. **Wait ~1 minute, then visit your site**
   - Refresh the same Settings → Pages screen — it'll show a green banner with your live URL:
     `https://YOUR-USERNAME.github.io/jijiko-landing/`

## Before you publish — fill in the placeholders
Open `index.html` and search for these, since they're still placeholder values:
- `255XXXXXXXXX` (two spots) — your real WhatsApp number, digits only, country code first
- `YOUR_FORM_ID` (two spots) — your actual Google Form link, once you've made one
- `YOUR_VIDEO_ID` — your YouTube video's ID (the part after `v=` or `youtu.be/`), once you have a demo recorded

## Updating later
Any time you want to change the page: open the file on GitHub (click on it in the repo), click the pencil/edit icon, make changes, and commit — the live site updates automatically within a minute or two.
