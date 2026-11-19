# Lifeline

A responsive, buildless blood donation prototype with donor and hospital flows. Uses fictional records only. No authentication, backend, external messaging, phone numbers or email.

## Preview locally

Clone this repository, then run `npm run dev` and open http://127.0.0.1:4173. Node.js is required; no dependency installation is needed. Run `npm run check` for JavaScript syntax validation.

For a preview without a server, open `dist/preview.html` in Chrome, Edge, or Firefox. It contains the styles and JavaScript in one file. The editable source lives in `dist/index.html`, `dist/styles.css`, and `dist/app.js`.

## Optional deployment

The repository includes `vercel.json` with `dist` as the output directory. No website deployment is performed by uploading this repository.

Donors can search six centers, apply, and receive simulated approval after five seconds. Hospitals enter six requirements and see five matching fictional profiles with the default quantity. Higher quantities intentionally demonstrate smaller result sets and an empty state. Profiles show the center coordination desk, sample address, blood type and request confirmation.

The demo does not persist medical data. Navigating away and returning within the same tab keeps an application in memory; reloading resets the session. Fonts use Google Fonts with local sans-serif fallbacks. All UI icons are inline SVG.
