# software-98.github.io

The Software 98 developer website, served by GitHub Pages at
https://software-98.github.io.

- `app-ads.txt`: the authorised ad sellers for the AdMob account. AdMob reads it
  from the root of the developer website listed on Google Play, so it must stay
  at the root of this site.
- `index.html`: the site, one page: the logo as a turning 3D title over a dark
  wall of faint logos, then shelves of jewel cases, one per game or app.
- `assets/`: the logo (`logo.webp`, cut from the master `software_98_logo.png`;
  `logo-tile.webp`, the background), the covers, FoodTrax's icon, the pixel
  cursors, and `og.png`, the picture shown when the site is shared.
- `favicon.png`, `apple-touch-icon.png`: the logo's "98" on a black tile.

To add a game or app, copy one `<li>` in its shelf and change the cover, the
spine's platform, the name, the price and the link. Covers are 315 x 250, as
on itch.io.
