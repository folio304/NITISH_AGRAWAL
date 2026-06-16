# Nitish Agrawal — Profile Site

A single-page, self-contained profile site. No build step, no dependencies to install — just HTML, CSS and JS in one file.

## What's inside

- `index.html` — the entire site
- You provide: `assets/profile.jpg` — your photo

## How to publish on GitHub Pages

1. Create a new repository on GitHub (e.g. `nitish-agrawal`).
2. Add `index.html` to the root of the repo.
3. Create a folder called `assets` in the repo and upload your photo into it, **named exactly `profile.jpg`** (a portrait/vertical photo with good lighting works best — it fills the entire first screen).
   - If you'd rather use a different filename or a `.png`/`.webp`, open `index.html`, find the line `<img id="hero-photo" src="assets/profile.jpg" ...>` and change `assets/profile.jpg` to your filename.
4. In the repo, go to **Settings → Pages**, set the source branch to `main` (root), and save.
5. GitHub will give you a live link like `https://yourusername.github.io/nitish-agrawal/` within a minute or two.

If the photo isn't found, the hero section will show a placeholder message instead of breaking — so you'll always know if the path is wrong.

## What's interactive

- A custom ink-pen cursor with a trailing dot effect (desktop only)
- Cards that tilt gently toward your cursor (audit/practice cards, contact cards, the work card)
- Magnetic buttons that pull slightly toward your pointer
- A parallax ledger-line grid behind your photo that shifts with mouse movement or touch drag
- Ink-ripple feedback wherever you tap, on touch devices
- A press-to-verify "seal" button near the contact section — tap it to stamp the profile as verified
- Scroll-reveal animations as each section enters view
- Respects "reduce motion" settings on phones/browsers for visitors who prefer it

## Editing content later

Everything is in `index.html` — your bio, the three practice areas, your firm details, and contact info are plain text inside the file, easy to open and edit in GitHub's own editor (click the pencil icon on the file) without needing any code tools.
