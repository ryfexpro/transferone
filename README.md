# TransferOne

Production website for TransferOne — Private Transfers · Moldova.

## Deploy to GitHub + Vercel

1. Create a new GitHub repository (for example `transferone`).
2. Upload **all files from this folder to the repository root**. Do not upload the outer ZIP/folder as a nested directory.
3. In Vercel choose **Add New → Project → Import Git Repository**.
4. Framework Preset: **Other**. Root Directory: `./`.
5. Build Command: leave empty. Output Directory: leave empty.
6. Deploy.
7. Add `transferone.md` in Vercel → Project → Settings → Domains, then use the DNS records Vercel shows.

## Contacts

Edit only `config.js` to set WhatsApp, phone, email and Instagram. WhatsApp must contain digits only.

## Main files

- `index.html` — homepage
- `styles.css` — design and responsive layout
- `app.js` — booking, languages, menu, interactions
- `config.js` — contacts/settings
- `assets/` — images
- `route/` — SEO route pages
- `privacy.html`, `terms.html`, `cookies.html` — legal pages
- `robots.txt`, `sitemap.xml` — search indexing
- `vercel.json` — Vercel configuration
