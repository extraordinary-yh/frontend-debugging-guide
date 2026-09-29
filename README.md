# The Slow Dashboard

An interactive frontend production-debugging guide built around a fictional commerce dashboard incident.

**[Open the live guide](https://extraordinary-yh.github.io/frontend-debugging-guide/)**

Six sections connect customer impact, field metrics, network/backend timing, browser work, controlled experiments and recovery. All 27 demonstrations have instructions, named states, local playback/reset and directly manipulable controls. Includes real DOM filtering, search, geometry and a 10,000-row versus virtualized-list experiment.

The incident, timings and traces are illustrative. Requests and backend operations are local simulations; no production service or database is contacted. The project was developed with AI-assisted coding and iterative editorial review. It is an educational artifact, not a claim of an observed production incident.

## Hosting

This repository publishes `index.html` from the root of `main` through GitHub Pages. Hosting uses GitHub's free public-repository option and its supplied HTTPS domain. Visitors do not need an account.

The page is self-contained: HTML, CSS, JavaScript and lesson data are embedded in `index.html`. It has no backend, API keys, external runtime dependencies or analytics. Practice notes stay in the browser tab until downloaded. GitHub Pages' own hosting/privacy policies still apply.

## Update or run locally

Replace `index.html` with a new built version and commit to `main`; GitHub Pages redeploys it. You can also download `index.html` and open it directly in a browser. The source code for every demonstration is embedded in the file.

Official documentation references are linked within the guide. No custom domain is required.
