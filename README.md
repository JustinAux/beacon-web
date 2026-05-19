# Beacon Finance — Website

Landing page, privacy policy, and terms of service for the Beacon app.

## Files
- `index.html` — main landing page
- `privacy.html` — privacy policy
- `terms.html` — terms of service

## Deploy to GitHub Pages (free, 5 minutes)

1. Go to github.com → New repository → name it `beacon-web` → Public → Create
2. Open terminal in this folder and run:

```bash
git init
git add .
git commit -m "Initial website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/beacon-web.git
git push -u origin main
```

3. On GitHub: Settings → Pages → Source: Deploy from branch → Branch: main → Save
4. Your site will be live at: `https://YOUR_USERNAME.github.io/beacon-web`

## Custom domain (optional)

If you buy `beaconfinance.app`:
1. Add a `CNAME` file to this folder containing: `beaconfinance.app`
2. In your domain registrar's DNS, add:
   - A record → `185.199.108.153`
   - A record → `185.199.109.153`
   - A record → `185.199.110.153`
   - A record → `185.199.111.153`
3. In GitHub Pages settings, enter your custom domain
