# Vivi Il Momento — website

One-page site for www.viviilmomentolabel.com. Plain HTML, no build step.

## Before you upload
Open `index.html` and search for `EDIT`. Replace:
- `https://soundcloud.com/YOUR-SOUNDCLOUD` (2 places)
- `https://instagram.com/YOUR-INSTAGRAM`
- `hello@viviilmomentolabel.com` (if you use a different label email)

## Put it on GitHub Pages
1. On GitHub, create a new **public** repository (e.g. `vivi-site`).
2. Upload everything in this folder (`index.html`, `CNAME`, `README.md`, and the `assets` folder).
3. Repo **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → Save.
4. In the same Pages screen, Custom domain should show `www.viviilmomentolabel.com` (from the CNAME file). Tick **Enforce HTTPS** once it's available.

## Point your domain at it (at your domain registrar's DNS settings)
- **CNAME** record: host `www` → value `YOUR-GITHUB-USERNAME.github.io`
- **A** records for the bare domain (`@`), so viviilmomentolabel.com also works:
  `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`

DNS can take from a few minutes up to 24 hours to kick in.
