<h1 align="center">Komati Tarun Portfolio</h1>

<p align="center">
  Personal portfolio website built to present profile, skills, projects, education, testimonials, and contact details in a clean single-page experience.
</p>

<p align="center">
  <a href="https://tarunkomati.in">Live Site</a> |
  <a href="https://github.com/tarunkomati">GitHub Profile</a> |
  <a href="https://www.linkedin.com/in/tarun-komati-421253329/">LinkedIn</a>
</p>

![Portfolio preview](assets/images/banner.webp)

## Overview

This project is a static personal portfolio site with a visual-first layout and a lightweight front-end stack. It is designed to highlight Tarun's profile, technical skills, featured projects, academic background, testimonials, and contact information.

## Highlights

- Responsive single-page layout for desktop, tablet, and mobile
- Dark and light theme toggle with saved preference
- Hero, about, skills, tools, projects, testimonials, education, and contact sections
- Scroll animations powered by AOS
- Testimonial carousel powered by Owl Carousel
- Contact form integrated with Formspree
- Custom branding, portfolio imagery, and social links

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Bootstrap Icons
- AOS
- Owl Carousel
- Formspree

## Project Structure

```text
.
|-- index.html
|-- assets
|   |-- css
|   |-- fonts
|   |-- images
|   `-- js
|-- CNAME
|-- ads.txt
`-- README.md
```

## Run Locally

This is a static website, so any small local server will work.

```bash
python -m http.server 5500
```

Then open `http://localhost:5500`.

Opening `index.html` directly also works, but a local server is better when checking assets and browser behavior.

## Customize

- Edit page content in `index.html`
- Update styles in `assets/css/style.css`
- Adjust interactions in `assets/js/script.js`
- Replace images inside `assets/images`
- Update the Formspree endpoint in the contact form when needed

## Deployment

This portfolio can be deployed to GitHub Pages, Netlify, Vercel static hosting, or any standard web server. The current custom domain is `tarunkomati.in`.

## Contact Form

The contact form currently submits to:

```text
https://formspree.io/f/mgodrlrw
```

## License

This project is for personal portfolio use. If you reuse the structure, replace the personal content, contact details, and media assets with your own.
