# Publishing checklist

Repeat this for every new blog post. The site (`/blogs/`) is always the canonical source — Hashnode is a mirror for reach.

1. **Write and publish on the site first.**
   - Add the post under `blogs/`, link it from `blogs/index.html`.
   - Add an entry to `sitemap.xml` with the publish date.
   - Commit and push to `main`; confirm it's live at `https://sanjay-ragavan.github.io/blogs/<slug>.html`.

2. **Cross-post to Hashnode.**
   - New post → paste/adapt the content (Hashnode's editor is markdown-based, so reformat from HTML as needed).
   - Settings → **Add canonical URL** → set it to the GitHub Pages URL from step 1. This tells search engines the site is the original, so Hashnode doesn't compete with it in search results.
   - Add a cover image, and tags (e.g. `kubernetes`, `devops`, `sre`, `aws`).
   - Publish.

3. **Share it.**
   - Post the Hashnode (or site) link on LinkedIn with a short personal note on why you wrote it.

4. **Update the sitemap lastmod** if you edit the post later.
