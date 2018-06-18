![Cover Image](https://raw.githubusercontent.com/shrunyan/plate-starting-foundation/master/cover.png)

# Zurb Foundation 6.2.2

Zesty.io blueprint for [Zurb Foundation 6.2.2](https://github.com/zurb/foundation-sites/releases/tag/v6.2.2)

Blueprints are repositories which contain content configurations, parsley templates, styles(css/less/sass), and Javascript files to install. They can also contain many other configuration options such as; pre-installed fonts,

Blueprints can also tell Zesty.io what fonts (e.g. Google Fonts) and Javascript frameworks (e.g. JQuery) to use.

An example site with this blueprint can be viewed here: https://lj40hmzh-dev.preview.zestyio.com/

## Getting Started

If this is your first blueprint you should start by reviewing our [template getting started guide](https://developer.zesty.io/docs/templating/building-a-template-with-github/). If you need more information on Foundation please see the offical [Zurb Documentation](http://foundation.zurb.com/sites/docs/).


# `plate.xml`
[plate.xml documentation](https://developer.zesty.io/docs/templating/plate-xml/)

Your `plate.xml` file contains the initial instructions for your site setup. Things such as pages, page sets, datasets, content clippings and your document head.

# `plate-variables.xml`

[plate-variables.xml documentation](https://developer.zesty.io/docs/templating/plate-variables-xml/)

Variables allow you to expose UI control over the templates you setup to your end users the content authors.

# `/js`

The `js` folder is where you should add all the default javascript files you want to be included in every site created from this blueprint. We have added the Zurb Foundation javascript files.

# `/styles`

The `styles` directory contains all the style files you want included by default in each site greated from this blueprint. You can use `css`, `less` and `scss` styling.

*Note: Generally you should not mix different preprocessors. Stick with either `less` or `scss`.*

We have added the SCSS files from the Foundation Sites github. They are modified to not include @imports and are ordered by the numbers prepended to the file names.
