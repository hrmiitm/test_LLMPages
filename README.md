# LLMPages

A tiny, static web application that publishes a handful of creative and data artifacts (text, JSON, SVG) suitable for GitHub Pages.

Live demo: When pushed to a public repository with GitHub Pages enabled, open `https://<your-username>.github.io/<your-repo>/` to view the site.

## Contents

- `index.html` – Homepage linking to every artifact with brief descriptions.
- `ashravan.txt` – 300–400 word short story about what happens to Ashravan after Shai restores him, culminating in a dramatic decision.
- `dilemma.json` – Autonomous vehicle moral dilemma with explicit swerve decisions and rationales.
- `about.md` – Exactly three words.
- `pelican.svg` – Valid SVG illustration of a pelican riding a bicycle, with an embedded LLM rating.
- `restaurant.json` – Delhi restaurant recommendation with coordinates and what to eat.
- `prediction.json` – Reasonable forecast for the U.S. Fed Funds rate by December 2025.
- `uid.txt` – Provided UID file, unmodified.
- `LICENSE` – MIT License.
- `README.md` – This file.

## Setup (GitHub Pages)

1. Create a new public GitHub repository and add all the files in this project to the root.
2. Commit and push to the `main` branch.
3. In the repository, go to Settings → Pages.
4. Under “Build and deployment”, set Source to “Deploy from a branch”, pick `main`, and folder `/root`.
5. Click Save. After a minute, your site will be live.

No build steps are required; it’s a static site.

## Usage

- Visit the homepage (`index.html`) and click any card to open the corresponding artifact.
- JSON files can be viewed directly in the browser or fetched by other tools.
- The SVG contains an embedded machine rating in a comment and metadata block.

## Code & Structure

- The site is intentionally minimal: a single HTML file with built-in CSS for fast loads and easy hosting on GitHub Pages.
- Accessibility: the SVG includes a `<title>` and `aria-label`.
- Portability: no external dependencies or scripts.

## Tests & Checks

This project is designed so automated or manual checks can verify:
- Every required file exists at the repository root.
- `uid.txt` exactly matches the provided content.
- `LICENSE` contains the full MIT License text.
- `index.html` links to all required files.
- `ashravan.txt` is 300–400 words and builds to a dramatic climax.
- `dilemma.json` matches the described scenario and is valid JSON.
- `about.md` contains exactly three words.
- `pelican.svg` is valid SVG and is rated by an LLM (see comment/metadata).
- `restaurant.json` contains consistent Delhi data.
- `prediction.json` includes a plausible rate and supporting reasoning.

## License

This project is released under the MIT License. See `LICENSE` for details.

## Contact

For questions or improvements, please open an issue or contact: 22f3002460@ds.study.iitm.ac.in
