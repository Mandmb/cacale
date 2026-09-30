# CACALE.IO — Deployment Build

This package is ready for GitHub Pages with the custom domain:

https://cacale.io

## Included
- PWA / installable web app
- Spanish 4-letter dictionary loading
- Daily puzzle
- Target word: CACA
- Correct-position highlighting
- One-letter-at-a-time rule
- Daily streaks and stats
- Shareable results
- App icons
- Service worker
- GitHub Pages custom-domain file (`CNAME`)
- `.nojekyll`

## Publish with GitHub Pages
1. Create or use a GitHub repository for the game.
2. Put every file from this folder in the repository root.
3. Enable GitHub Pages:
   Settings → Pages → Deploy from a branch → main → /(root)
4. GitHub Pages will detect the `CNAME` file and use `cacale.io`.

## Domain DNS
After purchasing cacale.io, point the apex domain to GitHub Pages using these A records:

185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153

Optional IPv6 AAAA records:

2606:50c0:8000::153
2606:50c0:8001::153
2606:50c0:8002::153
2606:50c0:8003::153

For `www.cacale.io`, create a CNAME pointing to your GitHub Pages hostname
(e.g. YOUR-GITHUB-USERNAME.github.io).

Once DNS propagates, enable "Enforce HTTPS" in GitHub Pages.
