# donassamongkol.com

Personal blog built with [Jekyll](https://jekyllrb.com/) and the [Chirpy theme](https://github.com/cotes2020/jekyll-theme-chirpy), deployed to GitHub Pages.

## Writing a new post

1. Create a file in `_posts/` named `YYYY-MM-DD-your-title.md`
2. Add front matter at the top:

```markdown
---
title: "Your Post Title"
date: 2026-04-05 09:00:00 -0500
categories: [general]
tags: [tag1, tag2]
---

Your content here...
```

3. Write the body in Markdown
4. `git add . && git commit -m "new post" && git push`

GitHub Actions builds and deploys the site automatically (~1-2 min).

## Running locally (optional)

Requires Ruby 3.x and Bundler.

```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

## Project structure

```
_config.yml        # Site settings
_posts/            # Blog posts (YYYY-MM-DD-title.md)
_tabs/             # Sidebar pages (about, archives, etc.)
assets/img/        # Images
CNAME              # Custom domain
.github/workflows/ # Auto-deploy on push to main
```
