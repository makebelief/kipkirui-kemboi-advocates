# Hosting notes

This folder is the production site root. Upload its contents as-is.

- Netlify: publish this folder; `_redirects` handles client-side routes.
- Apache/cPanel: upload to `public_html`; `.htaccess` handles client-side routes.
- Other hosts: configure all unknown paths to serve `/index.html` with status 200.
- Point `kipkiruikemboi.com` and `www.kipkiruikemboi.com` to the host and enable HTTPS.

## Contact forms

The forms submit through FormSubmit to `kaptelwaandassociates@gmail.com`. After the first live submission, open the activation email sent by FormSubmit once to enable delivery. Replace this address in `js/index-DO3PcNIs.js` if the firm's production inbox is different.

## Before launch

Confirm the firm name, email address, phone numbers, postal address, office hours, and advocate profiles. The current team section intentionally contains placeholder profiles.
