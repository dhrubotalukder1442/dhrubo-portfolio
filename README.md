# Portfolio — Deploy to Vercel

## Quick deploy (no coding needed)
1. Go to https://vercel.com and sign in (GitHub login is easiest).
2. Click **Add New → Project**.
3. Choose **Deploy without a Git repository** (or drag-and-drop) and upload `index.html`.
   - Alternatively: create a new GitHub repo, push `index.html` into it, then import that repo in Vercel — this also lets you edit and redeploy easily later.
4. Vercel auto-detects it as a static site. Click **Deploy**. Done — you'll get a live `.vercel.app` URL in under a minute.

## Before you deploy — fill these in
Open `index.html` and search for:
- `#` next to the LinkedIn icon → replace with your real LinkedIn URL
- `dhrubot1442@gmail.com` → confirm this is the email you want public, or swap it
- `+8801615823129` → confirm phone number

## What's already live
- GitHub feed (Projects → GitHub Feed section) pulls automatically from
  `https://api.github.com/users/dhrubotalukder1442/repos` — no setup needed, it'll always show your latest public repos.

## To add a custom domain later
Vercel dashboard → your project → Settings → Domains.
