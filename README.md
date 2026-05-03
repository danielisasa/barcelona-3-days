# Barcelona in 3 Days — Travel Guide Website

A beautiful editorial travel guide website for a 3-day itinerary in Barcelona.

## 🚀 Deploy to Railway

### Option A — Deploy via GitHub (recommended)

1. Push this folder to a GitHub repo:
   ```bash
   git init
   git add .
   git commit -m "Barcelona travel guide"
   git remote add origin https://github.com/YOUR_USER/barcelona-guide.git
   git push -u origin main
   ```

2. Go to [railway.app](https://railway.app) → **New Project** → **Deploy from GitHub repo**
3. Select your repo
4. Railway will auto-detect Node.js and deploy — no config needed
5. In **Settings → Networking** → click **Generate Domain** to get your public URL

### Option B — Deploy via Railway CLI

```bash
# Install CLI
npm install -g @railway/cli

# Login
railway login

# Create project and deploy
railway init
railway up
railway domain
```

## 🏃 Run locally

```bash
npm install
npm start
# Open http://localhost:3000
```

## 📁 Files

- `index.html` — The full website (single-page, no build step needed)
- `server.js` — Minimal Express server
- `package.json` — Node.js project config

## 🎨 Design

Editorial luxury travel magazine aesthetic with:
- Cormorant Garamond (display) + Jost (body) typography
- Barcelona-inspired palette: terracotta, sand, gold, slate
- Scroll-triggered timeline animations
- Responsive for mobile and desktop
