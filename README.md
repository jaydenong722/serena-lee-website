# Serena Lee Photography

One-page portfolio site for Serena Lee, a freelance wedding and portrait photographer. Plain HTML and CSS, no build step.

## Structure

- `index.html` – the whole site (hero, gallery, contact)
- `images/` – gallery photos
- `vercel.json` – Vercel settings (caching and security headers)

## Edit

- **Photos:** add files to `images/`. Replace each placeholder `<div class="photo ...">` in `index.html` with `<img class="photo p3" src="images/your-photo.jpg" alt="Describe the photo">`. Keep the same `p1`–`p5` class so the frame shape stays.
- **Email:** search `hello@serenalee.com` in `index.html` and replace it (two places).
- **Captions and text:** edit them directly in `index.html`.

## Preview locally

```
npx serve .
```

## Deploy on Vercel

1. Import this repository at https://vercel.com/new.
2. Leave Framework Preset as **Other**, with no build command and no output directory.
3. Deploy. Every push to `main` redeploys the site.

Or from the terminal: `npx vercel --prod`.
