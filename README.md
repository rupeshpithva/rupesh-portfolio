# Rupesh Pithva — Portfolio Site

A single-page static site built from the resume. No build step, no dependencies — just HTML/CSS/JS in `index.html`.

## Deploy on Netlify (pick one)

**Drag and drop (fastest):**
1. Go to https://app.netlify.com/drop
2. Drag this whole folder onto the page.
3. Netlify gives you a live URL immediately. Rename the site under Site settings → Change site name if you want a nicer subdomain.

**Connect a Git repo:**
1. Push this folder to a GitHub/GitLab repo.
2. In Netlify: Add new site → Import an existing project → pick the repo.
3. Build command: leave blank. Publish directory: `.` (already set in `netlify.toml`).
4. Deploy.

## Editing content

Everything is in `index.html` — text, styles, and the small canvas animation script are all in that one file, so you can open it in any editor and edit directly (search for section names like "Selected project ledger" or "Stack" to find the relevant part).

## Custom domain

Once deployed, Site settings → Domain management → Add a custom domain, then point your domain's DNS to Netlify as instructed there.
