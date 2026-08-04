# Jianbiao Mei Homepage

Minimal Jekyll source for a GitHub Pages personal homepage.

## Structure

- `index.md` uses `_layouts/default.html` as the homepage.
- `_posts/` contains the publication entries rendered in the Research section.
- `images/` contains only homepage and publication images currently referenced by the site.

## Deploy

1. Push this repository to GitHub.
2. In repository settings, enable GitHub Pages from the main branch root.
3. GitHub Pages will build the Jekyll site automatically.

Add a `CNAME` file only if you plan to use a custom domain.

## Local Preview

Use Ruby 3.0 or newer.

```sh
ruby -S bundle install
ruby -S bundle exec jekyll serve
```
