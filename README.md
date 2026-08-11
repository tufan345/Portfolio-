# Tufan Kar — Portfolio

A single-page portfolio site (Senior DevOps & Cloud Engineer), ready to host for free on GitHub Pages.

## 🌐 Host it live with GitHub Pages (free, public URL)

1. **Create a new GitHub repository**
   - Go to https://github.com/new
   - Name it anything, e.g. `portfolio` (or `<your-username>.github.io` if you want it at your root domain — see note below)
   - Set it to **Public**
   - Don't initialize with a README (you already have one here)

2. **Upload the files**
   - On the new repo's page, click **"uploading an existing file"**
   - Drag in `index.html` and `README.md` from this folder
   - Commit the changes

   *(Or via command line, from this folder:)*
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

3. **Turn on GitHub Pages**
   - In your repo, go to **Settings → Pages**
   - Under "Build and deployment" → **Source**, choose **Deploy from a branch**
   - Branch: `main`, Folder: `/ (root)` → **Save**

4. **Get your public URL**
   - GitHub will give you a link after ~1 minute, usually:
     `https://<your-username>.github.io/<repo-name>/`
   - Anyone can open this URL to view your portfolio, and can save/download the page from their browser (Ctrl+S / Cmd+S)

### Note on repo naming
- Repo named `<repo-name>` → site lives at `https://<your-username>.github.io/<repo-name>/`
- Repo named exactly `<your-username>.github.io` → site lives at `https://<your-username>.github.io/` (shorter, root URL)

## 📁 Files
- `index.html` — the full portfolio page (self-contained: all CSS is inline, fonts load from Google Fonts CDN)
- `Tufan_Kar_Resume.pdf` — downloadable resume, linked from the nav bar, hero, and contact section

## ✏️ Making edits later
Just edit `index.html` directly (in GitHub's web editor, or locally) and push/commit — GitHub Pages redeploys automatically within a minute or two.
