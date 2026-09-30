# rclone-oauth-homepage

Home page and privacy policy for a personal Google Drive OAuth client used with
[rclone](https://rclone.org/), served by GitHub Pages. This exists because Google
requires an application home page and privacy policy link before an OAuth consent
screen can be published — see [Making your own client ID](https://rclone.org/drive/#making-your-own-client-id)
in the rclone docs ("a free GitHub Pages site is fine for these").

## URLs

| Page | URL |
|---|---|
| Home page | https://kusold.github.io/rclone-oauth-homepage/ |
| Privacy policy | https://kusold.github.io/rclone-oauth-homepage/privacy.html |

## Paste into Google Cloud Console

When configuring the OAuth consent screen (**Branding** section), use:

- **Application home page**: `https://kusold.github.io/rclone-oauth-homepage/`
- **Application privacy policy link**: `https://kusold.github.io/rclone-oauth-homepage/privacy.html`
- **Authorized domains**: `kusold.github.io`

Then return to **Audience** → **PUBLISH APP** so grants don't expire weekly.

## Editing

Plain static HTML/CSS — edit `index.html`, `privacy.html`, or `styles.css` and push
to `main`; GitHub Pages rebuilds automatically. If you change the contact email,
it appears in both pages' footers and section 10 of the privacy policy.
