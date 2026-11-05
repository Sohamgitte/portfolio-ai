# Soham Gitte — Production Portfolio

A production-level static portfolio inspired by the information architecture and visual direction of [sohamgitte.in](https://sohamgitte.in).

## Included

- Premium dark blue responsive interface
- Hero profile section with remote profile image fallback
- About, capabilities and academic trajectory
- 18 technology cards with category filters
- Quick-Fix Home Services and SohamLabs Portfolio CMS project sections
- Experience and leadership timeline
- Education, certifications and milestones
- Resume download and preview links
- Contact cards plus a client-side mailto contact form
- Mobile navigation, scroll reveal animations and responsive layouts

## Run locally

```bash
python -m http.server 5500
```

Open `http://localhost:5500` in your browser.

## Optional local assets

The page currently uses the live profile image from `https://sohamgitte.in/soham-photo.jpg`. For a self-contained deployment, download the image and save it as `soham-photo.jpg` in the repository root, then change the image source in `index.html` to `soham-photo.jpg`.

If you have a PDF resume, save it as `Soham_Gitte_Resume.pdf` in the root so the Resume links work.

## GitHub Pages

1. Open **Settings → Pages**.
2. Select **Deploy from a branch**.
3. Choose `portfolio-ai-site` and `/ (root)`.
4. Save and wait for GitHub Pages to publish the site.

## Contact

- Email: sohamgitte125@gmail.com
- Phone: +91 7058574509
- LinkedIn: https://www.linkedin.com/in/soham-gitte-609470306
- GitHub: https://github.com/Sohamgitte

The contact form opens the visitor's default email client. No credentials or private API keys are exposed in the frontend.
