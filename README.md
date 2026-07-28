# Tanmay Srivastava — Portfolio

A single-page personal site. Plain HTML — no build step, no dependencies.

## Files (keep ALL of these together in the repo root)
- `index.html` — the site
- `resume.pdf` — linked by the "Download résumé" buttons

Work sample 01 — Private credit (Crescent Harbor):
- `crescent-harbor-memo.pdf`
- `crescent-harbor-deck.pdf`
- `crescent-harbor-model.xlsx`

Work sample 02 — Box office US vs South Korea:
- `box-office-us-korea-deck.pdf`

Work sample 03 — Macroeconomic determinants (VAR/VECM):
- `box-office-macro-analysis.pdf`

Every download/preview button points to a file by name, so ALL files must sit
next to `index.html` in the repo root.

## Put it on GitHub + Vercel
1. Create a new repository on GitHub (e.g. `portfolio`).
2. Upload **all** the files above to the repo root
   ("Add file → Upload files", or push with git).
3. On https://vercel.com → **Add New → Project** → import the repo.
4. Framework preset: **Other**. Leave build & output settings empty.
5. **Deploy**.

## Already live on Vercel?
Just update the GitHub repo — upload the new files + updated `index.html`,
commit, and Vercel auto-redeploys in about a minute.

## Updating files later
Replace a file but keep the same filename, and its link keeps working.
(The résumé downloads for visitors as `Tanmay_Srivastava_2026_Resume.pdf`.)
