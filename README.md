# Procela Public

## Overview
This repository contains the public-facing landing page for **Procela**.  
It includes HTML, CSS, and JavaScript files required for the homepage, branding, and contact form integration.

The site is deployed via **Cloudflare Pages** and automatically updates whenever changes are pushed to this repository.

---

## Deployment
The site is hosted on Cloudflare Pages:

- **Custom domain:** `https://procela.com`
- **Automatic builds:** Enabled via connection to this repository
- **SSL/HTTPS:** Managed automatically by Cloudflare

To update the website:
1. Make changes to the HTML/CSS/JS files in this repository.
2. Commit and push changes to the main branch.
3. Cloudflare Pages will automatically build and deploy the updated site.

---

## Contact Form Integration
The landing page contact form sends submissions to the general inquiries email:

- `hello@procela.com`

Ensure that email settings in Google Workspace are active to receive submissions.

---

## Repository Structure

procela-public/
│
├─ index.html # Main landing page
├─ styles.css # Styling for the page
├─ scripts.js # Optional JavaScript functionality
├─ assets/ # Images, logos, icons, and other media
└─ README.md # Project documentation

---

## Contributing
For updates or edits:

1. Fork the repository (if collaborating externally)
2. Make your changes
3. Submit a pull request for review

Internal team members can push directly to the repository if they have write access.

---

## Notes
- Keep sensitive data (like API keys) out of the repository.
- Use GitHub Pages or Cloudflare Pages build settings as configured.
- Ensure that the contact form email is functioning correctly before public launch.
