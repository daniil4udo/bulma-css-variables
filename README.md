# [Bulma CSS Variables](https://bulma.io)

Bulma is a **modern CSS framework** based on [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes) and [CSS Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)

## Quick install

Bulma is constantly in development! Try it out now:

### NPM

```sh
npm install bulma-css-variables
```

**or**

### Yarn

```sh
yarn add bulma-css-variables
```

### Bower

```sh
bower install bulma-css-variables
```

### Import
After installation, you can import the CSS file into your project using this snippet:

```sh
@import 'bulma-css-variables/css/bulma.css'
```

Feel free to raise an issue or submit a pull request.

## CSS only

Bulma is a **CSS** framework. As such, the sole output is a single CSS file: [bulma.css](https://github.com/jgthms/bulma/blob/master/css/bulma.css)

You can either use that file, "out of the box", or download the Sass source files to customize the [variables](https://bulma.io/documentation/overview/variables/).

There is **no** JavaScript included. People generally want to use their own JS implementation (and usually already have one). Bulma can be considered "environment agnostic": it's just the style layer on top of the logic.

## CSS Variables Drawbacks

CSS Variables named after SASS [variables](https://bulma.io/documentation/overview/variables/)

Each main color in `colors` and shade in `shades` has coresponding

`--#{$base}-h - hue`
`--#{$base}-s - saturation`
`--#{$base}-l - lightness`
`--#{$base}-a - alpha`

### Modify Opacity

I.e. to add opacity to the primary color, you'll have to

`--primary-a: .5`

or

`--primary-a: calc(var(--primary-a) - var(--some-other-value))`

### Modify Lightnes and Darkness

Same applies for lightness. Instead of using sass lightness function (which you cannot with css variables), just modify `--primary-l` value.

Tome make color lighter increase (add) value to the `--primary-l`, to make it darker, decrease (substract) accordingly.

### Proper color change in runtime

Best way to change main colors (primary, info etc.) is to change their coresponding `--#{$base}-h - hue` `--#{$base}-s - saturation` `--#{$base}-l - lightness` `--#{$base}-a - alpha`

## Versioning

Version will follow **v0.Y.Z**, where:

* **Y**: Major (breaking changes)
* **Z**: Minor or patch

## Browser Support

Bulma uses [autoprefixer](https://github.com/postcss/autoprefixer) to make (most) Flexbox features compatible with earlier browser versions. According to [Can I use](https://caniuse.com/#feat=flexbox), Bulma is compatible with **recent** versions of:

* Chrome
* Edge
* Firefox
* Opera
* Safari

Internet Explorer (10+) is not supported due to the use of css variables.

## Copyright and license ![Github](https://img.shields.io/github/license/jgthms/bulma?logo=Github)

Code copyright 2021 Jeremy Thomas. Code released under [the MIT license](https://github.com/jgthms/bulma/blob/master/LICENSE).

[npm-link]: https://www.npmjs.com/package/bulma
[awesome-link]:  https://github.com/awesome-css-group/awesome-css
[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
