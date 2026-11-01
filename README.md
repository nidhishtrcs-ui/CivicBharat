# CivicBharat

A single-page civic complaint register demo inspired by a Nagar Sahayak workflow. It includes a citizen sign-in flow, officer dashboard, and admin overview panel in one static HTML file.

## Run locally

From the project root:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deploy to Vercel

This project is configured as a static Vercel app via the included `vercel.json` file. To deploy:

1. Push this folder to a GitHub repository.
2. Import the repository in Vercel.
3. Select the project root as the app directory.
4. Vercel will serve the static `index.html` page automatically.

## Project files

- `index.html` — full UI and in-browser logic
- `vercel.json` — Vercel route configuration for a static page
