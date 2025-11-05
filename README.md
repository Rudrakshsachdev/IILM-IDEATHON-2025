# IILM Ideathon 2025 — Landing Page

A responsive static landing page for IILM Ideathon 2025 showcasing event details, registration, schedule, judging criteria, organizing team and FAQs.

## Features

- Hero section with countdown and call-to-action
- Event details, highlights, prizes and registration (with QR)
- Judging criteria, instructions and poster requirements
- Organizing team with tabs and social links
- FAQ section and footer
- Particles.js background and basic animations using CSS/JS
- Mobile-friendly navigation and scroll-to-top

## Tech stack

- HTML5
- CSS3 (custom)
- JavaScript (vanilla)
- Particles.js (background animation)
- Font Awesome (icons)

## Project structure

- c:\IDEATHON_IILM\index.html — main page
- c:\IDEATHON_IILM\css\style.css — styles (add/modify)
- c:\IDEATHON_IILM\js\script.js — interaction and countdown
- c:\IDEATHON_IILM\images\* — images and qr_code.png
- c:\IDEATHON_IILM\README.md — this file
- c:\IDEATHON_IILM\LICENSE — project license

## Local setup / quick start

1. Clone or copy the project folder to your machine.
2. Open `index.html` directly in a browser for a quick preview.
3. For a local static server (recommended):
   - Python 3: `python -m http.server 8000` then open `http://localhost:8000`
   - Node (serve/http-server): `npx http-server .` then open the printed URL

## Configuration & customization

- Registration link: update all occurrences of the Google Forms URL in `index.html`.
- QR code: replace `images/qr_code.png` with an updated image (same filename).
- Event date/time: update the hero event details and the countdown target in `js/script.js`.
- Team images: replace files in `images/` and update `alt`/names in `index.html` as needed.
- Styles & branding: edit `css/style.css` to change colors, fonts or layout.

## Development notes

- Keep JS modular and avoid inline scripts where possible; prefer `js/script.js`.
- Use modern CSS practices (variables, flexbox/grid).
- Optimize images (webp or compressed PNG/JPG) for faster load.

## Deployment

- Upload the repository folder to any static hosting (GitHub Pages, Netlify, Vercel, S3).
- For GitHub Pages: push to `main` (or `gh-pages`) and enable Pages from repository settings (choose root for this single-page site).

## Contributing

- Fork the repository, create a feature branch, make changes and open a pull request.
- Keep commits focused and small. Include screenshots for visual changes.
- For changes to content (names, dates, links), update `index.html` and related assets.

## License

This project is licensed under the MIT License — see the included `LICENSE` file for details.

## Contact

For issues or improvements, open an issue or reach out to the organizers:

- Designer / contributor: Rudraksh Sachdeva (rudrakshsachdeva.dev@gmail.com)
