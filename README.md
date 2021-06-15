# [Bulma CSS Properties](https://bulma.io)

Bulma is a **modern CSS framework** based on [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes). 
That is implementation of Bulma with CSS Variables

![Github](https://img.shields.io/github/v/release/jgthms/bulma?logo=Bulma)
[![npm](https://img.shields.io/npm/v/bulma.svg)][npm-link]
[![npm](https://img.shields.io/npm/dm/bulma.svg)][npm-link]
[![](https://data.jsdelivr.com/v1/package/npm/bulma/badge)](https://www.jsdelivr.com/package/npm/bulma)
[![Awesome][awesome-badge]][awesome-link]
[![Join the chat at https://gitter.im/jgthms/bulma](https://badges.gitter.im/jgthms/bulma.svg)](https://gitter.im/jgthms/bulma)
[![Build Status](https://travis-ci.org/jgthms/bulma.svg?branch=master)](https://travis-ci.org/jgthms/bulma)

<a href="https://bulma.io"><img src="https://raw.githubusercontent.com/jgthms/bulma/master/docs/images/bulma-banner.png" alt="Bulma: a Flexbox CSS framework" style="max-width:100%;" width="600"></a>

## Quick install

This packages is implementation of Bulma that uses CSS properties.

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

### CDN

[https://www.jsdelivr.com/package/npm/bulma](https://www.jsdelivr.com/package/npm/bulma)

Feel free to raise an issue or submit a pull request.

## CSS only

Bulma is a **CSS** framework. As such, the sole output is a single CSS file: [bulma.css](https://github.com/jgthms/bulma/blob/master/css/bulma.css)

You can either use that file, "out of the box", or download the Sass source files to customize the [variables](https://bulma.io/documentation/overview/variables/).

There is **no** JavaScript included. People generally want to use their own JS implementation (and usually already have one). Bulma can be considered "environment agnostic": it's just the style layer on top of the logic.

## Browser Support

Bulma uses [autoprefixer](https://github.com/postcss/autoprefixer) to make (most) Flexbox features compatible with earlier browser versions. According to [Can I use](https://caniuse.com/#feat=flexbox), Bulma is compatible with **recent** versions of:

* Chrome
* Edge
* Firefox
* Opera
* Safari

Internet Explorer (10+) is only partially supported.

## Copyright and license ![Github](https://img.shields.io/github/license/jgthms/bulma?logo=Github)

Code copyright 2021 Jeremy Thomas. Code released under [the MIT license](https://github.com/jgthms/bulma/blob/master/LICENSE).

[npm-link]: https://www.npmjs.com/package/bulma
[awesome-link]:  https://github.com/awesome-css-group/awesome-css
[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
