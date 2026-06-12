# Bay Area Weekend · Jun 13–15

A private, single-page itinerary for a weekend on the Peninsula. No build step — it's one
self-contained `index.html` (all CSS/JS inline), so it deploys as a static site in seconds.

## What's inside
- **Saturday** — land at SJC, base in Foster City with Sharma, Half Moon Bay coast, the
  Costco + Sephora run, dinner.
- **Sunday** — quiet morning hold, then San Francisco with Mahek (Ferry Building, Embarcadero, Lands End).
- **Monday** — morning hard-blocked for a "Senior Leadership Review" (kept discreet on purpose),
  then return the rental and fly home at 10p.
- A collapsed **private prep section** and a packing checklist.

The page is marked `noindex,nofollow` and is not meant to be shared publicly.

## Deploy in ~30 seconds (no CLI needed)

**Vercel**
1. Go to https://vercel.com/new
2. *Import* the `jatinbatra/BayAreaJune26` repo (branch `claude/sleepy-bell-bm77tn`).
3. Framework preset: **Other**. Root: `/`. No build command, no output dir needed.
4. **Deploy** → you get a live `*.vercel.app` URL.

**Netlify**
1. Go to https://app.netlify.com/start
2. Connect GitHub → pick `jatinbatra/BayAreaJune26` (branch `claude/sleepy-bell-bm77tn`).
3. Build command: *(leave empty)* · Publish directory: `.`
4. **Deploy** → you get a live `*.netlify.app` URL.

### Or run it locally
```bash
npx serve .        # then open the printed localhost URL
# or just double-click index.html
```
