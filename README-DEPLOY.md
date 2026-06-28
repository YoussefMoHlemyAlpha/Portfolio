Vercel Deploy Instructions
=========================

Quick steps to deploy this static portfolio to Vercel.

1) (Optional) Install the Vercel CLI globally:

```bash
npm i -g vercel
```

2) From the project root, deploy interactively the first time:

```bash
npx vercel
# or to deploy directly to production
npx vercel --prod
```

3) Non-interactive / CI deploy with a token:

```bash
# set VERSEL_TOKEN in your environment
vercel --token "$VERCEL_TOKEN" --prod
```

Notes
- If you haven't logged in before, `npx vercel` opens a browser to authenticate.
- The included `vercel.json` routes all requests to `index.html`, suitable for single-page static sites.
