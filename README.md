# Abdirahman Abdiaziz — portfolio

Data and insight analyst. SQL, Tableau and operational performance reporting.

Single static page. No build step, no dependencies, no framework — `index.html` is the whole site.

---

## Live

Once GitHub Pages is enabled on `main` / root:

```
(https://abdiaziz96.github.io/abdiaziz-portfolio/)```

## What's here

| File | |
|---|---|
| `index.html` | the portfolio — hero, about, skills, work, downloads, contact |
| `Abdirahman-Abdiaziz-CV.pdf` | two-page CV, downloadable from the page |
| `Abdirahman-Abdiaziz-Cover-Letter.pdf` | one-page cover letter |
| `.nojekyll` | tells GitHub Pages to skip Jekyll processing |

## Design

Steel blue on off-white, Poppins throughout. The hero has two looping rings — a 650px one pulsing at
2s and a 200px one pinging at 1s — with a typewriter role line and a blinking cursor at 0.8s. Motion
is CSS keyframes only, and it all switches off under `prefers-reduced-motion`.

## Editing

Everything is in one file. Colours are CSS custom properties at the top:

```css
--steel:#4682B4;   --steel-deep:#3a6e97;   --steel-wash:#eaf1f7;
--bg:#fafafa;      --dark:#0B111E;         --dark-card:#111A2E;
```

The typewriter phrases are in the `<script>` block at the bottom.

## Built with AI assistance

Developed with an AI pair programmer as a deliberate working method, and I can explain every query
and design decision in it.
