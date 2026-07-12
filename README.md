# Lia — Personal Site

Three pages, no build step, Netlify-ready.

## Deploy (2 minutes)

**Option A — drag and drop (fastest):**
1. Go to https://app.netlify.com/drop
2. Drag this whole folder onto the page. Done — you get a live URL immediately.

**Option B — GitHub (better long-term):**
1. Create a repo (e.g. `lia-site`), push these files to the root.
2. In Netlify: Add new site → Import from Git → pick the repo.
3. Build command: none. Publish directory: `/` (root).
4. Every push now auto-deploys.

## Before you deploy — the TODO checklist

Search the HTML files for `TODO`:

1. All pages — sidebar photo: create ``, add your photo, swap the
   `photo-placeholder` div for `<img class="photo" src="lia.jpg" alt="Lia" />`
2. All pages — sidebar links: Email, LinkedIn, GitHub, Substack
3. `index.html` — hero email ("Reach out: ..."), footer links, Substack URLs,
   and an optional receipts line in About (add 1-2 real numbers when you
   have shareable ones — specifics do the convincing)
4. `pound-cake-notebook.html` — live site URL (hero) + 2 screenshot
   placeholders → swap `<div class="img-placeholder">` for
   `<img src="your-screenshot.png" alt="describe what's shown" />`

## Customizing

- All colors and fonts are CSS variables at the top of `styles.css`.
- To add a third project later: copy a `.recipe-card` block in
  `index.html`, then duplicate `selling-agent.html` as the template
  for its page.

## Custom domain (optional, later)

Netlify → Domain settings → Add custom domain. Netlify handles HTTPS
automatically.
