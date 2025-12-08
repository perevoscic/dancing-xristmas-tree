# Dancing Xristmas Tree (Web AR)

Open `index.html` through a local server to see a marker-based AR Christmas tree built with A-Frame + AR.js.

## Quick start
- Install any static server (if you have Node): `npx serve .`
- Or with Python: `python -m http.server 8080`
- Visit the served URL on your phone; allow camera access.
- Point the camera at a Hiro marker: https://raw.githubusercontent.com/AR-js-org/AR.js/master/aframe/examples/marker-training/examples/hiro.png (print it or show it on another screen).

You should see a blinking, gift-wrapped tree sitting on the marker.

## Deploy to GitHub Pages (free)
1) Create a public repo (example: `ar-xmas-tree`) on GitHub.  
2) Add `index.html`, your `pattern-*.patt`, and the matching marker preview PNG to the repo root; commit and push to `main`.  
3) In the repo: Settings → Pages → Source = `Deploy from a branch`, Branch = `main`, Folder = `/ (root)`. Save.  
4) Wait ~1 minute; your site will be live at `https://<your-user>.github.io/ar-xmas-tree`.  
5) Test on phone: open that URL (use HTTPS), allow camera, and show your printed marker.

## Using your custom marker
- Pattern file: `pattern-2.patt`
- Preview image to print/show: `2.png` (alias: `pattern-2.png`) — this is the marker the camera should see
- Keep both files in the repo root (or same folder as `index.html`) so the AR marker loads.
