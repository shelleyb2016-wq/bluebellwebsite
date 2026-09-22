# Bluebell Pilates

A modern, responsive single-page marketing website for **Bluebell Pilates** — a boutique
one-to-one Reformer Pilates studio in Sharpthorne, West Sussex.

The site is a fully static build (HTML5 + Tailwind CSS) designed to be hosted on **GitHub Pages**.

## Structure

```
.
├── index.html        # The entire single-page site
├── images/           # Photography, logo and favicon
├── README.md
└── .nojekyll         # Serve files as-is on GitHub Pages
```

## Sections

- **Hero** — full-width studio image with the primary call to action
- **About** — Shelley's story and studio philosophy
- **Gallery** — responsive grid with a click-to-enlarge lightbox
- **Classes** — One to One Reformer sessions and who they suit
- **Pricing** — session and package pricing
- **Contact** — enquiry form (opens the visitor's email client) plus social links

## Tech

- Semantic HTML5
- Tailwind CSS via the Play CDN (no build step required)
- Google Fonts: Cormorant Garamond (display), Marcellus (body), Jost (UI)
- A small amount of vanilla JavaScript for the mobile menu, scroll reveal and gallery lightbox
- Respects `prefers-reduced-motion`

## Brand

| Token | Colour |
| ----- | ------ |
| Pale blue | `#d6e0e2` |
| Med blue | `#a3b9c4` |
| Deep blue | `#5b76ae` |
| Dark blue | `#374478` |
| Green (sage) | `#b4c0a8` |
| Background (cream) | `#f6f3ed` |

## Running locally

It's a static site — open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Notes

- The contact form uses a `mailto:` link so it works without a backend. Update `CONTACT_EMAIL`
  in `index.html` and the social media URLs (`Instagram` / `Facebook`) with the studio's real links.
