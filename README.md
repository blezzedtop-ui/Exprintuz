# EXPRINT GROUP — GitHub + Railway

This package preserves the supplied EXPRINT GROUP website and its assets, with a Node/Express wrapper for Railway deployment.

## Local
```bash
npm install
npm start
```
Then open http://localhost:3000

## GitHub → Railway
1. Create a GitHub repository.
2. Upload the contents of this folder (including `index.html`, assets, `package.json`, `server.js`, and `railway.json`).
3. Railway → New Project → Deploy from GitHub Repo.
4. Select the repository.
5. Railway runs `npm start` and supplies a public domain.

No database is required.
