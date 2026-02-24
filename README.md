# YU Zmanim Privacy Site (GitHub Pages)

This folder is ready to publish as a GitHub Pages site.

## Files
- `index.html` - landing page
- `privacy.html` - full policy page
- `styles.css` - site styles

## Option A (recommended): Dedicated repo
1. Create a new GitHub repo, for example `yuzmanim-privacy`.
2. Upload the contents of this folder to the repo root.
3. In GitHub: `Settings` -> `Pages`.
4. Under `Build and deployment`:
   - Source: `Deploy from a branch`
   - Branch: `main` and folder `/ (root)`
5. Save. Your site will be available at:
   - `https://<github-username>.github.io/yuzmanim-privacy/`

Use this URL in App Store Connect for `Privacy Policy URL`.

## Option B: User/org pages repo
If repo name is exactly `<github-username>.github.io`, your site URL is:
- `https://<github-username>.github.io/`

## Local preview
From this folder, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Before publishing
- Replace `support@yuzmanim.com` with your real contact email.
- Review the policy text with legal counsel if needed.
- Update effective date.
