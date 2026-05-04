# RUNBOOK – News site

## Enable GitHub Pages
1. GitHub → repo Settings → Pages
2. Deploy from branch → `main` / root

## Custom domain
- Set custom domain to `news.theraus.org`
- Enable HTTPS when available

## DNS
- Create a CNAME record:
  - name: `news`
  - target: `therausorg.github.io`
