# Resume-builder

PortfolioGen — a single-file AI-assisted resume & portfolio generator built as a client-side web app.

Features
- Smart PDF import and text extraction (pdf.js)
- AI-powered parsing & polishing (Gemini generator hooks)
- Live preview and downloadable static `index.html`
- Tailwind + customizable themes and fonts

Quick start
1. Open `index.html` in a browser (no server required) to try the UI.
2. For AI features, open the settings and paste your Gemini API key.

Developer
- Edit `index.html` to customize the builder and templates.
- To initialize a Git repo and push to GitHub, use the CLI or the provided automation in this workspace.

License
MIT

Enjoy — open `index.html` to get started.
# Resume-builder

PortfolioGen — a single-file AI-assisted resume & portfolio generator built as a client-side web app.

Features
- Smart PDF import and text extraction (pdf.js)
- AI-powered parsing & polishing (Gemini generator hooks)
- Live preview and downloadable static `index.html`
- Tailwind + customizable themes and fonts

Quick start
1. Open `index.html` in a browser (no server required) to try the UI.
2. For AI features, open the settings and paste your Gemini API key.

Developer
- Edit `index.html` to customize the builder and templates.
- To initialize a Git repo and push to GitHub, use the CLI or the provided automation in this workspace.

License
MIT

Enjoy — open `index.html` to get started.

Local API key (safe local-only setup)
 - Create a file named `config.local.js` next to `index.html` with:
   - `window.GEN_API_KEY = 'YOUR_API_KEY_HERE';`
 - `config.local.js` is gitignored by default; do NOT commit it.
 - The app will prefer a key typed in the settings UI, then `window.GEN_API_KEY`.

Security note
 - Embedding API keys into client-side code that is publicly hosted exposes them to others. For production, host a small server-side proxy that holds the key and forwards requests securely.

Enjoy the project — open `index.html` to get started.
