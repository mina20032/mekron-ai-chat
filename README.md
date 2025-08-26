# Mekron Static Chat (n8n)

Front-end static chat page that sends messages to an n8n Webhook.

## Configure
1. Open `index.html`
2. Replace `N8N_WEBHOOK` with your Production Webhook URL from n8n.
3. Commit & push to GitHub. On Vercel:
   - Framework preset: **Other**
   - Build command: *(leave empty)*
   - Output directory: `.`
   - Redeploy

This repo also includes a `vercel.json` that rewrites all routes to `index.html` to avoid 404s.
