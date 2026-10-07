# Luma Theta — temporary legal site (GitHub Pages)

Clean paths: `/privacy`, `/support`, `/terms` (each folder has `index.html`).

## Deploy (drag-drop or gh)

1. Create a **public** GitHub repo named `luma-theta-legal` (empty, no README required).
2. Push this folder to `main` (contents at repo root, not nested in another folder).
3. Repo → **Settings → Pages**: Source = Deploy from branch `main` / `/ (root)`.
4. Wait ~1 minute, then open:
   - `https://<YOUR_USER>.github.io/luma-theta-legal/privacy`
   - `https://<YOUR_USER>.github.io/luma-theta-legal/support`
5. Point app `LumaLinks` at those URLs (see `ship/LEGAL_HOSTING.md` option b).

Relative stylesheet/nav links work under the project-pages base path.
