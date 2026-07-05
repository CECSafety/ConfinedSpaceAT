# CEC Confined Space Entry — Interactive Training

Bilingual (English / Spanish) interactive training on permit-required confined
space entry, built to **OSHA 29 CFR 1910.146**. Ten modules with per-section
competency checks, a 20-question final exam, and an auto-generated completion
certificate emailed to Safety.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page + language picker (English / Español). **Start here.** |
| `CEC_Confined_Space_Entry_en.html` | English training module |
| `CEC_Confined_Space_Entry_es.html` | Spanish (es-MX) training module |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

All three HTML files are fully self-contained (styles, images, and logic are
embedded — no build step, no external assets except Google Fonts).

## Access

The site is password-gated. Enter the password once on the landing page and it
carries through to the training pages for that browser session.

- **Password:** `Safety1above!all1else!`

Progress is saved per browser/device under the learner's **EL #**. Sections
unlock sequentially — each section's quiz must be passed (100%) before the next
opens, and the final exam unlocks only after all ten sections are passed.

## Publish with GitHub Pages

1. Create a new repository on GitHub (e.g. `cec-confined-space-training`).
2. Upload all four files (`index.html`, both training files, and `.nojekyll`)
   to the repository root — keep the file names exactly as-is.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*,
   choose the `main` branch and the `/ (root)` folder, then **Save**.
5. Wait ~1 minute. Your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

The landing page (`index.html`) is the entry point and links to both languages.

## Certificate delivery

On passing the final exam (≥80%) a certificate is generated with the learner's
name, EL #, project, supervisor, score, and a unique certificate ID. The learner
saves it (PDF on desktop, image on mobile) and emails it — a message is
pre-filled to **safety@cecfg.com** and **training@cecfg.com**.

---
For internal CEC training use only.
