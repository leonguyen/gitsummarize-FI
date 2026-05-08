# GitSummarize on Fly.io

## Quick Deploy
1. Download this zip, unzip.
2. `fly auth login`
3. `fly launch --no-deploy` (select no, use existing fly.toml)
4. `fly secrets set GEMINI_API_KEY=your_key SUPABASE_URL=...` (optional for full features)
5. `fly deploy`

Get Gemini key: [Google AI Studio](https://aistudio.google.com/app/apikey)

App URL: https://[app-name].fly.dev
