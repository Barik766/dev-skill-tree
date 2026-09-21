# Developer Skill Tree

An interactive, bilingual skill-tree for developers. Choose a path, unlock topics by completing short quizzes, keep progress in the browser, and share a build with a link.

The project is intentionally lightweight: the complete experience currently lives in a single HTML file and runs without a framework or build step.

## Features

- Interactive skill trees with prerequisite-based progression
- Short quizzes for unlocking new topics
- English and Ukrainian interface
- Progress saved locally in the browser
- Shareable builds encoded in the URL
- Responsive, dependency-free frontend

## Run locally

No installation is required.

```bash
git clone https://github.com/Barik766/dev-skill-tree.git
cd dev-skill-tree/skill-tree
```

Open `index.html` directly, or serve the folder locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

```text
dev-skill-tree/
└── skill-tree/
    └── index.html   # UI, content, styles, and application logic
```

## Deployment

GitHub Pages cannot publish this repository correctly from the current nested folder using the standard branch settings. Use one of these options:

1. Move `skill-tree/index.html` to the repository root and publish from `main / (root)`.
2. Move the site into a `docs/` directory and publish from `main /docs`.
3. Add a GitHub Actions workflow that uploads `skill-tree/` as the Pages artifact.

After deployment, add the live URL to the repository's **About** section.

## Suggested next steps

- Extract content data from the HTML into JSON modules
- Add keyboard navigation and visible focus styles
- Add automated HTML/accessibility checks in GitHub Actions
- Add a social preview image and screenshots to this README
- Document how new paths, topics, and quiz questions are added

## License

No license is currently declared. Add one before inviting external contributions or reuse.
