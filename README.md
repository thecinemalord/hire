# Tanmay Srivastava — Portfolio

A single-page personal site. Plain HTML — no build step, no dependencies.

## Files
- `index.html` — the site
- `resume.pdf` — the résumé the "Download résumé" buttons link to

**Keep both files together in the repo root.** The download buttons point to
`resume.pdf`, so the PDF must sit next to `index.html`.

## Put it on GitHub + Vercel

1. Create a new repository on GitHub (e.g. `portfolio`).
2. Upload **both** `index.html` and `resume.pdf` to the repo
   (drag them into GitHub's "Add file → Upload files", or push with git).
3. Go to https://vercel.com → **Add New → Project** → import the repo.
4. Framework preset: **Other**. Leave build & output settings empty.
5. Click **Deploy**. Done — your site is live.

## Updating your résumé later
Replace `resume.pdf` in the repo with your new file, but **keep the name
`resume.pdf`**. The download link never changes, so it keeps working.
(The file downloads for visitors as `Tanmay_Srivastava_2026_Resume.pdf`.)
