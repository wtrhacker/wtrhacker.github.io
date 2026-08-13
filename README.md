# What mad pursuit

Minimal blog built with Jekyll and hosted on GitHub Pages.

## Edit a page

The homepage and post index are in `index.md`. Edit it and push the change to
`main`.

## Publish a post

Create a Markdown file in `_posts` using this naming pattern:

```text
YYYY-MM-DD-short-title.md
```

Start it with:

```yaml
---
title: "Post title"
description: "One sentence shown on the blog page."
date: YYYY-MM-DD
# Optional cover image shown on the homepage and post:
# image: /assets/images/post-name.jpg
# image_alt: "Short description of the image"
# image_caption: "Optional photo credit or caption"
---
```

Write the post below the second `---`. GitHub Pages publishes it after the
change reaches `main`.

## Preview locally

```sh
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000/`.
