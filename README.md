# Static CV (HTML + CSS)

This is a minimal static site scaffold for a CV/portfolio. It requires no build tools — you can open `index.html` in your browser or run a tiny local server if you want live reload or to serve from `http://localhost`.

Quick ways to view locally (PowerShell):

- Open directly in default browser:

```powershell
Start-Process "index.html"
```

- Serve with Python (if Python is installed):

```powershell
# from the project root
python -m http.server 8000
# then open http://localhost:8000
```

- Serve with `npx` (Node.js installed):

```powershell
npx serve . --port 5000
# or
npx http-server -p 5000
```

Notes

- To edit the content, update `index.html` and `css/styles.css`.
- This scaffold now includes Bootstrap (via CDN). You can use Bootstrap classes in `index.html` and the existing `css/styles.css` will override Bootstrap where needed.
- If you want live-reload while editing, I can add a dev script (requires Node.js).
