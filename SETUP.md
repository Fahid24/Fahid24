# 🚀 How to publish your futuristic profile README

Your GitHub profile README must live in a **special repo named exactly after your username**.

## 1. Create the special repo

1. Go to **https://github.com/new**
2. Repository name: **`Fahid24`** (must match your username exactly — case sensitive)
3. Set it to **Public**
4. Check **"Add a README file"**
5. Click **Create repository**

> GitHub will show a 💡 "secret" hint confirming this repo powers your profile.

## 2. Add the files

Copy these into the new `Fahid24` repo:

- `README.md`  →  repo root
- `.github/workflows/snake.yml`  →  enables the animated snake

### Option A — push from this folder
```bash
cd "Fahid24"
git init
git add .
git commit -m "✨ Futuristic profile README"
git branch -M main
git remote add origin https://github.com/Fahid24/Fahid24.git
git push -u origin main
```

### Option B — upload via the website
Drag `README.md` (and the `.github` folder) into the repo using **Add file → Upload files**.

## 3. Turn on the snake animation 🐍

1. In the repo, go to **Settings → Actions → General**
2. Under *Workflow permissions*, select **Read and write permissions** → Save
3. Go to the **Actions** tab → select **"Generate Snake Animation"** → **Run workflow**
4. Wait ~1 minute. It creates an `output` branch with the snake SVG that the README points to.

## 4. Done ✅

Visit **https://github.com/Fahid24** — your animated, neon, futuristic profile is live.

---

## 🎨 Customize it

| What | Where in `README.md` |
|------|----------------------|
| Your name / titles | The **Typing SVG** `lines=` text at the top |
| Tech badges | The **Tech Arsenal** section — copy any badge from [shields.io](https://shields.io) |
| Social links | The **Connect With Me** section — replace the `#` with your real URLs |
| Color theme | Swap `tokyonight` for `radical`, `dracula`, `synthwave`, `midnight-purple`, etc. |
| Neon colors | The hex codes `00F7FF` (cyan), `7B2FF7` (purple), `F222FF` (magenta) |

## ⚠️ Notes
- **Stats only count repos you own/contribute to.** Private commits show once you enable *Settings → "Include private contributions"* on github-readme-stats (already enabled via `count_private=true`).
- All images are live services — your stats **auto-update** every time someone views your profile. Nothing to maintain. 🔄
