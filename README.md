# Hugo theme utils

[![CircleCI](https://circleci.com/gh/RealOrangeOne/hugo-theme-utils.svg?style=svg)](https://circleci.com/gh/RealOrangeOne/hugo-theme-utils)

__Warning__: This repo is currently a work in progress!

Requires Hugo `>=0.42`.

Utility shortcodes and partials for use in Hugo sites. Thanks to [Theme Composition](https://gohugo.io/themes/theme-components/), themes can be merged. This repo houses many utility shortcodes and partials to reduce the amount of reuse and duplication in hugo sites.

This project is also partially in response to a [thread on the forums](https://discourse.gohugo.io/t/discussion-too-many-internal-shortcodes/12313) about Hugo having too many internal shortcodes. Moving them out to here allows them to be released and updated separately to Hugo itself, and doesn't bloat the application any more.

## Installation:

1. Add this repo as a git submodule inside the `themes/` directory of your site (Or just copy it in, but submodule is far easier to update), as a directory called `utils`, resulting in `themes/utils/`.
2. Add `utils` to your theme configuration as the last entry in the list.

You may now use any shortcode or partial from here in your site, as if it were included in your sites shortcodes and partials.

__Note__: Make sure `utils` is added as the last entry to ensure your theme overrides any shortcodes used in the utils, to avoid any name clashes.
