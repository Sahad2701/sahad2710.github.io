# Sahad Kachhawala — Portfolio

**Senior Flutter & Mobile App Engineer**

- **Site:** [sahad2701.github.io](https://sahad2701.github.io)
- **GitHub:** [@Sahad2701](https://github.com/Sahad2701)
- **LinkedIn:** [Sahad Kachhawala](https://www.linkedin.com/in/sahad-kachhawala/)

## Short URL + fix 404

1. **Rename repo** to **`sahad2701.github.io`** (Settings → Repository name → Rename). Otherwise the site URL will have an extra path.
2. **Settings → Pages** → **Build and deployment** → **Source:** choose **GitHub Actions**.
3. **Push** your code to `main`. Go to **Actions** → wait for **Deploy to GitHub Pages** to finish (green).
4. Open **https://sahad2701.github.io** after 1–2 minutes.

If you still see 404, see **[DEPLOY.md](DEPLOY.md)** for step-by-step troubleshooting.

## Local run

```bash
npm install
npm start
```

## Edit content

- **Profile, experience, projects, skills:** `src/portfolio.js`
- **Colors/theme:** `src/_globalColor.scss`
- **Resume:** replace `src/containers/greeting/resume.pdf`
- **Photo:** add `src/assets/images/portrait.jpg` and set `profileImage` in `portfolio.js`

## Deploy

Push to `main`. GitHub Actions builds and deploys; no manual steps.
