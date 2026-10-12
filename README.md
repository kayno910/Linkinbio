# Link in Bio

A simple, single-page bio site: intro, social links, newsletter signup, key links, and a grid of selected work. Plain HTML + CSS, no build step. Supports light/dark mode automatically.

## Editing

Everything lives in `index.html` and is marked with comments:

- **Intro** – name, tagline, bio, avatar (drop a photo at `assets/avatar.jpg` and swap the placeholder).
- **Socials** – update each `href`; delete icons you don't use.
- **Newsletter** – set the form `action` to your provider (Substack, ConvertKit, Beehiiv, Buttondown…), or replace it with a single link.
- **Links** – one `<li>` per link; the small text on the right is the destination label.
- **Selected work** – replace each `.work-media` div with `<img src="assets/work-1.jpg" alt="…" loading="lazy" />`. Images are cropped to 4:5.

Colors and fonts are CSS variables at the top of `styles.css`.

## Preview / deploy

Open `index.html` in a browser. To publish, enable GitHub Pages (Settings → Pages → deploy from this branch) or drag the folder into Netlify/Vercel.
