# Simplify My Life

A modern, single-page marketing site that showcases the Simplify My Life
ecosystem. The project is built with semantic HTML and a bespoke CSS design
system so you can deploy it quickly and iterate without a heavy build step.

## ✨ Features

- **Deployment-ready static page** – No frameworks or tooling required, so it
  works on any static host.
- **Curated product grid** – Spotlight live apps, upcoming launches, and ideas
  still in the lab. Cards link to real experiences like the
  [Password Generator](http://password-generator.simplifymylife.app/),
  [Games Hub](https://games.simplifymylife.app), and
  [RedLytics Reddit insights](https://redlytics.vercel.app/).
- **Brand-consistent visuals** – Navigation, favicon, and product tiles share a
  cohesive gradient-driven logo system with automatic fallbacks for missing
  icons.
- **Call-to-action modules** – Encourage visitors to read the blog, explore the
  ecosystem, or get in touch.
- **Automatic year updates** – A tiny script keeps the footer copyright
  current.
- **Floating support widget** – The Buy Me a Coffee widget rides along the page
  so fans can tip at any time.
- **Built-in contact form** – Collect messages securely via Formspree without
  adding server infrastructure.
- **Ready-to-publish policies** – Privacy, terms, cookie, and accessibility
  pages live alongside the landing page, and a sitemap is ready for search
  engines.

## 📂 Project structure

```
├── assets/            # SVG logos and icons used throughout the layout
├── accessibility.html # Accessibility statement
├── cookie-policy.html # Cookie policy details
├── index.html         # Landing page markup and content
├── privacy.html       # Privacy policy
├── sitemap.xml        # Sitemap for search engines
├── styles.css         # Global styles and responsive layout rules
├── terms.html         # Terms of service
└── README.md          # Project documentation (you are here)
```

## 🚀 Getting started

1. Clone the repository: `git clone https://github.com/<your-username>/simplifymylife.git`
2. Open `index.html` in your browser to preview the site locally.
3. Update the content to reflect your brand (see customization tips below).

Because this is a static site, you do not need to install dependencies or run a
build command.

## 🎨 Customization tips

- **Branding:** Update colors, typography, and spacing inside `styles.css` to
  align with your visual identity. Swap in a new `assets/logo.svg` and
  `assets/icon.svg` to refresh the nav logo and favicon in one go.
- **Content:** Edit `index.html` to rename sections, refresh copy, or link to
  new destinations such as updated product URLs.
- **Assets:** Replace the SVGs in `assets/` with your own logos or
  illustrations. The product cards ingest the live site favicons directly, but
  you can point each `img` at a local asset; if an icon fails to load, the
  gradient fallback in `assets/fallback-icon.svg` keeps the layout polished.
- **Support widget:** Configure the Buy Me a Coffee widget by adjusting the
  inline loader near the bottom of each HTML page. The snippet only assigns a
  welcome message the first time a visitor loads the site (it tracks a
  `bmcWidgetSeen` flag in `localStorage`), so tweak the copy or disable the
  behavior by editing that script.
- **Contact form:** Update the Formspree endpoint or adjust fields inside the
  `#contact` section of `index.html` to fit your workflow.
- **Policies:** Update the copy inside `privacy.html`, `terms.html`,
  `cookie-policy.html`, and `accessibility.html` to reflect your organization,
  and regenerate `sitemap.xml` if you add or remove pages.

## 🌐 Deployment

Deploy the site to any static host (Vercel, Netlify, GitHub Pages, etc.):

1. Push this repository to GitHub or your preferred Git provider.
2. Configure your host to serve the contents of the repository root as a
   static site—no build step is required.
3. Point your custom domain (for example `www.simplifymylife.app`) at the host
   once you're ready to go live.

## 🤝 Contributing

Issues and pull requests are welcome! If you plan to submit changes:

1. Fork the repo and create a feature branch.
2. Make your updates with clear, descriptive commits.
3. Open a pull request that explains the motivation behind the change.

## 📄 License

This project is licensed under the MIT License.
