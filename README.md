# Link in Bio

A simple, single-page bio site: intro, social links, newsletter signup, key links, and a grid of selected work. Plain HTML + CSS, no build step. Supports light/dark mode automatically.

## Editing

Everything lives in `index.html` and is marked with comments:

- **Intro** – name, tagline, bio. The photo is `assets/portrait-2026.jpg`: full-bleed across the top on phones, a rounded card on larger screens. Adjust the crop with `object-position` on `.hero` in `styles.css`.
- **Socials** – update each `href`; delete icons you don't use.
- **Newsletter** – the heading and blurb are plain HTML you can edit; the signup field below them is the Beehiiv embed (`<iframe class="nl-embed">`).
- **Links** – one `<li>` per link; the small text on the right is the destination label.
- **Selected work** – replace each `.work-media` div with `<img src="assets/work-1.jpg" alt="…" loading="lazy" />`. Images are cropped to 4:5.

Colors and fonts are CSS variables at the top of `styles.css`.

## Preview / deploy

Open `index.html` in a browser. To publish, enable GitHub Pages (Settings → Pages → deploy from this branch) or drag the folder into Netlify/Vercel.
