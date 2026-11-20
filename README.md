# Finds Worth Sharing — free affiliate website starter

## What's included
- `index.html` — responsive homepage, category filters, search, and product cards
- `styles.css` — design and mobile styles
- `products.js` — sample product catalog (fictional category ideas, not verified listings)
- `app.js` — filtering, search, and safe outbound links
- `manage.html` + `manage.js` — browser-based catalog editor with export
- `disclosure.html` — starter affiliate disclosure

## Run locally
Unzip, then open `index.html` in Chrome or Edge. Click **Manage Products** to edit the catalog. No installations required.

## Add your first real product
1. Apply for affiliate programs and check their rules and approval status.
2. Find a genuine product and confirm its availability and claims.
3. Open `manage.html`; add the title, category, original description, and authorized affiliate URL.
4. Add an image URL **only if the retailer/network grants permission to display that image in this way**. Otherwise leave blank; a decorative placeholder will display.
5. Click **Download updated products.js** and replace the original `products.js` file in your website folder.
6. Refresh `index.html` to see the update. Publish the changed file to your host when ready.

## Publish free with GitHub Pages
1. Create a free GitHub account, then create a public repository (for example `finds-worth-sharing`).
2. Upload the website files to the repository root.
3. In repository Settings > Pages, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
4. Wait for the Pages URL, usually `https://YOUR-USERNAME.github.io/finds-worth-sharing/`.
5. When you update products, upload the replacement `products.js` file and commit the change.

GitHub Pages is a public static host, not a private CMS. `manage.html` edits only your local browser copy, and **does not** directly change your published site. It is a convenience editor, not a secured administrator area. You may choose to remove `manage.html` and `manage.js` from your published repository and keep them only on your computer.

## Costs
- Build and run locally: $0
- GitHub public repository and Pages (within free-tier limits): $0
- Custom domain: optional and generally paid
- Affiliate applications: typically free; approval is not guaranteed

## Before going live
- Confirm brand name availability and potential trademark conflicts.
- Replace/remove demo entries; do not misrepresent sample concepts as verified bestsellers.
- Add affiliate links only after appropriate program access/approval and comply with their terms.
- Review disclosure language and place a clear notice near affiliate links.
- Do not scrape retailer sites or copy product images, prices, ratings, or descriptions without authorization.
- Test on mobile, confirm every link, and avoid unsupported claims about trends or product quality.
- Add privacy information if you later add analytics, forms, or tracking cookies.

## Future enhancement
A Google Sheets-to-JSON publishing script or GitHub Actions workflow can automate catalog publishing. This is intentionally **not** included in v1, to keep setup simple and avoid exposing credentials.
