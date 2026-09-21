# Galilee to Jerusalem

A devotional field guide for a ten-day Holy Land pilgrimage, 9–18 November 2026.

Thirty-five stops across ten days. Each one gives you where you are, why it
matters, the passages to read (ESV references), what you are actually standing
in, and one question to carry out of the place. Also included: a seven-week
reading plan ordered to the route, four maps, and a historical background
section covering the archaeological layers and the names you will hear guides
use.

## Hosting

`index.html` is the whole site. It has no build step and no dependencies to
install — all CSS, JavaScript and maps are inline. The only external request is
to Google Fonts, so the page keeps working offline once it has loaded.

To publish on GitHub Pages: commit `index.html` to the repository root, then go
to **Settings → Pages** and set Source to **Deploy from a branch**, branch
**main**, folder **/ (root)**. The site appears at
`https://<username>.github.io/<repository>/` within a minute or so.

No `.nojekyll` file is needed, since nothing here is named with a leading
underscore.

## Notes

- Reading-plan checkboxes are stored in the visitor's own browser
  (`localStorage`, key `gtj-reading-v1`). They never leave the device and are
  not shared between devices or people.
- The page carries `<meta name="robots" content="noindex">`. On a public
  repository the URL is still readable by anyone who has it.
- Printing (or "Save as PDF") uses a print stylesheet: the navigation is
  dropped and each day starts on a new page, which makes a usable paper backup
  for places with no signal.
- Sites are tagged **excavated** where the remains themselves are the
  attraction, and **traditional** where the location rests on long veneration
  rather than archaeological evidence.
