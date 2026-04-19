# Data Science Portfolio

A static HTML/CSS portfolio website showcasing data science projects.

## Project Structure

- `index.html` — Main portfolio landing page
- `autoprice.html` — Detailed page for the Automobile Price Prediction project (includes an interactive JS-based price predictor)

## Tech Stack

- Pure HTML5 and CSS3 (no build system or package manager)
- Vanilla JavaScript for interactive UI elements
- Google Fonts (Syne, DM Sans, DM Mono) via CDN

## Running the App

The app is served using Python's built-in HTTP server on port 5000:

```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment

Configured as a **static** deployment with the root directory (`.`) as the public directory.
