TICKLE MACHINE — WEBSITE

CONTENTS
- index.html: home page
- games.html: three-column games catalogue
- gangsta-style.html: dedicated page for the debut game
- about.html: studio and team page
- styles.css: layout, responsive styles, animation and colour system
- script.js: mobile menu, scroll reveals, header effect and current year
- assets/: images used by the website, including the transparent Tickle Machine logo (tickle-machine-logo.png)

HOW TO PREVIEW
1. Extract the ZIP file to a folder.
2. Open index.html in a browser.
3. For local testing, no installation or build tools are required.

HOW TO PUBLISH
Upload the entire contents of this folder, keeping the file and assets structure, to your static hosting provider (for example GitHub Pages, Netlify or your own hosting).

HOW TO ADD A GAME
1. Add the new game artwork to assets/.
2. In games.html, duplicate the first <article class="game-card reveal"> block inside .games-grid and change its image, title, summary, status and link.
3. Create a new page by copying gangsta-style.html and updating its content, metadata and images.
4. If you want the new game on the homepage, duplicate the <article class="game-feature reveal"> block in index.html and update its details.

EDITING BRAND / SOCIALS
- The shared header and footer are repeated in each HTML page; update links on all four pages if social account URLs change.
- The contact email is contact.ticklemachine@gmail.com.
- The Games grid includes two clearly labelled future-project placeholders; replace them with real titles when ready.
- The current release copy says “Planned release · November 12” without a year because the release year was not supplied in the brief. Update it if needed.

NOTES
- The mobile navigation opens as a glass-style dropdown directly under the header; links and social icons are visible immediately, and tapping outside or pressing Escape closes it.
- The website uses no external libraries, web fonts or paid services.
- Animations respect the user’s reduced-motion preference.
- Social links open in a new tab.
- The Gangsta Style logo is now a tightly cropped transparent PNG. Keep its natural aspect ratio (width with height:auto) and avoid forced-height containers or opaque white backing panels when reusing it.


BRAND LOGO
- The header uses assets/tickle-machine-logo.png, the transparent logo supplied by the studio.
- Keep width/height proportional and do not apply mix-blend-mode: multiply; it can make the white parts of the logo disappear against the light header.
