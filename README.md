# LLMPages

A minimal static site (GitHub Pages-ready) that publishes a curated set of text, JSON data, and SVG art assets.

## Contents

- `index.html` — Homepage linking to all assets with short explanations.
- `ashravan.txt` — A 300–400 word original short story about Ashravan after Shai restores him, culminating in a dramatic climax.
- `dilemma.json` — Ethical choices for an autonomous vehicle in two scenarios.
- `about.md` — Exactly three words describing the author.
- `pelican.svg` — A valid SVG of a pelican riding a bicycle (includes an embedded “LLM rating”).
- `restaurant.json` — A recommendation for a great restaurant in Delhi with coordinates and what to eat.
- `prediction.json` — A reasonable forecast of the Federal Funds rate by December 2025.
- `uid.txt` — The provided UID, copied verbatim.
- `LICENSE` — MIT License.

## Setup (GitHub Pages)

1. Create a new public GitHub repository and add these files to the root.
2. Commit and push to the `main` branch.
3. In your repository settings, enable GitHub Pages:
   - Go to Settings → Pages.
   - Source: Deploy from a branch.
   - Branch: `main` / root.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

No build steps are required. Everything is pure static content.

## Usage

- Visit the homepage to navigate to each artifact.
- Right-click `pelican.svg` and choose “Save image as…” if you want a copy of the illustration.
- The JSON files are human-readable and can be fetched programmatically for demos or tests.

## Code/Content Notes

- Accessibility: The SVG includes a `<title>` and `<desc>` for assistive technologies.
- Validation: The SVG uses simple primitives to remain broadly compatible with browsers.
- Ethics JSON: Booleans are true JSON booleans (`true`/`false`), and the schema matches the spec in the brief.
- Story length: `ashravan.txt` is within 300–400 words and climaxes with a decisive confrontation.
- Rating metadata: `pelican.svg` includes an explicit LLM rating both as a comment and in `<metadata>`.

## Contact

For questions, you can reach the maintainer at: 22f3002460@ds.study.iitm.ac.in

## License

This project is licensed under the MIT License — see `LICENSE` for details.
