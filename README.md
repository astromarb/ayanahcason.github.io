# Ayanah L Cason

Personal site for Ayanah L Cason — astrophysicist and computational scientist
exploring how metallicity shapes the evolution of stellar systems.

A single-page, dependency-free static site (HTML, CSS, vanilla JS) deployed via
GitHub Pages. Publications are pulled live from Semantic Scholar with a static
fallback.

## Structure

```
index.html    Markup for the page (hero, about/solar-system, journey, publications, contact)
styles.css    All styling
app.js         Interactions: nav, orbital animations, scroll effects, publication fetch
photos/        Images referenced by the page
```

## Local preview

```
python3 -m http.server 8000
# then open http://localhost:8000
```

## Photos

The page references the following files in `photos/`:

| File | Used for |
| --- | --- |
| `prof.jpg` | Hero + about portrait |
| `aliza.jpg` | Journey: community |
| `presenting.jpg` | Journey + research callout |
| `my-story-outdoors.png` | About panel — story |
| `research-aas.png` | About panel — research |
| `physics-metallicity-blackboard.png` | Journey: the beginning |
| `lanl-logo.png` | Journey: Los Alamos |
| `fisk-vanderbilt-bridge-logo.jpg` | Journey: the bridge |
| `unlv-logo.png` | Journey: undergraduate |
| `intergalactic-bg.png` | Background nebula |
