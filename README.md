[![Version](https://img.shields.io/npm/v/cocoen.svg?style=flat-square)](https://www.npmjs.com/package/cocoen?activeTab=versions) [![Downloads](https://img.shields.io/npm/dt/cocoen.svg?style=flat-square)](https://www.npmjs.com/package/cocoen) [![Last commit](https://img.shields.io/github/last-commit/iamturns/cocoen.svg?style=flat-square)](https://github.com/iamturns/cocoen/graphs/commit-activity) [![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%koenoe%2Fcocoen%2Fbadge%3Fref%3Dmaster&style=flat&label=build&logo=false)](https://actions-badge.atrox.dev/iamturns/cocoen/goto?ref=master) [![Coverage Status](https://coveralls.io/repos/github/iamturns/cocoen/badge.svg?branch=master)](https://coveralls.io/github/iamturns/cocoen?branch=main) [![License](https://img.shields.io/github/license/iamturns/cocoen.svg?style=flat-square)](https://github.com/iamturns/cocoen/blob/main/LICENSE)

Touch-enabled before/after slider. Inspired by [before-after.js](https://github.com/jotform/before-after.js).

![](readme.gif)

# Quick start

[Demo](https://koenromers.com/cocoen/demo.html)

## Install

Install with NPM

```
npm install cocoen --save
```

Or download the [latest release](https://github.com/koenoe/cocoen/releases).

## Usage

Only the class `cocoen` is mandatory to apply proper default styles:

```html
<div class="cocoen">
  <img src="img/before.jpg" alt="" />
  <img src="img/after.jpg" alt="" />
</div>
```

Include the Cocoen stylesheet in your page:

```html
<link rel="stylesheet" href="css/cocoen.min.css" />
```

### Javascript

Include the `cocoen.min.js` script in your page, and then:

```js
new Cocoen(document.querySelector(".cocoen"));
```

Multiple Cocoens in one page:

```js
document.querySelectorAll(".cocoen").forEach(function (element) {
  new Cocoen(element);
});
```

# License

The code and the documentation are released under the [MIT License](LICENSE).
