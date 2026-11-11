# Barntree website style guide

**This guide extends the [Barn website style guide](../../../../website/docs/style-guide.md)**
(`website/docs/style-guide.md` in the suite folder), which extends the Barn suite base style guide. Both
win for anything they state. This guide adds only Barntree's vocabulary, colour and exceptions.

## 1. Colour

Barntree is mint. Every page has `<body data-brand="tree">`, and components read `--brand`,
`--brand-ink`, `--brand-text`, `--brand-bright` and `--brand-tint`. No hex value appears in a page or in
`assets/site.css`; the tokens come from `assets/base/tokens.css`.

## 2. Vocabulary

The site uses Barntree's own words, the same ones as its browser app and command line:

- **Tree** for the types of one subject and the tree of items that follows them. Never "concept".
- **Template** for a Tree kept in the project, to make Constructions from. **Construction** for a named
  tree of real members made from a Template. Both are capitalised, as the app capitalises them.
- A **type** has an identifier, a name, a meaning and a kind: **leaf**, **list** or **map**. The app and
  the command line call a type a "building block"; the site says so once and says *type* elsewhere.
- An **item** follows a type; a **member** is an item in a list, with a name you give it. The
  **skeleton** is the starting tree.
- **Revision**, **snapshot**, **source**, **projection**, **tag** and **meaning** keep one meaning across
  the site and are defined once in the glossary.
- Say what a Tree says. It knows nothing of what a subject is about, and never judges it.
- Examples use an allotment (beds, a compost heap, a shed, a greenhouse), never Jupiter or Pleasant Stay.
  The `.barntree.json` file name is a file name, not a word to avoid.

## 3. Page set

`index.html` (introduction), `philosophy.html`, `quick-start.html`, and `docs/` with a page per topic. The
header navigation is the same on every page: Philosophy, Quick start, Documentation, Barn.

## 4. Exceptions

- The site header's wordmark is Barntree's own mark in a blue tile, not the Barn barn mark. Reason: each
  tool site reads as if the other tools did not exist (website guide §1). The `.tool-mark` rule is in
  `assets/site.css`.
- The header links to the main Barn site as "Barn", in place of the tool tabs of the main site.
- The introduction's panels hold short real output from the tool; the quick start runs everything for real.
- `assets/site.css` adds `.tree`, a text panel for trees and messages, which the base stylesheet does not
  have.
