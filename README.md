# Jam's Media Portfolio

Static GitHub Pages portfolio with a browser admin editor.

## How to use
1. Upload this folder to your GitHub repo.
2. Put portfolio images inside `assets/portfolio/`.
3. Open the site, click **Admin**, and use the password in `index.html`.
4. Add/edit items.
5. Click **Download media.json**.
6. Replace the old `media.json` in GitHub with the downloaded one.

## Important
GitHub Pages is static. It cannot securely save uploads or edits directly from the website without a backend.

The admin panel is for editing/exporting JSON. Real online admin uploads require Firebase, Supabase, Netlify CMS/Decap CMS, or a custom server.

## Change password
Open `index.html` and find:

```js
const ADMIN_PASSWORD='change-this-password';
```

Change it to whatever you want. Do not use a real personal password.
