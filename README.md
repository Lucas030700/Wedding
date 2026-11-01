# Wedding Event Planner

A lightweight, mobile-friendly wedding event builder for GitHub Pages / Cloudflare Pages.

## Included in v1.0
- No login or wedding date requirement.
- Selectable wedding feature catalog, grouped by event area.
- Custom event features.
- Guest count.
- Per-feature budget estimates.
- Budget details: cost type, quantity, unit cost, estimate, actual/quotation, deposit and status.
- Local browser autosave.
- JSON backup import/export and CSV budget export.
- Responsive layout for desktop and mobile.

## Deploy with GitHub
1. Create a repository, for example `wedding-event-planner`.
2. Upload `index.html` and this `README.md` to the repository root.
3. Commit to the `main` branch.
4. For GitHub Pages: open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Alternatively, connect the repository to Cloudflare Pages and use the root directory with no build command.

## Data and privacy
This version does not require an account and does not send event data to a server. Data is saved in the browser's local storage on the device/browser being used. Use **Settings → Export backup (JSON)** to move data to another device or browser. GitHub stores the app source code, not the planner's private data.

## Updating
Edit `index.html`, commit the changes, and let the hosting provider redeploy.
