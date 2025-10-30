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
- **Call-to-action modules** – Encourage visitors to read the blog, explore the
  ecosystem, or get in touch.
- **Automatic year updates** – A tiny script keeps the footer copyright
  current.
- **Floating support widget** – The Buy Me a Coffee widget rides along the page
  so fans can tip at any time.
- **Built-in contact form** – Collect messages securely via Formspree without
  adding server infrastructure.

## 📂 Project structure

```
├── assets/        # SVG logos and icons used throughout the layout
├── index.html     # Landing page markup and content
├── styles.css     # Global styles and responsive layout rules
└── README.md      # Project documentation (you are here)
```

## 🚀 Getting started

1. Clone the repository: `git clone https://github.com/<your-username>/simplifymylife.git`
2. Open `index.html` in your browser to preview the site locally.
3. Update the content to reflect your brand (see customization tips below).

Because this is a static site, you do not need to install dependencies or run a
build command.

## 🎨 Customization tips

- **Branding:** Update colors, typography, and spacing inside `styles.css` to
  align with your visual identity.
- **Content:** Edit `index.html` to rename sections, refresh copy, or link to
  new destinations such as updated product URLs.
- **Assets:** Replace the SVGs in `assets/` with your own logos or illustrations.
- **Support widget:** Configure the Buy Me a Coffee widget by changing the
  `data-*` attributes in the script tag near the bottom of `index.html`.
- **Contact form:** Update the Formspree endpoint or adjust fields inside the
  `#contact` section of `index.html` to fit your workflow.

## 🌐 Deployment

Deploy the site to any static host (Vercel, Netlify, GitHub Pages, etc.). For
Vercel specifically:

1. Push this repository to GitHub.
2. Import the repo into Vercel and choose the **Static Site** framework
   preset.
3. Leave the build command empty and set the output directory to `./`.
4. Map your production domain (for example `www.simplifymylife.app`) in the
   Vercel dashboard.

## 🤝 Contributing

Issues and pull requests are welcome! If you plan to submit changes:

1. Fork the repo and create a feature branch.
2. Make your updates with clear, descriptive commits.
3. Open a pull request that explains the motivation behind the change.

## 📄 License

This project is licensed under the MIT License.
