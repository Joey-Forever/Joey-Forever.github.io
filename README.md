# Joey's Notes

Source for the blog at [joey-forever.github.io](https://joey-forever.github.io/).

Built with [Jekyll](https://jekyllrb.com/) and the default `minima` theme, deployed automatically by GitHub Pages on push to `main`.

## Structure

```
_config.yml                 site configuration
index.md                    home page (lists posts)
about.md                    /about/
_posts/                     blog posts, filename YYYY-MM-DD-slug.md
assets/                     images and other static files
```

## Local preview (optional)

```bash
bundle init
bundle add jekyll
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Publishing a new post

1. Add a file under `_posts/` named `YYYY-MM-DD-slug.md` with Jekyll front matter.
2. Put any images under `assets/` and reference them as `/assets/<name>`.
3. Commit and push — GitHub Pages rebuilds the site within a minute.

## License

Content is © Joey, all rights reserved unless otherwise stated. Code snippets inside posts are released under the MIT License.
