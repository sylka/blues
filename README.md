# blues
![npm (scoped)](https://img.shields.io/npm/v/@jsylka/blues.svg)
![npm bundle size](https://img.shields.io/bundlephobia/min/@jsylka/blues.svg)

Sample repo - Removes all spaces from a string.

## Install

```
$ npm install @jsylka/blues
```

## Usage

```js
const tiny = require("@jsylka/blues");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
