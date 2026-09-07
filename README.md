# Compound Notes

Jekyll blog, built for free GitHub Pages hosting. Live at:
`https://kevinkearns1.github.io/compound-notes/` once Pages is enabled
(Settings → Pages → Source: Deploy from a branch → `main` / `(root)`).

## Adding a new post

Create a file in `_posts/` named `YYYY-MM-DD-a-url-safe-slug.md` with this
front matter:

```yaml
---
layout: post
title: "The Post Title"
date: 2026-09-10
description: "One or two sentences — this becomes the meta description and Google search snippet."
tags: [tag-one, tag-two]
affiliate: true   # only include this line if the post has a referral/affiliate link
reading_time: 6   # rough estimate, minutes
cover: /assets/images/covers/your-cover.svg   # shown on the homepage card and at the top of the post
cover_alt: "Plain-language description of the cover image, for screen readers"
image: /assets/images/covers/your-cover.png   # PNG render of the same cover, used for og:image / Twitter card
---
```

`image` matters because most social platforms (Twitter/X, Facebook, LinkedIn,
plus Google's rich-result previews) don't reliably render SVG for link
previews — only `cover` (the SVG) is used on-page. Render the PNG from the
SVG at 1200x800 (2x the on-page size) with headless Chrome, e.g.:

```
/opt/pw-browsers/chromium-1194/chrome-linux/chrome --headless --disable-gpu \
  --no-sandbox --screenshot=assets/images/covers/your-cover.png \
  --window-size=1200,800 --hide-scrollbars \
  file://$(pwd)/assets/images/covers/your-cover.svg
```

Then write the post in Markdown below the front matter. Put `<!--more-->`
after the first paragraph or two to control what shows as the excerpt on
the homepage.

If the post includes a referral or affiliate link, disclose it right next
to the link itself (not just via the site-wide `affiliate: true` badge) —
see `_posts/2026-09-02-college-students-should-invest.md` for the pattern
(a `.cta-box` block with the disclosure sentence inline).

## Local preview (optional)

```
bundle exec jekyll serve
```

Requires Ruby + Bundler + a `Gemfile` with the `github-pages` gem — not
included here since GitHub's own Pages build handles it server-side without
one. Only needed if you want to preview changes before pushing.
