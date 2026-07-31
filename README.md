# arctic-linux site

Static marketing page for Arctic Linux. Plain HTML/CSS, no build step, no JS.

## Structure

```
index.html   markup
style.css    styles
```

## Run locally

```
python3 -m http.server -d . 8000
```

then open `localhost:8000`.

## Deploy

Served via Cloudflare Pages, connected to this repo, root as the build output.
Custom domain: `arctic-linux.apiwow.net`.

## Links

- Packages: pkg-arctic.apiwow.net
- Ports: ports-arctic.apiwow.net
- Source: github.com/apiwo/arctic-linux
