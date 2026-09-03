# Entrepreneurship Area Research Seminar Series

A single-page academic website for the Entrepreneurship Area Research Seminar Series at IIM Bangalore.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Add the final content

All page content currently lives in `index.html`. Before publishing future seminars, add or replace:

- the featured seminar paper title, time, venue, and abstract;
- the speaker details for upcoming seminars.

Speaker photographs should use a consistent portrait crop. Images around 900 × 1100 pixels in WebP or AVIF format are recommended. Write meaningful alternative text when a photograph communicates information; if the adjacent name makes it purely decorative, use an empty `alt` value.

## Publish with GitHub Pages

This repository is intended to publish from:

`https://github.com/ENTSeminar/webpage`

Use GitHub's simple branch-based Pages setup:

1. In the repository settings, open **Pages**.
2. Set **Source** to **Deploy from a branch**.
3. Set **Branch** to `main` and folder to `/root`.
4. Save.

The public URL will be:

`https://entseminar.github.io/webpage/`

The site has no runtime dependencies or build step.
