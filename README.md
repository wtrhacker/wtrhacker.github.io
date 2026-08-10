# Tingran Wang

Personal site and blog, built with Jekyll and hosted on GitHub Pages.

## Edit a page

The main pages are `index.md`, `research.md`, `publications.md`, and `blog.md`.
Edit the Markdown or HTML in one of those files and push the change to `main`.

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
