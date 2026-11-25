# Tech CKS — Official Website

Static website for **Tech CKS** (Facebook Page / Instagram @tech_cks).
Plain HTML/CSS/JS — no build step. Just `index.html` + `logo.png`.

## Files

| File | Purpose |
|---|---|
| `index.html` | The complete website (all CSS & JS inline) |
| `logo.png` | Tech CKS logo (header, hero, favicon, social preview) |
| `README.md` | This file |

## Deploy on GitHub Pages

1. **Create a repo** on GitHub (e.g. `techcks-website`).
   - To get the clean URL `https://chandan-itian.github.io/`, name the repo
     `chandan-itian.github.io` instead.
2. **Push these files** to the repo's `main` branch, keeping them in the root:
   ```bash
   git init
   git add index.html logo.png README.md
   git commit -m "Tech CKS website"
   git branch -M main
   git remote add origin https://github.com/chandan-itian/techcks-website.git
   git push -u origin main
   ```
3. **Enable Pages:** in the repo, go to **Settings → Pages** →
   *Build and deployment* → Source: **Deploy from a branch** →
   Branch: **main**, folder: **/ (root)** → **Save**.
4. Wait ~1 minute. The site goes live at
   `https://chandan-itian.github.io/techcks-website/`
   (or `https://chandan-itian.github.io/` for the user-site repo name).
5. Copy that live URL and add it as the **Website** on the Tech CKS
   Facebook Page (and as the Page's action-button link, if desired).

## Updating the site

Edit `index.html`, commit and push — GitHub Pages redeploys automatically
within about a minute.

## Notes

- All links are relative, so the site works from any repo name or custom domain.
- Social links used: Facebook `facebook.com/ITSolutions83`,
  Instagram `@tech_cks`, Telegram `t.me/itsolutionss`,
  Email `chandantint@duck.com`.
