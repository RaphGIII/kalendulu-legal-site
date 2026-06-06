# Kalendulu Legal Website

This is a static legal/support website for App Store submission.

## Pages

- `/` landing page
- `/privacy/` privacy policy
- `/support/` support
- `/imprint/` imprint/operator information
- `/delete-account/` account deletion information

## Before publishing

Replace all placeholders in `public/**/*.html`:

- `REPLACE_LEGAL_OPERATOR_NAME`
- `REPLACE_LEGAL_ADDRESS`
- `REPLACE_COUNTRY`
- `REPLACE_SUPPORT_EMAIL`
- `REPLACE_DOMAIN`

Do not submit the app while any `REPLACE_...` placeholder remains.

## Cloudflare Pages deployment

Recommended settings:

- Framework preset: None
- Build command: leave empty
- Build output directory: `public`

## App Store Connect URLs

After deployment, use:

- Privacy Policy URL: `https://YOURDOMAIN/privacy/`
- Support URL: `https://YOURDOMAIN/support/`
- Marketing URL: `https://YOURDOMAIN/` optional
- Account deletion information: `https://YOURDOMAIN/delete-account/` optional but recommended
