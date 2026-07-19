# VANTAGE 5 — deploy to Render

1. Push this folder to a GitHub repo (index.html + render.yaml at the root).
2. Render dashboard → New → Static Site → connect the repo.
   - Build Command: (leave blank)
   - Publish Directory: .
3. Deploy. HTTPS + CDN on the free tier.

Notes
- Firebase auth + Firestore sync use the same tulip-dial-command project as before,
  so your account and saved Anthropic API key carry over automatically.
- "Work offline" on the sign-in screen runs everything on-device with zero backend.
- RECON and SPAR use your Anthropic key (set in FORGE). RECON tries live web search
  on your key and falls back to model knowledge automatically if unavailable.
- Full backup/restore lives in FORGE → Your Data.
