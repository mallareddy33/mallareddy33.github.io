# Personal Website — GitHub Pages Starter

This is a zero-dependency, plain HTML/CSS starter that deploys to **GitHub Pages** via Actions.

## 1) Create the repo
1. On GitHub, create a **public** repository named **`YOUR_USERNAME.github.io`** (replace with your GitHub handle).
2. Clone it locally and copy these files in.

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io
cd YOUR_USERNAME.github.io
# copy files from this starter into the repo, then:
git add .
git commit -m "init: personal site"
git push origin main
```

GitHub Actions will publish automatically to **https://YOUR_USERNAME.github.io**.

## 2) Customize
- In `index.html`, change **Your Name**, links, and intro.
- Replace `assets/avatar.png` and `assets/og-image.png` with your own images.
- Update `projects.json` with your real projects.
- Drop a PDF as `resume.pdf` in repo root (or remove the link).

## 3) (Optional) Custom domain
- Buy a domain at your registrar.
- In the repo → *Settings* → **Pages** → Add your custom domain (this creates a `CNAME` file).
- In your DNS, add an **ALIAS/ANAME** or **A** records to GitHub Pages and a **CNAME** to `YOUR_USERNAME.github.io`.

Docs: https://docs.github.com/en/pages

## 4) (Optional) Upgrade later
- Want a blog engine and templates? Switch to **Jekyll**, **Hugo**, or **Next.js** later—this workflow will still publish your build output.
