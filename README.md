# Aizen Thaufeek — Cradle Ceremony

A static invitation website for Muhammed Aizen Thaufeek's cradle ceremony.

## Local preview

```sh
python3 -m http.server 4173 --directory dist
```

Then open <http://localhost:4173>.

## Deployment

Vercel serves the static site from `dist/` as configured in `vercel.json`.
Pushing to `main` triggers the connected Vercel project and the GitHub Pages workflow.
