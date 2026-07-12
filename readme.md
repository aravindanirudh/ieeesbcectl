# IEEE SB CECTL - College IEEE SB Website
## Project Overview
- This repository contains the static website for the IEEE Student Branch (SB) at College of Engineering, Cherthala (CECTL). The site was created and maintained as the official landing page for the student branch to showcase events, publications (Sunday Seconds), announcements, and other resources.
- For live demo, check https://www.ieeesbcectl.in/
- Institute of Electrical and Electronics Engineers or IEEE is the world's largest technical professional organization dedicated to advancing technology for the benefit of humanity. SB stands for Student Branch and CECTL stands for College of Engineering, Cherthala.
- The main landing page for IEEE SB College of Engineering, Cherthala in July 2024 when I was selected as Web Master for IEEE SB CECTL.
- Purpose of this page was to act as an official landing page for college as well as showcase events, Sunday Seconds (monthly magazine) and other important events/updates.
- Previous IEEE SB website was hosted on Wordpress. It was very unprofessional and overpriced.
- Previously, no one knew much about web development. This all changed when I was selected as Web Master. I took all the sections from Wordpress site and implemented them using HTML, CSS, JS.
- Website went through so many updates and improvements over the period of months and years. It is continuously being updated and this is not the production repository. The production repository was created for deployment under the email account of IEEESBCECTL. So, this repository might not be up to date. This particular version is the website's state as of 13 July 2026.
- Search Engine Optimization (SEO) was implemented with the help of Google Search Console.
- AVIF image format used for maximum efficiency.
- Sensitive information/code redacted and replaced with placeholder.
- Domain ieeesbcectl.in was purchased on Blue Host. Website was hosted on Vercel through GitHub using ieeesbcectl999@gmail.com.

---

## Features
- Clean, responsive static pages built with HTML, CSS and vanilla JavaScript.
- Pages included: main landing (`index.html`), previous releases (`previous-releases.html`), Sunday Seconds magazine (`sunday-seconds.html`) and associated stylesheets.
- Optimized images in AVIF format to reduce page weight and improve performance.
- Basic SEO via metadata and Google Search Console integration.
- Local assets folder organized for events, executive committee photos, and previous magazine issues.

---

## Repository structure
Top-level files
- `index.html` - main landing page
- `previous-releases.html` - previous releases page
- `sunday-seconds.html` - Sunday Seconds magazine page
- `styles.css`, `previous-releases-styles.css`, `sunday-seconds-styles.css` - styles for pages
- `scripts.js` - site JavaScript (menu, interactions, etc.)
- `readme.md` - this file

Assets
- `assets/` - all images used by the site. Subfolders include:
	- `activities/` - event images
	- `IEEE_Execom/` - executive committee member photos
	- `previousSundaySeconds/` - magazine issue images

---

## How to run locally
This is a static site - no build step or server is strictly required. You can open `index.html` directly in a browser, but using a simple static server is recommended to avoid some browser restrictions (e.g., CORS for local fetches).

---

## Deployment notes
- The site was hosted on Vercel and the domain `ieeesbcectl.in` was pointed to the Vercel deployment.
- If deploying to Vercel: create a new project, connect the GitHub repo, and set the root directory to `/` (no build command required for pure static sites). Ensure that the `assets/` folder is included in the deployment.
- If deploying to other hosts (Netlify, GitHub Pages, S3+CloudFront), adapt accordingly. For GitHub Pages, push to a branch configured for Pages (usually `gh-pages`) or configure Pages to use the `main` branch root.

---

## SEO & accessibility notes
- Basic SEO implemented via metadata and Google Search Console. For better discoverability, ensure each page has unique `<title>`, `<meta name="description">`, and social sharing (Open Graph/Twitter) metadata.
- Accessibility recommendations:
	- Provide meaningful alt text for images in `assets/`.
	- Ensure color contrast meets WCAG AA for text and interactive elements.
	- Use semantic HTML elements (nav, main, header, footer, article) where appropriate.

---

## Contact
- Project author: [Aravind A Kamath](https://github.com/aravindanirudh)