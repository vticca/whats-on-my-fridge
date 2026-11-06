# what's on my fridge

A browser-only fridge magnet studio. Add alphabet and illustrated magnets, upload a photo, arrange and rotate pieces, attach notes or links, and share a visitor view.

## Run locally

Open index.html in a browser, or serve this folder with any static web server. There is no build step or package dependency.

## GitHub Pages

The included GitHub Actions workflow publishes the repository root after a push to main. In repository settings, choose Pages > Build and deployment > GitHub Actions if Pages is not already configured.

## Data

The editor stores its current fridge in that browser's local storage. Shared links encode a snapshot in the URL fragment. Uploaded pictures are resized in the browser before being stored; they are not uploaded to a server.
