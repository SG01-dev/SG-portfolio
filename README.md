# SG · Portfolio

Personal site of **Gaius Soetan (SG)**, AI solutions developer in Manchester.
Single-page HTML, CSS and vanilla JavaScript, with an AI chat assistant ("Ask SG's AI") powered by Claude through a Netlify Function.

## Structure
```
index.html                     the whole site
sg-photo.jpg                   your portrait (add this)
cv.pdf                         your CV (add this)
netlify/functions/ask-sg.mjs   serverless function for the AI chat
```

## Deploy on Netlify
1. Push this folder to a GitHub repo.
2. In Netlify: Add new site > Import from Git > pick the repo. No build command; publish directory is the repo root.
3. Site configuration > Environment variables > add `ANTHROPIC_API_KEY`.
4. Redeploy. The chat badge will switch from "Offline mode" to "Live AI".

## Editing
Search `index.html` for `✏️ EDIT`. Anything highlighted with a dashed marigold underline (`class="todo"`) still needs your real content.
