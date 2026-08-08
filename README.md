# trinhlk.github.io

Personal page of Trinh, Le-Khanh — a Jekyll static site hosted on GitHub Pages.

## Stack

- Jekyll 3.x (GitHub Pages build) + Bootstrap 3 / jQuery templates (FlexyVcard/PanelCV theme)
- Blog posts are written in **Markdown** — see `_posts/`

## Adding a new blog post

1. Create a file `_posts/YYYY-MM-DD-your-slug.md`
2. Fill in the front matter (see existing posts for examples):

```markdown
---
title: My new post title
date: 2026-08-01
collaborators: [Name One, Name Two]
tags: [tag1, tag2]
image: images/blog/blog-4.jpg    # single image (optional)
images: [images/blog/1.jpg, images/blog/2.jpg]  # or an image carousel
---

Write the post content in Markdown here...
```

3. Commit and push to `master`. GitHub Pages rebuilds automatically — no HTML editing needed.

## Local development

```bash
# Ruby >= 3.0 recommended (System Ruby 2.6 on macOS cannot build gems)
brew install ruby@3.3 && export PATH="$(brew --prefix)/opt/ruby@3.3/bin:$PATH"
bundle install          # gems install into ./vendor/bundle
bundle exec jekyll serve    # http://localhost:4000
```

## Author

- [Locky](https://github.com/junlulocky) (original PanelCV theme)
- [TrinhLK](https://github.com/TrinhLK) (customization + current content)