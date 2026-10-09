# SDE Mission Control

A responsive 90-day software-development interview preparation dashboard built with plain HTML, CSS, and vanilla JavaScript.

## Features

- Day-by-day study plan across 13 weeks, with six study days and a weekly recovery day
- DSA tracker based on Striver's A2Z topics, plus a problem log
- Checklists for a Spring Boot microservices Quiz Platform and an AI-enabled e-commerce backend
- Job application pipeline with status and follow-up tracking
- Weekly review, revision prompts, and progress indicators
- JSON backup import/export and applications CSV export
- Responsive layout with light/dark color-scheme support

## Run locally

No build tools or package installation are required.

1. Clone or download this repository.
2. Open `index.html` in a modern browser.

For a local web server, run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Data and privacy

Progress is stored in the browser's `localStorage`. It does not automatically sync between browsers or devices. Use **Export JSON backup** to keep a backup, and avoid using shared/public computers for personal job-search records.

## Deploy with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then save.
4. Wait for GitHub Pages to finish publishing. The URL is normally `https://lokeshkumarrongali.github.io/sde-mission-control/`.

The public page is available only after Pages is enabled and the deployment succeeds.

## Technology

- HTML5
- CSS (responsive layout and color-scheme variables)
- Vanilla JavaScript
- Browser `localStorage` and File/Blob APIs

## Notes

This is a client-side planning tool. Checklist completion is a personal tracking aid, not a measurement of interview readiness by itself. Adjust the daily workload to your schedule and use actual practice results to assess progress.
