# Pooja Peshane — Personal Portfolio

A single-page personal portfolio and professional profile site for **Pooja Peshane**, Cybersecurity Program Manager and Project Manager.

**Live site:** [https://poojapeshane.netlify.app/](https://poojapeshane.netlify.app/)

## Features

- Hero section with intro and profile image
- Impact snapshot (experience, cybersecurity, project & program management)
- Work / insights section with links to blog posts
- Interactive cyber tools section (with contact CTA)
- Contact form (Netlify Forms) and social links (LinkedIn, email)
- Floating chat-style assistant widget
- Responsive layout, accessibility improvements, and reduced-motion support

## Tech

- Plain HTML, CSS, and a small amount of JavaScript
- No build step; static files only
- [Netlify](https://www.netlify.com/) for hosting and form handling

## Project structure

```
profile1/
├── index.html      # Main page
├── style.css       # Styles
├── images/         # Local assets (see images/README.md)
├── README.md       # This file
└── LICENSE        # MIT
```

## Running locally

1. Clone or download this repo.
2. Add your images under `images/` as described in [images/README.md](images/README.md).
3. Open `index.html` in a browser, or serve the folder with any static server, e.g.:
   - `npx serve .`
   - `python3 -m http.server 8000`

## Deploying (Netlify)

- Connect the repo to Netlify and deploy the `profile1` (or project) folder as the publish directory.
- Ensure the contact form has `data-netlify="true"` and a hidden `form-name` field (already set in `index.html`).

## Images

Place the required image files in `images/` so the site and Open Graph previews work correctly. See [images/README.md](images/README.md) for the list and naming.

## License

MIT — see [LICENSE](LICENSE).
