# Anthommm — personal blog

A personal blog built with Hugo and Hugo Blox Builder, deployed to GitHub Pages at <https://anthommm.github.io>.

## Write a post

Create a Markdown file in `content/blog/`, for example `content/blog/my-first-post.md`:

```markdown
---
title: "My first post"
date: 2026-11-14
draft: false
summary: "A short preview shown in the post list."
tags:
  - notes
---

Write your post here in Markdown.
```

## Local preview

Install Hugo Extended 0.162.0 or later and Go, then run:

```sh
hugo server --disableFastRender
```

Open <http://localhost:1313>. Hugo downloads the Hugo Blox modules on the first build.

## Publish

The GitHub Actions workflow builds the site on every push to `main` and deploys it to GitHub Pages. In repository **Settings → Pages**, set the source to **GitHub Actions**. The first deployment should make <https://anthommm.github.io> available.

Replace the sample introduction and author details in `content/_index.md` and `data/authors/me.yaml` with your own information.
