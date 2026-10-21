# Pigeon Tax Department

A tiny, static copypasta generator disguised as the Pigeon Tax Department. The site branding is intentionally unrelated to copypasta; the page title and metadata are optimized for copypasta-generator searches. No AI, account, build step, or API key required.

## Run it

Open `index.html` in a browser. For the clipboard API and best compatibility, you can also serve the folder locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Internet inspiration

Every third refresh attempts to fetch a public Hacker News headline through its public Firebase API. The headline is used only as inspiration for a newly generated paragraph; the site does not reproduce article text. If the API, network, or browser blocks the request, the local generator continues to work. There is no backend and no AI connection.

## Deploy

Upload `index.html` to GitHub Pages, Netlify, or Vercel as a static site. No build command is needed.
