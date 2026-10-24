# Haspra EduTech — GitHub + Vercel Website

A responsive, static website starter for Haspra EduTech. It can be deployed directly from a GitHub repository to Vercel. No build command or framework is required.

## Included

- `index.html` — complete responsive single-page website
- `assets/haspra-edutech-logo.png` — supplied HP-style brand logo artwork
- `assets/favicon.svg` — browser tab icon
- `vercel.json` — lightweight security headers and URL settings

## Official contact details included

- Website: https://haspraedutech.in
- Email: Haspraedutech@gmail.com
- Phone / WhatsApp: +91 96778 13618
- Address: 7/91/1, Sree Murugalaya Nagar, Atthikattanoor, Konagapadi Post, Tharamangalam, Salem–636 502, Tamil Nadu, India

## Deploy using GitHub and Vercel

1. Download and extract this ZIP file.
2. Open GitHub and create a new repository, for example `haspra-edutech-website`.
3. Upload **the contents** of this extracted folder to the repository root. `index.html` must be at the top level, not inside another nested folder.
4. Open https://vercel.com and import the GitHub repository.
5. For Framework Preset, select **Other**. Leave Build Command and Output Directory empty/default; this is a static HTML site.
6. Click **Deploy**.
7. In the Vercel project, open **Settings → Domains** and add `haspraedutech.in` and `www.haspraedutech.in` if you want both versions.
8. In GoDaddy DNS, enter only the DNS records Vercel displays for your project. Do not guess or replace existing records until you have compared them with Vercel's instructions.
9. Wait for Vercel to verify the domain and enable HTTPS. DNS propagation may take time.

## Before publishing

- The Events area contains clearly marked sample/planned event cards. Replace these with confirmed event names, dates, formats and registration links before advertising them as real events.
- The contact form opens the visitor's default email application with a prepared message; it does not store submissions in a database. If you want messages to arrive without the visitor's email application, connect a form service or backend.
- Check the phone, email, address and all page content before launch.

## Updating content

Edit `index.html`, commit/push the changes to GitHub, and Vercel will redeploy the site automatically when Git integration is enabled.

## Important

This is a static website, **not a WordPress installation**. Standard WordPress requires PHP and a database on compatible hosting. GitHub + Vercel is appropriate for this static site.
