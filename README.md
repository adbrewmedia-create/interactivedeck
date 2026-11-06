# Liam Picks Fights: offer deck

Static site, no build step. `index.html` is the 10-slide offer deck; `demo/13/` is the site preview shown inside it.

## Deploy to Vercel
- Dashboard: New Project → import this folder (or a repo containing it). Framework preset: **Other**. No build command, no output directory.
- CLI: `cd liam-offer-deck && npx vercel --prod`

`vercel.json` sends `X-Robots-Tag: noindex, nofollow` on every file, on top of the page's own noindex meta tag, so search engines do not list it.

## Before you send it
1. Earnings use placeholders: 1% click-through, 6 sign-ups per 1,000 visits, about $61 per sign-up paid in full to the creator. Confirm all three with the commercial team.
2. Check every creator number (followers, views) against its source.
3. Only use pictures that are public or cleared.
4. The game mockup still uses football fixtures and scores.
