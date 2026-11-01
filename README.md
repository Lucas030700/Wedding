# Wedding Event Planner v1.1

Compact, mobile-friendly event planning software for GitHub Pages or Cloudflare Pages.

## Features
- No login and no wedding date requirement.
- Compact feature cards, initially collapsed.
- Each feature opens its own details panel with feature-specific fields.
- Budget slider plus exact amount input for every feature.
- Add/remove controls for repeatable details such as decoration elements, games, flower arrangements and transport entries.
- Guest count, actual/quoted amount, deposits and supplier/payment status.
- Custom event features.
- Browser autosave, JSON backup import/export and CSV budget export.

## Deploy
1. Create a GitHub repository (for example `wedding-event-planner`).
2. Upload `index.html` and `README.md` to the repository root.
3. Commit to `main`.
4. GitHub Pages: Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
5. Or connect the repository to Cloudflare Pages. No build command is required.

## Data
The app does not require login and does not send event data to a server. Data is stored in browser local storage. Export a JSON backup to transfer it to another device/browser. GitHub stores the application source code, not the private event data.
