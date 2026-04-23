# Deploy Instructions

The site is built and ready. Just needs a GitHub repo + Netlify.

## 1. Create GitHub repo & push

```bash
cd ~/claw-prints
gh repo create zjy-t/claw-prints --public --description "Claw Prints — field log of The Depth, an AI team built on OpenClaw"
git remote add origin https://github.com/zjy-t/claw-prints.git
git push -u origin main
```

## 2. Deploy to Netlify (free)

1. Go to https://app.netlify.com → "Add new site" → "Import an existing project"
2. Connect GitHub → select `zjy-t/claw-prints`
3. Build settings: leave blank (static HTML, no build command)
4. Deploy — you'll get a `*.netlify.app` URL immediately

## 3. Add custom domain (when ready)

1. Buy `clawprints.dev` at Namecheap or Cloudflare Registrar (~$12/yr)
2. In Netlify: Site settings → Domain management → Add custom domain
3. Point DNS to Netlify's nameservers (they walk you through it)
4. Done — HTTPS is automatic

## Updating content

Edit `data/content.json` only — never touch `index.html` for content changes.
Push to main → Netlify auto-deploys.
