# Debian Packaging Guide

A Jekyll site covering every command, file, and workflow for Debian packaging — explained in plain English for newcomers.

## Structure

```
_includes/sections/     ← one file per section
  05-commands/          ← commands section split by group
_layouts/default.html   ← site layout
assets/css/style.css    ← all styles
index.md                ← just front matter + {% include %} calls
_config.yml             ← Jekyll config and nav data
```

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`.

## Deploy

Pushed to GitHub → GitHub Pages builds and serves it automatically via Jekyll.
