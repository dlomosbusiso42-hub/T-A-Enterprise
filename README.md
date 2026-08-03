# T-A-Enterprise
An Infrastructure and Systems Development Website

This repository contains the static website for T & A Enterprise. The site is built as a single-page experience and can be deployed on Vercel, cPanel, or any static hosting provider.

## Files
- `index.html` — the full website content, styling, and JavaScript
- `vercel.json` — security headers for Vercel deployments
- `.htaccess` — HTTPS and security headers for Apache/cPanel deployments
- `README.md` — project overview and deployment notes

## Deployment

### Vercel
Upload the folder to a new Vercel project or run `vercel deploy` from this directory.

### cPanel / Apache
Upload `index.html` and `.htaccess` to your web root, such as `public_html`.

## Notes
- Contact details are currently set to `nzalocalvin@gmail.com` and `065 615 7138`.
- The contact form includes client-side validation and a honeypot field, but it does not send email by itself without a backend or form service.
- Security headers and HTTPS behavior are included for production deployment.
