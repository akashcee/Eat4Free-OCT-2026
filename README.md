# Discover Resorts — Room Command Center

A static, responsive dashboard for Discover Resorts Ltd. It includes room categories, room video links, the Eat4Free offer, tariff tables, booking policies, and an October 2026 activity calendar.

## Project structure

```text
discover-resorts-room-command-center/
├── index.html
├── assets/
│   ├── style.css
│   └── script.js
├── README.md
├── .gitignore
└── LICENSE
```

## Run locally

Open `index.html` in a browser. No build step or package installation is required.

The page loads Google Fonts from the internet; if unavailable, it falls back to system fonts.

## Deploy with GitHub Pages

1. Create a new repository on GitHub.
2. Upload the contents of this folder (upload `index.html` and the `assets` folder, not just the ZIP file).
3. Open **Settings → Pages**.
4. Under the build/deployment settings, choose **Deploy from a branch**.
5. Select your default branch (usually `main`) and the root folder (`/`), then save.
6. Wait for the Pages deployment to finish. GitHub will show the published URL in the Pages section.

## Notes

- This project is a static website and does not require a backend or environment variables.
- Room videos open on YouTube.
- Copy buttons use the browser clipboard API with a fallback.
- The offer and activity information are preserved from the supplied HTML. Check dates and tariffs before publishing because the offer validity shown in the dashboard is 11–20 October 2026.
