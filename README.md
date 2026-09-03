# Entrepreneurship Area Research Seminar Series

A single-page academic website for the Entrepreneurship Area Research Seminar Series at IIM Bangalore.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Add the final content

All page content currently lives in `index.html`. Before publishing, add or replace:

- the featured seminar paper title, time, venue, and abstract;
- the text-based header mark with an authorized IIMB logo asset, if one is supplied.

Speaker photographs should use a consistent portrait crop. Images around 900 × 1100 pixels in WebP or AVIF format are recommended. Write meaningful alternative text when a photograph communicates information; if the adjacent name makes it purely decorative, use an empty `alt` value.

## Publish with GitHub Pages

1. Create a GitHub repository and push this directory to its `main` branch.
2. In the repository settings, open **Pages**.
3. Set the source to **GitHub Actions**.
4. The included workflow will deploy the site on every push to `main`.

The site has no runtime dependencies or build step.
