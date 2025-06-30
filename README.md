# Stellar Voronoi - Celestial Cartography

**Stellar Voronoi** is an interactive star map that visualizes the night sky using data from the **Yale Bright Star Catalog**. This project lets you explore stars and their relationships through a **Voronoi diagram**, offering a unique and engaging way to view celestial objects.
https://sumeghp.github.io/starry-night/
---

## Features

- **Search by HR Number**: Look up specific stars using their Harvard Revised (HR) catalog number. Once found, the star is highlighted, and detailed information (name, spectral type, magnitude) is shown in a tooltip.
- **Interactive Tooltips**: Hover over stars to learn more about them, including their spectral type, brightness, and HR number.
- **Zoom and Pan**: Easily explore the star map with mouse-based zooming (1x to 10x) and panning.
- **Dynamic Voronoi Diagram**: Each star is surrounded by a Voronoi cell, making it easier to interact with individual stars.

---

## How It Works

1. The star data is fetched from the **Yale Bright Star Catalog**, which provides information like:
   - Right Ascension (RA)
   - Declination (Dec)
   - Spectral type
   - Magnitude
2. Stars with a **visual magnitude below 6.5** (visible to the naked eye) are plotted on the map.
3. A **Voronoi diagram** is generated to divide the space into cells, with each cell corresponding to a star.

---
