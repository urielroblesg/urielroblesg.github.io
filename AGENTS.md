# AGENTS.md

## Project

Static HTML/CSS site (GitHub Pages). No build system, no tests, no linting, no package manager. Open HTML files directly in a browser.

## Files

- `proyecto.html` — main project (exercises 2-8), linked to `estilos.css`
- `Ejercicio1.html` — standalone exercise 1 (inline + internal + external CSS demo)
- `estilos.css` — shared stylesheet for all exercises
- `Tarea_2_CSS.md` — full assignment instructions

## CSS conventions

- `estilos.css` is organized by exercise sections: `/* ===== Ejercicio N: Title ===== */`
- New rules go in the matching section. Never delete previous exercise rules — this is incremental by design.
- Theme uses CSS custom properties (`:root` vars) for a coffee color palette.
- Google Fonts loaded in HTML `<head>`: Poppins (body) and Merriweather (headings).

## Editing rules

- Do not reorder or restructure HTML tags in `proyecto.html` — only add attributes (`class`, `id`, `href`, etc.) when an exercise requires it.
- Do not use `lorem ipsum` — content must be real text about specialty coffee.
