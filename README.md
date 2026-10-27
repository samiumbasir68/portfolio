# Md Samium Basir — Portfolio Website

## What's inside
- `index.html` — the website
- `content/` — all your text, one file per section (edited by the admin panel)
- `images/` — your photos (admin panel uploads go here)
- `admin/` — the admin panel (open `yoursite.netlify.app/admin`)

---

## One-time setup (about 15 minutes, all free)

### Step 1 — Put the files on GitHub
1. Create a free account at https://github.com
2. Click **New repository** → name it `portfolio` → **Public** → Create.
3. Click **uploading an existing file** and drag in everything from this folder
   (`index.html`, `README.md`, and the `admin`, `content`, `images` folders). Click **Commit changes**.

### Step 2 — Tell the admin panel your repo name
1. In GitHub, open `admin/config.yml` → click the pencil icon.
2. Change `YOUR-GITHUB-USERNAME/portfolio` to your real username, e.g. `samiumbasir/portfolio`.
3. Click **Commit changes**.

### Step 3 — Publish on Netlify
1. Go to https://app.netlify.com and sign up **with GitHub**.
2. **Add new site → Import an existing project → GitHub** → pick `portfolio` → **Deploy**.
3. Your site is live at something like `random-name.netlify.app`.
   (Site configuration → Change site name to make it `samiumbasir.netlify.app`.)

### Step 4 — Turn on the admin login
1. On GitHub: profile picture → **Settings → Developer settings → OAuth Apps → New OAuth App**
   - Application name: `Portfolio Admin`
   - Homepage URL: `https://YOUR-SITE.netlify.app`
   - Authorization callback URL: `https://api.netlify.com/auth/done`
   - Click **Register**, then **Generate a new client secret**. Keep this page open.
2. On Netlify: your site → **Site configuration → Access & security → OAuth → Install provider**
   - Provider: **GitHub**, paste the **Client ID** and **Client secret** → Install.

### Done!
Go to **`https://YOUR-SITE.netlify.app/admin`** → **Login with GitHub**.

---

## Editing your site
1. Open `/admin` and log in.
2. Click a section (Profile, About, Education…).
3. Change text, add/remove/reorder items, upload photos, or untick **Show this section** to hide it.
4. Click **Publish → Publish now**. The live site updates in about a minute.

Only you can log in — the panel needs write access to your GitHub repository.

## Notes
- Upload your CV in **Profile → CV (PDF)**.
- Add DOI links in **Publications → Link**.
- The site won't show content if you double-click `index.html` on your computer — it must be opened from Netlify (or any web host).
