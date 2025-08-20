# Travel Quest (Indigo/600)

Arcade-style browser minigame with coupons. This build uses the **Indigo/600** color theme and renames **Mission → Travel**.

## Run locally
Just open `index.html` in any modern browser.

## Deploy on GitHub Pages
1. Create a new GitHub repo (public is fine).
2. Upload the two files: `index.html` and `README.md` (or push via Git).
3. In the repo: **Settings → Pages → Build and deployment**  
   - *Source*: **Deploy from a branch**  
   - *Branch*: **main** (or `master`) and root (`/`)
4. Wait a minute and open the Pages URL shown at the top of that section.

> Tip: No build tools are needed — it's a static site.

## Deploy on Render (Static Site)
1. Create a new Static Site on Render.
2. Connect the GitHub repo.
3. **Build Command**: *(leave empty)*  
   **Publish Directory**: `/`
4. Click Deploy.

## Notes
- The world map image is loaded from Wikipedia via HTTPS and will work on both GitHub Pages and Render.
- If you want to self-host the map asset, download the SVG and replace the `DEFAULT_SVG` URL in `index.html`.

— Generated 2025-08-20
