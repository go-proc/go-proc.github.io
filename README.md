<p align="center"><img src="https://raw.githubusercontent.com/go-proc/brand/main/social/go-proc.png" alt="go-proc/go-proc.github.io" width="720"></p>

# go-proc.github.io

The organization's institutional landing page, served at
<https://go-proc.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`, capability cards driven by
`[[params.phases]]` in `hugo.toml`, with a light/dark/system theme toggle).

Documentation lives in a separate repository,
[go-proc/docs](https://github.com/go-proc/docs), served at
<https://go-proc.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
