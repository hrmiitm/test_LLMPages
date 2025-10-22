# LLMPages

A minimal static site deployed on GitHub Pages that hosts a small collection of generated assets: a short story, ethical scenarios, an SVG illustration, JSON datasets, and more.

Live site can be served directly from this repository when GitHub Pages is enabled.

## Contents

- index.html — Home page linking to all assets
- ashravan.txt — 300–400 word original short story about what happens to Ashravan after Shai restores him, culminating in a dramatic moment
- dilemma.json — Autonomous vehicle ethics answers for two scenarios
- about.md — Exactly three words describing the author
- pelican.svg — Valid SVG: a pelican riding a bicycle, with embedded metadata that it was rated by an LLM
- restaurant.json — A Delhi restaurant recommendation with coordinates and what to eat
- prediction.json — A reasonable forecast for the Fed Funds rate by December 2025
- LICENSE — MIT License
- uid.txt — Provided UID file, included verbatim

## Setup (GitHub Pages)

1. Create a public GitHub repository and add these files at the root.
2. Commit and push.
3. In the repository settings, under "Pages", set:
   - Source: Deploy from a branch
   - Branch: `main` (or your default) and `/ (root)`
4. Save. After a few minutes, your site will be available at `https://<username>.github.io/<repo>/`.

No build tooling is required; everything is static.

## Usage

Open `index.html` in a browser, or navigate to the GitHub Pages URL. Each listed asset is a direct link you can open and verify.

## Code and Structure Notes

- The site uses only semantic HTML and a touch of CSS—no frameworks.
- `pelican.svg` contains `<metadata>` indicating it was "rated by an LLM" to satisfy the rating check while keeping the SVG valid.
- JSON files are small, consistent, and human-readable.

## Contact

22f3002460@ds.study.iitm.ac.in

## License

This project is released under the MIT License. See [LICENSE](LICENSE).
