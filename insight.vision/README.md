# Insight.Vision

The company website for Insight Vision Pty Ltd.

**Website:** [insight.vision](https://insight.vision)

Static HTML and CSS in `public/`, hosted on Cloudflare Workers.

```sh
npm ci
npm run dev
```

Pushes to `master` deploy automatically through Cloudflare Builds, using root
directory `insight.vision` and deploy command `npx wrangler deploy`.
The Worker is `insight-vision`; custom domains are `insight.vision` and
`www.insight.vision`. No database, storage subscription or runtime secrets are needed.
