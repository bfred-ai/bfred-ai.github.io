# bfred-ai.github.io

Brandon Frederick's portfolio site. Live at: https://bfred-ai.github.io

## Deploy (One-Time Setup)

You need:
- A GitHub repo named exactly: `bfred-ai.github.io`
- A GitHub Personal Access Token with `repo` + `contents: read/write` scope

### Step 1: Create the repo on GitHub
Go to github.com/new and name it exactly: `bfred-ai.github.io`
Set to **Public**. Do NOT initialize with README.

### Step 2: Set up git (run in WSL terminal)
```bash
cd /home/bfred/.openclaw/workspace/portfolio
git init
git add .
git commit -m "Initial portfolio launch"
git branch -M main
git remote add origin https://YOUR_TOKEN@github.com/bfred-ai/bfred-ai.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
- Go to: github.com/bfred-ai/bfred-ai.github.io/settings/pages
- Source: Deploy from a branch → `main` branch → `/ (root)` folder
- Hit Save

Site goes live at **https://bfred-ai.github.io** within ~2 minutes.

## Updates
```bash
cd /home/bfred/.openclaw/workspace/portfolio
git add .
git commit -m "Update portfolio"
git push origin main
```

## TODO Before Going Live
- [ ] Verify LinkedIn URL (currently: /in/brandonf1218 — confirm this is correct)
- [ ] Add real portfolio samples/screenshots for projects section
- [ ] Confirm brandonfrederick.com is still yours (in Profile.csv)
- [ ] Optional: custom domain via CNAME file
