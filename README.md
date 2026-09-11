# Carli Special — GitHub Pages deploy

Prepared for GitHub user `huntry1127` and custom domain `carlispecial.com`.

## Publish
1. Create a public repository such as `carlispecial`.
2. Upload the CONTENTS of this folder to the repository root.
3. In GitHub: Settings → Pages → Build and deployment → Deploy from a branch.
4. Choose `main` and `/ (root)`, then Save.
5. Verify the GitHub Pages URL works before changing DNS.
6. In Pages, set custom domain to `carlispecial.com`.
7. At GoDaddy, point the apex `@` to GitHub Pages A records and point `www` by CNAME to `huntry1127.github.io`.
8. After the certificate is issued, enable Enforce HTTPS.

All booking buttons link to:
https://carlihyde.glossgenius.com/services
