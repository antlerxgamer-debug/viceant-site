# viceant.fun

Ultra Instinct link hub for ViceAnt.

Static single-page site — just `index.html` + `/assets`. No build step.

## Deploy (Hostinger hPanel Git)

1. hPanel → Websites → `viceant.fun` → **Git** (under Advanced)
2. Connect this repo: `https://github.com/antlerxgamer-debug/viceant-site`
3. Branch: `main`
4. Directory: `public_html` (root)
5. **Auto-deploy: ON**
6. Every `git push origin main` redeploys automatically.

## Local preview

```
cd ~/viceant-site && python3 -m http.server 8080
# open http://localhost:8080
```

## Edit links

All links live in `index.html` inside `<nav class="links">`. Swap the `href` attributes.
