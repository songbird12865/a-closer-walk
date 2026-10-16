365 DAYS WITH GOD — MARKETING SITE

Intended address: https://365dayswithgod.acloserwalk.org

Contents: index.html, privacy.html, support.html, style.css, assets/365-days-logo.png.

DEPLOYMENT — IF USING A SEPARATE GITHUB PAGES REPOSITORY
1. Create a public repository, e.g. 365dayswithgod-site, and upload these files at repository root.
2. Under Settings > Pages, enable Deploy from a branch, main / (root).
3. Under Pages > Custom domain, enter 365dayswithgod.acloserwalk.org and save.
4. At your domain DNS provider, create a CNAME record: Host 365dayswithgod; Target songbird12865.github.io (if this is the GitHub Pages account serving the site).
5. Wait for DNS and GitHub Pages certificate issuance, then enable Enforce HTTPS.
6. Verify the three pages load over HTTPS before putting links in App Store Connect.

IMPORTANT: The site and DNS are NOT automatically published by this ZIP. If your current acloserwalk.org setup uses a different GitHub account or custom hosting, use that hosting target instead. Do not overwrite your existing main website. The privacy page is a pre-release draft; confirm its claims against the actual final app.
