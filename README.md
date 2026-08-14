# MoneyPort

Cross-border currency payments — a Tilda landing page.

**Live:** https://erix319.github.io/tilda-moneyport/

## About

Service page for a cross-border B2B payments broker that matches clients with vetted payment agents. Settlement in USD, EUR, CNY, AED and crypto, with a process walkthrough, trust signals, an FAQ accordion and a callback form.

Interface language is Russian.

## Stack

- **Tilda** — Zero Block layout, built from the platform's page builder
- **Static site** — plain HTML, CSS and JavaScript, no build step and no server
- Tilda's runtime bundle: grid, lazy-loading, forms, menu and animation modules

## Running locally

Any static file server works. From the repository root:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

Opening `index.html` straight off the filesystem mostly works too, but a
server is closer to how it is actually deployed.

## Layout

```
index.html   the page itself
assets/      34 files — styles, scripts, images and fonts
```
