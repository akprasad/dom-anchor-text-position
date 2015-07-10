Text Position Anchor
====================

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](http://opensource.org/licenses/MIT)
[![NPM Package](https://img.shields.io/npm/v/dom-anchor-text-position.svg)](https://www.npmjs.com/package/dom-anchor-text-position)
[![Build Status](https://travis-ci.org/hypothesis/dom-anchor-text-position.svg?branch=master)](https://travis-ci.org/hypothesis/dom-anchor-text-position)
[![Coverage Status](https://coveralls.io/repos/hypothesis/dom-anchor-text-position/badge.svg?branch=master)](https://coveralls.io/r/hypothesis/dom-anchor-text-position?branch=master)

This library offers conversion between a DOM `Range` instance and a text
position selector as defined by the Web Annotation Data Model.

For more information on `Range` see
[the documentation](https://developer.mozilla.org/en-US/docs/Web/API/Range).

For more information on the fragment selector see
[the specification](http://www.w3.org/TR/annotation-model/#text-position-selector).

Installation
============

There are a few different ways to include the library.

With a CommonJS bundler to `require('dom-anchor-text-position')`:

    npm install dom-anchor-text-position

With a script tag, include one of the scripts from the `dist` directory.

With AMD loaders, these scripts should also work.

Usage
=====

The module exposes a single constructor function, `TextPositionAnchor`.

## `new TextPositionAnchor(start, end)`

## `TextPositionAnchor.fromRange(range)`

## `TextPositionAnchor.fromSelector(selector)`

## `TextPositionAnchor.prototype.toRange()`

## `TextPositionAnchor.prototype.toSelector()`