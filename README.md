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


## Google Search setup

The repository includes a sitemap at:
`https://ashut7836-creator.github.io/ashu/sitemap.xml`

To ask Google to crawl the site:

1. Open Google Search Console: https://search.google.com/search-console
2. Add a **URL-prefix** property: `https://ashut7836-creator.github.io/ashu/`
3. Choose the **HTML tag** verification method. Copy the exact `google-site-verification` meta tag from Google Search Console.
4. Add that meta tag inside the `<head>` of `index.html`, commit the change, wait for GitHub Pages to publish, then click **Verify** in Search Console.
5. In Search Console, open **Sitemaps** and submit `sitemap.xml`.
6. Use **URL inspection** for the home page and important planet guide URLs, then request indexing.

Google's crawling and indexing are not guaranteed or instant. A sitemap helps discovery but does not guarantee indexing or rankings. Google may take days or weeks to crawl/reprocess changed pages.

Useful official documentation:
- Add a property: https://support.google.com/webmasters/answer/34592
- Verify with an HTML tag: https://support.google.com/webmasters/answer/9008080
- Submit a sitemap: https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap
- Request recrawling: https://developers.google.com/search/docs/crawling-indexing/ask-google-to-recrawl

Note: this GitHub Pages project currently lives at the `/ashu/` subpath. Google site-name selection has limits for subdirectory URLs; a dedicated domain or root-level site may offer a cleaner branded search identity.
