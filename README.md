# Meta title and description length checker

Measures SEO titles and descriptions in pixels rather than characters, and previews how the result truncates in a Google SERP.

Live: https://mayantha.ae/tools/meta-length-checker

## How it works

One self-contained page - `public/meta-length-checker.html` holds the markup, styles and logic.
There is no backend and no build step. Nothing is uploaded anywhere; the work happens
in the browser.

## Running it

```sh
npx wrangler dev     # local
npx wrangler deploy  # to your own Cloudflare account
```

`wrangler.jsonc` serves `public/` as static assets. Deploying gives you a
`workers.dev` URL; add a `routes` entry if you want it on your own domain.

## Note

The live version linked above is a React port that runs inside mayantha.ae. This repo
is the original standalone implementation - same behaviour, no framework.

MIT licensed.
