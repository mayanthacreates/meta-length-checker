# Meta Length Checker

Free tool at https://mayantha.ae/meta-length-checker - a single static page served by a
Cloudflare Worker routed onto the mayantha.ae zone.

- `public/meta-length-checker.html` - the whole tool (self-contained HTML/CSS/JS)
- `wrangler.jsonc` - static assets Worker + zone route

Deploy: `npx wrangler deploy`
