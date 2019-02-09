# Jörmungandr :: A Minimalist Hugo Theme

**Jörmungandr** (pronounced: _yor-mun-gan-der_) is a minimalist Hugo theme suited for blogging and personal websites.

Originally forked from the [alaGeek](https://github.com/gkmngrgn/hugo-alageek-theme) theme (which is itself derived from the [Cocoa Enhanced](https://github.com/mtn/cocoa-eh-hugo-theme) theme) and now includes several additional features and style changes.

## Key Features

* Minimalist, single-column, responsive design with beautiful typography.
* Display N number of latest posts.
* Syntax highlighting with `hightlight.js`.
* LaTeX support with `MathJax`.
* Twitter cards.
* `new:` Disqus comments system.
* `new:` Thumbnail images using a Hugo shortcode.
* Internationalization.

## Easily Customized (via config.toml)

* `new:` Custom page background color.
* `new:` Configurable fonts.
* `new:` Show/hide taxonomies on /blogs section.
* `new:` Show/Hide SVG social icons in header, footer or both.
* `planned:` Add custom CSS scripts.
* Add custom scripts with `footer_extra.html`.

## Beautiful Typography

* _Raleway_ for the titles, light but clearly visible
* _Merriweather_ for the text, an awesome sans serif font to read without difficulties
* _Menlo_ for the code

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

## Dependency versions

* bootstrap: 4.2.1
* highlightjs: 9.12.0
* mathjax: 2.7.5
* progressively: 1.2.5
* webfont: 1.6.28

## License

Licensed under the MIT License. See LICENSE.md.
