# Simplify My Life

A modern static landing page for the Simplify My Life ecosystem. This site is
ready to deploy on [Vercel](https://vercel.com) and highlight your collection of
apps, tools, and playful experiences.

## Getting started

1. Install dependencies (none required for a static site).
2. Preview locally by opening `index.html` in your browser.
3. Deploy to Vercel as a static project.

## Customization

- Update links in `index.html` as new products launch.
- Adjust the design system in `styles.css` to match future branding tweaks.
- Keep the product URLs in `index.html` aligned with the live experiences (blog, games, password generator, RedLytics, etc.).
- Swap in your own branding by editing the SVG assets in `assets/logo.svg` and `assets/icon.svg`.
- Update the contact form endpoint or copy in `index.html` if you change messaging or Formspree configuration. The form auto-includes the origin domain and uses a honeypot field for bot protection.

## Deployment tips

- Push this repository to GitHub and import it into Vercel.
- Ensure the project is configured as a static site (no build command needed).
- Map the deployment to `www.simplifymylife.app` in your Vercel dashboard.

## License

MIT
