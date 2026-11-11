# SPICE Club website

A responsive static website for SPICE Club, St. Agnes School, Kharagpur.

## Files
- `index.html` — website structure and page sections
- `styles.css` — responsive visual design
- `data.js` — editable trees, activities and initiatives
- `app.js` — rendering and individual tree profile routes
- `assets/spice-logo.jpg` — logo image supplied for this project

## Preview locally
Open `index.html` in a browser. For the best local preview, use a simple local web server.

## Publish free with GitHub Pages
1. A school-approved adult/club representative should create or use a GitHub account.
2. Create a public repository, for example `spice-club`.
3. Upload the contents of this folder (not the containing folder itself) to the repository's main branch.
4. In the repository, open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. GitHub will publish the site at a free `github.io` address. The exact URL depends on the account/repository name.

## Add trees and QR codes
1. Add each tree's real photograph inside `assets/`.
2. Open `data.js` and add an entry to `trees`, giving it a unique ID, e.g. `tree-001`.
3. After publishing, that tree's page will be at:
   `https://YOUR-ACCOUNT.github.io/YOUR-REPOSITORY/#/trees/tree-001`
4. Generate a QR code from that exact public URL and print it on the tree's information plate.

## Important before public launch
- Confirm school approval for publishing the school name, logo and photographs.
- Use photographs only with appropriate permission, especially where students are identifiable.
- Replace the empty contact email link with an approved school/club contact address.
- Add only verified tree species, locations and ecological facts.
- This is a static website: it does not collect form submissions or upload photos. A school-approved submission service can be linked later.
