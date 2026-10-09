# SANTA CLAWS — Original series website

Static HTML/CSS/JS site, ready for GitHub Pages.

## Deploy
Upload `index.html` and the `assets` folder to the root of your GitHub repository. In Settings > Pages, deploy from the main branch / root.

## Preview locally
From this folder run `python3 -m http.server 8000` and visit http://localhost:8000.

## Notes
- The loading screen and hero both use the original cinematic Santa Claws illustration, with CSS-animated glow effects.
- The notify form is not connected to a mailing service.
- Background music streams from YouTube ("3 Hours of Scary, Ominous & Creepy Horror Music" by Spooky Night). It tries to start with sound as soon as the page opens; where the browser blocks that, it plays muted and fades in on the first tap, click or key press. The MUSIC pill in the nav turns it on/off. It only plays when the site is served over https (e.g. GitHub Pages), not from a local file.
- If no one interacts, the page auto-scrolls after the intro: 22% speed while a section is on screen, speeding up between sections and easing back (READ / TRAVEL in the script). Any wheel, touch, click or key press pauses it for 8 seconds.
- Includes reduced-motion handling (no auto-scroll, minimal animation).
