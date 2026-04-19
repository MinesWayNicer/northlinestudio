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

## Customization Guide

- **Editing Content:** Update text, links, and images directly in the HTML files. For example, change studio description in `index.html`, add real project images in `projects.html`, or update contact info in `contact.html`.
- **Adding Pages:** Create new HTML files following the existing structure (include nav, header, footer). Add links to the navbar and footer nav in all files.
- **Styling Changes:** Modify `style.css` for colors, fonts, or layouts. The color palette is based on #7A806F (dark green) with accents in #90978A and #4f9a70.
- **Images:** Replace placeholder images in `images/` with your own assets. Maintain aspect ratios for best display (banner: ~800x220, logos: square/circle as needed).
- **JavaScript:** Extend `script.js` for new interactions. Currently handles back-to-top and newsletter placeholder.

## Branding Notes

- **Color Palette:** Primary #7A806F (buttons, links), Secondary #90978A (headings), Accent #4f9a70 (highlights).
- **Fonts:** Uses browser defaults; consider adding Google Fonts like 'Inter' for body and 'Playfair Display' for headings if desired.
- **Logo Usage:** Square logo floats in top-left, circle logo used on socials page. Banner appears on all pages.
- **Tone:** Professional yet creative; keep copy concise and confident.

## Future Improvements

- Integrate a real newsletter service (e.g., Mailchimp) for the signup form.
- Add more social platforms to `socials.html` with icons.
- Implement a lightbox or modal for project gallery images.
- Add an "About" section or page with studio history.
- Optimize images and add lazy loading for better performance.
- Consider adding analytics (e.g., Google Analytics) for visitor tracking.

## Changelog

- **Latest (April 2026):** Polished socials page button alignment, centered action buttons across pages, refined homepage layout.
- **Initial Build:** Created responsive portfolio site with navigation, gallery, contact directory, and social links.

## License

This project is open-source under the MIT License. Feel free to use and modify for your own portfolio needs.

## Maintenance Tips

- Test on multiple devices/browsers after changes.
- Update meta descriptions in HTML head for better SEO.
- Backup images before replacing them.
- If deploying to GitHub Pages, ensure repository is public and enable Pages in settings.

