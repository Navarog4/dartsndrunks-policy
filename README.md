# DartsNDrunks — Privacy Policy

Static site hosting the privacy policy of the mobile application **DartsNDrunks**.

- **English (default):** https://navarog4.github.io/dartsndrunks-policy/
- **Français :** https://navarog4.github.io/dartsndrunks-policy/fr/
- Sources: [`PRIVACY.md`](./PRIVACY.md) (EN) / [`CONFIDENTIALITE.md`](./CONFIDENTIALITE.md) (FR)
- Generator: `node scripts/gen-privacy-page.js` (root of the app repo)

## How to update

1. Edit `legal/PRIVACY.md` (EN) and/or `legal/CONFIDENTIALITE.md` (FR) in the app repo.
2. Regenerate the HTML pages (see commands below), then copy to this directory.
3. Commit and push.

### Regeneration commands

```bash
node scripts/gen-privacy-page.js ../legal/PRIVACY.md ./index.html en \
  "Privacy Policy - DartsNDrunks" \
  "Privacy policy for DartsNDrunks mobile application" \
  "./fr/index.html" "Francais"

node scripts/gen-privacy-page.js ../legal/CONFIDENTIALITE.md ./fr/index.html fr \
  "Politique de Confidentialite - DartsNDrunks" \
  "Politique de confidentialite de l'application DartsNDrunks" \
  "../index.html" "English"
```