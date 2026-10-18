# ADI WATER PARK Website

A premium, responsive static website for ADI WATER PARK, Sasaram, Rohtas, Bihar.

## Project structure

- `index.html` — complete page, SEO metadata, content and structured data
- `css/style.css` — responsive visual system, layout, animations and components
- `js/script.js` — mobile menu, scroll reveal, active navigation, gallery lightbox and current year
- `assets/images/` — place all park images here
- `assets/icons/` — optional local icons
- `README.md` — this guide

## Add or change images

Put local images inside `assets/images/`. The website expects:

- `hero.jpg`
- `about.jpg`
- `attraction1.jpg`
- `attraction2.jpg`
- `attraction3.jpg`
- `facility1.jpg`
- `facility2.jpg`
- `facility3.jpg`
- `gallery1.jpg` through `gallery8.jpg`

Update the matching `src` in `index.html` if you use different filenames. No remote image URLs are used.

## Change ticket prices

Search `₹300`, `₹200`, and `₹500` in `index.html` and update the corresponding Adult, Child and Family values.

## Change phone / WhatsApp

The current number is `+91 9876776788`. Search for `919876776788` and `+919876776788` in `index.html` to update WhatsApp and phone links.

## Change opening hours

Search for `9:00 AM – 6:00 PM` in `index.html`. Also update the opening-hours value in the JSON-LD structured data if the hours change.

## Deploy on Netlify

1. Extract the ZIP.
2. Open Netlify.
3. Use the option to deploy a site manually.
4. Upload the `ADI-WATER-PARK` project folder (or its contents as supported by Netlify).
5. `index.html` must be at the project root.

## Deploy on GitHub Pages

1. Create a GitHub repository.
2. Upload the project files with `index.html` at the repository root.
3. Open repository Settings → Pages.
4. Select the branch/folder containing the website.
5. Save and wait for the GitHub Pages URL.

## Customize the website

- Colors and spacing: edit CSS variables at the top of `css/style.css`.
- Text: edit the corresponding section in `index.html`.
- Navigation: edit the links in the navbar.
- Gallery: replace local image files while keeping their filenames.
- Booking: update the WhatsApp and phone links consistently.
- Map: the “Get Directions” link uses a Google Maps search URL based only on the supplied park name and location.

## Important

This project intentionally does not include a backend, database, payment gateway, fake booking confirmation, fake reviews, fake statistics or external images. Booking is handled through WhatsApp or phone contact.
