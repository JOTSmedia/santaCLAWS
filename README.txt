SANTA CLAWS — Official Series Landing Page

GITHUB PAGES DEPLOYMENT
1. Unzip santa-claws-website.zip.
2. Upload the CONTENTS of santa-claws-site/ (index.html and assets/) to the root of your GitHub repository.
3. Go to repository Settings > Pages.
4. Select Deploy from a branch > main > /(root) > Save.
5. Your site should be available at https://YOUR_USERNAME.github.io/YOUR_REPO/

LOCAL PREVIEW
Open index.html in Chrome, Safari, or Firefox. For the most reliable local preview, run
  python3 -m http.server 8000
inside the santa-claws-site directory, then visit http://localhost:8000/

FEATURES
- Military-style loading screen
- Dramatic animated bionic claw breach / screen-split reveal
- Snow, grain, red atmospheric lighting, slow hero zoom
- Replay Intro button
- Sound toggle for synthesized ambient drone (user interaction required)
- Responsive story, case-file, origin, and signup sections
- Accessible reduced-motion fallback

NOTES
- Mailing-list form is a demo; connect your email service before launch.
- Sound starts only after a click because browsers block unsolicited audio.
- No framework or build process required. Google Fonts requires an internet connection.
