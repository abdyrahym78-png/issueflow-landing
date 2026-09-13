# IssueFlow Desktop — Landing Page

Blazing-fast, developer-first landing page for **IssueFlow Desktop** — the offline-first, SQLite-backed issue tracker with Vim shortcuts and 0ms latency.

---

## 🔒 Secret Security & Compliance (CRITICAL)

- **Zero Hardcoded Secrets**: No API keys, tokens, or credentials are stored in source files.
- **Environment Isolation**: `.env` and `.env.*` files are strictly ignored via `.gitignore` (except `.env.example`).
- **Production Secrets**: Configured securely inside the **Vercel Dashboard** under Environment Variables.

---

## 🚀 Vercel Deployment

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```
2. Deploy to production:
   ```bash
   vercel --prod
   ```

---

## 📦 GitHub Repository Setup

```bash
git init
git add .
git commit -m "feat: initial landing page MVP"
gh repo create issueflow-landing --public --source=. --remote=origin --push
```
