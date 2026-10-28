# Junry Avenido — Personal Portfolio

A responsive, minimal black-and-white portfolio built with plain HTML, CSS, and JavaScript. It can be hosted on Vercel as a static site.

## Files
- `index.html` — page content, SEO metadata, and structured data
- `styles.css` — layout, typography, responsive styles
- `script.js` — mobile navigation and dynamic footer year

## Before publishing
1. In `index.html`, replace every `example.com` with your real domain in the canonical URL and Open Graph URL.
2. Replace `your.email@example.com` with your professional email.
3. Replace the LinkedIn and GitHub links with your actual profile URLs.
4. Review all project descriptions and links. Keep only projects you worked on and details you are allowed to publish.
5. Add your approved profile photo, screenshots, and verified metrics if you want them.

## Deploy to Vercel
1. Upload these files to the root of a GitHub repository.
2. In Vercel, choose **Add New → Project**, import the repository, and deploy.
3. For a plain static HTML site, no build command is required. Leave the output directory blank/default unless Vercel asks otherwise.
4. In project **Settings → Domains**, add your domain and follow the DNS values Vercel provides.
5. In Namecheap, open **Domain List → Manage → Advanced DNS** and set the records to match Vercel. Do not delete email records you still use.
6. After verification, update the canonical and Open Graph URLs in `index.html` to your actual primary domain, commit the change, and verify HTTPS.

## Notes
- No server-side code or database is required.
- The Google Fonts import requires an internet connection; system fallback fonts are included.
- Vercel Hobby is intended for personal, non-commercial use. Check current plan terms if the site becomes commercial or is used for client/business purposes.
