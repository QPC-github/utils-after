# SUIT utilities: after

[![Build Status](https://secure.travis-ci.org/suitcss/utils-after.png?branch=master)](http://travis-ci.org/suitcss/utils-after)

A SUIT collection of utility classes for offsetting elements.

Read more about [SUIT's design principles](https://github.com/suitcss/suit/).

## Installation

* [Component(1)](http://component.io/): `component install suitcss/utils-after`
* [Bower](http://bower.io/): `bower install --save suitcss/utils-after`
* Download: [zip](https://github.com/suitcss/utils-after/zipball/master)
* Git: `git clone https://github.com/suitcss/utils-after.git`

## Available classes

* `u-afterXofY` (numerous) - Specify the proportional offset before an object.

`X` must be an integer less than `Y`.

`Y` can be any of the following numbers: 2, 3, 4, 5, 6, 8, 10, 12.

### Plugins

Utilities that can be limited to specific Media Query breakpoints.

* `v1-u-afterXofY` - To use at the first Media Query breakpoint.
* `v2-u-afterXofY` - To use at the second Media Query breakpoint.
* `v3-u-afterXofY` - To use at the third Media Query breakpoint.

## Usage

Please refer to the README for [SUIT utils](https://github.com/suitcss/utils/)

## Testing

Install [Node](http://nodejs.org) (comes with npm) and Bower.

From the repo root, install the project's development dependencies:

```
npm install
bower install
```

To run the CSS Lint tests:

```
npm test
```

Open `test.html` in a browser to ensure each visual test is passing.

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 8+