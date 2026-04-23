# Copilot instructions for this repository

## Build, test, and lint

This repository currently has no package manager setup and no automated build, test, or lint scripts.

- **Run locally:** open `index.html` directly in a browser, or use VS Code Live Server (as described in `README.md`).
- **Single test:** not applicable (no test framework is configured yet).

## High-level architecture

The current codebase is a static client-side site:

- `index.html` is the single application entry point and contains all rendered content.
- UI styling and behavior come from Bootstrap loaded via CDN in `index.html` (no local dependency installation).
- Local static assets are referenced by relative path (currently `img/Bart.jpg`).
- `css/` and `js/` directories exist but are currently empty, so page structure, styles, and behavior are not yet split into separate layers.

## Key conventions in this codebase

- Keep content and labels in **Spanish** to stay consistent with existing UI and documentation.
- Prefer **Bootstrap utility/classes via CDN** for layout and styling before introducing local tooling.
- Use simple relative asset paths from the repository root (example: `img/...`) to keep the project runnable by just opening `index.html`.
- `README.md` describes a broader course-oriented structure (`tp*`, `proyectos`) that may be introduced later; align new folders with that naming when expanding the repo.

##Recomendaciones
- Cada vez que ingreses un nuevo codigo, inserta un comentario en español que explique las etiquetas utilizadas, para que el código sea más fácil de entender para los estudiantes.
- Los ejemplos y los contenidos en gerneral necesito que esten en español 