# Naomi Isabelle K. Reyes — E-Portfolio

A single-page portfolio site. Everything is static — no build step, no dependencies.

## Files

```
index.html          the whole page
style.css           all styling
assets/naomi.png    your headshot, background and overlay text removed (transparent PNG)
assets/banner.png   a wide header graphic in your palette (spare — not used by index.html)
```

## Look at it locally

Open `index.html` in any browser. That's it.

## Deploy it

**GitHub Pages** (free, uses your existing account)
1. Make a new repo named `nomjie33.github.io`
2. Upload these files to the root of the repo
3. Settings → Pages → Source: `main` / `root` → Save
4. Live at `https://nomjie33.github.io` in a minute or two

**Netlify / Vercel** — drag the unzipped folder onto the dashboard. Done.

**Google Sites** — Sites can't take a full HTML page like this. Two options:
- Deploy to GitHub Pages (above), then in Sites use **Insert → Embed → By URL** and paste the live link.
- Or rebuild natively in Sites. The theme values to use:
  - Custom theme colours: `#406093`, `#FFF799`, `#4C8CE4`
  - Headings: **Quicksand Bold** · Body: **Nunito Regular**
  - `assets/banner.png` works as the page header image.

## Palette

| Swatch | Hex | Used for |
|---|---|---|
| Deep blue | `#406093` | hero background, headings, contact band |
| Bright blue | `#4C8CE4` | links, accents, gradient end |
| Green | `#91D06C` | accent bar, dots, stat card |
| Pale yellow | `#FFF799` | primary button, eyebrow text, accents |

## Editing

- **Text** — all content lives in `index.html`, section by section (`<!-- ====== PROJECTS ====== -->` etc.)
- **Colours** — change the variables at the top of `style.css` under `:root`
- **A new project** — copy any `<article class="card">` block and edit it. Add `card--wide` to the class to make it span the full row.

## Notes

- Your phone number is in your resumes but is deliberately **not** on the site — email, GitHub and LinkedIn only. Add it in the Contact section if you want it public.
- The Brainworks Vercel URL (`brainworks-blush.vercel.app`) returns 404 right now, so that card links to the repo instead. Swap it in once the deployment is live.
- The PH vs. US stock market study has no public repo, so it's listed without a link.
