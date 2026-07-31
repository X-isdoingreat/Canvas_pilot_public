# Canvas Pilot site

Static website for `https://canvas-pilot-rho.vercel.app`.

Deploy from this directory through the linked Vercel project:

```text
npx --yes vercel@latest deploy --prod --yes
```

The previous custom-domain alias remains online during migration. The Vercel
URL is the canonical public identity for search, sitemap, robots, and llms.txt.

Canonical localized landing pages:

- English: `/install`
- 简体中文: `/zh/install`

Detailed setup and assignment-fit guides remain available at `/setup` and
`/zh/setup`. Vercel rewrites the canonical install URLs to the shared landing
page sources at `/index.html` and `/zh/index.html`.

Run the static site checks from this directory with:

```text
npm test
```
