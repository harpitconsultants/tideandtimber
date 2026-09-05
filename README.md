# Tide & Timber Getaways

A static vacation-rental showcase for East Coast beach locations and mountain stays. It does not process bookings and does not expose property street addresses.

## Edit the site

- `index.html` contains the property names, city/state locations, guest counts, amenities, descriptions, contact email, and image links.
- `styles.css` controls colors, type, spacing, and responsive layouts.
- `script.js` controls the Beach/Mountain filters and property inquiry pop-up.

Before publishing, replace every occurrence of `hello@example.com` in `index.html` and `script.js` with the real inquiry email. The ten current rentals, details, and photos are sample content intended to be replaced.

## Publish with GitHub and Cloudflare Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `styles.css`, `script.js`, and this `README.md` to the repository root.
3. In Cloudflare, open **Workers & Pages** and create a Pages project connected to the repository.
4. Select **No framework**. Leave the build command blank and set the output directory to `/`.
5. Deploy the project.

Because this is a static site, no packages, database, or server setup is required.
