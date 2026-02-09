# Fix 404 — Get your site live at https://sahad2701.github.io

Follow these steps **on GitHub** (in order).

---

## Step 1: Repo name (required for short URL)

Your site can only be at **https://sahad2701.github.io** if the repo is named **exactly**:

**`sahad2701.github.io`**

- On GitHub: open your repo → **Settings** → under **Repository name** change it to **sahad2701.github.io** → **Rename**.
- If you keep the name **sahad2710.github.io**, the site will be at **https://sahad2701.github.io/sahad2710.github.io/** (long URL).

---

## Step 2: Turn on GitHub Pages

1. Same repo → **Settings** → **Pages** (left sidebar).
2. Under **Build and deployment**:
   - **Source:** choose **GitHub Actions**.

If you don’t see **GitHub Actions**, use the **gh-pages** option below instead.

---

## Step 3: Push your code and run the workflow

1. Push your latest code (with the `.github/workflows/deploy.yml` file) to the **main** branch.
2. Go to the **Actions** tab → open the **Deploy to GitHub Pages** workflow run.
3. If it’s green (success), the site is deployed.
4. Wait 1–2 minutes, then open **https://sahad2701.github.io** (or the long URL if you didn’t rename the repo).

---

## If you still get 404

- Confirm the repo name is **sahad2701.github.io** (for the short URL).
- Confirm **Settings → Pages → Source** is **GitHub Actions**.
- In **Actions**, confirm the latest workflow run **succeeded** (green check).
- Try opening the site in a private/incognito window.

---

## Optional: Deploy from branch (gh-pages)

If **GitHub Actions** doesn’t work or you prefer branch deploy:

1. **Settings → Pages** → **Source:** **Deploy from a branch**.
2. **Branch:** **gh-pages** (create it if needed). **Folder:** **/ (root)**. Save.
3. Locally run once:  
   `npx gh-pages -d build`  
   (This pushes the `build` folder to the `gh-pages` branch.)
4. After a minute, open **https://sahad2701.github.io** (if repo is named **sahad2701.github.io**).
