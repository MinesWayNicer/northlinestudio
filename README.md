# Northline Studio Website

This repository contains a professional portfolio website for Northline Studio, a digital art, animation, and design studio. Built with plain HTML, CSS, and JavaScript for simplicity and performance.

## Project Structure

- `index.html` — Home page with hero section, about info, newsletter signup, and navigation.
- `projects.html` — Art gallery page with placeholder project tiles (ready for real artwork).
- `socials.html` — Social media page featuring the studio logo and Instagram link.
- `contact.html` — Contact directory with departments, team members, and contact details.
- `style.css` — Comprehensive stylesheet with responsive design, custom color scheme, and animations.
- `script.js` — JavaScript for interactive features like back-to-top button and form handling.
- `images/` — Logo and banner assets used throughout the site.

## Features

- **Responsive Design:** Fully mobile-optimized with breakpoints for tablets and phones.
- **Navigation:** Sticky top navbar, floating home logo button, and footer navigation links.
- **Interactive Elements:** Back-to-top button, smooth scrolling, hover effects, and newsletter form.
- **Color Scheme:** Custom green palette matched to the studio's branding (#7A806F).
- **SEO Basics:** Meta tags, favicon, and preload directives for better search visibility.
- **Accessibility:** Focus states, semantic HTML, and keyboard navigation support.

## Notes

- The site is designed to be simple, professional, and easy to extend.
- Replace placeholder project gallery images with real artwork in `projects.html`.
- Update department and team email addresses as needed in `contact.html`.
- The floating logo in the top-left corner links back to the homepage and follows scrolling.
- Newsletter signup is a placeholder; integrate with a service like Mailchimp for real functionality.
- All links are internal and working; external links open in new tabs.

## Local Testing

You can preview the site locally using a simple HTTP server:

```bash
cd /home/mineswaynicer/northlinestudio
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000` in your browser.

## Deployment

The site is static and can be deployed to any web host, CDN, or platform like GitHub Pages, Netlify, or Vercel. No build process required.

