# The Velvet Oven Bakery

A ready-to-deploy, mobile-friendly multi-page bakery recipe website.

## Start locally
Open `index.html` in a browser, or serve the directory with `python -m http.server 8000`.

## Deploy on Vercel
1. Unzip this package into a GitHub repository.
2. In Vercel, select **Add New > Project** and import that repository.
3. Choose **Other** as framework preset and leave the build command empty.
4. Deploy. The root page is `index.html`.

## Included
Homepage, searchable recipes, category filters, 9 detailed recipe pages (dynamic query parameters), about, contact, privacy, print/share, local saved recipe state, responsive navigation, local photos when downloadable.

## Notes before publishing
- The contact form prepares an email to `hello@thevelvetovenbakery.com` through the visitor's mail application. Replace this placeholder email in `app.js` with an address you own.
- The newsletter is a clearly labeled non-collecting demo. Connect an actual mailing list service to collect subscriptions.
- Recipes are sample editorial recipes. Test them independently before presenting them as kitchen-tested.
- Images are from Unsplash and subject to its license/attribution rules; verify images and rights before commercial publication.
