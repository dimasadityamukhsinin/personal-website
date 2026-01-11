# Portfolio

Personal portfolio site built with Tailwind CSS and Sass. Source HTML lives in `src/pages` and is copied to `dist` during build.

## Requirements

- Node.js (LTS recommended)
- npm

## Install

```bash
npm install
```

## Development

Build once:

```bash
npm run build
```

Watch styles (run in separate terminals):

```bash
npm run watch:css
npm run watch:tw
```

Then open `dist/index.html` in your browser.

## Project structure

- `src/pages/index.html` — homepage source
- `src/styles/main.scss` — main stylesheet source
- `src/styles/main.css` — generated Sass output (gitignored)
- `dist/output.css` — Tailwind build output

## Deploy (Vercel)

- Build Command: `npm run build`
- Output Directory: `dist`

## Notes

- Edit styles in `src/styles/main.scss` only.
- Update content in `src/pages/index.html` and run `npm run build`.
