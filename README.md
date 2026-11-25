# Portfolio

Personal site of Florian Krötz. It is plain HTML and CSS with no build step, published with GitHub Pages.

- `index.html`: all content
- `assets/style.css`: styles (light and dark mode follow the system setting)
- `assets/favicon.svg`: tab icon

## Preview locally

```sh
python3 -m http.server 8000   # then open http://localhost:8000
```

## Publish

Name the repository `Flousen.github.io` and push to `main`. The site is then served at https://flousen.github.io/.
Under Settings → Pages, set the source to "Deploy from a branch" with `main` and `/ (root)`.
