---
title: "Introduction"
teaching: 0
exercises: 0
questions:
- "How do we edit this documentation?"
objectives:
- "Understand how to create and configure additional documentation repositories."
keypoints:
- "This documentation site was derived from templates prepared by Software Carpentry."
- "This site is built by `jekyll`, a static site generator, and served using GitHub Pages."
---

These instructions are adapted from the [Software Carpentry tooling guide][sw-tooling].

1. To start, we import (don't clone!) the [Software Carpentry styles repository][sw-styles] using the [GitHub Importer][gh-import].
  + for this project, we imported into [graveslab/howto][lab-howo].
2. Clone the new repo locally, e.g. with `git clone git@github.com:/graveslab/howto bc-lab-howto`
3. `cd` into the repo directory and run `bin/lesson_initialize.py` **once** to generate an initial Jekyll configuration file (`_config.yml`) and some other files.
4. edit `_config.yml` to customize it for your project.
5. start creating lesson material in `_episodes` and `_extras`!




[sw-tooling]: https://swcarpentry.github.io/lesson-example/02-tooling/
[sw-styles]: https://github.com/swcarpentry/styles
[gh-import]: https://github.com/new/import
[lab-howo]: https://github.com/graveslab/howto
