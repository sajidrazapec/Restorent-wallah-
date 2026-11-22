# Restaurant website — installable app folder

Upload this whole folder to a free host (Netlify Drop, Cloudflare Pages, GitHub Pages).

- index.html        customer site + admin (open /#admin)
- owner.html        owner app entry (redirects to the admin; use it for the owner's Play Store app)
- manifest.webmanifest / owner.webmanifest   app name, colours, icons — edit per restaurant
- sw.js             offline support (change V to force an update)
- icons/            app icons (replace with the restaurant's logo, same file names and sizes)
- extras/assetlinks.template.json   fill in and host at /.well-known/assetlinks.json for the Play Store app

Privacy page for Play Console: https://YOURSITE/#privacy
Full step-by-step guide: see the Play Store Launch & Selling Guide document.
