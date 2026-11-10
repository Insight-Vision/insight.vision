# Insight.Vision

The company website for Insight Vision Pty Ltd.

**Website:** [insight.vision](https://insight.vision)

Static HTML and CSS in `public/`, hosted on Cloudflare Workers.

```sh
npm ci
npm run dev
```

Cloudflare builds deploy from `master` using `npx wrangler deploy`.
The Worker is `insight-vision`; custom domains are `insight.vision` and
`www.insight.vision`. No database, storage subscription or runtime secrets are needed.
