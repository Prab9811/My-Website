# Prabhat Singh — Portfolio

My personal portfolio website. Built as a simple static site — plain HTML, CSS, and JavaScript, no build tools required.

## 📁 Files

| File | What it's for |
|------|---------------|
| `index.html` | The **content** — edit your text, sections, and links here |
| `styles.css` | The **design** — colors, fonts, spacing, animations |
| `script.js` | The **interactions** — mobile menu, scroll animations |
| `photo.jpg` | Your profile photo (add this yourself — see below) |
| `README.md` | This file |

## ▶️ Viewing it locally

Just **double-click `index.html`** — it opens in your browser. No server needed.

## 📸 Adding your photo

Put an image named **`photo.jpg`** in this folder (same place as `index.html`).
It appears automatically in the hero section. A portrait/vertical photo (4:5) looks best.
Using a `.png` instead? Change `src="photo.jpg"` in `index.html` to `src="photo.png"`.

## ✏️ Things to personalize

Open `index.html` and update:

- Your **name** (currently "Prabhat Singh")
- **About** text — your own story
- **Experience** — real company names, dates, and achievements
- **Skills** — match exactly what you use
- **Projects** — replace the 3 placeholders with real work + links
- **Contact** links — your real LinkedIn, GitHub, and résumé URLs

To change **colors**, edit the `--c1`…`--c5` and `--grad` variables at the top of `styles.css`.

## 🚀 Publishing to GitHub Pages

1. Create an empty **public** repo on [github.com/new](https://github.com/new) (no README/license).
2. Connect and push:
   ```bash
   git remote add origin https://github.com/<YOUR-USERNAME>/<REPO>.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Deploy from a branch → `main` / root → Save**.
4. Your site goes live at `https://<YOUR-USERNAME>.github.io/<REPO>/`

### Updating later
```bash
git add -A && git commit -m "Update site" && git push
```
