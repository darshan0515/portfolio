# Darshan Patel — Portfolio

A single-page portfolio site. No build step, no installs.

## Files
- `index.html` — the whole website (HTML + CSS + JavaScript in one file)
- `resume.pdf` — linked from the Résumé buttons
- `README.md` — this file

## Run it on your computer
**Option A (quickest):** double-click `index.html` to open it in your browser.

**Option B (local server, recommended so the résumé link behaves like the live site):**
```bash
cd darshan-portfolio
python -m http.server 8000      # use python3 on Mac/Linux
```
Then open http://localhost:8000 in your browser. Press Ctrl+C to stop.

## Put it online (Vercel, free)
1. Create a new GitHub repo (e.g. `portfolio`) and upload these files.
2. Go to vercel.com → sign in with GitHub → Add New → Project → import the repo → Deploy.
3. Settings → Domains → rename to something like `darshan-patel.vercel.app`.

Any edit you commit to GitHub redeploys automatically.

## Editing tips
- Text: search `index.html` for the sentence you want to change.
- Colors: edit the variables at the top of the `<style>` block (`--accent`, `--green`, `--bg`).
- Project code links: search for `github.com/Darshan150504` and replace with each repo's URL.
- New résumé: replace `resume.pdf` with a file of the same name.
