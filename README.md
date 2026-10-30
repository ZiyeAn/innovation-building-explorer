# Innovation by Design — Interactive Building Map

A browser-based architectural metaphor map for the Innovation by Design course. Explore Foundation, LL, L1, L2, and L3 through an interactive SVG building.

## Explore

- Hover over rooms to highlight areas; click to read their ideas and reflection questions.
- Navigate floors, switch isometric / top-down views, zoom, and drag to pan.
- Filter internal spaces, external spaces, reflection areas, and roadblocks.
- Follow a guided tour, inspect staircases, and animate conditional express-lift routes.
- Use the responsive floor navigation and details sheet on smaller screens.
- Pause animation or use the operating system's reduced-motion preference.

## Run locally

No installation or build step is required. Serve this directory with a static HTTP server:

```sh
python3 -m http.server 4317
```

Then visit http://localhost:4317.

## GitHub Pages

Publish the `main` branch's root directory from **Settings → Pages → Deploy from a branch**. The `.nojekyll` file keeps these static files unchanged. All application and font URLs are relative, so the map works beneath a repository's project URL.

## Content and libraries

The map content and colour palette are adapted from the author's Figma map, read on 30 October 2026. This is a snapshot, not a live Figma connection. The original Figma file is not modified by the website.

- [GSAP 3.13.0](https://gsap.com/) powers the interactive motion.
- [Instrument Serif](https://fonts.google.com/specimen/Instrument+Serif) and [DM Sans](https://fonts.google.com/specimen/DM+Sans) are served locally.
- The application uses vanilla JavaScript, SVG, CSS, and HTML. There is no application database, analytics, or visitor information stored by the app.

See the respective projects for dependency licensing. No licence for the course content is granted by this repository.
