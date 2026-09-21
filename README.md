# Developer Skill Tree

An interactive, bilingual skill tree for developers. Choose a path, unlock topics with short quizzes, keep progress in the browser, and share a build with a link.

**[Open the live demo →](https://dev-skill-tree.pages.dev/)**

The project is intentionally lightweight: the complete experience currently lives in a single HTML file and runs without a framework or build step.

## Features

- Interactive skill trees with prerequisite-based progression
- Short quizzes for unlocking new topics
- English and Ukrainian interface
- Progress saved locally in the browser
- Shareable builds encoded in the URL
- Responsive, dependency-free frontend

## Run locally

```bash
git clone https://github.com/Barik766/dev-skill-tree.git
cd dev-skill-tree/skill-tree
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

The production build is hosted on Cloudflare Pages:

- **Live:** https://dev-skill-tree.pages.dev/
- Deploy the `skill-tree/` directory as the site output.

## Suggested next steps

- Extract content data from the HTML into JSON modules
- Add keyboard navigation and visible focus styles
- Add automated HTML/accessibility checks
- Add a social preview image and screenshots
- Document how new paths, topics, and quiz questions are added

## License

No license is currently declared. Add one before inviting external contributions or reuse.
