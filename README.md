# Tanmay Srivastava — Portfolio

A single-page personal site. Plain HTML — no build step, no dependencies.

## Files (keep ALL of these together in the repo root)
- `index.html` — the site
- `resume.pdf` — linked by the "Download résumé" buttons
- `crescent-harbor-memo.pdf` — work sample: investment committee memo
- `crescent-harbor-deck.pdf` — work sample: IC deck
- `crescent-harbor-model.xlsx` — work sample: the underlying Excel model

Every download button points to a file by name, so all files must sit
next to `index.html` in the repo root.

## Put it on GitHub + Vercel
1. Create a new repository on GitHub (e.g. `portfolio`).
2. Upload **all** the files above to the repo root
   ("Add file → Upload files", or push with git).
3. On https://vercel.com → **Add New → Project** → import the repo.
4. Framework preset: **Other**. Leave build & output settings empty.
5. **Deploy**. Your site is live.

## Updating files later
Replace a file in the repo but keep the same filename, and its link
keeps working. (The résumé downloads for visitors as
`Tanmay_Srivastava_2026_Resume.pdf`.)
