# Hugo theme utils

Requires Hugo `>=0.42`.

Utility shortcodes and partials for use in Hugo sites.

Note: This repo is a work in progress, things may change!


## Installation:

1. Add this repo as a git submodule inside the `themes/` directory of your site (Or just copy it in, but submodule is far easier to update), as a directory called `utils`, resulting in `themes/utils/`.
2. Add `utils` to your theme configuration as the last entry in the list.

Note: Make sure `utils` is added as the last entry to ensure your theme overrides any shortcodes used in the utils, to avoid any name clashes.
