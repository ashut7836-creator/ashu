# Space Explorer

An original, responsive 3D solar-system website.

## Explore

- Interactive 3D Sun and eight planets.
- Drag to orbit the camera; scroll or pinch to zoom.
- Tap a planet or use the planet selector to open its science guide.
- Planet facts, metric cards, atmosphere, surface/composition, orbit, moons/rings, exploration and quick facts.
- Pause/resume motion and reset camera controls.
- Switch to NASA Eyes on the Solar System, embedded in the page.

## Run locally

Open `index.html` in a modern browser with an internet connection. Three.js is loaded from jsDelivr. NASA Eyes loads from NASA's own website.

## Publish with GitHub Pages

1. Open the repository's **Settings**.
2. Select **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then save.
5. After GitHub finishes publishing, open the site URL shown in the Pages settings.

GitHub's current instructions: https://docs.github.com/en/pages/quickstart

## NASA experience

The NASA Eyes viewer is a separate NASA/JPL web application displayed in an iframe, following NASA's published embed guidance. Its controls and object selection remain inside NASA's viewer; the planet information panels on this site belong to Space Explorer.

NASA guidance: https://science.nasa.gov/eyes/museums/

## Notes

- No website-builder badge or vendor branding is included in this source.
- The custom solar-system model uses illustrative sizes and orbital spacing, not scale distances.
- This is a static site and does not require an API key, database, login, or paid backend.
