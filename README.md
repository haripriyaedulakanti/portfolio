# Portfolio Deployment

This is a static portfolio website for Edulakanti Haripriya.

## Deploy to GitHub Pages

1. Create a new GitHub repository (for example `portfolio`).
2. In this folder, initialize git and push:

```bash
cd /Users/edulakanti.anupriya/Desktop/PORTFOLIO
/usr/bin/git init
/usr/bin/git add .
/usr/bin/git commit -m "Initial portfolio site"
/usr/bin/git branch -M main
/usr/bin/git remote add origin https://github.com/<your-username>/<repo-name>.git
/usr/bin/git push -u origin main
```

3. Go to GitHub > repository settings > Pages.
4. Set source to `main` branch and folder `/ (root)`.
5. After a few minutes, your site will be live at:

```text
https://<your-username>.github.io/<repo-name>/
```

## Local preview

```bash
cd /Users/edulakanti.anupriya/Desktop/PORTFOLIO
ruby -run -e httpd . -p 8000
```

Open `http://localhost:8000` in your browser.
