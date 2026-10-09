# animated-railway

A zero-dependency Node app that serves an animated flow-field page. Move your mouse (or finger) and the lines bend toward it. A live status chip reads `/health` from the running server.

## Run locally

```bash
npm start
# http://localhost:3000
```

## Deploy on Railway via GitHub

1. Push this repo to GitHub.
2. Railway dashboard → **New Project** → **Deploy from GitHub repo** → pick this repo.
3. Open the service → **Settings → Networking → Generate Domain**.
4. Done. Every `git push` to the main branch redeploys automatically.

No env vars needed. Railway sets `PORT`; the server reads it.
