# Jörmungandr :: A Minimalist Hugo Theme

**Jörmungandr** (pronounced: _yor-mun-gan-der_) is a minimalist Hugo theme suited for blogging and personal websites.

Originally forked from the [alaGeek](https://github.com/gkmngrgn/hugo-alageek-theme) theme (which is itself derived from the [Cocoa Enhanced](https://github.com/mtn/cocoa-eh-hugo-theme) theme) and now includes several additional features and style changes.

## Key Features

* Minimalist, single-column, responsive design with beautiful typography.
* Syntax highlighting - works smoothly with Hugo's built-in build-time syntax highlighter.
* LaTeX support with `MathJax`.
* Twitter cards.
* `new:` Disqus comments system.
* `new:` Thumbnail images using a Hugo shortcode.
* `new:` Display most-recent posts on any page using a Hugo shortcode.
* Internationalization.

## Easily Customized (via config.toml)

* `new:` Custom page background color.
* `new:` Configurable fonts.
* `new:` Show/hide taxonomies on /blogs section.
* `new:` Show/Hide SVG social icons in header, footer or both.
* Add custom CSS by overriding `head_extra.html`.
* Add custom scripts by overriding `body_extra.html`.

## Beautiful Typography

* _Merriweather_ - Serif font for main site text.
* _Raleway_ - Light font for blog post titles.
* _SFMono_ / _Consolas_ - For code.

## Quick Start

### Step 1 -- Install the theme

If you manage your Hugo site using Git then you can add the theme as a submodule.

Alternatively you can download the theme as a zip archive and extract it.

#### To add as a Git Submodule
* Run the following commands:

      cd /path/to/your/hugo/site
      git submodule add https://github.com/daveagill/jormungandr.git themes/jormundandr

* In the future, to update to the latest version of the theme:

      git submodule update --remote

#### To download as a Zip

* [Download the Zip](https://github.com/daveagill/jormungandr/archive/master.zip)
* Extract to: themes/jormundandr

### Step 2 -- Update config.toml

Set the `theme` property in your `config.toml` file:

    theme = "jormundandr"

Look at the [example site](https://github.com/daveagill/jormungandr/tree/master/exampleSite) to see other config options that you can set.

For syntax highlighting we recommend the following:

    [markup.highlight]
        style = "dracula"
        guessSyntax = true
        lineNos = true

## Dependency versions

* mathjax: 2.7.5
* webfont: 1.6.28

## License

Licensed under the MIT License. See LICENSE.md.
