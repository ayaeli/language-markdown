# Markdown grammar

A realistic implementation of the [CommonMark](http://www.commonmark.org/) specifications as a more flexible (drop-in) alternative to [language-gfm](https://github.com/atom/language-gfm/).

**Supports**:

- CommonMark Markdown
- Github Flavored Markdown
- Markdown Extra
- CriticMark annotation
- Front Matter (yaml and toml)
- [more details](STATUS.md)

If you experience any issue above a reasonable/tolerable level of annoyancy, don't hesitate to [create an issue](issues/new/) or contact @burodepeper directly.

[![Build Status](https://travis-ci.org/burodepeper/language-markdown.svg?branch=master)](https://travis-ci.org/burodepeper/language-markdown)

---

## Features

Pretty much _all of your regular Markdown needs/uses_ are supported by this package, but certain features have been toned down a little to limit the number of false-positives.

I'd rather have you ask why your specific situation isn't italicized as you'd intended, than have you complain that your entire document acts like Microsoft Word 2007 after you've accidently moved an image two pixels and it decides to change the formatting on every single paragraph of your twelve page essay that is due in a hour at the exact moment you realize that your printer is probably either out of ink or paper, and you really need to pee.

Anyway, a few things are nerfed, but they are not worth the emphasis a proper list would give them: no setext headings, no indented code blocks, and complex nested grammar is at your own risk.

Check out [EXAMPLES.md](EXAMPLES.md) for a pretty extensive list of possibilities.

---

### Created with blood, sweat, tears, and these amazing tools:

[minimal-syntax](https://atom.io/packages/minimal-syntax)<br>
A light syntax theme, high contrast/low brightness, three primary colors, and easy on the eyes. Now also available as [minimal-syntax-dark](https://atom.io/packages/minimal-syntax-dark).

[lib-ass](https://www.npmjs.org/packages/lib-ass)<br>
Describe your tests in re-usable language-independent semantical format, and have them quickly translated into automated tests of your choosing.

[language-ass](https://github.com/burodepeper/language-ass/)<br>
Syntax highlighting in Atom for `.ass` files.
