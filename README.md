# Ankit Sapkota — Portfolio

My personal portfolio site, built to showcase my front-end projects, skills, and
background in business management and hospitality. Live on GitHub Pages.


## About

I'm a BSc (Hons) Computer science student based in London with different
experience across London and Sydney, and an administrative background  This site is where I bring
those two sides together — organised, detail-first work applied to code.

## Features

- Custom 3D signature element — a draggable, pure-CSS cube in the hero (no
  external 3D library)
- Fully responsive layout with a mobile nav menu
- Contact form that emails messages straight to my inbox via EmailJS
- Client-side form validation (name, email format, message length)
- Scroll-reveal animations on section entry
- Accessible focus states and `prefers-reduced-motion` support

## Tech stack

- HTML5
- CSS3 (custom properties, Grid, Flexbox, 3D transforms)
- Vanilla JavaScript (no frameworks)
- [EmailJS](https://www.emailjs.com) for serverless contact-form email

## Project structure

```
├── index.html      # Page structure and content
├── style.css       # All styling and responsive layout
├── script.js       # Nav, 3D cube interaction, form logic, animations
└── README.md
```

## Running locally

No build step required — it's plain HTML/CSS/JS.

1. Clone the repo:
   ```bash
   git clone https://github.com/ankitsapkota2002-boop/My-protfolio.git
   ```
2. Open `index.html` in a browser, or serve it locally:
   ```bash
   npx serve .
   ```

## Setting up the contact form

The site is static, so email sending is handled client-side through EmailJS:

1. Create a free account at [emailjs.com](https://www.emailjs.com)
2. Add an Email Service connected to `ankitsapkota2002@gmail.com`
3. Create an Email Template using the variables `{{name}}`, `{{email}}`, `{{message}}`
4. In `script.js`, set `EMAILJS_PUBLIC_KEY`, `EMAILJS_SERVICE_ID`, and
   `EMAILJS_TEMPLATE_ID` to your own values

## Deployment

Hosted on GitHub Pages from the `main` branch. Any push to `main` updates the
live site automatically.

## Contact

- Email: ankitsapkota2002@gmail.com
- [LinkedIn](https://www.linkedin.com/public-profile/settings?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_self_edit_contact-info%3BkUxom3phQX6q8TT6m0QWOA%3D%3D)
- [GitHub](https://github.com/ankitsapkota2002-boop)
- [Facebook](https://www.facebook.com/ankit.sapkota.703233)

## License

© 2025 Ankit Sapkota. All rights reserved.