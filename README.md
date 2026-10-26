# auditlint.ai

Static one-page site for AuditLint.ai. No build step.

## Deploy on GitHub Pages
1. Push this folder's contents to the root of a repo (e.g. `AuditLint/auditlint.ai`), branch `main`.
2. Repo → Settings → Pages → Source: "Deploy from a branch", `main` / `(root)`.
3. Custom domain is set by `CNAME` (`auditlint.ai`). At your DNS provider add:
   - `A` records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` for `www` → `<your-github-user>.github.io`
4. Once DNS resolves, tick "Enforce HTTPS".
