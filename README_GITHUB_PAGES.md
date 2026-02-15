# Deploy To GitHub Pages (`khire12/resume`)

## 1) Create Repository
Create a new **public** repo named:

`resume`

Then enable GitHub Pages for this repo (`main` branch, `/root`) and the site will publish at:

`https://khire12.github.io/resume/`

## 2) Keep These Files At Repo Root
- `index.html`
- `styles.css`
- `script.js`
- `sarvesh_khire_resume_analytics_engineer_ats.pdf`

## 3) Push From This Folder
Run:

```bash
cd "/Users/sarvesh/Documents/New project"
git add .
git commit -m "Create resume website for GitHub Pages"
git branch -M main
git remote add origin https://github.com/khire12/resume.git
git push -u origin main
```

If `origin` already exists:

```bash
git remote set-url origin https://github.com/khire12/resume.git
git push -u origin main
```

## 4) Verify In GitHub
- Go to repo `Settings` -> `Pages`
- Confirm source is `Deploy from a branch`
- Branch should be `main` and folder `/ (root)`

## 5) Optional Custom Domain
- Add your domain in `Settings` -> `Pages`
- Add required DNS records at your domain provider
