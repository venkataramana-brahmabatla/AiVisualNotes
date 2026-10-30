# AI Visual Notes

AI Visual Notes is an interactive study library for learning AI engineering concepts and preparing for technical interviews. It brings together 16 visual lesson posters and scenario-based interview questions in one searchable, mobile-friendly site.

## What’s included

- Lessons covering LLMs, context engineering, RAG, agents, MCP, multimodal AI, evaluation, safety, and system design.
- Search and category filters to find topics.
- Full-size poster viewing with zoom controls.
- Interview questions with explanations, production scenarios, pseudocode, and senior engineering notes.
- Standalone poster images in `assets/posters/` for easier maintenance.

## Run locally

Requires Python 3.12 or newer. From this directory, run:

```sh
python serve.py
```

Open <http://127.0.0.1:8000> in your browser and stop the server with `Ctrl+C`.

Python is only used for local preview. The site itself is static HTML, CSS, and JavaScript, so it can be hosted on GitHub Pages without a Python runtime or external dependencies.

## Publish with GitHub Pages

Push the project to GitHub, then open the repository’s **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and `/(root)` folder, and save. GitHub will show the published site URL in the Pages settings.

## Project files

```text
.
├── index.html
├── styles.css
├── app.js
├── serve.py
└── assets/
    └── posters/
```
