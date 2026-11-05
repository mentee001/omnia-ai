OMNIA AI — Android installation

1. This is a browser-based Progressive Web App (PWA). It is designed for Android Chrome.
2. Upload the contents of this folder to a static HTTPS host. One simple route:
   - Open https://github.com in Chrome and sign in.
   - Create a new public repository named omnia-ai.
   - Use Add file → Upload files. Upload index.html, style.css, app.js,
     manifest.json, sw.js and icon.svg from this folder; commit the files.
   - In the repository, open Settings → Pages.
   - Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
   - Wait for the Pages URL to appear. Open it on your Android phone.
3. In Chrome, tap ⋮ → Add to Home screen (or Install app), then confirm.
4. Open OMNIA from your home screen. Tap ⚙, add your OpenRouter API key and choose a model.
   Create/manage a key at https://openrouter.ai/keys.
5. API usage may cost money. Set a spending limit with your provider.

Privacy and limitations:
- Tasks and notes are stored in this browser's local storage. Clearing browser data can erase them.
- The API key is stored in this browser's local storage. Do not use this on a shared or compromised phone.
- Chat prompts are sent to OpenRouter and the selected model provider. Review their privacy and billing terms.
- This is a useful MVP, not an unrestricted autonomous agent. It cannot control other Android apps,
  make phone calls, access private accounts, bypass security, or guarantee perfect answers.
- Never put sensitive personal, financial, medical or password information into prompts.
