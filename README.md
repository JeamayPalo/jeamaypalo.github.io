# Jeamay Palo — portfolio site

Plain HTML/CSS, no build step. Four pages:

| File | Page |
|---|---|
| `index.html` | Home |
| `work.html` | Work (nine projects) |
| `resume.html` | Resume highlights and download |
| `case-study.html` | Case study template (JPL Earth Science Presentation Library) |

## Put it on GitHub Pages
1. On github.com click **New repository**. Name it exactly `YOUR-USERNAME.github.io` (all lowercase). Set it to **Public**.
2. Click **uploading an existing file**, drag in everything from this folder (the `images` folder too), and click **Commit changes**.
   The `.nojekyll` file may be hidden on your computer; it is optional.
3. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch **main**, folder **/ (root)**, and Save.
4. Wait 1 to 2 minutes. Your site is at `https://YOUR-USERNAME.github.io`.

Custom domain later: Settings → Pages → Custom domain, then add the DNS records GitHub shows.

## Swap a picture
Upload a new file to the `images` folder with the SAME name and type (e.g. `headshot.jpg`), then commit. Hard refresh to see it (Ctrl/Cmd+Shift+R).
Keep photos under about 500 KB. Banner: about 2000 px wide.

| File | Where it shows | Status |
|---|---|---|
| `hero.jpg` | Home banner | PLACEHOLDER drawing. Replace with a public-domain NASA/JPL photo and update the credit line in `index.html` |
| `headshot.jpg` | Home, next to "Hi, I'm Jem" | PLACEHOLDER |
| `ocsdo-reports.jpg` | OCSDO feature + cards | Real covers |
| `jpl-earth-science-decks.jpg` | JPL Earth Science feature + cards | Real thumbnails (low-res; replace with full-size) |
| `cassini-archive.jpg` | Cassini feature + cards | Real screenshot |
| `slide-smap.jpg`, `slide-grace.jpg`, `slide-swot.jpg` | Case study page | Real thumbnails (low-res) |
| `iss-briefings.jpg` | ISS card | PLACEHOLDER |
| `iac-papers.jpg` | IAC papers card | PLACEHOLDER |
| `cbp-report.jpg` | CBP report card | PLACEHOLDER |
| `ai-video.jpg` | AI videos card + "Stories in Motion" | PLACEHOLDER |
| `exec-slides.jpg` | Executive slides card | PLACEHOLDER |
| `dataviz.jpg` | Data Visualization card | PLACEHOLDER |

## Still to fill in (search the HTML for `[` brackets)
- `resume.pdf` — add your resume PDF to the main folder (all "Download" buttons point to it).
- Email — footer link says `[your email]`; change to `mailto:you@example.com`.
- Job dates and titles on `resume.html`.
- "Plain-text version" link on `resume.html`.
- Case study text in `case-study.html` (Problem, Approach, Reflection) and a one-line result for the ISS card.
- Cards flagged on `work.html`: AI videos (confirm cleared), executive slides (public NASA slides only, anonymize CBP), Data Visualization (add the piece), ISS briefings (confirm cleared).
- Every "Read the case study" link currently opens the one sample case study.
- Image `alt` text: update it when you swap in real pictures.

## Edit text
On GitHub, open a file, click the pencil icon, change the words between the tags, and Commit.
