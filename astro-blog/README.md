# Astro Blog

This folder contains an Astro blog that builds into the repository root `blog/` folder.

## Setup

1. Install Node.js if not already installed.
2. Open a terminal in `astro-blog/`.
3. Run:

```bash
npm install
npm run build
```

## Output

- `astro-blog/src/pages/index.astro` is the blog list page.
- `astro-blog/src/pages/[slug].astro` renders each blog post.
- `astro-blog/src/posts/` contains Markdown blog posts.
- The generated static blog will be saved to `../blog/`.

## Access

After building, the blog will be available at:

```
https://b0gdvn.github.io/blog/
```

## Add posts

Add new Markdown files to `astro-blog/src/posts/` with frontmatter:

```markdown
---
title: "Post title"
pubDate: "2026-07-14"
description: "Krótki opis wpisu."
---

Treść wpisu.
```
