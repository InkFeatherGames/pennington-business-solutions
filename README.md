# Pennington Business Solutions — Website v1

A responsive, static consulting website designed for Cloudflare Pages.

## What's included
- `index.html` — all homepage sections and content
- `styles.css` — visual design and responsive layouts
- `script.js` — mobile navigation and consultation email preparation
- `favicon.svg` — simple geometric brand mark

## Important: consultation form
The form does **not** send submissions to a server. It opens the visitor's default email application with a prepared message to `Jason.Robert.Pennington@gmail.com`. This is explicitly disclosed on the page. Visitors without a configured email app can use the visible direct email link. For reliable website submissions, connect a form service or Cloudflare Worker and add spam prevention and a privacy notice before enabling server-side collection.

## Deployment with Cloudflare Pages
1. Create a **new GitHub repository**, e.g. `pennington-business-solutions`. Do not use the InkFeather Games repository.
2. Upload these four site files to the repository root.
3. In Cloudflare, go to **Workers & Pages**, create a Pages project, and connect the new GitHub repository.
4. Select a static site with **no build command** and output directory `/` (or use Cloudflare's default for static files).
5. Deploy and verify the `*.pages.dev` preview URL.
6. In the Pages project, add custom domains `penningtonbusinesssolutions.com` and (optionally) `www.penningtonbusinesssolutions.com`; follow Cloudflare's domain/DNS prompts.
7. Check the live website on desktop and mobile, and test the consultation request button using an email application.

## Before marketing launch
- Consider a professional email address on the domain.
- Add a real form delivery service if you want visitors to submit directly in-browser.
- Review wording and business details for accuracy.
- Add privacy policy when collecting data through a hosted form or analytics.
- The dashboard illustration is explicitly fictional; no client work or testimonials are claimed.

## Local preview
Open `index.html` in a browser, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Version 2
Adjusted consultation form labels, required asterisks, and input alignment for consistent rows.