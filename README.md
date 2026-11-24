# software-98.github.io

The Software 98 developer website, served by GitHub Pages at
https://software-98.github.io.

- `app-ads.txt`: the authorised ad sellers for the AdMob account. AdMob reads it
  from the root of the developer website listed on Google Play, so it must stay
  at the root of this site.
- `index.html`: the site, one page. The logo is a solid drawn with WebGL
  (three.js r128): its exact outline, traced from the artwork into 164 points
  (`OUTLINE` in the page), extruded, with the artwork on its face and chrome
  sides, the back printed from `assets/logo-back.webp`: the artwork mirrored, so
  its edges fit the outline from behind, with the lettering put back to read the
  right way. It turns slowly all the
  way round, drawn at 70% resolution in 32 colours (`PALETTE`: 24 from the
  artwork, 8 for the chrome). Browsers without WebGL see
  the flat logo. Below it, shelves of cases, each a six-sided
  CSS 3D box (jewel cases for apps, portrait keep cases for PC games).
- `assets/`: the logo (`logo.webp`, cut from the master `software_98_logo.png`;
  `logo-tile.webp`, the background), the covers, FoodTrax's icon, the pixel
  cursors, and `og.png`, the picture shown when the site is shared.
- `favicon.png`, `apple-touch-icon.png`: the logo's "98" on a black tile.

To add a game or app, copy one `<li>` in its shelf and change the cover, the
spine's platform, the name, the price and the link. Jewel-case covers are
315 x 250; a PC game's box art is portrait (add `tall` to its `box`). Give a
changed image a new filename: Pages lets browsers keep images for 10 minutes.

## Covers

App covers are drawn in the page itself (`.cover-app`): a black strip naming the
platform and kind of app, then the app's icon over its name on a plain
background. To add an app, copy one and change its `--bg`, strip text, icon
(256 x 256 in `assets/`) and name.

`art-source/covers.html` keeps an earlier, unused style for the two Baccarat
apps: late-90s casino CD-ROM box art. To use it, open it from a local server at
the repository root and screenshot each `.cover` at 2x into `assets/`.
