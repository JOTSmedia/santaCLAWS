# SANTA CLAWS — Original series website

Static HTML/CSS/JS site, ready for GitHub Pages.

## Deploy
Upload `index.html` and the `assets` folder to the root of your GitHub repository. In Settings > Pages, deploy from the main branch / root.

## Preview locally
From this folder run `python3 -m http.server 8000` and visit http://localhost:8000.

## Notes
- The loading screen and hero both use the original cinematic Santa Claws illustration, with CSS-animated glow effects.
- The notify form is not connected to a mailing service.
- Background music streams from YouTube ("3 Hours of Scary, Ominous & Creepy Horror Music" by Spooky Night) and starts on the first click/tap; the MUSIC pill in the nav toggles it. It only plays when the site is served over https (e.g. GitHub Pages), not when index.html is opened directly from disk.
- If no one interacts, the page gently auto-scrolls after the intro (speed set by SPEED in the script); any wheel, touch, click or key press pauses it for 8 seconds.
- Includes reduced-motion handling (no auto-scroll, minimal animation).
