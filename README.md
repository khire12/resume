# Sarvesh Khire Resume Site

Live site: `https://khire12.github.io/resume/`

## GitHub Pages Setup (`khire12/resume`)

### 1) Repository
Use a public repo named `resume` under account `khire12`.

Enable GitHub Pages from:
- Branch: `main`
- Folder: `/ (root)`

Published URL:
- `https://khire12.github.io/resume/`

### 2) Required Root Files
- `index.html`
- `styles.css`
- `script.js`
- `favicon.svg`
- `sarvesh_khire_resume_analytics_engineer_ats.pdf`

### 3) Push Commands
```bash
cd "/Users/sarvesh/Documents/New project"
git add .
git commit -m "Update resume site"
git branch -M main
git remote add origin https://github.com/khire12/resume.git
git push -u origin main
```

If `origin` already exists:
```bash
git remote set-url origin https://github.com/khire12/resume.git
git push -u origin main
```

### 4) Optional Custom Domain
- Add your domain in GitHub repo `Settings` -> `Pages`
- Add required DNS records at your domain provider
