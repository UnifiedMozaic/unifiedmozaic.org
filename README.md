# unifiedmozaic.org

Source of the UnifiedMozaic website — <https://unifiedmozaic.org>.

A single static page with no build step. English and Japanese live side by side in `index.html` (`<span lang="en">` / `<span lang="ja">`); the shown language follows the browser and the EN / 日本語 switch.

## Preview

```sh
python3 -m http.server 8000
```

## Deploy

Cloudflare Pages: no build command, output directory `/`. `_headers` sets the response headers.
