# Barntree website

Part of [Barn](https://rogerbarnfather.github.io/barn-website/).

Live at <https://rogerbarnfather.github.io/barntree-website/>.

The website for [Barntree](https://packagist.org/packages/rmb32/barntree): an introduction, the
philosophy, a quick start and the documentation. Static HTML, no build step; open `index.html` in a
browser. Links between pages are relative, because GitHub Pages serves a project site from a subpath.

- `assets/base/`: the shared Barn website stylesheet. An identical copy of the main site's, checked by
  `bin/ci-all` in the suite folder. Don't edit it here.
- `assets/site.css`: Barntree's own components.
- `assets/screens/`: real captures of the tool, 2× resolution, from a disposable barn with made-up
  allotment data.
- `docs/style-guide.md`: this site's style guide.

Pages: `index.html` (introduction), `philosophy.html`, `quick-start.html`, and `docs/` (overview,
trees, templates, constructions, history, export, check, gui, cli, php, install, data, glossary,
troubleshooting). Every command shown was run for real in a disposable barn with the released
packages, and its output pasted in with paths shortened by "…". Retake them when a command's output
changes.

## Screenshots refreshed 2026-11-14

All five images were retaken in Chrome at 1280 CSS pixels wide and 2× resolution,
using the released GUI v0.1.3 (unchanged checkout) and core v0.1.4. They show the
current white Barntree mark on mint and mint navigation highlights. Existing image
names and dimensions are retained.

The disposable allotment is created through the app’s API from the Quick start’s
Template. Its four real revisions add a description, create Greenhouse and add it
to the root. An independent Construction made before Greenhouse is added retains
its original structure; its seven revisions create Plot 12, add Beans and Carrots,
rename Carrots to Leeks, add and remove Peas, and rename the Construction.

- `barntree-tpl-tree`: the expanded Allotment Template, including Each Bed.
- `barntree-tpl-glossary`: its four Leaves, one List and one Map with meanings.
- `barntree-tpl-history`: its four saved revisions.
- `barntree-cs-tree`: Plot 12, north end, with Beans and Leeks tagged Watered.
- `barntree-cs-history`: the Construction’s seven saved revisions.

Only the temporary local barn path is hidden; the app’s content and branding are
unmodified. Seed and capture scripts are retained in
`/private/tmp/barntree-green-screens/` on the capture machine.
